# Directory Permissions

This directory contains scripts related to managing file permissions and user/group ownership in Linux. Below is a brief overview of each script:

0. `0-username_switch.sh`: Switches the current user to the user "betty".
1. `1-who_am_i.sh`: Prints the effective username of the current user.
2. `2-groups.sh`: Prints all the groups the current user is part of.
3. `3-owner_change.sh`: Changes the owner of the file "hello" to the user "betty".
4. `4-create_hello.sh`: Creates an empty file called "hello".
5. `5-add_execute_permission.sh`: Adds execute permission to the owner of the file "hello".
6. `6-multiple_permission.sh`: Adds execute permission to the owner and the group owner, and read permission to other users, to the file "hello".
7. `7-all_execute_permission.sh`: Adds execution permission to the owner, the group owner, and the other users, to the file "hello".
8. `8-no_owner_permissions.sh`: Sets the permission to the file "hello" as follows: Owner - no permission at all, Group - no permission at all, Other users - all permissions.
9. `9-mode_rwxr-x-wx.sh`: Sets the mode of the file "hello" to "rwxr-x-wx".
10. `10-mode_like_olleh.sh`: Sets the mode of the file "hello" the same as the mode of "olleh".
11. `11-add_execute_subdirectories.sh`: Adds execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users. Regular files should not be changed.
12. `12-create_my_dir.sh`: Creates a directory called "my_dir" with permissions 751 in the working directory.
13. `13-group_owner_change.sh`: Changes the group owner to "school" for the file "hello".
14. `14-owner_group_change.sh`: Changes the owner to "vincent" and the group owner to "staff" for all files and directories in the working directory.
15. `15-owner_group_change_hello.sh`: Changes the owner and the group owner of "_hello" to "vincent" and "staff" respectively.
16. `16-owner_change_if_guillaume.sh`: Changes the owner of the file "hello" to "vincent" only if it is owned by the user "guillaume".

Each script addresses specific tasks related to permissions, ownership, and mode changes in Linux filesystems, aiding in understanding the concepts outlined in the learning objectives.
