# dotfiles
mkdir ~/.vim/backups ~/.vim/swaps ~/.vim/undo
# 设置软连接
ln -s ~/dotfiles/.vimrc ~/.vimrc
# Vundle 安装
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
# 安装插件
:BundleInstall
# 卸载插件
:BundleClean

