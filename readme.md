# Dreck Visual Studio Code Plugin [![License](https://img.shields.io/github/license/sunruse/dreck-visual-studio-code-plugin.svg)](https://github.com/sunruse/dreck-visual-studio-code-plugin/blob/master/license) [![Renovate enabled](https://img.shields.io/badge/renovate-enabled-brightgreen.svg)](https://renovatebot.com/)

Adds Visual Studio Code boilerplate to a project built using Dreck.

## Installation

Run the following in a Bash shell at the root of your project:

```bash
git submodule add https://github.com/sunruse/dreck-visual-studio-code-plugin plugins/visual-studio-code
make --file ./plugins/dreck/makefile
```

## Features

### Build shortcut

The bundled [tasks.json](./bundled/.vscode/tasks.json) file means that a build can be started by any of the following:

- `Terminal` > `Run Build Task...`.
- Ctrl + Shift + B (Windows/Linux).
- Cmd + Shift + B (macOS).

### Default `settings.json`

The bundled [settings.json](./bundled/.vscode/settings.json) file hides the `tmp` directory and makes some other "common sense" configuration changes for Dreck projects.
