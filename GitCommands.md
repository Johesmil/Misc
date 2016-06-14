#Git Commands

### Common tasks
Task | Command
--- | ---
Add all changes to index and commit | `git commit -a -m "Commit message"`
Commits all changes added to the index | `git commit -m "Commit message"`
Add changes to the index | `git add -A` </br> `git add changed_file.txt` </br> `git add folder_with_changed_files/`
Fetch and merge changes from the server | `git pull`
xxx | `git push`
xxx | `git fetch`
Merge the given branch to your active branch | `git merge <branchname>`
xxx | `git rebase`
xxx | `git tag`
test 

### Get info
Task | Command
--- | ---
Show the working tree status | `git status`
Show changes between commits | `git diff`
See current settings | `git config --list`
View remote urls | `git remote -v`

### Manage branches
Task | Command
--- | ---
List all branches | `git branch`
Create new branch | `git checkout -b <branchname>`
Switch to branch | `git checkout <branchname>`
Delete branch | `git branch -d <branchname>`

### Recovery
Task | Command
--- | ---
xxx | `git checkout -- discard_changes.txt`
xxx | `git fetch origin` </br> `git reset --hard origin/master`

### Setup Git

Task | Command
--- | ---
Set user details | `git config --global user.name "John Doe"` </br> `git config --global user.email "john@example.com"`
Clone a remote repository | `git clone https://github.com/johesmil/misc.git`
