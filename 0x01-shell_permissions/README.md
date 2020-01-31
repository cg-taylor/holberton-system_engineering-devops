0x01. Shell permissions

#General Requirements
- Allowed editors: vi, vim, emacs
- All scripts will be tested on Ubuntu 14.04 LTS
- All scripts should be exactly two lines long (`$ wc -l file` should print 2)
- All files should end with a new line
- The first line of all files should be `#!/bin/bash`
- There should be a README file at the root of the project folder, describing each script
- Do not use backticks, `&&`, `||`, or `;`
- All files must be executable

#Files
0-iam_betty:
Change user ID to `betty`

1-who_am_i:
Print the effective UID of the current user

2-groups:
Print all the groups the current user is part of

3-new_owner:
Change the owner of the file `hello` to `betty`

4-empty:
Create an empty file called `hello`

5-execute:
Give file owner execute permissions for file `hello`

6-multiple_permissions:
Change permissions for the owner, group owner, and others for file `hello`

7-everybody:
Give execution permission to everyone for file `hello`

8-James_Bond:
Set permissions to 007 for file `hello`

9-John_Doe:
Set permissions to 753 for file `hello`

10-mirror_permissions:
Set permissions for file `hello` to mirror file `olleh`

11-directories_permissions:
Change permissions of subdirectories without changing file permissions

12-directories_permissions:
Create directory with permissions 751 in the working directory

13-change_group:
Change group owner for file `hello`

14-change_owner_and_group:
Change the owner and group owner for all files and directories in the working directory

15-symbolic_link_permissions:
Change the owner and group owner of a symbolic link

16-if_only:
Change the owner of a file only if it is owned by a specific user

100-Star_Wars:
Play Star Wars Episode IV in the terminal

101-man_holberton:
Man page for Holberton School
