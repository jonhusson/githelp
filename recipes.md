## Recipes for Working with Git/GitHub

### Making a new GitHub repository.

Make a new repository in GitHub. On your local machine, navigate to root of directory to be stored on GitHub in Terminal. Type:

````
git init
git add .
git commit -m "initial commit"
git remote add origin https://github.com/jonhusson/REPO_NAME
git push -u origin master
````

### Keeping things fresh.

If you make a change to a repository, Git will notice. Type:

````
git status
````

Items in red have been altered. Type:

````
git diff
````

to see what has changed and how. To push changes to GitHub, type:

````
git add -u
git commit -m "YOUR MSG HERE"
git push
````

These three lines of code will be much of what you do!

### Adding new files to repository.

If a file has been added to your local copy of your repository, push it to GitHub! Type:

````
git add FNAME
git commit -m "FNAME added"
git push
````

Its now on GitHub!

### Adding new files to repository.

It is helpful to ignore some files that reside on your local copy, but ones you do not 
want followed and updated by GitHub. On a text editor, create a file called:

````
.gitignore
````

In this file, type out file names you wish to ignore (test.txt in this example). Now, type:

````
git add .gitignore
git commit -m ".gitignore added"
git push
````

If this file has been pushed to the repository, but you no longer want to track changes, type:

````
git rm FNAME
git commit -m "removed FNAME"
git push
````

Now the file has been removed from GitHub, and the file (on your local machine) will not be tracked by Git.