<div align="center">

# asdf-xcparse [![Build](https://github.com/younke/asdf-xcparse/actions/workflows/build.yml/badge.svg)](https://github.com/younke/asdf-xcparse/actions/workflows/build.yml) [![Lint](https://github.com/younke/asdf-xcparse/actions/workflows/lint.yml/badge.svg)](https://github.com/younke/asdf-xcparse/actions/workflows/lint.yml)


[xcparse](https://github.com/ChargePoint/xcparse) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- swift 5.3+ toolchain as required by [xcparse](https://swiftpackageindex.com/ChargePoint/xcparse)

# Install

Plugin:

```shell
asdf plugin add xcparse
# or
asdf plugin add xcparse https://github.com/younke/asdf-xcparse.git
```

xcparse:

```shell
# Show all installable versions
asdf list-all xcparse

# Install specific version
asdf install xcparse latest

# Set a version globally (on your ~/.tool-versions file)
asdf global xcparse latest

# Now xcparse commands are available
xcparse --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/younke/asdf-xcparse/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Vasily Ptitsyn](https://github.com/younke/)
