See below step-by-step instruction 


1 Create a new directory named "new-project" in your environment.
	- mkdir new-project
	- cd new-project
2 Initialize a new public Git repository inside the "new-project" directory.
	-git init
3 Create a new file named "README.md" and add initial text to it.
	- touch README.md


4 Prepare the "README.md" file for commit.
	- git add README.md
5 Commit the changes to the repository with the commit message "init".
	- git commit -m "init"
6 Create a new branch named "development" and switch to it.
	- git checkout -b development
7 Commit the changes in the "development" branch with the commit message "Add instructions for   	development".
	- git add README.md
	- git commit -m "Add instructions for development"
8 Merge the changes from the "development" branch into the "main" branch.
	- git checkout main
	- git merge development
9 Check the status to ensure everything is up to date.
	- git status
10 Commit the changes.
	- git commit -m "Merge changes from development to main"
