<div align="center">

# asdf-github-actions-runner [![Build](https://github.com/mathew-fleisch/asdf-github-actions-runner/actions/workflows/build.yml/badge.svg)](https://github.com/mathew-fleisch/asdf-github-actions-runner/actions/workflows/build.yml) [![Lint](https://github.com/mathew-fleisch/asdf-github-actions-runner/actions/workflows/lint.yml/badge.svg)](https://github.com/mathew-fleisch/asdf-github-actions-runner/actions/workflows/lint.yml)


[github-actions-runner](https://docs.github.com/en/actions/hosting-your-own-runners) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add github-actions-runner
# or
asdf plugin add github-actions-runner https://github.com/mathew-fleisch/asdf-github-actions-runner.git
```

github-actions-runner:

```shell
# Show all installable versions
asdf list-all github-actions-runner

# Install specific version
asdf install github-actions-runner latest

# Set a version globally (on your ~/.tool-versions file)
asdf global github-actions-runner latest

# Now github-actions-runner commands are available
github-actions-runner --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mathew-fleisch/asdf-github-actions-runner/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Mathew Fleisch](https://github.com/mathew-fleisch/)
