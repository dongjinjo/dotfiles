# dotfiles


## zsh
### Manual 
``` sh
# install zsh
sudo apt install zsh

# change default shell 
sudo chsh -s `which zsh`

# install oh-my-zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

# install syntax highlighting
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

# install auto suggestions 
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

# mv .zshrc 
mv ~/.zshrc ~/.zshrc.old
mv dotfiles/.zshrc ~/.zshrc
```
