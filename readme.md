# Linux & Git Command Cheat Sheet

## Linux Commands

### 1. ls
Description: Lists files and directories.
Example:
```bash
ls -a   # lists all files, including hidden files, and directories. 
```

### 2. cd
Description: Changes directory.
Example:
```bash
cd Downloads   # moves into the Downloads folder directory.
```

### 3. mkdir
Description: Creates a new directory.
Example:
```bash
mkdir sample_repo   # makes a new directory called "sample_repo"
```

### 4. rm
Description: Removes files and directories.
Example:
```bash
rm file1.txt   # removes the file called file1.txt
```

### 5. touch
Description: Creates an empty file or updates file timestamps. 
Example:
```bash
touch readme.md   # creates a new readme.md file
```

### 6. pwd
Description: Prints the current working directory. 
Example:
```bash
pwd   # just typing pwd shows the path to your current directory you are in.
```

### 7. mv
Description: Moves/renames files and directories.
Example:
```bash
mv file1.txt file1complete.txt   # renames file1.txt to file1complete.txt
```

### 8. cp
Description: Copies files and directories.  
Example:
```bash
cp file1.txt allFiles.txt   # this copies file1.txt into allFiles.txt
```

## Git Commands

### 9. git init
Description: Initializes an existing directory as a Git repository.
Example:
```bash
git init   # this is how you turn your current folder/directory into a Git repository.
```

### 10. git branch [branch-name]
Description: Creates a new branch that is at the current commit.
Example:
```bash
git branch pwd   # this creates a new branch called pwd.
```

### 11. git commit -m "[descriptive message]"
Description: Commits and saves your staged content as a new commit snapshot with a descriptive message.
Example:
```bash
git commit -m "added readme.md file"   # saves your staged changes with a descriptive message.
```

### 12. git checkout
Description: Switches to another branch in your repository and checks it out into your working directory.
Example:
```bash
git checkout main   # switches to the main branch.
```

### 13. git status
Description: Shows the modified files in your working directory, staged for your next commit. 
Example:
```bash
git status   # displays the staged/modified files in the directory.
```

### 14. git merge [branch]
Description: Merges the changes you made from the specified branch into the current one. 
Example:
```bash
git merge pwd   # merges the pwd branch into the current branch.
```

### 15. git push [alias] [branch]
Description: Pushes your local branch commits to the remote repository branch, such as GitHub.
Example:
```bash
git push origin main   # pushes the local main to the remote main, such as GitHub.```

### 16. git pull
Description: Fetches and merges any commits from the remote branch into your current working branch. 
Example:
```bash
git pull origin main   # updates the local main with changes from remote main, such as GitHub.
```

