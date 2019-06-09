# About
Guide on how to write shell scripts

# All in one
It is suggested that package your script into one 

# As shorter as possible
Whenever there is a way to reduce repeating code and use a simpler way,use it.

# Providing examples
Scripts are sometimes hard to get started,especially these for specialized purpose.


# Practice
Place the help string in head, you can have another way to optimize how your help string is formed, but place it at head will help persons who read it understand it quickly.The simplest way to do this is to place the help message in a function,and place that function at head.

Place all functions before all scripts, this is because bash does not support forward function declare.

# Name Convention
File: use hyphen as word split

Local Variable: use camel case

Script Level Variable: use upper case

Function name: use underscore as word split

Script Invoke: prefer making a symbolic link with suffix removed in the bin directory

# Persist Data
Prefer file rather than environment variables

Use $$ as session identifier Tty-based session

Use /tmp/PROG/$$ as session scope files

Use ~/.PROG as global scope files


