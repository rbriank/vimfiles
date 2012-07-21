rbriank's vim configuration
==========================

Thanks to these guys:
* [Mislav](https://github.com/mislav),
* [Gary Bernhardt](http://destroyallsoftware.com),
* [Drew Neil](http://vimcasts.org),
* [Tim Pope](http://tbaggery.com),
* and the [Janus project](https://github.com/carlhuda/janus).

My configuration uses [Pathogen](https://github.com/tpope/vim-pathogen) and git submodules.
(But you don't need to care about any of that.)

## Installation:

Prerequisites: ruby, git.

1. Move your existing configuration somewhere else:  
   `mv ~/.vim* ~/.gvim* my_backup`
2. Clone this repo into ".vim":  
   `git://github.com/rbriank/vimfiles.git ~/.vim`
3. Go into ".vim" and run "rake":  
   `cd ~/.vim && rake`

This will install "~/.vimrc" and "~/.gvimrc" symlinks that point to
files inside the ".vim" directory.

To add a new plugin:
$ cd ~/.vim/
$ git init

git submodule add https://github.com/msanders/snipmate.vim.git bundle/snipmate

## Features:

* 2 spaces, no tabs
* incremental, case-insensitive search
* 'Leader' character mapped to "," (comma)
* `,f` opens file search via :CommandT plugin
* `,,` switches between two last buffers
* `<C-j/k/h/l>` switches between windows (no need to prepend `<C-w>`)
* cursor keys for movement disabled!

## Plugins:

* ack
* command-t
* commentary
* endwise
* fugitive
* rails
* javascript
* ruby
* surround
* repeat
* syntastic

## Colors:

* vividchalk

