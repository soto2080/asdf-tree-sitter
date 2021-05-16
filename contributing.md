# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test tree-sitter https://github.com/soto2080/asdf-tree-sitter.git "tree-sitter -h"
```

Tests are automatically run in GitHub Actions on push and PR.
