# Useful Git Commands

## Learning git and GitHub with Alpha

### Useful Commands
- git clone file-name
- git status
- git add file-name
- git commit -m "meaningful message here"
- git push origin main

### Vocabulary
- repository (repo) - a named folder on GitHub
- git - version control software
- GitHub - online platform for git, GUI for sharing code and collaboration
- local - your personal computer
- commit - adding a tracking number and message to your version
- diff - the difference between states of your local and GitHub repo

### Git Process Notes
- create a new repo on GitHub
- clone the repo to your local
- add a new file
- add code to the new file
- use git status to see where you are at in the process
- add, commit, and push code into GitHub

### Branching Notes 
- branching protects your code from errors that can cause your app to be down in production
- branching allows multiple people to work on code at the same time
- branching is a best practice for all developers on all projects 
- main branch - source of truth, should always be in a working state
- deleting branches needs to occur on local and on GitHub

### Branching Vocabulary
- branch - an alternative timeline where a developer can code safely
- main - the branch where only working code is allowed
- git checkout - command to navigate between branches
- checkout -b - creates a new branch that doesn't currently exist
- branch -d - deletes a branch 

### Branching Commands
- $ `git checkout -b branch-name` - creates new branch that doesn't exist
- $ `git branch` - lists all the current branches on your local and shows which branch you are on
- $ `git branch -d branch-name` - deletes a branch when you are done 
- $ `git checkout main` - navigates back to main branch




## Terminal - Interface that allows access to command line
### (text-based commands)
- pwd - shows location on computer 
- ls - lists out what is inside that level
- cd - change directory to go down a level
- cd .. - goes back up a level
- mkdir - make a new directory
- touch - create a new file 
- code . - opens file in VS Code
- open "filename" - opens file
- "filename/" - shortcut to access file
- open . - opens file
- ~ - takes you back to the start
- clear - clears commands