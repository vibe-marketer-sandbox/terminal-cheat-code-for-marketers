# Terminal Cheat Code for Marketers

A beginner-friendly cheat sheet for marketers who want to use Claude Code the right way, in the terminal.

---

## Terminal Basics

Navigate, create, and manage files & folders.

### Navigation

| What you want to do | Command |
|---|---|
| See where you are | `pwd` |
| List files in current folder | `ls` |
| List files with details | `ls -la` |
| Go into a folder | `cd folder-name` |
| Go back one level | `cd ..` |
| Go to home directory | `cd ~` |

### Creating

| What you want to do | Command |
|---|---|
| Create a new folder | `mkdir folder-name` |
| Create nested folders | `mkdir -p parent/child` |
| Create a new file | `touch filename.md` |

### Viewing

| What you want to do | Command |
|---|---|
| Read a file | `cat filename.md` |
| Open file in default editor | `open filename.md` |

### Deleting & Moving

| What you want to do | Command |
|---|---|
| Delete a file | `rm filename.md` |
| Delete a folder & everything inside | `rm -rf folder-name` |
| Move or rename a file | `mv old-name new-name` |
| Copy a file | `cp file.md copy.md` |

> ⚠️ **Be careful with `rm -rf`**. It permanently deletes everything. There's no undo. Double-check the folder name before running it.

---

## Git Essentials

Version control: save, track, and sync your work.

### Setup (one time)

| What you want to do | Command |
|---|---|
| Set your name | `git config --global user.name "Your Name"` |
| Set your email | `git config --global user.email "you@email.com"` |

### Starting a project

| What you want to do | Command |
|---|---|
| Initialize git in a folder | `git init` |
| Clone an existing repo | `git clone url` |

### Daily workflow

| What you want to do | Command |
|---|---|
| Check what's changed | `git status` |
| Stage all changes | `git add .` |
| Stage a specific file | `git add filename` |
| Save your changes | `git commit -m "what you changed"` |
| See commit history | `git log --oneline` |

### Syncing with GitHub

| What you want to do | Command |
|---|---|
| Push your changes | `git push` |
| Pull latest changes | `git pull` |

### Branches (when you're ready)

| What you want to do | Command |
|---|---|
| See all branches | `git branch` |
| Create & switch to new branch | `git checkout -b branch-name` |
| Switch to a branch | `git checkout branch-name` |

> 💡 **The daily loop:** `git add .` → `git commit -m "message"` → `git push`. That's 90% of what you'll ever do. Master this first, everything else is optional.

---

## Resources

- [Git Basics Videos (YouTube)](https://www.youtube.com/results?search_query=git+basics)
- [Full Git Cheat Sheet (PDF)](https://education.github.com/git-cheat-sheet-education.pdf)
