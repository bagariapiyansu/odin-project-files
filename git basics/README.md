# Development Environment Setup and Git Basics

## A. Essential Tools Installation

- **VS Code:** IDE for writing codes
- **Git Bash:** For version control

## B. The Web

- Basic understanding of how the web works (client-server model)
- The role of HTTP and DNS in web communication
- Introduction to HTML, CSS, and JavaScript as the building blocks of websites

**Key takeaway:** Grasping the interaction between clients and servers is essential for future web development.

## C. Command Line Basics

The command line allows for direct interaction with the operating system via text-based commands.

### Basic Navigation Commands

- `pwd`: Print working directory to show the current directory
- `ls`: List files and directories
- `cd`: Change directories
- `mkdir`: Create a new directory
- `rm`: Remove files or directories

### Commands for Manipulating Files and Directories

- `touch`: Create an empty file
- `mv`: Move or rename files
- `cp`: Copy files or directories
- `rm -r`: Recursively remove directories

## D. Git Basics

- Git is a critical tool for software development, particularly for tracking changes and collaborating efficiently
- Understanding version control and the importance of Git in collaborative projects

### Basic Git Commands Learned

- git init, git add, git commit, git status, git log
- Working with repositories and branches
- Pushed code to a remote repository on GitHub

## E. Git Commands in Detail

### Checking Git Version
```bash
git --version
```

### Initializing a Repository
```bash
git init
```
Creates a new Git repository and a hidden folder '.git'

### Staging Changes
```bash
git add <filename>
# or
git add .  # to stage all files
```

### Committing Changes
```bash
git commit -m "message"
```

### Other Important Commands
- `git push`: Push commits to the remote repository
- `git pull`: Fetch and merge changes from the remote repository
- `git status`: Check the status of your working directory
- `git log`: View commit history
  - Use `--all` to show all versions
  - Use `--graph` to show things graphically in command prompt