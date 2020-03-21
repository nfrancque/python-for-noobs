# Installation

Python is a program like any other.  It takes our commands and interprets them into something the computer can run.

So, before learning Python we must first install it.

The details of this vary significantly but on Windows I personally find it easiest to install Windows Subsystem for Linux.

As the name suggests, this is a compatibility layer between Windows and Linux that allows us to do Linux-like commands in a Windows environment.

It also happens to come with all the programs we need baked in. 

So, go ahead and follow the [install guide](https://wsl-guide.kennethreitz.org/en/latest/installation.html) for WSL and come back once it's ready to go.

# Testing Our Setup

Okay, we've now installed Windows Subsytem for Linux.  This lets us run Linux commands in Windows, like Python and Git (we'll get to this in a bit).

Now, let's test out our installation.

In the WSL command prompt, type `python3 --version`.

You should see some information about what eversion of `python3` is installed with WSL, and it should be >=3.6.

Next, type `git --help`.  Some similar information for our version of git should be displayed.

