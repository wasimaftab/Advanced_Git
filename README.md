# Basic to advance git commands for daily use:

## Initializing Repo
```
git init ## this will initialize the folder as a git repo and .git folder will be created
```

## View branches
```
git branch ## this will not output anything if there has not been any commit
```
## Create first commit
```
echo "# My Project" > README.md
git add README.md
git commit -m "Initial commit"
```
## Rename a branch
```
git branch -M <OldBranch> <NewBranch> ## this rename <OldBranch> to <NewBranch>
```
## Add a remote repo to local Git repo
```
git remote add origin https://github.com/<username>/<remote repo name>.git
```
## Create a new branch locally:
```
git branch <branch name>
```
## Switch to a branch locally:
```
git checkout <branch name>
```
## Create a New Branch Locally and switch (only if it doesn't exist):
```
git checkout -b <branch name>
```
## Delete a branch:
```
git branch -d <branch name> ## safe delete
git branch -D <branch name> ## force delete
## note cannot delete a branch when you are on it :laughing:
```
