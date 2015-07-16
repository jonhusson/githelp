## Recipes for Working with Git/GitHub

### Making a new GitHub repository

Make a new repository in GitHub. Navigate to root of directory to be stored on GitHub in Terminal. Type:

````
git init
git add .
git commit -m "initial commit"
git remote add origin https://github.com/jonhusson/REPO_NAME
git push -u origin master
````

### Keeping things fresh

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

Website was created by and is maintained by **Jon Husson**, post-doctoral researcher in geology at [Univeristy of Wisconsin - Madison](http://geoscience.wisc.edu/geoscience/).

## Copyright and License

Copyright 2013-2015 Iron Summit Media Strategies, LLC. Code released under the [Apache 2.0](https://github.com/IronSummitMedia/startbootstrap-bare/blob/gh-pages/LICENSE) license.