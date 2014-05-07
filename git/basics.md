# Git basics

## Adding files
Add files to stage them for a commit

### Single files
```
git add [filename]
```

### All modified files
```
git add -u
```

### All untracked files
```
git add -A
```

## Committing
Committing will create a snapshot of the current state of the working directory. The commit will have a unique hash assigned that works as an identifier. It is possible to roll back to a previous commit.

```
git commit -m "[commit message]"
```

## Pushing
Pushing files will transfer un-pushed commits to a remote repository (e.g. Unfuddle or GitHub)

```
git push [remote] [branch]
```

## Pulling
Pulling will transfer un-pulled commits from a remote repository to your local machine

```
git pull [remote] [branch]
```

## Remotes
Remotes are remote places to sync your repositories to (e.g. GitHub, Unfuddle, self-configured git-server)

### Adding a remote
To add a remote, simply use the following command

```
git remote add [remote name] [address]
```

### Displaying all remotes
If you forget what one of your remotes is called (e.g. when you want to push) it is simple to display all remotes in a repository:
```
git remote -v
```

### Removing a remote
```
git remote rm [remote name]
```

