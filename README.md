# Git With NguyxnTruong
## WHAT'S GIT
    Git is a version control system. Git helps you keep track of code changes.
    Git is used to collaborate on code.

    WHY GIT? 
        Because Git is free, Open Source, Supper Fast, Scalabale, Cheap Branching/ Merging.
        => We can using or work together with colleagues anywhere.
##  USING GIT
###### Git using the command line, it's support code editors and IDEs (codespace), GUI (Graphical user interfaces) made for using git
## CONFIGURING GIT
######  Configuring Git involves setting up vavious options that control how Git operates and look for each user.
### Setting up your identity
    git config --global user.name "Your Name"
    git config --global user.email youremail@example.com
### Choosing a default editor
###### You can select the text editor that will be used when Git requires you to type in a message.
### Configuring preferences 
###### Such as setting up aliases for commands, choosing the default behavior for certain operationsm, or setting up Git to work with a proxy.
### Managing remote repositories
###### Including adding remote repositories, changing their URLs, and setting up branch tracking.
## STORED
###### Include: System level, Global level, Local level.
## GIT HELP
###### We using: Git config
    git config --list
## COMMAND IN GIT
### GIT INIT
#### The git init command is used to initialize a new Git repository. Executing this command in a directory on your computer creates a new .git subdirectory. This subdirectory contains all the necessary metadata and configurations for the new repository. It’s the first step you take when you want to start version control for a project with Git.
##### Command
    git init
#### You can use ls -a immediately after entering git init to check whether a .git file has been created or notWe can using ls -a after text git init 
##### Command
    ls -a
#### Additionally, you can try some commands like open .git to see what's interesting
##### Command
    opend .git
#### Remove repository 
##### Command
    rm -rf .git
## GIT WORKFLOW
    git init
    git add .
    git status
    git commit -m "comment"
    git branch
    git remote add origin "initialize"
    git push -m origin "name.."
    
