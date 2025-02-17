# developers_101

## IDE
We will be using VS Code for the development . However you can use any IDE of your choice.
Based on your OS download the appropriate version from [here](https://code.visualstudio.com/download).

## GIT
Now that we are all set the very first skill across all domains is to know about version controlling methodologies such as Git.
Follow the video [here](https://www.youtube.com/watch?v=JN63v_czZqI) to learn the fundamentals about version control.

## Linux
Love it or Hate it, You will have to use it. For a smooth developer experience Linux is the OS to use and that's why we we will download Ubuntu(A flavor of Linux).
Now the next thing would be to learn the fundamentals of Linux so you can always debug your application on the standard OS across the industry i.e LINUX
Here's a video to get you started. [Linux Basics](https://www.youtube.com/watch?v=V1y-mbWM3B8).

>**Note:** 
>
>* If you are on Windows, I'd recommend installing WSL2 for Windows to follow along in the course. Follow the [link](https://ubuntu.com/tutorials/install-ubuntu-on-wsl2-on-windows-10#1-overview) to get started.
>
>* After Ubuntu is installed on your WSL2, Open VS Code and open Extensions `(Ctrl+Shift+X)` and search for Remote - WSL and install it.
>
>* Now click on the Green Button on the bottom left corner to start a remote window (Ubuntu), click on `New WSL Window Using Distro` and finally select `Ubuntu 20.04`
>
>This opens a workspace in your Ubuntu WSL2

## Networking
We all hate it but your software needs to be restricted and also allowed across the internet. And often you will hear about networking terminologies. Here's a video to ensure that you don't get an impostor syndrome at work for not knowing it.FYI We all feel it :D -> [Networking Basics](https://www.youtube.com/watch?v=OqsXzkXfwRw).

## Your First Assignment
- I can't emphasize it enough but what makes you a great developer is how well you can document your work. Hence the first thing we shall do is clone this repo and either beautify it or add any additional info that shall be useful for your upcoming colleagues. Note- We are not looking to share subject expert material here.
> So let's start with having a section for developers and then a section of skills they have with proper hyperlinks.
- Once our batch is onboarded with the fundamentals above, we can jump on to our internal full stack project [here](https://github.com/caxefaizan/slackapp).
> Here you can either choose to work on the front end of the application, backend of the application or the cloud operations of the app. Well if you love being a full stack dev. The stage is yours. Note: For the Slack App our Dependant frameworks are : Python, GCP, Flask, HTML, Postgres.


## My First Assignment
 Hi , 
     I am Vaibhav Nirmal pursuing B.Tech (final year) in IT. I have joined Blue Altair as a Intern.
     In my first Assignment I contributed below useful things.

### Getting & Creating Projects

| Command | Description |
| ------- | ----------- |
| `git init` | Initialize a local Git repository |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Create a local copy of a remote repository |

### Basic Snapshotting commands

| Command | Description |
| ------- | ----------- |
| `git status` | Check status |
| `git add [file-name.txt]` | Add a file to the staging area |
| `git add -A` | Add all new and changed files to the staging area |
| `git commit -m "[commit message]"` | Commit changes |
| `git rm -r [file-name.txt]` | Remove a file (or folder) |

### Branching & Merging commands

| Command | Description |
| ------- | ----------- |
| `git branch` | List branches (the asterisk denotes the current branch) |
| `git branch -a` | List all branches (local and remote) |
| `git branch [branch name]` | Create a new branch |
| `git branch -d [branch name]` | Delete a branch |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git checkout -b [branch name]` | Create a new branch and switch to it |
| `git checkout -b [branch name] origin/[branch name]` | Clone a remote branch and switch to it |
| `git branch -m [old branch name] [new branch name]` | Rename a local branch |
| `git checkout [branch name]` | Switch to a branch |
| `git checkout -` | Switch to the branch last checked out |
| `git checkout -- [file-name.txt]` | Discard changes to a file |
| `git merge [branch name]` | Merge a branch into the active branch |
| `git merge [source branch] [target branch]` | Merge a branch into a target branch |
| `git stash` | Stash changes in a dirty working directory |
| `git stash clear` | Remove all stashed entries |

### Sharing & Updating Projects

| Command | Description |
| ------- | ----------- |
| `git push origin [branch name]` | Push a branch to your remote repository |
| `git push -u origin [branch name]` | Push changes to remote repository (and remember the branch) |
| `git push` | Push changes to remote repository (remembered branch) |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git pull` | Update local repository to the newest commit |
| `git pull origin [branch name]` | Pull changes from remote repository |
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Add a remote repository |
| `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` | Set a repository's origin branch to SSH |

### Inspection & Comparison

| Command | Description |
| ------- | ----------- |
| `git log` | View changes |
| `git log --summary` | View changes (detailed) |
| `git log --oneline` | View changes (briefly) |
| `git diff [source branch] [target branch]` | Preview changes before merging |

## My First Assignment
 Hi , 
     I am Prashant Bagde. I have joined Blue Altair as a Intern.
     In my first Assignment I contributed below useful things.
### Features of Git
Tracks history
Free and open source
Supports non-linear development
Creates backups
Scalable
Supports collaboration
Branching is easier
Distributed development
dev-git
![download](https://www.simplilearn.com/ice9/free_resources_article_thumb/dev-git.JPG)

### Git Workflow
![download](https://www.simplilearn.com/ice9/free_resources_article_thumb/git-workflow.JPG)

The Git workflow is divided into three states:

Working directory - Modify files in your working directory
Staging area (Index) - Stage the files and add snapshots of them to your staging area
Git directory (Repository) - Perform a commit that stores the snapshots permanently to your Git directory. Checkout any existing version, make changes, stage them and commit.
working-directory

![download](https://www.simplilearn.com/ice9/free_resources_article_thumb/working-directory.JPG)

### Branch in Git
Branch in Git is used to keep your changes until they are ready. You can do your work on a branch while the main branch (master) remains stable. After you are done with your work, you can merge it with the main office.

![download](https://www.simplilearn.com/ice9/free_resources_article_thumb/small-feature.JPG)

The above diagram shows there is a master branch. There are two separate branches called “small feature” and “large feature.” Once you are finished working with the two separate branches, you can merge them and create a master branch.



