#MyApp
THis is my working first github repository. So, normally when you make changes in a code, first it needs to be added to the staging area, 
you commit that code from staging area to branch master and then you push your code to remote repository. 

Any files or folder included in gitignore file are not sent to staging area.

The commands i learned include 

1 git status // displays status of current staging area, and changed files if they are not add to staging area
1 git add something.anyextension // adds any file mentioned to staging area
2 git add . // add all changed files to staging area
3 git restore . // removes all changed files from staging area
4 git commit -md 'Enter comment for commit' // commits code changed in staging area to master
5 git push -u origin master