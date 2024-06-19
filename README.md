# Installation of Alacritty
Initial setup on MacOS. Use different package manager for Linux.

## Additional dependencies

```
brew install font-meslo-lg-nerd-font
```

```
brew install powerlevel10k
```

### Install zsh-autosuggestions and add to .zshrc
```
brew install zsh-autosuggestions
```
```
echo "source $(brew --prefix)/share/zsh-autosuggestions/zsh-autosuggestions.zsh" >> ~/.zshrc
```

### Install zsh-syntax-highlighting and add to .zshrc
```
brew install zsh-syntax-highlighting
```
```
echo "source $(brew --prefix)/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ~/.zshrc
```

### Install Eza (better ls) and update .zshrc
```
brew install eza
```
#### Add this to .zshrc
```
# Eza (better ls)

alias ls="eza --icons=always"
```

### Install Zoxide (better cd) and update .zshrc
```
brew install zoxide
```
#### Add this to .zshrc
```
# Zoxide (better cd)
eval "$(zoxide init zsh)"

alias cd="z"
```


## PowerLevel10k Setup
```
nvim ~/.p10k.zsh
```

