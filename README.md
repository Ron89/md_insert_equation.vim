# Markdown Function Insert Plugin for Vim

This plugin helps inserting LaTeX function into markdown file as gif generated
by [latex.codecogs.com](latex.codecogs.com).

## How to Install

Use your plugin manager of choice.

- [Pathogen](https://github.com/tpope/vim-pathogen)
  - `git clone https://github.com/ron89/md_insert_function.vim ~/.vim/bundle/thesaurus_query.vim`
- [Vundle](https://github.com/gmarik/vundle)
  - Add `Bundle 'ron89/md_insert_function.vim '` to .vimrc
  - Run `:BundleInstall`
- [NeoBundle](https://github.com/Shougo/neobundle.vim)
  - Add `NeoBundle 'ron89/md_insert_function.vim'` to .vimrc
  - Run `:NeoBundleInstall`
- [vim-plug](https://github.com/junegunn/vim-plug)
  - Add `Plug 'ron89/md_insert_function.vim'` to .vimrc
  - Run `:PlugInstall`

## How to Use

Invoke the function by command `:InsertNewFunction`, or keybinding
`<localleader>if`, then type in the function. Output would be an image link:

    ![](http://latex.codecogs.com/gif.latex?[your_function])
