# Markdown Equation Insert Plugin for Vim

This plugin helps inserting LaTeX equation into markdown file as gif generated
by [latex.codecogs.com](latex.codecogs.com).

## How to Install

Use your plugin manager of choice.

- [Pathogen](https://github.com/tpope/vim-pathogen)
  - `git clone https://github.com/ron89/md_insert_equation.vim ~/.vim/bundle/thesaurus_query.vim`
- [Vundle](https://github.com/gmarik/vundle)
  - Add `Bundle 'ron89/md_insert_equation.vim '` to .vimrc
  - Run `:BundleInstall`
- [NeoBundle](https://github.com/Shougo/neobundle.vim)
  - Add `NeoBundle 'ron89/md_insert_equation.vim'` to .vimrc
  - Run `:NeoBundleInstall`
- [vim-plug](https://github.com/junegunn/vim-plug)
  - Add `Plug 'ron89/md_insert_equation.vim'` to .vimrc
  - Run `:PlugInstall`

## How to Use

 * To insert a new equation, invoke the function by command `:EditEquation`, or
   keybinding `<localleader>ee`, then type in the equation. Output would be an
   image link:
```
    ![](http://latex.codecogs.com/gif.latex?\\alpha\\frac\{a\}\{b\})
```
   and on github, it shall appear like ![](http://latex.codecogs.com/gif.latex?\\alpha\\frac\{a\}\{b\})

 * To edit an existing equation, invoke the same function/keybinding when cursor is on an existing equation link.

testing
  * ![](http://latex.codecogs.com/gif.latex?\\alpha+\\frac\{a\}\{b\})
  * ![](http://latex.codecogs.com/gif.latex?\\alpha-\\frac\{a\}\{b\})
  * ![](http://latex.codecogs.com/gif.latex?\\alpha\\times\\frac\{a\}\{b\})
  * ![](http://latex.codecogs.com/gif.latex?\\alpha*\\frac\{a\}\{b\})
  * ![](http://latex.codecogs.com/gif.latex?\\alpha/\\frac\{a\}\{b\})
  * ![](http://latex.codecogs.com/gif.latex?\\alpha/\\frac\{a_a\}\{b\})
  * ![](http://latex.codecogs.com/gif.latex?\\alpha/(\\frac\{a_a\}\{b\}))
  * ![](http://latex.codecogs.com/gif.latex?\\alpha/[\\frac\{a_a\}\{b\}])
  * ![](http://latex.codecogs.com/gif.latex?\\alpha/\\{\\frac\{a_a\}\{b\}\\})
  * ![](http://latex.codecogs.com/gif.latex?\\alpha/\{\\frac\{a.a\}\{b'\}\})
  * ![](http://latex.codecogs.com/gif.latex?\\alpha/\{\\frac\{a_a\}\{b`\}\})
  * ![](http://latex.codecogs.com/gif.latex?\\alpha/\{\\frac\{a_a!?\}\{b`\}\})
