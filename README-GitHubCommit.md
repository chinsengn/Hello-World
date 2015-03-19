

## A Readme markdown file on how to commit files to Git

### First start the Git Shell. 

### Next, use `cd` to switch to the folder where the file resides

### Then at the shell prompt, enter 
> git init

### Tells Git that I want to commit `README.md`
> git add README.md  

### Actually commits the file with the comments in quotes
> git commit -m "first commit"  

### next line tells git where to send the commit file to at the GitHub repo. Note you must create that repo first!
> git remote add origin https://github.com/chinsengn/Hello-World.git

### next line will push the local file up to GitHub
> git push -u origin master


