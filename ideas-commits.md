# ideas

## commits and staging
[main](./README.md#main)

### What are commits?
Think of commits like a snapshot or committing a database transaction.
Commits will persist any changes that are `staged`.

<br/>

### What are staged changes?
Think of staging as the setup "stage" before a commit. Changes can also be reset back to a working state.

The 3 phases of files are
1. working changes
1. staged
1. committed

<br/>

### How do i stage and commit changes?
```
# working changes
echo "new line" > file.txt

# stage changes
git add file.txt

# commit changes
git commit -m "added new line to file"
```
