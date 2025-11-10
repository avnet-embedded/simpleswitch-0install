# simpleswitch-0install

This repository contains definitions for [0install](https://0install.net), a decentralised cross-platform software installation system.

This allows to install and automatically update applications on Windows, Linux and MacOS.

## Currently supported

- `SimpleSwitch Launcher`

## Add new templates

- Add a new `.xml.template` file to `templates`
- Trigger `Release` workflow

Artifacts can then be installed from `https://github.com/avnet-embedded/simpleswitch-0install/releases/download/current/<template>.xml` with [0install](https://0install.net)
