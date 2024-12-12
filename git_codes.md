#basic commands
1. git status :checks the repo status
2. git init :initializes the current dir 
3. git branch -m main :changes the main branch name to main
4. git remote add origin ssh-url : a git url of the origin to connect
5. git add . :adds the files in the cd to staging area
6. git config --global user.email xyz@email.com user.name xyz :a repository needs a user configuration to commit 
7. git commit "comment" :commits the filse in the repo to main branch with comment
8. git log :shows the logs of the repo with user names commits and comments
#push pull and difference
9. git push -u origin main :pushes the files to origin-main
10. git pull origin main :pulls the files from github (including changes done on github)
11. git diff filename :used for checking the difference bw present and previous commit
12. git diff --staged filename :used to check the difference bw versions in staged file
13. git reset filename :to unstage files that are staged
14. git checkout filename :to reset file to previous version, works only if not commited or staged.
15. git add (. -A -u) :three commands used for staging depending on the scenario
#branching
16. git branch : to check the number of braches
17. git branch branchname :creates a branch of the name
18. git checkout branchname :changes current branch to branchname
19. git merge branchname :merges the branch name with current branch 
20. git branch -d brancname :delets the local branch with branchname
21. git push origin --delete branchname :delets the branch with branchname form origin
