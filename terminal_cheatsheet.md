# Terminal CheatSheet

## Overview

- This cheatsheet provides a quick overview of Terminal!
- These basic commands will be frequently used.

## Basic Syntax

| Element | Syntax | Description |
| ------- | ------ | ----------- |
| Working Directory | pwd    | Displays the complete path to the current directory |
| Change Directory  | cd my_directory | Changes current directory to my_directory |
| List | ls | Lists all contents in current directory |
| List: Detailed\Long Format | ls -l | Lists all files/directories in a long and detailed format. **Note: -l is called a flag** |
| List: Hidden | ls -a | Lists all files including hidden files. **Note: hidden files start with a "."**|
| List: Combining Flags | ls -la | A comprehensive and detailed list of directories/files, including hidden files |
| Navigate to Parent Directory | cd .. | Allows us to navigate up one level in the directory hierarchy |
| Create New Directory | mkdir my_directory | Creates a new directory in the current location |
| Create New File | touch new_file.txt | Creates a new file in the current location |
| Open Directory/File | open . | Opens the current directory/file in the default file explorer |
| Rename File | mv old_file_name.txt new_file_name.txt | Used to rename a file or directory |
| Move File | mv file_name.txt ~/Directory | Used to move a file or directory |
| Delete Files | rm file_name.txt | Removes/deletes files and directories in the terminal |
| Delete Directories: Recursive | rm -r my_directory | Deletes directories and their contents recursively. **Note: Be careful with this command!** |
| Delete Directories: Recursive and Forced | rm -rf my_directory | Forcefully and recursively deletes directories and their contents. **Note: Be careful with this command!** |
| Open Current Directory in VS Code | code . | Opens files/folders in current directory | 
| Clear Terminal Screen | clear | Provides a clean slate but you can see old work if you scroll up |

## Git

| Element | Syntax | Description |
| ------- | ------ | ----------- |
| Make New Git Repository | git init | Initialises new Git repository in current directory |
| Add Files to Staging Area | git add my_file.txt | Adds file to staging area, preparing files for inclusion in next commit |
| Commit | git commit -m "Description of what you changed" | Creates a new commit with a specified commit message |
| Display Current Status | git status | Shows changed that have been made and files staged for commit |
| Display Commit History | git log | Shows a chronological list of commits |
| Add Remote Repository to Local Repository | git remote add origin git@github.com:... | Established connection between two repositories, typically hosted by GitHub/BitBucket etc. |
| Push Local Commit | git push origin main | Pushes local commit to a remote repository called 'origin' in the 'main' branch |
| Create Local Copy of Repository | git clone git@github.com:... | Copy is created on local machine, including files, commit history, and branches | 

## Other: Not Covered in Lession but Useful to Know

| Element | Syntax | Description |
| ------- | ------ | ----------- |
| Copy File to Directory | cp file_name.txt my_directory | Might overwrite existing file |
| Copy Directory and the Contents to Another Directory | cp -r my_directory_01 my_directory_02 | Might overwrite files in existing directory |
| Output File Contents | cat file_name.txt | Displays file content on screen |