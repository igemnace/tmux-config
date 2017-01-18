# my-tmux-config

Easy way to transfer my tmux configuration across multiple machines.

## Pre-Installation

Make sure that your machine satisfies the following:
- Is using GNU/Linux (scripts are untested on other UNIX systems and will flat-out fail on Windows)
- Has tmux 1.9 or later (version required by Tmux Plugin Manager)
- Has no pre-existing `.tmux.conf` (backup and remove if existing)
- Has bash and git (required by install scripts)
- Has python and pip (required by powerline)
- Has a working internet connection (will be downloading plugins)

## Installation

Just run `install.sh`. This will automatically do the following:
- Symlink `.tmux.conf` into your home directory (`tmux-conf.sh`)
- Clone Tmux Plugin Manager into `~/.tmux/plugins/tpm` (`tpm.sh`)
- Install powerline as a Python module (`powerline.sh`)

Once you run Tmux, press `C-b I` to install the plugins from `.tmux.conf`.

## Licensing

If anyone else sees this and wants to use it, go ahead.

This project is licensed under the Unlicense and is entirely under public domain.
