# vim configs

 *Adapted from: https://github.com/Valloric/dotfiles/blob/master/vim/vimrc.vim*
 

## Installation

Link the .vimrc file

		ln -s ~/.vim/.vimrc ~/.vimrc

use Vundle to install the Bundles.

		vim +BundleInstall! +BundleClean +q

Grab and install the **Inconsolata-dz** patched font for Powerline:

<https://gist.github.com/1595572>

## What's packed in this:

### Package Manager

#### [vundle](https://github.com/gmarik/vundle)
Vundle, the plug-in manager for Vim


Name                                                         | Desc                                                         | Bindings
------------                                                 | -------------------------------------------                  | ------------
[ctrlp](https://github.com/kien/ctrlp.vim)                   | Fuzzy file, buffer, mru and tag finder                       | `,p`
[ack](https://github.com/mileszs/ack.vim)                    | Vim plugin for the Perl module / CLI script                  | `,f`
[fugitive](https://github.com/tpope/vim-fugitive)            | fugitive.vim: a Git wrapper so awesome, it should be illegal | `:G<command>`
[ctrlp](https://github.com/kien/ctrlp.vim)                   | Fuzzy file, buffer, mru and tag finder                       | `,p`
[sparkup](https://github.com/rstacruz/sparkup)               | A parser for a condensed HTML format.                        | `<C-e>`
[nerdcommenter](https://github.com/scrooloose/nerdcommenter) | The premier commenting tool.                                 | `,cc / ,cu`
[vim-easymotion](https://github.com/Lokaltog/vim-easymotion) | Easymotion provides a much simpler way to use motion in Vim  | `,e`
[tabular](https://github.com/godlygeek/tabular)              | Text filtering and alignment                                 | `,t`
[vim-surround](https://github.com/tpope/vim-surround)        | Quoting/parenthesizing made simple                           | `S`


## Screenshot

![](https://camo.githubusercontent.com/eecdcc0e13dec640a9a3becf84759b98d5032689/687474703a2f2f692e696d6775722e636f6d2f653739396333442e706e67)
