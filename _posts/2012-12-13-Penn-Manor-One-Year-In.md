---
layout: post
title: Penn Manor, One Year In
---

Just a few weeks ago, I passed my 1 year 'anniversary' at Penn Manor.
I'd like to take this opportunity to reflect on two of the awesome projects that I've been able to do over the past 12 months. 

## Student Linux Machines
The biggest project of which I've been a part would be the creation of "Comet Linux". 
This is a totally customized version of Ubuntu Linux, created specifically for the students in grades 1-12. 
Picture
Screenshot of an early version of Comet Linux
We've worked very hard to include features based upon feedback from staff. 

The OS uses XFCE as the window manager, and at it's core is Ubuntu 12.04 LTS. 
The machines are managed through the use of a program called Puppet. 
Puppet allows us to explicitly define files and folders on the system, creating the perfect method for setting up a stable student system. 
Currently, the code for Comet Linux is closed source, but we hope to make it available to others in the future. 
The most interesting feature about our OS setup is the fact that the computers have the ability to 'self heal'. This means that if a student accidentally changes settings or deletes a needed file, one would simply have to log out, and then log back in to fix it. 
The profiles are stored with a 'skeleton' setup that is copied over any changes made whenever a user logs in. 
Students save their files on a remote server, not only to back them up, but to access them from anywhere in the school district.
Because all 4 of our Tech Support Analysts work on the maintenance of the Linux machines, we need a way to manage the updates. To make things easier, we have a Git server set up.
Git is a version control program that allows multiple people to work on the same files at the same time, all while avoiding the inevitable 'too many cooks in the kitchen' problem. 
All in all, the Comet Linux OS is one of my favorite projects to have worked. 
## Computer Builds
Very recently, the entire Tech Team and I have worked to build 40 computers for custodians, nurses, and cafeteria workers throughout the district. 
We chose to build the machines ourselves to save quite a bit of money, as compared to purchasing a pre-built system. 
We created a 'Master' computer, configured to include everything that the staff would need, and created an image using the utility FOG. FOG is a program like Clonezilla (an imaging program that I've discussed earlier) but it operates at high speeds, making it ideal for a project such as this.
There are a number of pictures available from this event also available on the Penn Manor Techblog. 
