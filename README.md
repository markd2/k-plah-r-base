# This is a repository purely to exercise git manipulations.

Cheat sheet:

### Cherry Picking

```plain
% git checkout <branch to pull commits in to>
% git cherry-pick <SHA of commmit>
```


### Amending

```plain
% git commit -m "blahblabh" file1 file2
% modify file1
% git add file1
% git commit --amend
<editor spawns>
```


