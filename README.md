# my dotfiles

- Very useful scripts are in `~/.local/bin/`
- Settings for:
	- vim/nvim (text editor)
	- zsh (shell)
	- sxhkd (general key binder)
	- ranger (file manager)
	- mpd/ncmpcpp (music)
	- sxiv (image/gif viewer)
	- mpv (video player)
	- calcurse (calendar program)
	- tmux
	- other stuff like xdg default programs, inputrc and more, etc.
- I try to minimize what's directly in `~` so:
	- All configs that can be in `~/.config/` are.
	- Some environmental variables have been set in `~/.zprofile` to move configs into `~/.config/`
- Bookmarks in text files used by various scripts (like `~/.local/bin/shortcuts`)
	- File bookmarks in `~/.config/files`
	- Directory bookmarks in `~/.config/directories`

## Usage

These dotfiles are intended to go with numerous suckless programs I use:

- [dwm](https://github.com/hamidout/dwm) (window manager)
- [dwmblocks](https://github.com/hamidout/dwmblocks) (statusbar)
- [st](https://github.com/lukesmithxyz/st) (terminal emulator)

I also recommend trying out
[mutt-wizard](https://github.com/lukesmithxyz/mutt-wizard), which additionally
works with this setup. It gives you an easy-to-install terminal-based email
client regardless of your email provider. It is integrated into these dotfiles
as well.

## Install these dotfiles and all dependencies

Use [auto-rice](https://github.com/hamidout/auto-rice.git) to autoinstall everything:

```
curl -LO "https://raw.githubusercontent.com/hamidout/auto-rice/master/auto-rice.sh"
```

or clone the repo files directly to your home directory and install the
[dependencies](https://github.com/hamidout/auto-rice/blob/master/progs.csv).
