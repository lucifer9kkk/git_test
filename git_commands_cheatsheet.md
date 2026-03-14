
# Git Command Line Code

| Code | Meaning |
|---|---|
| `git --version` | To check if Git is installed |
| `git config --global user.name "Your Name"` | To set Git username |
| `git config --global user.email "your@email.com"` | To set Git email |
| `git config --list` | To see Git configuration |
| `git init` | To initialize a new Git repository in a folder |
| `git clone [repository link]` | To copy a repository from GitHub to your computer |
| `git status` | To check current status of files in repository |
| `git add [file name]` | To add a specific file to staging area |
| `git add .` | To add all files to staging area |
| `git commit -m "message"` | To save staged changes as a commit |
| `git commit -am "message"` | To add and commit tracked files together |
| `git log` | To see full commit history |
| `git log --oneline` | To see short commit history |
| `git remote add origin [repo link]` | To connect local repository to GitHub |
| `git remote -v` | To see connected remote repositories |
| `git push -u origin main` | To push code to GitHub first time |
| `git push` | To upload commits to GitHub |
| `git pull` | To download latest changes from GitHub |
| `git fetch` | To fetch changes from remote repository without merging |
| `git branch` | To see all branches |
| `git branch [branch name]` | To create a new branch |
| `git checkout [branch name]` | To switch to another branch |
| `git checkout -b [branch name]` | To create and switch to a new branch |
| `git merge [branch name]` | To merge another branch into current branch |
| `git rm [file name]` | To remove a file from Git repository |
| `git mv [old name] [new name]` | To rename or move a file in Git |
| `git diff` | To see changes between commits or files |
| `git restore [file]` | To discard changes in a file |
| `git reset [file]` | To remove file from staging area |
| `git reset --hard` | To reset repository to last commit (dangerous) |

---

## Typical Daily Git Workflow

```bash
git status
git add .
git commit -m "describe changes"
git push
```
