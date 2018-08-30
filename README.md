# 343-HW1

The first git command that is useful for us is git clone <repository url>. This will copy the current directory from github into your current directory.
  
In order to add a file to the git repository, you must first add your file. This is done with git add <filename>. Once all the files are added that you wish to add and update to the repository, you  must commit. git commit will commit the changes and allow you to enter text to explain the changes. Finally, git push will push the changes to the repository.
  
Branching is good for creating states of the repository in case you need to revert changes. To start working on a branch, git checkout -b <branch name> will create a new branch and check you out on it, so it assigns you onto it. Doing git branch will show the current branches, and will put an asterik next to the current accessed branch.
  
If you want to make those changes final, you will have to merge your branch with the master branch using git merge, which will merge your current branch with the master.

Contributing to an existing project is often done with a pull request, which is a request to the owner of the repository to make some changes. They will get to review it before they decide whether or not to merge the pull with the current repository.


