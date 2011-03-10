GIT Cheat sheet
===============

## Some useful git commands

### Checkout out a repository from remote source
	git clone *url*

### Get Updates from repository server and merge them in local checkout
	git pull

### Initialize a repository
	git init  
	git add . 
	git commit

### Get a status of changed files/folders
	git status

### Applying a patch
	git apply


### To restore a file from the last revision
	git checkout *path*

### Adding / Updating / Deleting / Moving -
	git add file
	git rm file 
	git mv file

### Committing changes to repository
	git commit -a -m "Commit Msg"

### Look for changes in the repository
	git log
	git blame file
	
### See contents of a file, listing of directory or commit
    git show rev:path/to/file 
    git show rev:path/to/directory 
    git show rev


