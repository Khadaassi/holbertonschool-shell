# IO Redirection and Filter

This directory focuses on Shell scripting techniques related to I/O redirection and filtering data. It covers essential commands such as `head`, `tail`, `find`, `wc`, `sort`, `uniq`, `grep`, `tr`, `rev`, `cut`, and exploration of the `/etc/passwd` file.

## Learning Objectives
- Understand Shell I/O Redirection
- Learn the functionalities of commands like `head`, `tail`, `find`, `wc`, `sort`, `uniq`, `grep`, `tr`, `rev`, `cut`
- Master redirecting standard output to a file
- Utilize standard input from a file instead of keyboard
- Combine commands and filters with redirections
- Explore special characters and their usage in Shell scripting
- Understand the formats and usage of `/etc/passwd` and `/etc/shadow` files

## Requirements
- Scripts should be exactly two lines long
- Files should end with a new line
- Scripts must start with `#!/bin/bash`
- README.md file describing each script's functionality
- No backticks, &&, || or ;
- All files must be executable
- No sed or awk usage

## 

This directory contains scripts focusing on I/O redirection and filtering commands in Shell scripting. Here's a brief overview of what each script does:

1. `0-hello_world`: Prints "Hello, World" to the standard output.

2. `1-confused_smiley`: Displays a confused smiley "(Ôo)".

3. `2-hellofile`: Displays the content of the `/etc/passwd` file.

4. `3-twofiles`: Displays the content of `/etc/passwd` and `/etc/hosts`.

5. `4-lastlines`: Displays the last 10 lines of `/etc/passwd`.

6. `5-firstlines`: Displays the first 10 lines of `/etc/passwd`.

7. `6-third_line`: Displays the third line of the file `iacta`.

8. `7-file`: Creates a file named `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text "Best School".

9. `8-cwd_state`: Writes the result of `ls -la` into the file `ls_cwd_content`, overwriting it if it exists.

10. `9-duplicate_last_line`: Duplicates the last line of the file `iacta`.

11. `10-no_more_js`: Deletes all regular files with a .js extension in the current directory and its subfolders.

12. `11-directories`: Counts the number of directories and subdirectories in the current directory.

13. `12-newest_files`: Displays the 10 newest files in the current directory.

14. `13-unique`: Prints only words from input that appear exactly once.

15. `14-findthatword`: Displays lines containing the pattern "root" from `/etc/passwd`.

16. `15-countthatword`: Displays the number of lines containing the pattern "bin" in `/etc/passwd`.

17. `16-whatsnext`: Displays lines containing the pattern "root" and the 3 lines after them in `/etc/passwd`.

18. `17-hidethisword`: Displays all lines in `/etc/passwd` that do not contain the pattern "bin".

19. `18-letteronly`: Displays all lines of `/etc/ssh/sshd_config` starting with a letter.

20. `19-AZ`: Replaces characters A and c with Z and e respectively.

21. `20-hiago`: Removes all letters c and C from input.

22. `21-reverse`: Reverses its input.

23. `22-users_and_homes`: Displays all users and their home directories, sorted by users.

Each script adheres to specific requirements and learning objectives, providing hands-on practice with various aspects of Shell scripting, including I/O redirection, filtering, and command usage.
