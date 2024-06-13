# Git Commands Cheatsheet

git init /* start a new repo in current directory */

git pull

git --help

git status

git branch

git branch branchName /* creates branchName branch */

git checkout branchName /* switch to branchName branch */

git stage fileName

git commit -m "commit message"

git reset HEAD~ /* deletes the last commit */

git checkout fileName /* resets fileName file changes according to the last commit */

git restore --staged fileName // unstages fileName file

git log

git push

git push --force

### Change Git Configuration (email)

`git config --show-scope --get user.email` -- shows the current **LOCAL** email; use inside the working directory

`git config --show-origin --get user.name` -- show global settigs (username)

git config user.email "new@email.com"

## Working with the Remotes

git remote -v

git remote add NAME URL /* https://repo_url.git */

git remote remove NAME

git push --set-upstream RemoteName BranchName
