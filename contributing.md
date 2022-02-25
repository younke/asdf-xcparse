# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test xcparse https://github.com/younke/asdf-xcparse.git "xcparse --help"
```

Tests are automatically run in GitHub Actions on push and PR.
