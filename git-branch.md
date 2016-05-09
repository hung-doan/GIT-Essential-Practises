Ref: http://stackoverflow.com/questions/2003505/delete-a-git-branch-both-locally-and-remotely

1.Git delele local branch
````
$ git branch --delete <branch>
$ git branch -d <branch> # Shorter version
$ git branch -D <branch> # Force delete un-merged branches
````

2.Deleting a remote branch:
````
$ git push origin --delete <branch>  # Git version 1.7.0 or newer
$ git push origin :<branch>          # Git versions older than 1.7.0
````
3.Update branch upstream
Ref: http://stackoverflow.com/questions/4878249/how-do-i-change-the-remote-a-git-branch-is-tracking
````
$ git branch branch_name --set-upstream-to your_new_remote/branch_name
````
