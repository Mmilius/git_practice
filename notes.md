# Git is a Distrubted Version Control system--allows mulitple people to work together and share code. It keeps track of the history and version changes. You also don't have to be in the same location. 

# A central hub stores the code. Github stores all our code. We get copies of the code to use and it allows us to all work at the same time on different parts of the code. 

# Git Flow:
#Stage, Commit, and Push

#stage--changes first have to be changed. 

To see what's going on in your local respository you type: git status
the file will be red if it is untracked 

to stage a file: git add (the name of the file) in your terminal 

when it is green it is "staged" --not saved. We're just tracking changes. To save it, we must "Commit" it. 

After any changes, you must Stage it to save it. 
git add . ---the dot will stage everything so be cautious. 

Next yo will: git commit -m "Description of what the commit does in present tense."

the -m is a tag for message. 

git status---gives you back the status if all commited then it will say, "nothing to commit, working tree clean". 

You would want to do a commit for each chunk of code ie. method. 

Push it you write: git push origin(remote repo) master

git remote - v  
^this will will give you the name of the remote repo that lives on GitHub. 

Git push origin master

