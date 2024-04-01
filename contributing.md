# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test apollo-ios-cli https://github.com/MacPaw/asdf-apollo-ios-cli.git "apollo-ios-cli --help"
```

Tests are automatically run in GitHub Actions on push and PR.
