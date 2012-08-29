GIT Cheat sheet
===============

***["Good to Know" overview](/piscis/good-to-know)***

## Links
* [stackoverflow.com/questions/3419658/understanding-git-fetch-then-merge](http://stackoverflow.com/questions/3419658/understanding-git-fetch-then-merge) - answer to svn status -u update problem   
* [git.or.cz/course/svn.html](http://git.or.cz/course/svn.html) - svn2git converter guide  
* [gitready.com](http://gitready.com) - A good beginners guide
* [learn.github.com](http://learn.github.com) - Good quick reference

***

## Useful setup commands
> git config --global user.name "Your Name Comes Here"  
> git config --global user.email you@yourdomain.example.com 

***

## Basic Git commands

### Checkout out a repository from remote source
> git clone *url*  

### Get Updates from repository server and merge them in local checkout
> git pull  

### Initialize a repository
> git init  
> git add .  
> git commit  

### Get a status of changed files/folders
> git status  

### Applying a patch
> git apply  

### To restore a file from the last revision
> git checkout *path*  

### Adding / Updating / Deleting / Moving -
> git add *file*  
> git rm *file*  
> git mv *file*  

### Committing changes to repository
> git commit -a -m "Commit Msg"  

### Look for changes in the repository
> git log  
> git blame file  
	
### See contents of a file, listing of directory or commit
> git show rev:path/to/file  
> git show rev:path/to/directory  
> git show rev  

***

## Tagging and branching

### Create a tag
> git tag -a name  
	
### List a tag + list tag msg
> git tag -l  
> git show tag  
	
### Create and use a branch
> git branch *branch*  
> git checkout *branch*  

### Get a list of branchnames
> git branch  

### Move tree to a older revision
> git checkout *rev*  
> git checkout *prevbranch*  

***

## Git + Remote commands

### Switching to a remote branch
> git checkout --track -b branch origin/branch  

### Show the remote repositories
> git remote show  
> git remote show *origin*  

***
