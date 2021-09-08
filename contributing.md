# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test github-actions-runner https://github.com/mathew-fleisch/asdf-github-actions-runner.git "github-actions-runner --version"
```

Tests are automatically run in GitHub Actions on push and PR.
