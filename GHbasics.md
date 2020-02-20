## GitHub Basics
### Background
[Git](https://git-scm.com) is a version control tool which allows developers to manage their source code history. It is designed for collaboration since it puts the code in an accessible place where users can download, edit, and push it back with its recorded changes. It is also an open-source tool, meaning the software is freely available and may be redistributed and modified.

[GitHub](https://github.com) is a Git repository hosting service, meaning that it stores your Git projects in their servers. Among many features it contains a graphical user interface (GUI) so you don't need the command line to communicate with your repository.

### Creating a new project

 Command | Description |
| ------- | ----------- |
| `git init` | Initialize a local Git repository |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Create a local copy of a remote repository |

### Basic Commands

| Command | Description |
| ------- | ----------- |
| `git status` | Check status of working tree and staging area |
| `git add [file-name.txt]` | Add a file to the staging area |
| `git add -A` | Add all new and changed files to the staging area |
| `git commit -m "[commit message]"` | Commit changes |
| `git rm -r [file-name.txt]` | Remove a file (or folder) |
| `git push` | Push changes to remote repository|
| `git pull` | Update local repository to the newest commit|
| `git log` (`--summary`/ `--oneline`) | View changes (detailed/ briefly)



