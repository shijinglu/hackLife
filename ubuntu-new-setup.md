
## Install basic softwares

```sh
# install snap store, vscode 
sudo apt install snapd
sudo snap install code 
sudo snap install emacs --classic
sudo apt-get install vim git curl

# install chrome from web
# install nerd font
pushd ~
git clone --depth=1 https://github.com/ryanoasis/nerd-fonts.git
cd nerd-fonts
./install.sh

# setup .inputrc, search history backward
echo '"\e[A": history-search-backward' > ~/.inputrc
echo '"\e[B": history-search-forward' >> ~/.inputrc
echo '"\e[C": forward-char' >> ~/.inputrc
echo '"\e[D": backward-char' >> ~/.inputrc

# install 
# setup space-emacs
git clone https://github.com/syl20bnr/spacemacs ~/.emacs.d

# setup space-vim
# setup sh alias and git
# set up git alias
# 
```
