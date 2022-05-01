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
* 
