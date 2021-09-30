# my-zsh-config
```sh
sudo apt update && sudo apt upgrade -y && sudo apt install git zsh -y && sudo chsh -s /usr/bin/zsh $USER

zsh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"    

zsh -c 'git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions'

zsh -c 'git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting'

git clone https://github.com/sindresorhus/pure.git "$HOME/.zsh/pure"
```
