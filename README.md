<div align="center">

# asdf-restish [![Build](https://github.com/polds/asdf-restish/actions/workflows/build.yml/badge.svg)](https://github.com/polds/asdf-restish/actions/workflows/build.yml) [![Lint](https://github.com/polds/asdf-restish/actions/workflows/lint.yml/badge.svg)](https://github.com/polds/asdf-restish/actions/workflows/lint.yml)

[restish](https://rest.sh/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add restish
# or
asdf plugin add restish https://github.com/polds/asdf-restish.git
```

restish:

```shell
# Show all installable versions
asdf list-all restish

# Install specific version
asdf install restish latest

# Set a version globally (on your ~/.tool-versions file)
asdf global restish latest

# Now restish commands are available
restish --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/polds/asdf-restish/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Peter Olds](https://github.com/polds/)
