
## Installation:

Prerequisites: ruby, git.

1. Clone this repo into ".vim":
   `git clone https://github.com/angelbit/MyVimConfig ~/.vim`
3. Go into ".vim" and run "rake":
   `cd ~/.vim && rake`

This will install "~/.vimrc" and "~/.gvimrc" symlinks that point to
files inside the ".vim" directory.

## Features:

* 2 spaces, no tabs
* incremental, case-insensitive search
* 'Leader' character mapped to "," (comma)
* `,t` opens file search via FuzzyFinder plugin (instead of Command-T)
* `<C-j/k/h/l>` switches between windows (no need to prepend `<C-w>`)
* cursor keys for movement disabled!
* `F2` open/closes NerdTree
* `F4` remove unecessary whitelines
* `F6` re-indent file

## Plugins:

   * fugitive
   * nerdtree
   * ruby
   * rails
   * cucumber
   * haml
   * scss
   * rspec


