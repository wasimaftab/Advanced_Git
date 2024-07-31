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
## Renme a branch
```
git branch -M <newbranch> ## this will not output anything if there has not been any commit
```