# start
cp dotfile/\* .config/

# creat symbolic link
ln -s .config/vim/.vimrc ~/.vimrc
ln -s .config/vim/.vimrc ~/.vimrc
ln -s .config/zsh/.zshenv ~/.zshenv

# vim-plug
:PlugInstall
