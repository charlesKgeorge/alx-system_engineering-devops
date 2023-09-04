# 0x02. Shell, I/O Redirections and filters
The directory as the name suggests shall contain some shell standard input and standard output redirections that includes into files or other commands for input and into files instead of standard output for output

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
| 0-hello_world | Prints hello world to the standard output |
| 1-confued_smile | Displays a confused smiley **"(Ôo)'** |
| 2-hellofile | Displays content of the */etc/passwd* file |
| 3-twofiles | Displays the content of  */etc/passwd* and */etc/hosts* |
| 4-lastlines | Displays the last 10 lines of */etc/passwd* |
| 5-firstlines | Displays the first 10 lines of */etc/passwd* |
| 6-third_line | Displays the third line of the file *iacta* which will be in the working directory |
| 7-file | Creates a file named exactly
     containing the text *Best School* ending by a new line |
| 8-cwd_state | Writes into the file *ls_cwd_content* the results of the command *ls -la* |
| 9-duplicate_last_line | Duplicates the last line of the file *iacta* |
| 10-no_more_js | Deletes all regular files (not the directories) with a *.js* extention that are present in the current directory and all subdirectories |
| 11-directories | Counts the number of directories and sub-directories in the current directory<ul><li>The current and parent directories should be taken into account</li><li>Hidden directories should be counted</li></ul> |
