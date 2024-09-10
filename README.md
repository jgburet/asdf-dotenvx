<div align="center">

# asdf-dotenvx [![Build](https://github.com/jgburet/asdf-dotenvx/actions/workflows/build.yml/badge.svg)](https://github.com/jgburet/asdf-dotenvx/actions/workflows/build.yml) [![Lint](https://github.com/jgburet/asdf-dotenvx/actions/workflows/lint.yml/badge.svg)](https://github.com/jgburet/asdf-dotenvx/actions/workflows/lint.yml)

[dotenvx](https://dotenvx.com/docs) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add dotenvx
# or
asdf plugin add dotenvx https://github.com/jgburet/asdf-dotenvx.git
```

dotenvx:

```shell
# Show all installable versions
asdf list-all dotenvx

# Install specific version
asdf install dotenvx latest

# Set a version globally (on your ~/.tool-versions file)
asdf global dotenvx latest

# Now dotenvx commands are available
dotenvx --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jgburet/asdf-dotenvx/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jean-Guillaume Buret](https://github.com/jgburet/)
