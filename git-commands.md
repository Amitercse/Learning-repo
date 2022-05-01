### Popular git commands
* Check git version - git --version
* Configure git user settings in your local -
  * git config --global user.name "Name"
  * git config --global user.email "email"
* Initialize git empty repository - git init
* Check list of modified files - git status
* Check diff of modified file - git diff file1.txt
* Add a modified file to staging area of git. Even if we deleted some file from working directory, we need to remove that from staging area by using below add commands only. 
  * git add file1.txt file2.txt
  * git add *.txt
  * git add . -> it will add all modified files in current repository recursively.
* Commit staging changes - git commit -m "message"
* Add remote repositories - git remote add origin "remote url" or git remote add upstream "remote url"
* push changes to remote repo - git push origin "branch-name". Here origin is the name of remote repo name which we configured.
* Check remote configuration - git remote -v
* Clone a remote repo - git clone "remote url"
* Revert a modified file - git revert "file-name"
* Revert a particular commit changes - git revert "commit-id"
* Switch the branch - git checkout "branch-name", it will create new branch if doesn't exist already
* Undo local changes - git reset
* Fetch remote changes to local - git pull upstream "branch-name" - here upstream is remote configured repo.


### Pushing local project to git server
After creating project from scratch, we need to push it to git server. Follow below steps.
* Create local repo and initialize it with git - git init
* Create a new project and add files there as required.
* Create a new repo on github.
* Configure new repo as remote repo for local project - git remote add origin "remote repo url".
* Commit all files.
* Push the changes.


