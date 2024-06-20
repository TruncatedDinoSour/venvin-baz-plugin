# This repository has been migrated to the self-hosted ari-web Forgejo instance: <https://git.ari.lt/ari/venvin-baz-plugin>
# Baz plugin: venvin-baz-plugin

> Baz plugin for entering and exiting virtualenvs with ease

# Installation

- Using [baz plugin manager](https://ari-web.xyz/gh/baz):

```bash
$ baz install git 'https://ari-web.xyz/gh/venvin-baz-plugin'
```

# Dependencies

- Virtualenv

# Usage

It's simple, just type `venv`, it will either:

- Create a venv if it doesn't exit
- Enter a venv if it exists
- Exit a venv if you're in one

`venv` also accepts optional arguments for virtualenv

# Customisation

- `PY3` -- The `python3` command
