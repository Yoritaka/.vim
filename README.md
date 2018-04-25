# .vim

# install

## ~/.vimrc

    set encoding=utf-8
    scriptencoding utf-8
    set runtimepath+=~/.vim
    runtime! configs/users/*.vim
    runtime! configs/plugins/*.vim

## init

    #設定ファイルを置くディレクトリを作成
    $ mkdir configs
    $ mkdir configs/users
    $ mkdir configs/plugins
    $ mkdir configs/plugins/install
    $ cd configs/users
    #plugins.vimを作成
    $ vim plugin.vim
