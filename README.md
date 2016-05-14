# myvim
My vim configuration for MacOSX, Ubuntu, and Redhat/CentOS.

# To install

- cd $HOME

- git clone https://github.com/robertojrojas/myvim.git .vim

- ln -s ~/.vim/vimrc ~/.vimrc

- modify .vimrc to fix paths for GO, etc....

- git clone https://github.com/Valloric/YouCompleteMe.git ~/.vim/bundle/YouCompleteMe

- pushd ~/.vim/bundle/YouCompleteMe

- ./install.py --clang-completer

- popd

- git clone https://github.com/fatih/vim-go.git ~/.vim/bundle/vim-go


- enjoy!


![alt text](https://raw.githubusercontent.com/robertojrojas/myvim/master/mvim.png "MacVim screenshot")
