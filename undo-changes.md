## Undo Git Changes

go through logs history 

```shell
git log author=<USERNAME>
```

go to specific commit (by commit it). This can be executed multiple times

```shell
git reset --hard <COMMIT ID>
```

You can go back x commits in the past and come back to later commits (time travel)

#

move changes to new a branch

```shell
git checkout -b <NAME-OF-THE-BRANCH>
```

drop all changes before commiting

```shell
git checkout .
```

undo *git add <FILE-PATH>*

```shell
git reset <FILE-PATH>
```

undo *git add .*

```shell
git reset
```

#
  
undo git commit -m & git add 
  
```shell 
  git reset HEAD~1
```

undo the last commit (locally) but keep your changes (git commit -m "...")

```shell 
git reset --soft HEAD^
```

drop changes and reset the branch to the previous commit

```shell
git reset --hard HEAD^
```
  
drop changes and undo x commits

```shell
git reset --hard HEAD~x
```

undo x commits

```shell
git reset --soft HEAD~x
```

Undo Git Merge

```shell
git merge --abort
```
 
