# My dotfiles

This directory contains the dotfiles for my system

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
#### Changing default shell:
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
**Note: make sure you are in ~/dotfiles/
