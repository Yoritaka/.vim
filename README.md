# .vim

# install

## ~/.vimrc

    set encoding=utf-8
    scriptencoding utf-8
    set runtimepath+=~/.vim
    runtime! ./configs/users/*.vim
    runtime! ./configs/plugins/*.vim
    runtime! ./configs/plugins/install/*.vim
    
    :set number
    :set backspace=indent,eol,start

## init

    #設定ファイルを置くディレクトリを作成
    $ mkdir configs
    $ mkdir configs/users
    $ mkdir configs/plugins
    $ mkdir configs/plugins/install
    $ cd configs/users
    #plugins.vimを作成
    $ vim plugin.vim
