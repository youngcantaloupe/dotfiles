# My dotfiles

This directory contains the dotfiles for my system

The zsh.rc file will automatically install [zinit](https://github.com/zdharma-continuum/zinit), [p10k](https://github.com/romkatv/powerlevel10k?tab=readme-ov-file#installation), and a few other zsh plugins listed below. 
### Powerlevel10k

**Note**: P10k works best with a [Nerd Font](https://www.nerdfonts.com/font-downloads(https://www.nerdfonts.com/font-downloads).

### zinit plugins

These plugins are from [zsh-users](https://github.com/zsh-users)

- [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
- [zsh-completions](https://github.com/zsh-users/zsh-completions)
- [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)

## Requirements

Ensure that you have the following installed on your system. 
### Git

```
sudo apt install git
```
```
sudo apt install gh
```

### Stow

```
sudo apt install stow
```

### Zsh

```
apt install zsh
```
- Changing default shell:
```
chsh -s $(which zsh)
```
**Note: using sudo will change default shell for root, not user.**

*Can also be changed through /etc/passwd*

## Installation

First, check out the dotfiles repo in your ~/HOME directory using git

```
git clone https://github.com/youngcantaloupe/dotfiles.git
cd dotfiles
```

then use GNU stow to create symlinks

```
stow .
```
**Note: make sure you are in ~/dotfiles/**
