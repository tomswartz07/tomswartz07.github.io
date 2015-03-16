---
layout: post
title: The Secret to great Git commit messages
---

### How to use Git in such a way that will make your friends and co-workers not want to kill you.
        
I've been using Git for a number of years, between personal projects at home, and collaborative projects at work.
Many of the projects are maintained for many years, and sometimes managed by many different people.

When sorting through a project, I can guarantee that there will come moments when you read some code and mutter under your breath "Why the heck is that done that way?".

At that very second, your first instinct should be to look at the history, to see who did what, trace it to a Commit Message, and figure out why.

If you don't already know how to to that, take moment to figure out a way quickly to access the history of a line in your editor or in your repo. The less friction it causes, the easier it is to go back and read about the changes. 
If you're looking for suggestions, how about Vim-Fugitive? A second terminal with git-blame?
Once you make a habit out of always checking the git history, you will quickly learn what type of Git Commit message is helpful and what is not. 

Then, if you are like me, you'll want to go back to slap your past-self in the head for being lazy and giving a few bullet points of "what" was changed and not "why" it was changed.
In my experience, the best way to ensure that you have a reasonable commit message is to always include the word 'because'.
Let's take a peek at an example, to illustrate the power of 'because'.

First up, here is a typical commit message that I'm sure pretty much everyone has seen or dealt with at some point:

```diff
Changed the post title font size 

Changed 0.8em 16px. 

h2 { 
- font-size: 0.8em;
+ font-size: 16px; 
} 
```
        
Unfortunately, this commit message gives absolutely zero context as to why it was changed.
Did we just not like that size? Was there a vendetta against em scaling of fonts? Is someone just trying to screw with me?
Yes, of course we know that the size was changed from 0.8em to 16px: the git diff is included right there! Why tell me twice?

Without any further context, it's almost impossible to discern the reasoning behind why this single line of code was changed.
Now, let's examine a 'proper' commit message:

```diff
Changed the post title font size 

Change H2 font to 16 pixels because when the 
overall font size was increased, the blog titles 
were wrapping on mobile views. 

h2 { 
- font-size: 0.8em; 
+ font-size: 16px; 
} 
```
        
You'll notice right away that the message includes a 'why?' solution. I know right away what it does, how it works, and what was broken.

However, most importantly, you'll also notice that it doesn't reiterate the same information included in the diff.
This second changelog message is most helpful.
Here's why:

- It provides context to the change, rather than regurgitating the same info for the sake of including a message. 
- It provides information as to the reasoning behind it and what might break if it is reverted. 
- It's completely and totally obvious that it isn't some arbitrary change. 


I will appreciate all of these facts in 2 years when I'm looking back at it.
I'd like to see anyone else find a better way to communicate with their future selves that doesn't involve time travel.
