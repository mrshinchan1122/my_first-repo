# 🚀 Git Commands Cheat Sheet (All-In-One)

```bash
# Setup & Configuration
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
git config --list

# Creating & Initializing
git init
git clone <repo-url>

# Staging & Committing
git status
git add <file>
git add .
git commit -m "message"
git commit --amend

# Branching & Merging
git branch
git branch <name>
git checkout <branch>
git checkout -b <branch>
git branch -d <branch>
git branch -D <branch>
git push origin --delete <branch>
git branch -m <new-name>
git push origin <new-name>
git push origin --delete <old-name>
git checkout main --index.html

# Merging
git merge <branch>
git merge --no-ff <branch>

# Cherry-Pick
git cherry-pick <commit-hash>
git cherry-pick --abort
git reset --hard HEAD~1
git cherry-pick <start> -- <end>

# Rebase
git rebase <branch>
git rebase --skip
git rebase --continue

# Pull with Rebase
git pull --rebase origin main

# Commit Amend
git commit --amend

# Remote Repositories
git remote -v
git remote add origin <url>
git push origin <branch>
git pull origin <branch>
git fetch
git push origin --delete <branch>
git remote remove origin
git remote set-url origin <url>

# Logs & History
git log
git log --oneline --graph --all
git reflog

# Reset, Revert & Clean
git reset --hard <commit>
git revert <commit>
git clean -fd

# Stash
git stash
git stash push -m "msg"
git stash list
git stash apply stash@{0}
git stash drop stash@{0}
git stash branch <branch>
git stash clear

# Tags
git tag
git tag <tag-name>
git tag -a <tag-name> -m "message"
git push origin <tag>
git push origin :refs/tags/<tag>
git show <tag-name>
git cat-file -t <tag-name>
git tag newname oldname
git tag -d oldname
git push origin :refs/tags/oldname
git push origin newname

# Git Fetch
git fetch origin

# Git Reflog (Reference Log)
git reflog

# Other Essentials
# .gitignore - Exclude files from version control
# GitHub Gist - Share single or multi-file code snippets
# GitHub Wiki - Project-level documentation
# GitHub Issues - Track bugs, features, tasks
# GitHub Pages - Host static sites from GitHub repos
# GitHub Templates - Reuse template repos, issues, or PRs
