<div align="center">

# Linux Lab 01
### File System and Navigation

<img src="https://img.shields.io/badge/Linux-Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white">
<img src="https://img.shields.io/badge/Level-Beginner-28A745?style=for-the-badge">
<img src="https://img.shields.io/badge/Shell-Bash-black?style=for-the-badge&logo=gnubash">

</div>

---

# Commands Reference

This document contains every command used throughout **Linux Lab 01** with a brief explanation of its purpose.

---

## Current Working Directory

```bash
pwd
```

Displays the absolute path of the current working directory.

---

## Listing Files

### Standard Listing

```bash
ls
```

Lists files and directories.

### Detailed Listing

```bash
ls -l
```

Displays permissions, ownership, file size and modification date.

### Display Hidden Files

```bash
ls -la
```

Displays all files, including hidden files.

---

## Directory Navigation

### Change Directory

```bash
cd directory_name
```

Moves into a directory.

### Parent Directory

```bash
cd ..
```

Moves one level up.

### Home Directory

```bash
cd ~
```

Returns to the current user's home directory.

### Previous Directory

```bash
cd -
```

Returns to the previous location.

---

## Creating Directories

### Single Directory

```bash
mkdir LinuxLab
```

Creates one directory.

### Multiple Directories

```bash
mkdir Documents Scripts Backups
```

Creates several directories simultaneously.

### Nested Directories

```bash
mkdir -p Projects/Web/Application
```

Creates nested directories automatically.

---

## Creating Files

```bash
touch notes.txt
```

Creates an empty file.

Multiple files:

```bash
touch report.txt config.conf backup.log
```

---

## Viewing File Contents

```bash
cat notes.txt
```

Displays the contents of a file.

---

## Copying Files

```bash
cp notes.txt backup.txt
```

Copies a file.

Copy an entire directory:

```bash
cp -r Documents Documents_Backup
```

---

## Moving Files

```bash
mv backup.txt Backups/
```

Moves a file to another directory.

---

## Renaming Files

```bash
mv notes.txt lab_notes.txt
```

Renames a file.

---

## Removing Files

```bash
rm lab_notes.txt
```

Deletes a file.

---

## Removing Directories

```bash
rmdir EmptyFolder
```

Deletes an empty directory.

Recursive removal:

```bash
rm -r Projects
```

Deletes a directory and all its contents.

---

## Searching Files

```bash
find . -name "*.txt"
```

Searches recursively for every `.txt` file.

---

## Displaying the Directory Tree

```bash
tree
```

Displays the complete directory hierarchy.

Install Tree if necessary:

```bash
sudo apt install tree
```

---

## Clearing the Terminal

```bash
clear
```

Clears the terminal window.

---

## Command History

```bash
history
```

Displays previously executed commands.

---

# Command Summary

| Command | Purpose |
|----------|---------|
| `pwd` | Display current working directory |
| `ls` | List files and directories |
| `ls -l` | Detailed directory listing |
| `ls -la` | Show hidden files |
| `cd` | Change directory |
| `mkdir` | Create directories |
| `touch` | Create files |
| `cat` | Display file contents |
| `cp` | Copy files or directories |
| `mv` | Move or rename files |
| `rm` | Remove files |
| `rmdir` | Remove empty directories |
| `find` | Search for files |
| `tree` | Display directory hierarchy |
| `history` | Show command history |
| `clear` | Clear terminal |

---

<div align="center">

### Skills Practiced

`Linux Navigation` • `File Management` • `Directory Management` • `Shell Commands` • `System Administration Fundamentals`

</div>
