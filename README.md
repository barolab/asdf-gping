<div align="center">

# asdf-gping ![Build](https://github.com/barolab/asdf-gping/workflows/Build/badge.svg) ![Lint](https://github.com/barolab/asdf-gping/workflows/Lint/badge.svg)

[gping](https://github.com/orf/gping) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)
- [Credits](#credits)

# Dependencies

- `bash`, `curl`, `tar`.

# Install

Plugin:

```shell
asdf plugin add gping
# or
asdf plugin add gping https://github.com/barolab/asdf-gping.git
```

gping:

```shell
# Show all installable versions
asdf list-all gping

# Install specific version
asdf install gping latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gping latest

# Now gping commands are available
gping --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/barolab/asdf-gping/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Romain Bailly](https://github.com/barolab/)

# Credits

This repository was heavily inspired from [asdf-exa](https://github.com/nyrst/asdf-exa)
