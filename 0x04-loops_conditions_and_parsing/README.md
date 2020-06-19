# 0x04. Bash - Loops, conditions, and parsing

## Learning Objectives
- How to create SSH keys
- What is the advantage of using `#!/usr/bin/env bash` over `#!/bin/bash`
- How to use `while`, `until`, and `for` loops
- How to use `if`, `else`, `elif`, and `case` condition statements
- How to use the `cut` command
- What are files and other comparison operators, and how to use them

## Requirements
- Allowed editors: vi, vim, emacs
- All your files will be interpreted on Ubuntu 14.04 LTS
- All your files should end with a new line
- A README.md at the root of your project folder is mandatory
- All of your Bash scripts must be executable
- You are not allowed to use `awk`
- Your Bash script must pass `Shellcheck` (version 0.3.3-1~ubuntu14.04.1 via `apt-get` without any error)
- The first line of all your Bash scripts should be `#!/usr/bin/env bash` exactly
- The second line of all your Bash scripts should be a comment explaining what the script is doing

## Tasks
0. Create a SSH/RSA key pair
        - Create a RSA key pair. Keep the priavte key in a secure location.
   File: 0-RSA_public_key.pub

1. For Holberton School loop
        - Display `Holberton School` 10 times using a `for` loop.
   File: 1-for_holberton_school

2. While Holberton School loop
        - Display `Holberton School` 10 times using a `while` loop
   File: 2-while_holberton_school

3. Until Holberton School loop
        - Display `Holberton School` 10 times using an `until` loop
   File: 3-until_holberton_school

4. If 9, say Hi!
        - Print `Holberton School` 10 times, print `Hi` after the 9th print
	- You must use a `while` loop and an `if` statement
   File: 4-if_9_say_hi

5. 4 bad luck, 8 is your chance
        - Print `Holberton School` 10 times
	- Print `bad luck` on the 4th iteration
	- Print `good luck` on the 8th iteration
	- You must use a `while` loop, and the `if`, `else`, and `elif` statements
   File: 5-4_bad_luck_8_is_your_chance

6. Superstitious numbers
        - Display the numbers 1-20, including the ones with bad luck
	- Print `bad luck from China` on the 4th iteration
	- Print `bad luck from Japan` on the 9th iteration
	- Print `bad luck from Italy` on the 17th iteration
	- You must use a `while` loop and the `case` statement
   File: 6-superstitious_numbers

7. Clock
        - Display the time for 12 hours and 59 minutes
	- You must use a `while` loop
   File: 7-clock

8. For ls
        - Display the content of the current directory in list format
	- Print only the part of the name after the first dash
	- You must use a `for` loop
	- Do not display hidden files
   File: 8-for_ls

9. To file, or not to file
       - Check if the `holbertonschool` file exists and print a message
       - If the file exists, check if it's empty and print a message
       - Print a message if the file is a regular file
       - You must use `if` and `else`
       - You cannot use `case`
   File: 9-to_file_or_not_to_file

10. FizzBuzz
        - Display the numbers 1 to 100 in list format
	- Display `FizzBuzz` if the number is a multiple of 3 and 5
	- Display `Fizz` if the number is a multiple of 3
	- Display `Buzz` if the number is a multiple of 5
	- Otherwise display the number
    File: 10-fizzbuzz

### Author
Cynthia Taylor
June 19, 2020

Holberton School, SF Cohort 11, Trimester 1