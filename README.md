# SHELL

## Summary:

The term "Shell" can refer to two distinct concepts: the shell as a command-line user interface and the shell as a scripting language. Here is a summary of these two aspects:

* **Shell as a Command-Line User Interface:**
  * **Definition:** The shell is a command-line interface that allows the user to interact with the operating system by entering commands.

  * **Basic Commands:**
    * `cd`: Change directory.
    * `ls`: List the contents of a directory.
    * `mkdir`: Create a new directory.
    * `cp`: Copy files or directories.
    * `mv`: Move or rename files or directories.
    * `rm`: Remove files or directories.
    * `echo`: Display text to the standard output.
    * `cat`: Display the contents of a file.

  * **Advanced Operations:**
    * **Redirection (`>`, `>>`):** Redirect output to a file.
    * **Pipe (`|`):** Pass the output of one command as input to another.
    * **Environment Variables:** Store information useful to the system.
    * **Alias:** Create shortcuts for frequently used commands.

### General
* What does RTFM mean?
* What is a Shebang

### What is the Shell
* What is the shell
* What is the difference between a terminal and a shell
* What is the shell prompt
* How to use the history (the basics)

### Navigation
* What do the commands or built-ins cd, pwd, ls do
* How to navigate the filesystem
* What are the . and .. directories
* What is the working directory, how to print it and how to change it
* What is the root directory
* What is the home directory, and how to go there
* What is the difference between the root directory and the home directory of the user root
* What are the characteristics of hidden files and how to list them
* What does the command cd - do

### Looking Around
* What do the commands ls, less, file do
* How do you use options and arguments with commands
* Understand the ls long format and how to display it
* A Guided Tour
* What does the ln command do
* What do you find in the most common/important directories
* What is a symbolic link
* What is a hard link
* What is the difference between a hard link and a symbolic link

### Manipulating Files
* What do the commands cp, mv, rm, mkdir do
* What are wildcards and how do they work
* How to use wildcards

### Working with Commands
* What do type, which, help, man commands do
* What are the different kinds of commands
* What is an alias
* When do you use the command help instead of man

### Reading Man Pages
* How to read a man page
* What are man page sections
* What are the section numbers for User commands, System calls and Library functions

### Keyboard Shortcuts for Bash
* Common shortcuts for Bash

### LTS
* What does LTS mean?


### General
* Allowed editors: vi, vim, emacs
* All your scripts will be tested on Ubuntu 20.04 LTS
* All your scripts should be exactly two lines long ($ wc -l file should print 2)
* All your files should end with a new line (why?)
* The first line of all your files should be exactly #!/bin/bash
* A README.md file at the root of the repo, containing a description of the repository
* A README.md file, at the root of the folder of this project, describing what each script is doing
* You are not allowed to use backticks, &&, || or ;
* All your scripts must be executable. To make your file executable, use the chmod command: chmod u+x file. Later, we’ll learn more about how to utilize this command.
