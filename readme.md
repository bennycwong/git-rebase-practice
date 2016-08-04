Git Rebase Practice. See Blog post for more info:

To configure, clone the repo:
```bash
git clone git@github.com:bennycwong/git-rebase-practice.git
```
Try the following:

Merge:
```bash
git checkout master
git merge origin/feature
git log
```

Rebase:
```bash
git checkout master
git rebase origin/feature
git log
```

