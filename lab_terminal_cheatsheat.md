# Terminal commands

## 1. Change Directory

**cd** : Home directory

**cd [folder]** : Change directory, e.g. cd Documents

**cd ~** : Home directory

**cd/** : Root of the drive

**cd -** : Previous directory or folder you last browsed

**pwd** : Show your working directory

**cd..** : Move up to the parent directory


## 2. List Directory Contents

**ls** : Display the name of files and subdirectories in the directory

**ls -C** : Force multi-column output of the listing

**ls -a** : List all entries including those with .(period) and ..(double period)

**ls -1** : Output the list of files in one entry per line format

**ls -F** : Display a / (slash) immediately after each path that is a directory, * (asterisk) after executable programs or scripts, and @ after a symbolic link

**ls -S** : Sort files or entries by size

**ls -l** : List in a long format. Includes file mode, owner and group name, date and time file was modified, pathname, and more

**ls -l** / : List of the file system from root with symbolic links

## 3. File and Directory Management
**rm <file>** : Delete a file (This deletes the file permanently; use with caution.)

**touch <file>** : Create a new file without any extension



# Github commands
## 1. STAGE & SNAPSHOT
*Working with snapshots and the Git staging area*

**git status** : Show modified files in working directory, staged for your next commit

**git add [file]** : 
add a file as it looks now to your next commit (stage)

**git commit -m “[descriptive message]”** : 
commit your staged content as a new commit snapshot

## 2. SETUP & INIT
*Configuring user information, initializing and cloning repositories*

**git init** : 
initialize an existing directory as a Git repository

**git clone [url]** :
retrieve an entire repository from a hosted location via URL


## 3. INSPECT & COMPARE
*Examining logs, diffs and object information*

**git log** : show the commit history for the currently active branch
