---
{"dg-publish":true,"dg-path":"Soleil/Shell.md","permalink":"/soleil/shell/","created":"2024-12-16T17:00:58.089+08:00","updated":"2024-12-17T15:47:45.668+08:00"}
---

2024-12-16
Status: #idea
Tags: [[Vanilla/Soleil/Web Development\|Web Development]]
# Shell
- The shell is a program where users can type commands.
- When the shell is first opened, you are presented with a **prompt**
- Most popular Shell is Bash
# CLI
- Stands for (Command Line Interface)
- Can be accessed in windows via terminal

![CLI.png](/img/user/Vanilla/Files/CLI.png)
# BASH

- Stands for "Bourne Again Shell"
- is the most common [[Vanilla/Soleil/Shell\|Shell]] for Unix based systems (MacOS, Linux).
- Windows uses [[Vanilla/Soleil/Git\|Git]] bash for [[Vanilla/Soleil/Git\|Git]] version control via terminal.

## Commands and Syntax

- "xxx" here will refer to a name, be it a file name or directory name.
- This will not be a full comprehensive list of syntaxes, just enough to get started (because who the hell genuinely remembers everything anyways)


General Syntax of a Shell Command (taken from swcarpentry.github.io):
![syntaxShell.png](/img/user/Vanilla/Files/syntaxShell.png)


## Commands 
| Commands | Function/Purpose                                                            | Example use case                              |
| -------- | --------------------------------------------------------------------------- | --------------------------------------------- |
| pwd      | Print Working Directory (AKA where you're at now)                           | pwd                                           |
| ls       | List Items (Default in current category)                                    | ls                                            |
| man      | Shows the manual for said command                                           | man [Command]                                 |
| cd       | Change directory (if used without argument, returns to base/root directory) | cd [Directory Name]                           |
| mkdir    | Makes a Directory                                                           | mkdir [Directory Name]                        |
| cp       | Duplicates a file (Copy in Windows) *                                       | cp [Old File] [New Directory]                 |
| mv       | Moves a file (Cut in Windows) *                                             | mv [File] [New Directory]                     |
| rm       | Removes a file/Directory *                                                  | rm [Target]                                   |
| nano     | Opens the nano text editor                                                  | nano [File]                                   |
| touch    | Makes an empty file                                                         | touch [FileName.Extension]                    |
| cat      | Prints the contents of a file, as well as concatenates files                | cat [File] //(This is the print version only) |

*To affect an entire directory, you need to use -r (recursive)

## Arguments

| Arguments (Short Form) | What it does                                                       |
| ---------------------- | ------------------------------------------------------------------ |
| -F                     | Classifies output by adding markers (like /, @, *)                 |
| --help                 | lists syntax and modifiers                                         |
| -l                     | long listing format                                                |
| -r                     | reverse *                                                          |
| -R                     | recursive flag *                                                   |
| -a                     | show all                                                           |
| -t                     | last modified                                                      |
| *                      | matches zero or more characters in a filename (basically wildcard) |
| ?                      | Stricter Wildcard                                                  |

*often times, -r and -R both mean recursive unless reverse is applicable.
## Markers

| Markers | What they indicate                     |
| ------- | -------------------------------------- |
| /       | Directory (returns root if used alone) |
| *       | Executable                             |
| @       | Link                                   |


# References
[The Unix Shell: Introducing the Shell](https://swcarpentry.github.io/shell-novice/01-intro.html)