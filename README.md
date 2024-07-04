# Git command
This is my first git commit.

```
git clone <repo-ssh-url>
git status
git add <file-name>
git commit -m "message"
git push origin <branch-name>
```

## Creating branch

```
git checkout -b <branch-name>   [create and switch to 'branch-name']
git branch <branch-name>    [ create branch 'branch-name' but does not switch to it]
git branch          [ show existing branch]
git checkout <branch-name>  [ switch to branch 'branch-name']
```

## Pull request

```
git pull origin <branch-name> 
```

## Shorthand
```
git add .    [ to stage all modified + new created file at once]
git push -u origin main   [ to set upstream branch 'main']
git push
```