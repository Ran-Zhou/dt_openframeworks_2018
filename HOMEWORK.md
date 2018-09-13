# Pushing your Homework to Git

Every week before class you should upload your code to your homework repo on GitHub.  
In Git, uploading/syncing files to GitHub is called "pushing".  (the opposite of "pulling", or syncing _from_ GitHub) 

Here are the basic commands to **push** all your homework code to GitHub.
Feel free to bookmark this page to refer back to these instructions later.  As you practice typing them out, you'll begin to remember them: 


```bash
# inside your local repo, i.e. 'cd ~/Documents/openFrameworks/henrt555_dtOf_2018/' ...

git status								# just helpful - displays a list of recently modified files

# step 1
git add -A 								# add ("stage") _all_ files. -A means "all".  You could instead specify a list of files.  

# step 2
git commit -m "your commit message" 	# "commit": confirm the added file changes / Git takes a snapshot
										# "-m" adds a commit log message, e.g. "homework week 3"
# step 3
git push origin master					# "push" the new "commit" to the "origin": your remote repo on GitHub
										# "master" is always the default version (the main "branch") of your repo

```

If you ran those steps, reload your homework repo's page on GitHub.com. You should see the synced files appear with a new commit message.