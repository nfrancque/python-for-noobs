# Lesson One

## Printing
In this lesson, we will learn some basics of how to write Python.  As we saw earlier, it is possible to write a program that displays the message 'Hello, World!' onto the screen.  We would like to do something similar - let's say we want to display 'Vive La Resistance' to screen.

Let's start by creating a file to write our program in.  In VSCode, create a new file in this folder (lessons/lesson1) called vive_la_resistance.py.

.py is the common extension for Python files, similar to .txt or .docx.

In this file, we want to write a program that tells the Python interpreter to write 'Vive La Resistance' to the screen for us.

We do this using a function called `print`.

You may be familiar with functions from excel - something like `=SUM(E1, 2)` denotes the calling of the sum function on the value stored in cell E2 and the number 2, giving us the end result.  Python functions are quite similar.

One common function, called `print`, displays the arguments provided to it in our console window.

For example, if I call `print('seven')`, then I expect 'seven' to be written - or, 'printed' - the screen.  Note that the print function takes quotes around its arguments.  The quotes surrounding it indicate the to interpreter that this is a `string` - a series of numbers or letters to be interpreted as such.  In constrast, if we wanted to print '7', we would write `print(7)`, indicating we want to print the actual *number* 7.

In your new file, write a program using the print statement to print out 'Vive La Resistance'.

To verify this, you may run `python3 vive_la_resistance.py` on the command line and check your results.

## Checking in Work

So, we've managed to write this program that does something vaguely useful.  How do we share it?  We could email it back and forth, but that would be quite the pain for lots of changes.  Git offers us the concept of a `branch`, a separate stream of saved source code files so that two people can work independently on it.

Let's try this out.  

In your command line, type `git checkout -b [username]`.  Use your github username or similar for this.

This command will `checkout` a new `branch` called `username` in your working copy.  

Now, type `git status`.  You should see a message in red about how your files have been added.  We would like to get them checked in.

Type `git add .`.  This will add all the files you have changed into the git repository to be checked in.  

Next, type `git commit -m "Your commit message here"`, where you commit message is some useful information about the work that you have just done.

We are almost there.  The commands up until now have added your changes to your local git repository.  We would now like to check them in to be shared with our teammates.

Type `git push --set-upstream origin [username]` where username is the name of the branch you previously created.  You may need to input your credentials.

We did it!  Now, visit the [GitHub](https://github.com/nfrancque/python-for-noobs) page and check where it says 'Branch: master'.  Click on the dropdown box and select your new branch.  

You are now looking at your own personal branch of this repository.  Great job!  We will use this branch to check in your work as the course progresses.


# Review 

What is a function?

What is printing?

What is a string?

What is a git branch?

Why do we need a git branch?

# Pop Quiz

Before continuing on to the next lesson, notify your instructor that you've completed lesson 1.  We will verify that your branch has been checked in and that your program prints out the proper message.

# Next Lesson

Once your program has been verified, go ahead and check out [Lesson 2](../lesson2/README.md)!


