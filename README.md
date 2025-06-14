# Static_website
Contains the details of the static application code
# Install GIThub in local system
# execute below commands to push the code/app from local to the repoistory

PS C:\WINDOWS\system32> cd C:\Users\HP\OneDrive\Desktop\Devops\App_EC2
  -- cd to the local directory
  
PS C:\Users\HP\OneDrive\Desktop\Devops\App_EC2> git init
  -- Initializes a new Git repository in the current directory.
  
Reinitialized existing Git repository in C:/Users/HP/OneDrive/Desktop/Devops/App_EC2/.git/
  --The message "Reinitialized existing Git repository" indicates there was already a .git folder here, so Git is just reusing it.
  
PS C:\Users\HP\OneDrive\Desktop\Devops\App_EC2> git remote add origin https://github.com/siva82538/Static_website
  -- Connects your local repository to a remote repository on GitHub.
  
PS C:\Users\HP\OneDrive\Desktop\Devops\App_EC2> git add .
  -- Stages all changes in the current directory (the . means "all files here").
  
PS C:\Users\HP\OneDrive\Desktop\Devops\App_EC2> git commit -m "your commit message describing the changes"
[master (root-commit) d70f0e8] your commit message describing the changes
 1 file changed, 279 insertions(+)
 create mode 100644 HBD.html
   -- copied the app to repo under master.
PS C:\Users\HP\OneDrive\Desktop\Devops\App_EC2> git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/siva82538/Static_website'


PS C:\Users\HP\OneDrive\Desktop\Devops\App_EC2> git push -u origin master
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 2.37 KiB | 1.19 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/siva82538/Static_website/pull/new/master
remote:
To https://github.com/siva82538/Static_website
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.


PS C:\Users\HP\OneDrive\Desktop\Devops\App_EC2> git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean


PS C:\Users\HP\OneDrive\Desktop\Devops\App_EC2> git remote -v
origin  https://github.com/siva82538/Static_website (fetch)
origin  https://github.com/siva82538/Static_website (push)
