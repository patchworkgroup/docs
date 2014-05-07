# git basics

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