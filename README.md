<div align='center'> 

# Git and Github Resources :books:
*A curated list of all git and github resources at one place.* 
<br>

  
  ![Message](https://img.shields.io/badge/I%20%E2%9D%A4%20-OpenSource-%23ff0055)
  </div>
  <div align='center'>  
  
  
## What is Git :confused:
  
  
  </div>
  
  Git is the most popular [version control system](https://www.atlassian.com/git/tutorials/what-is-version-control). It tracks changes you make to files and keeps a record of your work. It also lets you revert to earlier versions of your code if the need arises. Git drastically improves collaboration, allowing multiple people to work in sync on the same source code. Below is a selection of the most helpful and commonly used Git commands to power up your programming!
  
<div align='center'>  
  
  
## 💻  Let's Install Git
  
  
  </div>
  
  
- [Official Website](https://git-scm.com/)
- [Windows Installer](https://git-scm.com/downloads)
  - Video : [Link](https://www.youtube.com/watch?v=2j7fD92g-gE)
- [MacOs Installer](https://git-scm.com/download/mac)
  - [Install homebrew](https://www.youtube.com/watch?v=SELYgZvAZbU)
  - Run the command : `brew install git`
- For Linux :
  - Debain based distro : `sudo apt-get install git`
  - Fedora based distro : `sudo yum install git`

<div align='center'>  
  
  
## Basic Git Commands
  
 </div> 

 ### Creating a New Repository
 | Command | Description |
| ------- | ----------- |
| `git init` | Initialize a local Git repository |
| `git add .` | Add all files in the working directory to the staging area |
| `git commit -m "<commit message>"` | Commit your changes |
| `git remote add origin git@github.com:<username>/<repository-name>.git` | Add upstream repo to publish commits at (the remote repo) |
| `git push -u origin master` | Push your changes to remote repository |

**[⬆ Back to Top](https://github.com/MahimaKhatri/Git-Github-Resources/blob/master/README.md#git-and-github-resources-books)**




### Working on Existing Projects

| Command | Description |
| ------- | ----------- |
| `git clone ssh://git@github.com/<username>/<repository-name>.git` | Create a local copy of a remote repo using SSH |
| `git clone https://github.com/<username>/<repository-name>.git` | Create a local copy of a remote repo using HTTPS |

**[⬆ Back to Top](https://github.com/MahimaKhatri/Git-Github-Resources/blob/master/README.md#git-and-github-resources-books)**


### Essential Commands

| Command | Description |
| ------- | ----------- |
| `git add <file-name.txt>` | Add a single file to the staging area |
| `git add -A` | Add all files in all directories to the staging area |
| `git rm -r . --cached` | Remove all files recursively from staging area |
| `git status` | See details about the current branch |
| `git show` | Shows changes in committed files |
| `git log` | View changes in commit history |
| `git branch` | List branches (the * is the current branch) |
| `git branch -a` | List all branches (local and remote) |
| `git branch <branch name>` | Create a new local branch |
| `git branch -d <branch name>` | Delete a local branch |
| `git push origin --delete <branch name>` | Delete a remote branch |
| `git checkout -b <branch name>` | Create a new local branch and switch to it |
| `git checkout <branch name>` | Switch to a branch |
| `git merge <branch name>` | Merge a branch into the active branch |
| `git merge <source branch> <target branch>` | Merge a branch into a target branch 
|`git push origin <branch name>` | Push a branch to your remote repo |
| `git push -u origin <branch name>` | Push changes to remote repo (and remember the branch) |
| `git push` | Push changes to remote repo (only if you have previously set a remote origin) |
| `git push origin --delete <branch name>` | Delete a remote branch |
| `git pull` | Synchronize local repo with remote repo |
| `git pull origin <branch name>` | Pull changes from remote repo |
| `git fetch` | Checks to see if there are any changes on the remote repo (does not pull changes) | 
| `git remote -v` | Shows URLs of remote repositories when listing your current remote connections |
| `git remote add origin ssh://git@github.com/<username>/<repository-name>.git`| Add upstream repo to publish commits at (the remote repo) |

**[⬆ Back to Top](https://github.com/MahimaKhatri/Git-Github-Resources/blob/master/README.md#git-and-github-resources-books)**



