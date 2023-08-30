# Basic shell commands
The directory as the name suggests shall contain the basic shell commands in form of executable scripts so as to verify and be sure of comprehension of navigation of shell.

## Specifications
- Used editor: *vi*
- All scripts are tested on Ubuntu 20.04 LTS
- All scripts contain exactly two lines (`$ wc -l file` should print *2*)
- All files end in a new line
- The first line of all files is `#!/bin/bash`
- A readme is present at the root of the directory
- All scripts are executable

| File_name | Description |
| --------- | ----------- |
| 0-current_working_directory | Prints the absolute path name of the current working directory |
| 1-listit | Displays the contents list of your current directory |
| 2-bring_me_home | Changes working directory to the user's home directory |
| 3-listfiles | Displays current directory contents in a long format |
| 4-listmorefiles | Display current directory contents, including hidden files |
| 5-listfilesdigitonly | Display current directory content in the following specifications:<ul><li>Long format</li><li>with user and group IDs displayed numerically</li><li>And hidden files</li></ul>|
| 6-firstdirectory | Creates a script that creates a directory named *my_first_directory* within the location */tmp/* |
| 7-movethatfile | Moves file */tmp/betty* to */tmp/my_first_directory* |
| 8-firstdelete | Delete the file */tmp/my_first_directory/betty* |
| 9-firstdirdeletion | Delete the directory */tmp/my_first_directory* |
| 10-back | Changes the working directory into the previous one |
| 11-lists | Lists all files even the hidden files in long format that are within the current directory, the parent of the working directory and the */boot* directory |
| 12-file_type | Prints the type of file: */tmp/iamfile* |
| 13-symbolic_link | Creates a symbolic link to */bin/ls* named *__ls__* in the working directory |
| 14-copy_html | copy all html files in currrent directory to parent directory only if the files don't exist in the parent directory or are newer than the version in the parent diretory |
| 100-lets_move | Moves all files beginning with an uppercase letter to the directory */tmp/u* |
| 101-clean_emacs | Deletes all files in the current working directory that end with th character *~* |
| 102-tree | Creates the directories *welcome/*, *welcome/to/* and *welcome/to/school* |
| 103-commas | Lists all files in current directory separated by commas, arranged in alphabetic order, directory names separated by / and all hidden files are displayed |
| school.mgc | Can be used with command *file* to detect *School data* files that always contain string **SCHOOL** to offset 0 |
