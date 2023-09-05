# GIT Tips
*the tips and tricks that helped me learn how to use git and github!*

[Youtube Video that helped me step by step to start committing](https://youtu.be/AW_U0q5BtFI)

### Command Prompt Terminal Commands
- cd - change directory (move between folders)
- mkdir - make directory (create new folder)
- dir - list of all files and directories in current location
- cd .. - change directory (back out one folder at a time)
- echo texthere > <newfilename>.txt - make new document
- type <filename> - prints text within document
- del - delete directory or file (-y)
- cls - clear screen
- rm - remove filec
- rmdir - remove directory
- exit - closes terminal

### Git-Specific
- git clone URL - clone linked github repo to dir (folder) you are in
- git status - see status of files (Untracked files section in red)
- git add <file_name> - adds file to be watched
- git add . - add ALL
- git commit -m "enter message for commit here" - creates commit, and assigns a message
- git push - push to github
- git branch - list branches
- bit branch -a - list all branches (local and remote)
- git checkout <branch_name> - switch to branch
- git checkout -b <new_branch_name> - create and switch to new branch
- git branch <new_branch_name> - create new branch without switching into it


### Forking/Branching/PR
1. Fork original repository
2. Clone fork
3. create branch, make changes, commit
4. Push new branch to fork
5. Go to original repo, open new pull request
6. Explain changes made
7. Pull request will be accepted by original creator
