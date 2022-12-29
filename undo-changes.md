## Undo Git Changes

go through logs history 

```git log author=<USERNAME>```

go to specific commit (by commit it). This can be executed multiple times

```git reset --hard <COMMIT ID>```

You can go back x commits in the past and come back to later commits (time travel)

#

move changes to new a branch

```git checkout -b <NAME-OF-THE-BRANCH>```

drop all changes before commiting

```git checkout .```

undo *git add <FILE-PATH>*

```git reset <FILE-PATH>```

undo *git add .*

```git reset```

#

undo the last commit (locally) but keep your changes (git commit -m "...")

```git reset --soft HEAD^```

drop changes and reset the branch to the previous commit

```$ git reset --hard HEAD^```
  
drop changes and undo x commits

```$ git reset --hard HEAD~x```

undo x commits

```git reset --soft HEAD~x```
 
