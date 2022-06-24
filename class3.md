# Class 3 Reading Notes

## Intro to Git Notes

### Version Control

- Version control is a system which allows you to revisit versions of a file or set of files by recording changes
- Version control allows you to revert a file or project to a previous version, track modifications and modifying individuals, and compare changes
- Local Version Control System (Local VCS) entails one database on the hard disk that stores changes to files
- Centralized Version Control System (CVCS) streamlined the collaboration process through a single server storing all changes and file versions, which can be accessed by various clients
- Distributed Version Control System (DVCS) allows clients to create mirrored repositories where data backups can be easily placed on the server to replace any lost information

### What is Git?

- Git is a DVCS that stores data in a file system made up of snapshots
- Each time there's a changed and saved version of the project (called commit), Git creates a snapshot of the file and stores a reference of it
- Git relies mostly on local operations, allowing for process expediency and for someone to work on a project even when not online or on a VPN
- Files in Git are in three main states: committed (data securely stored in a local database), modified (file has been changed but not committed to the database), and staged (flagged a file's changed version to be committed to the next snapshot)

### Getting Started

- Git can be installed as a package, via another installer, or downloading and compiling the source code
- If you already have Git on your computer, check you have the latest version
- After installation, you should do customizations steps, which should only be need once on any machine
- The Git tool `git config` allows the setting of the configuration variables which control aspects of Git's operation and look
- You'll have to set up the user name and email address, which will be used for every Git commit
- Git will use the system's default editor (most likely Vim) unless configured; to configure a different text editor (such as Emacs), type `git config --global core.editor emacs`
- Check settings using `git config --list`

### Setting up a Git Repository

- To import an existing project or directory into Git:
1. Switch to the target project's directory 
`cd test (cd = change directory)`
2. Use the git init command
`git init`
3. To start tracking these repository files, perform an initial commit
`git add *.c`
`git add LICENSE`
`git commit -m "any message here"`
- Now the files are tracked, and there's an initial commit.
- You can also great a copy of an existing Git repository from a particular server by using the clone command with a repository's URL:
`git clone https://github.com/test`
- To clone a repository into a directory with another name:
`git clone https://github.com/test mydirectory`

### Workflow

The local Git repository has three components:
1. Working Directory: The actual files reside here
2. Index: The area used for staging
3. Head: Points to the most recent commit

- Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot
- Untracked files were not in the last snapshot and do not currently reside in the staging area
- After editing a file, Git flags it as modified; you stage the modified file; then, you commit staged changes
- `git status` command determines the state of the files
- track one file only by using `git add filename`
- track all files in a repository by using `git add *`
- After staging one or multiple files, commit the changes and record what you did within the commit message `git commit -m "made change x,y,z"`
- `git commit -a` commits a snapshot of all modifications to tracked files in the working directory
- push changes to a remote repository with `git push origin master`
- `git stash` is an option for when you are not ready to commit changes but don't want to lose them
- `git stash apply` is used to retrieve the hidden changes

### Remote Repositories

- In order to collaborate on Git projects, you must interact with remote repositories, which are versions of a project residing online or on a network
- Teams can use remote repositories to push information to and pull data from

