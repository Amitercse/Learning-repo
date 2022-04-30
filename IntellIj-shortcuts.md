### Live template
We can check all available shortcuts for live templates using "command+j" in mac or "control+j" in windows or linux. Few examples are given below - 

* foreach - to generate for each syntax
* fori - create iterative loop, example -
```
for(int i=0; i<n; i++)
{
}
```
* ifn - if null statement
* inn - if not null statement
* iter - iterator (enhanced for loop)
* itar - iteratre elements over array
* itli - iterate over list
* serr - System.err.println()
* sout - System.out.println()
* main - create main() method

We can also create our custom live templates. Go to preferences -> editor -> live templates -> create a new template

### Intellij with git
Intellij provides easy integration with git. Using intellij, we can directly perform git operations without using command operations as well. Below are some important git operations we can perform using intellij.
* We can directly clone a remote repo in local using option - 'Get from VCS' at intellij home page.
* If already one project is opened in intellij, then go to option, 'git -> clone'. Enter remote url and local directly and hit clone.
* There are many options related to git operations under oprion 'git'. 
* We can manage remote config like adding origin or upstream. Go to git -> manage remotes.
* Take pull from remote. Git -> pull -> select remote details to pull
* See the diff in local file. There are two ways - 
  * Click on local file then git -> current file -> show diff
* Git -> commit - it will show list of all files which are changed in local. Select any file and see the diff.
* Git -> show git log - to check commit history
* Git -> pull - to take changes from remote
* Git -> push - to push the changes.
* If we have created a new project in local which is not yet on github then we can share local project to github using VCS -> share project on github.

Similar to that many operations can be performed.

