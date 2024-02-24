# Permissions

This directory focuses on understanding and manipulating permissions in Linux systems. It covers the following commands:

- `chmod`: Change file permissions
- `sudo`: Execute a command as the superuser
- `su`: Switch user to superuser or another user
- `chown`: Change file owner
- `chgrp`: Change file group
- `id`: Print user and group IDs
- `groups`: Print groups a user is in
- `whoami`: Print effective user ID
- `adduser`, `useradd`: Create a new user
- `addgroup`: Create a new group

## Learning Objectives
By the end of this project, you should be able to:

- Explain the purpose of each command related to permissions
- Understand Linux file permissions and how to represent them
- Change permissions, owner, and group of a file
- Explain why a normal user can't `chown` a file
- Execute commands with root privileges
- Change user ID or become superuser

## Requirements
- Scripts tested on Ubuntu 20.04 LTS
- Scripts should be exactly two lines long
- All files must be executable
- README.md file describing each script's purpose
## Files

This directory contains scripts related to managing file permissions and user/group ownership in Linux. Below is a brief overview of each script:

0. `0-iam_betty`: Switches the current user to the user "betty".
1. `1-who_am_i`: Prints the effective username of the current user.
2. `2-groups`: Prints all the groups the current user is part of.
3. `3-new_owner`: Changes the owner of the file "hello" to the user "betty".
4. `4-empty`: Creates an empty file called "hello".
5. `5-execute`: Adds execute permission to the owner of the file "hello".
6. `6-multiple_permission`: Adds execute permission to the owner and the group owner, and read permission to other users, to the file "hello".
7. `7-everybody`: Adds execution permission to the owner, the group owner, and the other users, to the file "hello".
8. `8-James_Bond`: Sets the permission to the file "hello" as follows: Owner - no permission at all, Group - no permission at all, Other users - all permissions.
9. `9-John_Doe`: Sets the mode of the file "hello" to "rwxr-x-wx".
10. `10-mirror_permissions`: Sets the mode of the file "hello" the same as the mode of "olleh".
11. `11-directories_permissions`: Adds execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users. Regular files should not be changed.
12. `12-directory_permissions`: Creates a directory called "my_dir" with permissions 751 in the working directory.
13. `13-change_group`: Changes the group owner to "school" for the file "hello".
14. `14-change_owner_and_group`: Changes the owner to "vincent" and the group owner to "staff" for all files and directories in the working directory.
15. `15-symbolic_link_permissions`: Changes the owner and the group owner of "_hello" to "vincent" and "staff" respectively.
16. `16-owner_change_if_guillaume.sh`: Changes the owner of the file "hello" to "vincent" only if it is owned by the user "guillaume".

Each script addresses specific tasks related to permissions, ownership, and mode changes in Linux filesystems, aiding in understanding the concepts outlined in the learning objectives.
