# my-tmux-config

Easy way to transfer my tmux configuration across multiple machines.

## Pre-Installation

Make sure that your machine satisfies the following:
- Is using GNU/Linux (scripts are untested on other UNIX systems and will
  flat-out fail on Windows)
- Has tmux 1.9 or later (version required by Tmux Plugin Manager)
- Has no pre-existing `.tmux.conf` (backup and remove if existing)
- Has bash and git (required by install scripts)
- Has a working internet connection (will be downloading plugins)

## Installation

Just run `./install`. This will automatically do the following:
- Symlink `.tmux.conf` into your home directory (`install-tmux-conf`)
- Clone Tmux Plugin Manager into `~/.tmux/plugins/tpm` (`install-tpm`)

Once you run Tmux, press `C-b I` to install the plugins from `.tmux.conf`.

## Licensing

If anyone else sees this and wants to use it, go ahead.

This project is open source, licensed under MIT.

Do you remember this project being Unlicensed? Read more about the license
change [here][license-change].

[license-change]: https://github.com/igemnace/dotfiles/issues/2
