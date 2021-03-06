
# 2020-08-17-git-tasha

## Local

- `git init`: create git repository in current folder
- `git config --global user.name` "Tasha Vipond"
- `git config --global user.email` "vipondn@vt.edu"

- `git status`: tells you what is going on in your respository
- `git add <FILE>` : places <FILE> into the staging area
	-`git add README.md`
- `git commit`: commits files in the staging area
	-if you opned this in VI(M): <ESC> `:q!`
	-`git config --global core.editor "nano -w"`

- `git log`: shows you your history
	- `git log --oneline`: shows you your 1-line version of history
- `HEAD`: tells you where you are looking at in history

## Remotes

- `git diff`: shows difference between previous file and file you are adding
	- `git diff --staged`: shows difference between file in staging area (that has been git added) and the previously committed file
	-you can use `git log --oneline` to specify different versions in history
- `git commit -m "MESSAGE" `: allows you to add a comment without opening nano when committing
- `git remote add origin <URL> `: adds <URL> with the name origin
- `git push origin master`: pushes the master branch to the origin remote
- `git pull origin master`: pulls the master branch from origin to local computer

- You make changes to different parts of a file and it will be combined automatically
- Look for the `>>>` `===` `<<<` and fix those lines to what you actually want
	-delete other lines and create new section instead
