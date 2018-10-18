#GitLearn
Git is a version control system.

Git is a free software.

we use **git add** to tell git add the file to Git's repository

we use **git commit -m Xxx** to tell Git upload the file 
to repository

we use **git status** to get the result of behavior

we use **git diff xx** to get the revised content

we use **git log** to show recent commits, and enter q to exit git log

 - we could add --pretty=oneline parameter to let git log only show commit id

in git **HEAD** represents the current version, the last version is **HEAD^**, the last last version is **HEAD^^**

- we use **git reset --hard HEAD^** to return last version

- we use **git reflog** to record your every command

- we also can use **commit id** to return version we want

### `.git` the repository of Git

 - Git has a mutable index called **stage**
 - Git create the first branch **master** for us automatically and there has a pointer called **HEAD** point to **master**
 - we use **git commit** to submit all changes to branch
 
we use **git dif HEAD -- XXX** to see the difference between version in workstation and the latest version in **stage**
 
we use **git checkout -- file** to discard revision in workstation

we use **git reset HEAD file** to discard revision in **stage** which not be commited yet

- if we have commit the revision, we should use  **version roll back** 

	-  if we have push to the remote repository, no way to deal with the record..
 
