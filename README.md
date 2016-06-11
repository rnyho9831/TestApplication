# learnrubythehardway
Files from my Learn Ruby The Hard Way course Repo to store our exercises.

Suggested naming convention for files is "ex[number of exercise].[number of the study lesson]-[initials].rb". For example, file ex15.1-gs.rb would contain all the answers the Grace submitted for exercise 15 study lesson #1.

#The following information is the basic steps to working within our repo at the command line.
*git status* - shows where I'm at.  If you're ahead, you need to push.  If you're behind, you need to "pull" 

*git checkout master* - puts me on the master branch of the repo. If you want to be on your branch, subsitute master for your branch name. The remaining instructions will be in refrence to working on the master branch.

*git pull origin master* - pulls all of the code on that branch of the repo (in this case "master")
-- make changes to file, one at a time.
*git add* "ex1/ex1-rn.rb" - adds file to repository

NOTE *git add ** - only ADDS all files, not removes

*git commit -m "Message for commit"*

*git push origin master*

*git status* -- run again to make sure that there is nothing to commit.  Ensures you're up-to-date with master branch
