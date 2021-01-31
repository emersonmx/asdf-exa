<div align="center">

# asdf-exa ![Build](https://github.com/emersonmx/asdf-exa/workflows/Build/badge.svg) ![Lint](https://github.com/emersonmx/asdf-exa/workflows/Lint/badge.svg)

[exa](https://the.exa.website/introduction) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add exa
# or
asdf plugin add https://github.com/emersonmx/asdf-exa.git
```

exa:

```shell
# Show all installable versions
asdf list-all exa

# Install specific version
asdf install exa latest

# Set a version globally (on your ~/.tool-versions file)
asdf global exa latest

# Now exa commands are available
exa --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/emersonmx/asdf-exa/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Emerson MX](https://github.com/emersonmx/)
