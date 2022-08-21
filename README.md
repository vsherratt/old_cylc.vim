# cylc.vim

Simple standalone vim plugin for [Cylc](https://github.com/cylc/cylc-flow)

## Installation

It is recommended to install as a Vim package
(see [`:help packages`](https://vimhelp.org/repeat.txt.html#packages)):

```bash
mkdir -p ~/.vim/pack/vendor/start
cd ~/.vim/pack/vendor/start
git clone https://github.com/vsherratt/cylc.vim.git
```

Otherwise, use your favourite plugin manager, such as
[pathogen.vim](https://github.com/tpope/vim-pathogen).

## Usage

Cylc syntax is linked to standard vim highlighting groups, so should already be
consistent with any colour scheme.

Syntax-based folding is enabled; if you want to open files with folds initially
open, then add the following line to your vimrc:

```vim
set foldlevelstart=99
```
