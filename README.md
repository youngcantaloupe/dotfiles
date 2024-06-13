# My dotfiles

This directory contains the dotfiles for my system

The zsh.rc file will automatically install [zinit](https://github.com/zdharma-continuum/zinit), [p10k](https://github.com/romkatv/powerlevel10k?tab=readme-ov-file#installation), and a few other zsh plugins listed below. 
### Powerlevel10k

**NOTE**: Needs: [nerd font](https://www.nerdfonts.com/font-downloads).

### zinit plugins

The first three plugins are from [zsh-users](https://github.com/zsh-users)

- [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
- [zsh-completions](https://github.com/zsh-users/zsh-completions)
- [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
- [Aloxaf-fzf-tab](https://github.com/Aloxaf/fzf-tab)

## Requirements

### Git

```
sudo apt install git
```

### Stow

```
sudo apt install stow
```

### Zsh

```
sudo apt install zsh
```
- Changing default shell:
```
chsh -s $(which zsh)
```
**Note: using sudo will change default shell for root, not user.**
*Can also be changed through /etc/passwd*

### Tmux

```
sudo apt install tmux
```

Tmux plugin manager

```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```
## Installation

```
git clone https://github.com/youngcantaloupe/.dotfiles.git
cd .dotfiles
```

### Using stow
- To create sym-links
```
stow .
```
- To remove sym-links
```
stow -D .
```