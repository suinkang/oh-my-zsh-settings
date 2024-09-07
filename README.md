# oh-my-zsh-settings

## Install zsh
```bash
brew install zsh
```

## Install oh-my-zsh
oh-my-zsh(https://ohmyz.sh/#install)
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Set zsh theme
1. $ vi ~/.zshrc
2. ZSH_THEME=”agnoster”
3. $ source ~/.zshrc

## Install plugins
### Auto suggestions
```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
vi ~/.zshrc
```
add zsh-autosuggestions in plugins


### Syntax Highlighter
```bash
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
vi ~/.zshrc
```

add zsh-syntax-highlighting in plugins
```
plugins=( [plugins...] zsh-syntax-highlighting)
```
