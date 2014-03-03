# VIM-KAREL

This vim bundle adds syntax highlighting for FANUC's KAREL programming language.

## Installing and Using

- Install [pathogen](http://www.vim.org/scripts/script.php?script_id=2332) into `~/.vim/autoload/` and add the
   following line to your `~/.vimrc`:

        call pathogen#infect()

- Make a clone of the `vim-karel` repository:

        $ mkdir -p ~/.vim/bundle
        $ cd ~/.vim/bundle
        $ git clone https://github.com/onerobotics/vim-karel

- OR use [vundle](https://github.com/gmarik/vundle), adding this line to your `~/.vimrc`:

        Bundle 'onerobotics/vim-karel'

- OR use git submodules:

        $ git submodule add https://github.com/onerobotics/vim-karel.git bundle/vim-karel
        $ git submodule init

## License ##

MIT
