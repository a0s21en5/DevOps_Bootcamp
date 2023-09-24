## Day 1 : Complete Git and GitHub

# What is Git and Github?
Git is a distributed version control system that allows multiple people to collaborate on a project simultaneously. It tracks changes to files and allows users to merge and manage different versions of a project.

GitHub, on the other hand, is a web-based hosting service for Git repositories. It provides a platform for developers to store, manage, and share their code with others. GitHub offers additional features like issue tracking, pull requests, and collaboration tools, making it popular for open-source projects and team collaborations.

# Why are we using Git and Github?
we use Git and GitHub because they offer a robust and efficient way to manage and collaborate on software development projects. Git helps us track changes and work on different branches, while GitHub provides a convenient online platform for hosting and collaborating on Git repositories.

# Some basic Linux commands

- `ls`: Lists files and directories in the current directory.
   - Example: `ls -l` (displays detailed information)

- `cd`: Changes the current directory.
   - Example: `cd /path/to/directory` (changes to a specific directory)

- `pwd`: Prints the current working directory.

- `mkdir`: Creates a new directory.
   - Example: `mkdir new_directory` (creates a directory named "new_directory")

- `rm`: Removes a file or directory.
   - Example: `rm file.txt` (removes a file)
   - Example: `rm -r directory` (removes a directory and its contents)

- `cp`: Copies files and directories.
   - Example: `cp file.txt destination/` (copies "file.txt" to the "destination" directory)

- `mv`: Moves or renames files and directories.
   - Example: `mv file.txt new_location/` (moves "file.txt" to the "new_location" directory)
   - Example: `mv old_name.txt new_name.txt` (renames "old_name.txt" to "new_name.txt")

- `cat`: Displays the contents of a file.
   - Example: `cat file.txt` (displays the contents of "file.txt")

- `grep`: Searches for a specific pattern in files.
   - Example: `grep "pattern" file.txt` (searches for "pattern" in "file.txt")

- `chmod`: Changes the permissions of a file or directory.
   - Example: `chmod +x script.sh` (gives execute permission to "script.sh")

- `sudo`: Executes a command with administrative privileges.
   - Example: `sudo apt-get update` (updates system packages using the APT package manager)

- `man`: Displays the manual pages for a command.
   - Example: `man ls` (displays the manual for the "ls" command)

# Git Cheat Sheet

## Basic Commands

- ```git init``` : Initializes a new Git repository.
- ```git clone <repository>``` : Clones a remote repository to your local machine.
- ```git add <file>``` : Adds a file to the staging area.
- ```git commit -m "Commit message"``` : Commits the changes in the staging area with a descriptive message.
- ```git status``` : Displays the current status of the repository.
- ```git log``` : Shows the commit history.
- ```git push``` : Pushes local changes to a remote repository.
- ```git pull``` : Fetches and merges changes from a remote repository to the current branch.

## Branching and Merging

- ```git branch``` : Lists all branches in the repository.
- ```git branch <branch-name>``` : Creates a new branch.
- ```git checkout <branch-name>``` : Switches to the specified branch.
- ```git merge <branch-name>``` : Merges changes from the specified branch into the current branch.
- ```git rebase <branch-name>``` : Applies changes from the specified branch on top of the current branch.

## Remote Repositories

- ```git remote add <remote-name> <remote-url>``` : Adds a new remote repository.
- ```git remote -v``` : Lists all remote repositories.
- ```git pull <remote-name> <branch-name>``` : Fetches and merges changes from a remote repository and branch.
- ```git push <remote-name> <branch-name>``` : Pushes changes to a remote repository and branch.

## Undoing Changes

- ```git reset <file>``` : Unstages a file.
- ```git checkout <file>``` : Discards changes in a file.
- ```git revert <commit>``` : Reverts a commit.

## Additional Resources

- [Git Documentation](https://git-scm.com/doc)
- [Pro Git Book](https://git-scm.com/book)
