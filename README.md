
1) What is version control system?
Version control, also known as source control, is the practice of tracking and managing changes to software code. A version control system is a software that help software teams manage changes to source code over time and track the changes.

2) What is Git?
 Git is a software which is used for tracking changes in code files, usually used for coordinating work among programmers/developers developing source code during software development.

3) What is Repository in Git?
  A Git repository is a folder which hosts the different versions of the files. 

4) What is Git Bash?
  It is an application which provides a Git command line experience for executing git commands.

5) What is Github?
   Github is an internet hosting provider for software development and version control using Git.

6) What is branch in Git?
  In git, a branch is a new/separate version of the main repository where new code can be written without impacting the main (master) branch.

7) What is commit in Git?
  A commit in git is a process to keep track of our progress and changes as we work.Each commit is considered as a change point or save point. It is a point in the project you can go back to if you find a bug, or want to make a change.



Basic Git Commands

git clone repository_url - It is used to make a copy of the remote repository to the local system.

git init - It is used to initialize the local folder as a git repository.

git branch - It is used to list the branches available in the repository.

git checkout -b branch_name - It is used to create a new branch in the working repository.

git add filename - It is used to add the file to staging area.

git add * - It is used to add all the files in the local repository to staging area.

git add . - It is also used to add all the files in the local repository to staging area.

git status - It is used to show the list of all new files or modified files in the local repository.

git diff - It is used to show the file differences of all the files which has been modified but not yet staged.

git commit -m "message" - It is used to It is used to record the changes in the repository with a proper message to identify the change.

git push origin branch_name - It is used to push the commits to a particular branch name.

git pull origin branch_name - It is used to update the changes from the remote repository to local workspace/.

git fetch --all - It is used to download contents from the remote repository to update the local repository to the same state as that of remote repository.

git merge branch_name - It is used to merge the current branch to the specified branch. 

git config --list - It shows the list of all git configuration properties throughout all the git files.

git config --global user.email "youremail" It is used to configure the user's email id with the remote repository.

git remote -v - It gives the url of the remote repo with which the local repo is connected.

git log - list of all commit id in full format

git log --oneline - list all the commits in short format

git log --oneline <num> - list only the specified number of commit ids



