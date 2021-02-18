# How to git

## Commands to cover:
[clone](#clone)
[checkout](#checkout)

### <a name="clone"></a> clone

* What does it do?
    * Obviously - it downloads the repo onto my computer
    * Not so obvious - it sets up the remote for us

### <a name="checkout"></a> checkout

* What do we use it for?
    * checking out new branches from an existing branch
        * `git checkout -b feature/123`
    * checking out a specific file or folder from a different branch / commit
        * `git checkout origin/development file1.txt # branch`
        * `git checkout head^ # commit `
        * `git checkout -- file1.txt # assumes HEAD - but allows for deleted files`
