How to use:
1. Install vundle
```
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```
2. Install Pathogen
```
mkdir -p ~/.vim/autoload ~/.vim/bundle && \
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
```
3. Install Nerdtree
```
git clone https://github.com/scrooloose/nerdtree.git ~/.vim/bundle/nerdtree
```
4. Create swap dir
```
mkdir ~/.vim/swap
```
5. Install NodeJS
```
curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
sudo apt-get install -y nodejs
```
6. Install YouCompleteMe
```
sudo apt-get install build-essential cmake && \
sudo apt-get install python-dev python3-dev && \
cd ~/.vim/bundle/YouCompleteMe && \
./install.py --js-completer
```
7. Install Prettier
```
sudo npm install --global prettier
```
8. Install vim-sensible (optional)
```
git clone git://github.com/tpope/vim-sensible.git ~/.vim/bundle/vim-sensible
```
