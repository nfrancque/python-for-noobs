# Lesson 2

## Variables and Data Types

So, now we know how to print messages.  However, imagine we wanted to print the same message 4000 times - would you want to type 'Vive La Resistance!' 4000 times?  I doubt it.

This is where Python's `variable` comes into play.  In our Excel comparison, variables are similar to cell references - when we write `=SUM(A1, A2)`, A1 and A2 are variables referenced in the equation.

Python variables are remarkably simple.  For example, we can write the following statement:

`display_message = 'Vive La Resistance!'`

just once, and then the variable `display_message` contains that string for us later.

**Note**:  It is suggested convention to name variables all lowercase with underscores separating words.  Variable naming conventions are *extremely* important and people will hate you a lot if you suck at it.  Don't suck at variable naming!!

Now, we can type things like

`print(display_message)`

and Python will know that we are referring to the variable called display_message, which is really 'Vive La Resistance!'.  

Cool, right?  But how does it know?

It was glossed over in the previous lesson, but quotes are very important here - the quotes surrounding the words indicate that it is of data type string.  So, if we instead typed:

`print('display_message')`

This would actually print out the string 'display_message'.

There are many different data types - all programming languages decide which kind to use.  You can think of this like Spanish using the [subjunctive case](https://www.spanishdict.com/guide/spanish-subjunctive).  English uses this tense much less, but still works fine without it.  In the same way, some programming languages use one data type or another but can operate nonetheless.

In Python, we have a list of all data types [here](https://www.w3schools.com/python/python_datatypes.asp).

This is a bit of a complex subject, so let's try and sum it up quickly with some code.  I'll only cover the ones that are used most, and we'll go into greater depth on each in later lessons.

```
name    = 'John'                           # str
x       = 4                                # int
x       = 4.5                              # float
names   = ['John', 'Mary', 'Michael]       # list
info    = {'name' : 'John', 'age' : 4}     # dict
correct = True                             # bool
```

Strings have quotes.

Integers are whole numbers

Floats are decimals.

The brackets "[]" indicate a list, whose values are comma separated.

The curly braces "{}" indicate a dictionary, a key : value mapping.  These are extremely useful for stuff we'll talk about later!

Booleans are simply the values True and False.

## Exercise:

So, we want to test out our knowledge of variables and data types.

Try creating your own variables like the above with different names and values in a file called `variables.py`.  Then, print each of the variables on a different line.

## Checking In Work

Now that you've created your branch, things will be much easier.  The following steps will be true for all lessons, and in general is a common flow for commiting to a git repo.

Type `git status`.  You should again see the files you've changed in red.  To add them, type `git add .`.  Type `git status` again, and you'll see they are no longer red.

Type git commit -m "Message", where message is a *useful* description of the work you've done.

Finally, simply type `git push` and it will be committed to your remote branch!

# Review 

What is a string?

What is an integer?

What is a float?

What is a list?

What is a dictionary?

What is a boolean?

Why are variables useful?

Why might having several data types be useful? (We haven't learned this yet, just take a guess)

# Pop Quiz

Before continuing on to the next lesson, notify your instructor that you've completed lesson 2.  We will verify that your branch has been checked in and that your program prints out the proper message.

# Next Lesson

Once your program has been verified, go ahead and check out [Lesson 3](../lesson3/README.md)!







