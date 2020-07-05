
Tiis is my working github repository that i used while learning to use github. So, normally when you make changes in a code, first it needs to be added to the staging area, 
you commit that code from staging area to branch master and then you push your code to remote repository. 

Any files or folder included in gitignore file are not sent to staging area.

The commands i learned include 

1 git status // displays status of current staging area, and changed files if they are not add to staging area
2 git add something.anyextension // adds any file mentioned to staging area
3 git add . // add all changed files to staging area
4 git restore . // removes all changed files from staging area
5 git commit -md 'Enter comment for commit' // commits code changed in staging area to master
6 git remote // shows if you have any remote repository for your code
7 git remote add origin (Link to github repository) // adds remote repository to your local code  
8 git push -u origin master // pushes code to your remote repository
9 git branch login // creates a new branch (codes changed in this branch do not affect master branch)
10 git checkout login // changes branch from master to login branch
11 git merge login // merges the changes in login branch to master branch 