git status #checks the repo status
git init #initializes the current dir 
git branch -m main #changes the main branch name to main
git remote add origin ssh-url # a git url of the origin to connect
git add . #adds the files in the cd to staging area
git config --global user.email xyz@email.com user.name xyz #a repository needs a user configuration to commit 
git commit "comment" #commits the filse in the repo to main branch with comment
git log #shows the logs of the repo with user names commits and comments
git push -u origin main #pushes the files to origin-main
git pull origin main #pulls the files from github (including changes done on github)
git diff filename #used for checking the difference bw present and previous commi
git diff --staged filename #used to check the difference bw versions in staged file
git reset filename #to unstage files that are staged
git checkout filename #to reset file to previous version, works only if not commited or staged.
git add (. -A -u) #three commands used for staging depending on the scenario
git branch # to check the number of braches
git branch branchname #creates a branch of the name
git checkout branchname #changes current branch to branchname
git merge branchname #merges the branch name with current branch 
git branch -d brancname #delets the local branch with branchname
git push origin --delete branchname #delets the branch with branchname form origin


