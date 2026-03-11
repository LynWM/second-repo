# STEPS

These are the following steps taken in creating the local repository, all the way to pushing it to a remote repository on Github.

## Creating Local Repository

In the directory mod1, make a new repository 'second-repo' - mkdir second-repo.

Change to that directory - cd second-repo
Initialize Git repository - git init
Create files - touch README.md steps.md
Open VS Code - code .
Add steps in the steps.md file

## Creating Remote Repository

### In VS Code terminal
Stage changes - git add .
Check Status - git status
Commit changes - git commit -m "message"

### In Github
Create new repository 'second-repo'
Create connection using:
    git remote add origin git@github.com:LynWM/second-repo.git
    git branch -M main
    git push -u origin main
Refresh Github to see changes.