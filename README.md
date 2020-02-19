# dotfiles
Config files for [Regolith Desktop](https://regolith-linux.org/) and zsh environment with [oh-my-zsh](https://ohmyz.sh/).<br>
The repo is meant to be cloned into your home dir and the environment to be created by [stow](https://www.gnu.org/software/stow/).<br>
## Necessary packages 
on top of the above:<br>
- colorls
- fonts-powerline
- fzf
- maim
- p10k theme

## Usage
```
cd ~
git clone git@github.com:lehoczkics/dotfiles.git
cd dotfiles
stow env \
	zsh \
	i3
```

