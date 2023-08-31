# 0x01. Shell, permissions
The directory as the name suggests shall contain the shell file permission alteration commands in form of executable scripts so as to verify and be sure of comprehension of the various possible permissions able to be allocated on a single file to different users i.e *owners*, *groups* and *users*.

## Specifications
- Used editor: *vi*
- All scripts are tested on Ubuntu 20.04 LTS
- All scripts contain exactly two lines (`$ wc -l file` should print *2*)
- All files end in a new line
- The first line of all files is `#!/bin/bash`
- A readme is present at the root of the directory
- All scripts are executable

# Files
| **File_name** | **Description** |
| ------------- | --------------- |
| 0-iam_betty | Switches the current user to the user *betty* |
| 1-who_am_i | Print effective user name of the currrent user |
| 2-groups | Prints all the groups the current user is part of |
| 3-new_owner | Changes the owner of the file *hello* to the user *betty* |
| 4-empty | Creates empty file called *hello* |
| 5-execute | Adds execute permission to the owner of the file *hello* in the current working directory |
| 6-multiple_permissions | Adds execute permission to the owner and the group owner and read permission to other users, to the hello file |
| 7-everybody | Adds execution permission to all users, to the hello file |
| 8-James_Bond | Sets the permissions to the file *hello* as follows: <ul><li>Owner: *no permissions at all*</li><li>Group: *no permissions at all*</li><li>Other users: *all the permissions*</li></ul> |
| 9-John_Doe | Sets the mode of the file *hello* to this: `-rwxr-x-wx 1 owner group 23 Sep 23 14:25 hello` |
| 10-mirror_permissions | Set the mode of the file *hello* the same as that ot the file *olleh* <ul><li>*Should work despite of any mode that olleh is set to*</li></ul> |
| 11-directories_permissions | Adds execute permissions to all subdirectories of the current directory for the owner, the group owner and all other users |
| 12-directory_permissions | Creates a directory called *my_dir* with permissions 751 in the working directory |
| 13-change_group | Changes the group owner to *school* for the file *hello* |
| 100-change_owner_and_group | Changes the owner to *vincent* and the group owner to *staff* for all files and directories in the working directory |
| 101-symbolic_link_permissions | Changes the owner and the group owner of *_hello* to *vincent* and *staff* respectively <ul><li>*_hello* is in the working directory</li><li>*_hello* is a symbolic link and the its referenced file should not be affected by the change</li></ul> |
| 102-if_only | Changes the owner of the file *hello* to *betty* only if its owned by the user *guillaume* |
| 103-Star_Wars | Plays the StarWarsIV episode in the terminal |
