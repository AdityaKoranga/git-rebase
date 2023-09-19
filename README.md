# git-rebase

firstly fetch the data in the local system.

```bash
git fetch origin
```
fetching will not directly merge the new fetched changes, however you can see the logs:

```bash
git log origin/<branch-name>
```

Then just rebase the branch with the current fetched data
```bash
git rebase origin/<branch-name>
```
