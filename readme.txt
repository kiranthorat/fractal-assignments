practice git github commands

1. git init
2. git add .    // Adds all files to the staging area   
3. git commit -m "first commit"    // Commits the staged files with a message
4. git status    // Checks the status of the repository
5. git log    // Shows the commit history
6. git diff    // Shows the differences between commits
7. git branch    // Lists all branches in the repository
8. git checkout -b new-branch    // Creates and switches to a new branch
9. git merge new-branch    // Merges the new branch into the current branch
10. git remote add origin <repository-url>    // Adds a remote repository
11. git push -u origin master    // Pushes the changes to the remote repository
12. git pull origin master    // Pulls the latest changes from the remote repository
13. git clone <repository-url>    // Clones a remote repository to the local machine
14. git reset --hard HEAD~1    // Resets the current branch to the previous commit...when
                                //  you do hard reset head will be moved to the respecting commit but other commits will get ignored
15. git revert <commit-id>    // Reverts a specific commit by creating a new commit that undoes the changes
16. git stash    // Stashes changes in the working directory
17. git stash pop    // Applies the stashed changes back to the working directory
18. git cherry-pick <commit-id>    // Applies the changes from a specific commit to the current branch
19. git tag v1.0    // Creates a new tag for the current commit

20. git fetch origin    // Fetches changes from the remote repository without merging
21. git rebase master    // Reapplies commits on top of another base tip
22. git config --global user.name "Your Name"    // Sets the global username for Git
23. git config --global user.email "your.email@example.com"    // Sets the global email for Git
24. git config --global core.editor "code --wait"    // Sets the default editor for Git
