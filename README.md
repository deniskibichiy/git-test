# git-test
* First GitHub repository! Yaay.
* Applying practical skills in Git basic workflow: create repository, clone, make changes, stage, and commit.
## Git clone
git clone: clones the remote .git repository and place files and folders on the local machine for modification or use.
## Git status
git status: checks the state of git repositories and displays files as either modified (changes made to them), staged (green: changes made to the files have been tracked), and committed (working treee clean. indicates that changes made to the files have been committed).
## Git add
Adds all the selected files to the staging area, making them available for committment to the remote repository. This step is fundamental to ensure that changes made to a file are tracked accordingly.
## Git commit
Git takes a snapshot of the project in the project in the staging area and stores it as a reference to the snapshot.
It is during this time that Git takes a snapshot of the project's current state and sores
## Git log
Display entries of changes made to the project, including the commit message, the author making the commit, the date, and the time of the commit.
## Git push
git push: uploads the project files to the GitHub repository of the project.
### git push origin main
Used for specificity if the project you are working on has another branch or a different remote. To learn more about this down the Odin curriculum.

# Git Cheatsheet for beginnners
1. Commands related to the remote repository
    ```
    git clone
    git push
2. Commands related to workflow
    ```
    git add .
    git commit -m "A message describing what has been done to make this snapshot different"
3. Commands related to checking status or log history
    ```
    git status
    git log
4. Basic Git syntax
Program | action | destination e.g. 
    ```
    git | add | .
    git | commit -m | message

# Git Best Practices
* Atomic commits. Make commits to include changes related to only one feature or task of the program.
* Leveraging the atomic commits to make commit messages more useful. 
These two practices:
    - Easy to revert a specific change without losing other changes
    - Facilitates writing of better commit messages.
