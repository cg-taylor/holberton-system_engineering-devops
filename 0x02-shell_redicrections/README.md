0x02. Shell, I/O Redirections and filters

#General Requirements
- Allowed editors: vi, vim, emacs
- All scripts will be tested on Ubuntu 14.04 LTS
- All scripts should be exactly two lines long (`$ wc -l file` should print exactly 2)
- All files should end with a new line
- The first line of every file shoudl be exactly `#!/bin/bash`
- A README file at the root of the project folder should describe each script
- Do not use backticks, `&&`, `||`. or `;`
- Do not use `sed` or `awk`
- All files must be executable

#Tasks
0-hello_world:
Print \"Hello, World\" to stdout

1-confused_smiley:
Display a confused smiley face

2-hellofile:
Display the content of a file

3-twofiles:
Display the contents of multiple files

4-lastlines:
Display the last 10 lines of a file

5-firstlines:
Display the first 10 lines of a file

6-third_line:
Display the third line of a file without using `sed`

7-file:
Create a poorly named file

8-cwd_state:
Create a file if it does not exist or overwrite it if it does

9-duplicate_last_line:
Duplicate the last line of a file within that file

10-no_more_js:
Delete all regular files with a `.js` extension in the current directory and its subfolders

11-directories:
Count the number of directories and subdirectories in the current directories, including hidden ones

12-newest_files:
Display the 10 newest files in the current directory

13-unique:
Print only unique words from a list of words

14-findthatword:
Display lines from a file containing a certain pattern

15-countthatword:
Display the number of lines in a file that contain a pattern

16-whatsnext:
Display the lines and three lines after them that contains a specific pattern

17-hidethisword:
Display all lines in a file that do not contain a specific pattern

18-letteronly:
Display all lines in a file that begin with a letter

19-AZ:
Replace all characters `A` and `c` with `Z` and `e` respectively

20-hiago:
Remove `c` and `C` from input

21-reverse:
Reverse the input

22-users_and_homes:
Display all users and their home directoriesm, sorted by users

100-empty_casks:
Find all empty files and directories in the current directory and all sub-directories

101-gifs:
List all files with a `.gif` extension in the current directory and all sub-directories

102-acrostic:
Decode acrostics that use the first letter of each line

103-the_biggest_fan:
Parse web servers logs in TSV format and display the 11 hosts or IP addresses that did the most requests