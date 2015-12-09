---
layout: post
title: How to install "Packer', the ArchLinux AUR Helper
keywords: Pacman, packer, archlinux, arch, aur, install packer, linux
---

Packer is an extremely useful 'wrapper' for ArchLinux's Arch User Repository (AUR). According to the ArchWiki:

> packer — wrapper for pacman and the AUR. It was designed to be a simple and very fast replacement for the basic functionality of Yaourt. It has commands to install, update, search, and show information for any package in the main repositories and in the AUR. Use pacman for other commands, such as removing a package

Every time I install Arch, I find myself trying to remember how I installed packer. Many of the times, I'm trying to do this via command line only access.
#### To install Packer:
I find it easiest to do everything quickly from the command line.

```bash
# Install the package dependencies
# needed to use and build Packer:
pacman -S base-devel fakeroot jshon expac wget git

# Get the PKGBUILD
# (I typically save it in a separate folder for cleanliness)
wget https://aur.archlinux.org/cgit/aur.git/plain/PKGBUILD?h=packer

# Run makepkg on the PKGBUILD as a regular user
makepkg

# Install the newly created package
pacman -U packer-*.pkg.tar.gz
```

#### To Use Packer:
Packer works exactly the same as Pacman.

As a regular user you can run:

```bash
# To install the package you wish, or you can run:
sudo packer -S newpackage

# To find a package based on your 'something' search term:
sudo packer -Ss something
```

However, remember that Packer will not let you remove a package. Use regular pacman to remove an unneeded package from your system.

```bash
pacman -R package_to_remove
```
