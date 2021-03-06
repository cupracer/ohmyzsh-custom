# ohmyzsh-custom

## Installation

Assuming that zsh is already installed and current shell...

Manually setup [ohmyzsh](https://github.com/ohmyzsh/ohmyzsh) as usual and cleanup the dummy custom directory:
```
git clone https://github.com/ohmyzsh/ohmyzsh.git ~/.oh-my-zsh
rm -rf ~/.oh-my-zsh/custom
```
Add this project either via SSH
```
git clone --recurse-submodules git@github.com:cupracer/ohmyzsh-custom.git ~/.oh-my-zsh/custom
```
or HTTPS
```
git clone --recurse-submodules https://github.com/cupracer/ohmyzsh-custom.git ~/.oh-my-zsh/custom
```
Set symbolic links to the pre-defined config files:

.zshrc:
```
ln -sf ~/.oh-my-zsh/custom/cfg/zshrc ~/.zshrc
```

Choose .p10k.zsh with a lot of icons:
```
ln -sf ~/.oh-my-zsh/custom/cfg/p10k.zsh.bragger ~/.p10k.zsh
```

or only a few icons:
```
ln -sf ~/.oh-my-zsh/custom/cfg/p10k.zsh.light ~/.p10k.zsh
```

And finally restart the ZSH session:
```
exec zsh
```

## Fonts

Setup fonts for Powerlevel10k theme as described here:

https://github.com/romkatv/powerlevel10k#meslo-nerd-font-patched-for-powerlevel10k

## Extra

Link to config file for top:
```
ln -sf ~/.oh-my-zsh/custom/cfg/toprc ~/.toprc
```
and VIM:
```
ln -sf ~/.oh-my-zsh/custom/cfg/vimrc ~/.vimrc
```

