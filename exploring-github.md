# Intro to GitHub

## Smaller header 

### Even smaller header

Hello this is some text!

Github commands:


pwd         Present Working Directory, shows what directory you are currently in
ls          List, tells you all the files available in your current directory
cd          Change Directory, follow this command with a name of a directory one level deeper ( Example: cd Desktop )
cd ..       Move one level up from where you are currently.
mkdir       Make directory, follow this command with a name to create a new directory ( Example: mkdir my_project)
rmdir       Remove directory, follow with a name to remove a directory ( Example: rmdir my_project )
touch       Follow with a name to create a file ( Example: touch index.html )
open        Follow with the full file name to open ( Example: open index.html )
open .      Opens the directory as if you double clicked on a folder
atom .      Opens all the files in the current directory using Atom editor
atom        Follow this command with the full file name to open Atom to directly edit the file ( Example: atom index.html )
code .      Opens all the files in the current directory using Visual Studio Code editor
code        Follow this command with the full file name to open VSCode to directly edit the file.( Example: code index.html )
;           Allows multiple commands in sequence ( Example: mkdir test_folder; touch index.html )
history     See all commands used
clear       Clear the Terminal screen


Git Trio:

#1 git status
#2 git add file-name.md
#3 git commit -m "explanation of what you changed"
#4 git status 
#5 git push origin main