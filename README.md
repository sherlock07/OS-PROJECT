# SELF WRITTEN COMMAND LINE SHELL

# Problem Statement:

This project aims to write our own shell and execute different commands created by us. A shell is a program that creates an environment to execute commands. The shell first reads and executes its configuration files in the initializing phase. These change aspects of shell's behavior. It then reads commands that the user write through stdin which could either be a written command or file. After all the execution of commands, the shells terminates,executes any shutdown commands and frees up any memory.

# Project Scope:
This project deals with the following commands:
1 Read a line from stdin.
2 Split a line into arguments.
3 Execute each command.
4 Change the directory feature.
5 Exit the program using exit() function.
6 Feature of saving and viewing History.
7 A Word Predictor.
8 Separate window for Shell.
9 Help option for user with commands manual.
10 Display of previous commands using up arrow key.
11 Making another clone of program(Multiprogramming)

# REQUIREMENTS
• An Open Source Linux based Operating System.
• GCC Compiler
• Terminal
• Text Editor

# Performance
There is no special system requirements.

# Scalability
The project can be written and implemented in any language.

# Maintainability
This code requires a little of maintenance. Only timely adding new commands and making the commands more user friendly would be the main motive for program maintenance.

# Usability
This shell could be used to execute different user made commands easily, other than writing them again and again.


# IMPLEMENTATION
This code is strictly based on C implementation as of now. The program uses a string buffer to read lines and calls different functions based on the input requirements.This module as of now has the following functions-
• Read a line
• Split a line into different arguments
• Execute the arguments by either running user made commands or per-default system commands.

The following commands are added-
• help
• cd
• exit
• All other basic Linux commands
• Few user defined commands

As of now, a running module of the project is being implemented and in future, more commands could be added.
