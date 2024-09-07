# oh-my-zsh-settings

## Install requirements
```
sudo apt install wget curl git
```

## Install zsh 
### For Mac OS
```bash
brew install zsh
```

### For ubuntu
```bash
sudo apt install zsh
```

## Install oh-my-zsh
oh-my-zsh(https://ohmyz.sh/#install)
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Set zsh theme
update zsh theme to agnoster
```
vi ~/.zshrc
```
ZSH_THEME=”agnoster”

```
source ~/.zshrc
```
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
