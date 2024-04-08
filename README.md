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
### You can display a list of devices
    git config --list
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

### GIT SSH
#### Create SSH key and add SSH key on Github
#### Step1: Open Git Bash or Terminal, access the folder or director contains key
##### Command
    cd ~/.ssh
#### Step2: Check to see if there is an SSH key
##### Command
    ls
#### Step3: If you don't have an SSH key, you need to create one of the following ways and coppy SSH key
##### Command create SSH key
    ssh-keygen -t ed25519 -b 2048
    ssh-keygen -t ed25519 -b 2048 -C "email"
    ssh-keygen -t rsa -b 4096 -C "email"
##### Command copy SSH key
    clip < ~/.ssh/id_ed25519
    cat ~/.ssh/id_ed25519.pub | clip
#### Step5: Go to Github, Setting, select SSH and GPG keys, select New SSH key, paste the SSH key into the key and select add Authorize SSH key
#### Step6: Check if the SSH key has been added successfully
##### Command
    ssh -T

## SOME BASIC COMMANDS
    cd <path or name Directory>: change directory
    mkdir <name DIrectory>: make directory
    ls: lists directories and files contained in the current directory
    touch <file name>: create a file named <file name>
    code <file name>: Open the file named <file name> with vscode
    rm -rf <path>: delete the folder with path <path> and all subfolders inside
    rm <file name>: delete file named <file name>
    rmdir <directory name>: delete directory named <directory name>
    cat <file name>: Displays the contents of the named <file name>
    clear: clear screen

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
#### Remove repository <span style="color: grey;">rm -rf .git</span>
## GIT WORKFLOW
    git init : initialize the Git repository
    git add . : Add all files to the initialize
    git add <file name> : Add file named <file name> to the initialize
    git status : Check the status of your Git repository
    git commit -m "comment" : Save changes to the Git repository
    git log : Displays a list of commits
    git log --oneline : Displays  a list pf commits on onel line
    git show <commit code> : Displays detailed information of the commit code <commit code>
    git diff : Shows differences between commits
    git diff <commit1 code> <commit2 code> : Show the difference between two commits code <commit1 code> and <commit2 code>
    git checkout <commit code> <file name> : Restore the contents of the file named <file name> from the commit with <commit code>
    git checkout <commit code> : Restore all content from commit with code <commit code>
    git reset --hard <commit code> : Delete all history and restore all content from commit with code <commit code>
    git reset --hard : Delete all history and restore all content from the most recent commit
## SOME BASIC COMMANDS IN GITHUB
    git branch :
    git remote add origin "repository path"
    git push -m origin "branch name"
