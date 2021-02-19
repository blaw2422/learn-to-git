# ideas

## remotes
[main](./README.md#main)

Git remotes are usually thought of as a server like github that we push to and pull from.

Remotes are _actually_ pointed at those servers.  They are what your computer knows about those servers.

For example, `git fetch` will update your remote to get latest changes from the server.

```
git checkout development

git pull

# merge pull request

git fetch

git cda origin/development
