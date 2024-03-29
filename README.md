<div align="center">

# asdf-apollo-ios-cli [![Build](https://github.com/MacPaw/asdf-apollo-ios-cli/actions/workflows/build.yml/badge.svg)](https://github.com/MacPaw/asdf-apollo-ios-cli/actions/workflows/build.yml) [![Lint](https://github.com/MacPaw/asdf-apollo-ios-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/MacPaw/asdf-apollo-ios-cli/actions/workflows/lint.yml)

[apollo-ios-cli](https://github.com/apollographql/apollo-ios-cli) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add apollo-ios-cli
# or
asdf plugin add apollo-ios-cli https://github.com/MacPaw/asdf-apollo-ios-cli.git
```

apollo-ios-cli:

```shell
# Show all installable versions
asdf list-all apollo-ios-cli

# Install specific version
asdf install apollo-ios-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global apollo-ios-cli latest

# Now apollo-ios-cli commands are available
apollo-ios-cli --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/MacPaw/asdf-apollo-ios-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [MacPaw](https://github.com/MacPaw/)
