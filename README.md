<p align="center"><img src="./images/Git-Logo-1788C.png" alt="Git-Logo" width="400"/></p>

<div align="center">
<h1><b>Git Commands</b></h1>
</div>

<div align="center">
<h2><b><i>Curated list of commonly used Git commands.</i></b></h2>
</div>

## Table of contents

  - [Setup and Config](#setup-and-config)
  - [Getting and Creating Projects](#getting-and-creating-projects)
  - [Basic Snapshotting](#basic-snapshotting)
  - [Branching and Merging](#branching-and-merging)
  - [Sharing and Updating Projects](#sharing-and-updating-projects)
  - [Inspection and Comparison](#inspection-and-comparison)
  - [Patching](#patching)

## Setup and Config

| **Name** | **Command** | **Description** |
| :---:    |    :----:   |      :---:      |
| git      | `git --version` | Install [Git](https://git-scm.com/downloads) & check the version. |
| config user_name | `git config --global user.name "John Doe"` | Git global configuration settings. |
| config email | `git config --global user.email johndoe@example.com` | Git global configuration settings. |
| config user_name | `git config user.name "John Doe"` | Git configuration settings on the current repository settings. |
| config email | `git config user.email johndoe@example.com` | Git configuration settings on the current repository settings. |

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Getting and Creating Projects

| **Name** | **Command** | **Description** |
| :---:    |    :----:   |      :---:      |
| init | `git init` | Initialize a local Git repository |
| clone | `git clone SSH: git@github.com/<username>/<repository-name>.git` | Create a local copy of a remote repository |

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Basic Snapshotting

| **Name** | **Command** | **Description** |
| :---:    |    :----:   |      :---:      |
| add | `git add <file or directory name>` | Add a file or folder to the staging area |
| add | `git add .` | Add all file or folder to the staging area |
| status | `git status` | Check status |
| commit | `git commit -m "Commit message in quotes"` | Adding a commit with message |
| rm | `git rm -r -f <file_name / directory_name>` | Remove a file / directory (force) |
| mv | `git mv -f <source> <destination>` | Move or rename a file / directory (force) |

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Branching and Merging

| **Name** | **Command** | **Description** |
| :---:    |    :----:   |      :---:      |
| branch | `git branch <branch_name>` | Create a new branch |
| branch | `git branch -a` | List all remote or local branches |
| branch | `git branch -d <branch_name>` | Delete a branch |
| checkout | `git checkout <branch_name>` | Checkout an existing branch |
| checkout | `git checkout -b <new_branch>` | Create a new branch and switch to it |
| merge | `git merge <branch_name>` | Merge changes into current branch |
| merge | `git merge <source_branch> <target_branch>` | Merge a branch into a target branch |
| stash | `git stash -u` | Store current work with untracked files |
| stash | `git stash pop` | Bring stashed work back to the working directory |

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Sharing and Updating Projects

| **Name** | **Command** | **Description** |
| :---:    |    :----:   |      :---:      |
| fetch | `git fetch origin` | A copy of our remote repository (located at “origin”) is downloaded and saved to our local machine |
| pull | `git pull <branch_name> <remote_URL/remote_name>` | This pulls the changes from the remote repository to the local computer |
| push | `git push origin <branch_name>` | Push a branch to your remote repository |
| push | `git push —all` | Push all local branches to remote repository |
| remote | `git remote add origin SSH: git@github.com/<username>/<repository-name>.git` | Add a remote repository |

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Inspection and Comparison

| **Name** | **Command** | **Description** |
| :---:    |    :----:   |      :---:      |
| show | `git show commitA...commitD` | This will output all commits in the range from commitA to commit D |
| log | `git log` | Show entire git log |
| log | `git log --<author>="Author Name"` | Show git log based on commit author |
| log | `git log --summary` | View changes (detailed) |
| diff | `git diff <source_branch> <target_branch>` | Preview changes before merging |

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Patching

| **Name** | **Command** | **Description** |
| :---:    |    :----:   |      :---:      |
| rebase | `git rebase -i <branch_name>` | The git rebase command is used to merge the history of two branches on a repository |
| revert | `git revert <commit_to_revert>` | Revert last commit |

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## 🛡️ License

This project is licensed under the MIT License - see the [`LICENSE`](LICENSE) file for details.

## 🙏 Support

This project needs a ⭐️ from you. Don't forget to leave a star ⭐️

If you like this project, please consider <b>Buying Me a Coffee.</b> 

Thanks for the Support. 😍

<div align="center">
<a href="https://www.buymeacoffee.com/syedsohan" target="_blank"><center><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;"></center></a>
</div>
