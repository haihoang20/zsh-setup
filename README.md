# Zsh setup for Iterm 2

### Install Iterm 2
https://www.iterm2.com

### Jump words
1. Go to `Preferences... > Profile > Keys`
2. Press `Load Preset`
3. Select `Natural Text Editing`

### Iterm 2 Colours
Import the `iterm2-colours.itermcolors` into `Preferences > Profile > Colors`

### Install SauceCodePro Nerd Font
```
brew tap homebrew/cask-fonts
brew cask install font-sourcecodepro-nerd-font
```

### Install Zsh
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

### Add Powerlevel9k
```
git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k
```

### Autosuggestions
```
git clone https://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions
```

### .zshrc
```
cp .zshrc ~/
```

### .gitconfig
Make sure you change the name and email before using this
```
cp .gitconfig ~/
```

### .vimrc
```
cp .vimrc ~/
```

References:
- https://medium.com/@Clovis_app/configuration-of-a-beautiful-efficient-terminal-and-prompt-on-osx-in-7-minutes-827c29391961

