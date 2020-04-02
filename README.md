<div align="center">

# asdf-kpt ![Build](https://github.com/ggilmore/asdf-kpt/workflows/Build/badge.svg) ![Lint](https://github.com/ggilmore/asdf-kpt/workflows/Lint/badge.svg)

[kpt](https://googlecontainertools.github.io/kpt/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add kpt
# or
asdf plugin add https://github.com/ggilmore/asdf-kpt.git
```

kpt:

```shell
# Show all installable versions
asdf list-all kpt

# Install specific version
asdf install kpt latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kpt latest

# Now kpt commands are available
kpt --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ggilmore/asdf-kpt/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Geoffrey Gilmore](https://github.com/ggilmore/)
