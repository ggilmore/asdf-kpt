# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test kpt https://github.com/ggilmore/asdf-kpt.git "kpt --help"
```

Tests are automatically run in GitHub Actions on push and PR.
