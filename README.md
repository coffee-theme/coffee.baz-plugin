# Baz plugin: coffee.baz-plugin

> Baz plugin for coffee theme in bash prompt

# Installation

- Using [baz plugin manager](https://ari-web.xyz/gh/baz):

```bash
$ baz install git 'https://github.com/coffee-theme/coffee.baz-plugin'
```

# Dependencies

- GNU coreutils
- (Optional) git -- show git branch
- (Optional) virtualenv -- show current virtual environment

# Looks

![Screenshot](/screenshot.jpg)

# Customisation

- `COFFEE_ROOT_CHAR` -- The character to use for the `root` user as the prompt [`#`]
- `COFFEE_CLR_USER` -- The colour to use for the normal user [`green`]
- `COFFEE_USER_CHAR` -- The character to use for the normal user as the prompt [`%`]
- `COFFEE_CLR_ERR` -- The error colour [`red`]
- `COFFEE_CLR_VENV` -- The colour to use for virtual environments [`green`]
- `COFFEE_CLR_ROOT` -- The user colour for the `root` user [`red`]
