# Commands

[main](./README.md#main)


### <a name="merge"></a> merge

Merge takes 2 different branches ( or hashes ) and merges the histories together

> The output will be that it also merges the files together and can cause "merge conflicts"

What's a merge conflict
 - Merge conflicts happen when git can't figure out what to do with file changes between 2 commits.  This happens when 2 separate commits change a file in the same location.
 - The question is "Which change, or combination of changes, should be the end result of these 2 commits?
 - Sometimes a single person can understand what the result should be
 - Sometimes 2 or more should sit together to achieve desired result of the 2 commits

```
git merge feature/merge
```
<img src="./images/merge.png" />
