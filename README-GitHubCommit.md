

#starts 
> git init

#tells Git that i want to commit README.md
> git add README.md  

#actually commits the file with the comments in quotes
> git commit -m "first commit"  

# next line tells git where to send the commit file to at the GitHub repo
# note you must create that repo first!
> git remote add origin https://github.com/chinsengn/Hello-World.git

# next line will push the local file up to GitHub
> git push -u origin master


