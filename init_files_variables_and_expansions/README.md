# Shell Init Files, Variables, and Expansion

## Overview
This project comprises scripts designed to enhance your understanding of shell initialization files, variables, expansions, and related concepts in Bash scripting.

## Learning Objectives
By completing this project, you'll be able to explain the following without external assistance:

### General
- Understand command execution like `$ ls -l *.txt`
- Knowledge of shell initialization files such as `/etc/profile`, `/etc/profile.d`, and `~/.bashrc`

### Variables
- Differentiation between local and global variables
- Creation, modification, and deletion of shell variables
- Roles of reserved variables like HOME, PATH, PS1, and special parameters like `$?`

### Expansions
- Utilization of expansions and their types
- Differentiation between single and double quotes
- Command substitution using `$()` and backticks

### Shell Arithmetic
- Execution of arithmetic operations within the shell

### The Alias Command
- Creation, listing, and temporary disabling of aliases

## Requirements
- Scripts should be two lines long
- Scripts should end with a newline
- First line of scripts must be `#!/bin/bash`
- Scripts should be tested on Ubuntu 20.04 LTS

## Files Description
- `0-alias`: Creates an alias.
- `1-hello_you`: Prints "hello user" where user is the current Linux user.
- `2-path`: Adds `/action` to the PATH.
- `3-paths`: Counts the number of directories in the PATH.
- `4-global_variables`: Lists environment variables.
- `5-local_variables`: Lists all local and environment variables, and functions.
- `6-create_local_variable`: Creates a new local variable.
- `7-create_global_variable`: Creates a new global variable.
- `8-true_knowledge`: Prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE.
- `9-divide_and_rule`: Prints the result of POWER divided by DIVIDE.
- `10-love_exponent_breath`: Displays the result of BREATH to the power LOVE.
- `11-binary_to_decimal`: Converts a number from base 2 to base 10.
- `12-combinations`: Prints all possible combinations of two letters, except "oo".
- `13-print_float`: Prints a number with two decimal places.
- `14-decimal_to_hexadecimal`: Converts a number from base 10 to base 16.

## Restrictions
- Avoid usage of &&, ||, or ;
- Do not use bc, sed, or awk
- Ensure all files are executable
