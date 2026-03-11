# STEPS

These are the following steps taken in creating the local repository, all the way to pushing it to a remote repository on Github.

## Creating Local Repository

1. In the directory mod1, make a new repository 'second-repo' - mkdir second-repo 
2. Change to that directory - cd second-repo 
3. Initialize Git repository - git init
4. Create files - touch README.md steps.md
5. Open VS Code - code .
6. Add steps in the steps.md file

## Creating Remote Repository

### In VS Code terminal
1. Stage changes - git add .
2. Check Status - git status
3. Commit changes - git commit -m "message"

### In Github
1. Create new repository 'second-repo'
2. Create connection using:
    - git remote add origin git@github.com:LynWM/second-repo.git
    - git branch -M main
    - git push -u origin main
3. Refresh Github to see changes.