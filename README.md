# tree-cli-debug

## ignore option issue

This command excludes only the node_module folder, even the module folder.

```sh
tree -l 2 --ignore "node_modules"
```

## clone & test

```sh
git clone https://github.com/Euiyeon/tree-cli-debug && cd tree-cli-debug && yarn && yarn test
```
