# Git Cheat Sheet

## Init & Clone

- Create a new local new repo in current directory

  > git init

- Download a projectwith history from remote repo
  > git clone <url>

---

## Configure User

> git config --global user.name "[username]"

> git config --global user.email "[userEmail]"

---

## To view files

> cd

> ls

> ls --all

## Working with Stages

- Show modified files in working directory & staging area.

  > git status

- Add a file to your next commit (stage).

  > git add [filename]

- Unstage a file while keeping changes (unstage).

  > git reset [filename]

- Show difference between files (un/staged vs committed).

  > git diff

- Show difference between staged & unstaged files.

  > git diff --staged

- Commit staged changes as a snapshot.
  > git commit -m "[message]"

---

### Init Command

> git init

> git remote add origin [link]

> git remote -v

> git branch

> git branch -M main

---

## PUSH

> git push origin main

or

> git push -u origin main

## Branches & Merging:

### Create & Switch Branches:

- Create a new branch.

  > git branch [branchName]

  or

  > git checkout -b [newBranchName]

- Switch to a different branch.

  > git checkout [branchName]

- Delete a branch
  > git branch -d [branchName]

---

### Merge Branches:

Combine changes from another branch into current one.

> git merge [branch name]:

### View History:

- Show commit history with details.

> git log

- Track changes of a specific file across commits.
  > git log --follow [file]
