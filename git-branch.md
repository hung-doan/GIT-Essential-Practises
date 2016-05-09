Ref: http://stackoverflow.com/questions/2003505/delete-a-git-branch-both-locally-and-remotely

1. Git delele local branch
````
$ git branch --delete <branch>
$ git branch -d <branch> # Shorter version
$ git branch -D <branch> # Force delete un-merged branches
````

2. Deleting a remote branch:
git push origin --delete <branch>  # Git version 1.7.0 or newer
git push origin :<branch>          # Git versions older than 1.7.0
