# configs

A private repo for holding various system configuration files for easy syncing between computers. Contains:
* Risko's custom RC file — contains various aliases, PATH additions and functions that I find useful. Should work in both Bash and Zsh. Some functions expect non-default packages (such as `code` or `xclip`) to be installed.
* Settings, bindings and theme for the `micro` editor
* oh-my-zsh `headline` theme with custom settings applied
* Backups of other configuration files, such as VS Code's `settings.json`.


## Installation

Run `./install` to check and create symlinks at the destination directories.

Add `. ~/.riskorc` to the main shell RC file.


## Docs

Once `.riskorc` is installed, run `riskohelp` for help.
