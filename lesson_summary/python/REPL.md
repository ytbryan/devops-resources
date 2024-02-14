###Introducing the REPL for Rapid Experimentation

Python is an interpreted language, and the code is evaluated line-by-line. 
Each line can be evaluated by itself, and this allows us to have a REPL.


What is a REPL?

>REPL stands for: Read, Evaluate, Print, Loop

>Each line is read, evaluated, the return value is then printed to the screen, 
and then the process repeats.

>Python ships with a REPL, and you can access it by running python3.6 from your terminal.

Eg.1: 
$ python3.6
Python 3.6.4 (default, Jan 5 2018, 20:24:27)
[GCC 4.8.5 20150623 (Red Hat 4.8.5-16)] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>>

Expln 1:
The >>> indicates that you can type on that line. Later on, you’ll also see a ... which 
means that you are currently in a scoped area and will need to enter a blank line (no spaces) 
before it evaluates the entire code block.

The simplest use of this would be to do some math:

Eg.2:
>>> 1 + 1 
2
>>>

Expln 2:
2 is the return value of the expression, and it is then printed to the screen. If something
doesn’t have a return value, then nothing will be printed to the screen and you’ll see the 
next prompt immediately. We’ll cover this later, but an example would be None:

Eg.3: 
>>> None
>>>


Lastly, to exit the REPL, you can either type exit() (the parentheses are important), or you
can hit Ctrl+d on your keyboard.
