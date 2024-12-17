---
{"dg-publish":true,"permalink":"/vanilla/soleil/git/"}
---

2024-12-16
Status: #idea
Tags: [[Vanilla/Soleil/Web Development\|Web Development]]
# Git

Git is a cool software that enables you to do version control.
Version control allows you to do things like:
- Rollback
- Systemic Error Management.

>[!info] Take note that Git is the software, while [[Github\|Github]] is a remote repository. It's like the difference of your windows File Explorer compared to Google Drive

In the terminal, you use `git` before any command you need to do.
![Git.png](/img/user/Vanilla/Files/Git.png)

| Command    | What it Does                                             | Example syntax               |
| ---------- | -------------------------------------------------------- | ---------------------------- |
| git add    | Stages a File for Committing                             | git add [file]               |
| git commit | Commit a change (something like put changes in a folder) | git commit -m "message here" |
| git push   | Pushes your commits to your repository                   | git push origin main         |
| git status | Queries the current status of the stage                  | git status                   |
| git clone  | Clones a repository onto the local machine               | git clone (link)             |
>Staging is basically saying "This file is ready for a commit"


# References
[Introduction to Git \| The Odin Project](https://www.theodinproject.com/lessons/foundations-introduction-to-git#git-local)
[Git Basics \| The Odin Project](https://www.theodinproject.com/lessons/foundations-git-basics)