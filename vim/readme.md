# Setup
```bash
:exe 'edit '.stdpath('config').'/init.vim'
:write ++p

set runtimepath^=~/.vim runtimepath+=~/.vim/after
let &packpath = &runtimepath

ls -n ~/.config/nvim/init.vim .vimrc

git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim

:PlugInstall
```
