# GitHelp
Git cheatsheet for when you messed something up and need to fix it. Was tired of stackoverflowing all this so this is my compilation. Enjoy.

## Undo last commit (local)
```git reset --soft HEAD~1```

## Undo a deleted file (havent committed yet)
```git checkout HEAD <path to file>```

## Reset branch to last commit (S/O to Aaron for this puppy)
```git reset --hard HEAD```

## Amend commit + force push (don't do this if its a shared branch)
```git commit --amend```
```git push origin <branch-name> -f```
