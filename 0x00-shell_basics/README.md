0x00. Shell basics

#General Requirements
- Allowed editors: vi, vim, emacs
- All scripts will be tested on Ubuntu 14.04 LTS
- All scripts should be two lines long (`$ wc -l file` should print 2)
- All files should end with a new line
- The first line of all files should be `#!/bin/bash`
- `README.md` files at the root of the section repository and project folder
- Do not use backticks, `&&`, `||`, or `;`
- All scripts must be executable. Use the command `chmod u+x file`.

#Files
0-current_working_directory:
Prints the absolute path name of the current working directory

1-listit:
Prints a list of the contents of the current directory

2-bring_me_home:
Takes the user to their home directory without using any variables

3-listfiles:
Prints a list of the contents of the current directory in long format

4-listmorefiles:
Prints a list of the contents of the current directory, including hidden files, in long format

5-listfilesdigitonly:
Prints a list of the contents of the current directory, including hidden files, in long format with the UID and GID displayed numerically

6-firstdirectory:
Creates the directory `/tmp/holberton`

7-movethatfile:
Move the file `betty` from `\tmp\` to `\tmp\holberton`

8-firstdelete:
Delete the file `betty`

9-firstdirdeletion:
Delete the directory `\tmp\holberton`

10-back:
Change the working directory to the previous one

11-lists:
List all files, including hidden files, in long format that are in the current directory, the parent of the working directory , and the `/boot` directory, in order.

12-file_type:
Print the type of the file named `/tmp/iamafile`

13-symbolic_link:
Create a symbolic link to `/bin/ls` named `__ls__` in the current directory

14-copy_html:
Copy all HTML files from the current working directory to the parent of the working directory that do not exist or are newer than the versions in the parent of the working directory

15-lets_move:
Move all files beginning with an uppercase letter to `/tmp/u`. Assume the directory exists

16-clean_emacs:
Delete all temporary files (end in `~`) from the current working directory

17-tree:
Create the directories `welcome/`, `welcome/to`, and `welcome/to/holberton` in the current directory

18-commas:
Lists all files and directories of current directory in a comma separated list

holberton.mgc
Detects `Holberton` data files when used with the `file` command