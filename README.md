# vim configs

 *Adapted from: https://github.com/Valloric/dotfiles/blob/master/vim/vimrc.vim*
 

## Installation

Link the .vimrc file

		ln -s ~/.vim/.vimrc ~/.vimrc

use Vundle to install the Bundles.

		vim +BundleInstall! +BundleClean +q

copy base16 colors

    cp ~/.vim/bundle/base16-vim/colors/* ~/.vim/colors

Grab and install the **Inconsolata-dz** patched font for Powerline:

<https://gist.github.com/1595572>

## What's packed in this:

### Package Manager

#### [vundle](https://github.com/gmarik/vundle)
Vundle, the plug-in manager for Vim


Name	     |  Desc                                       | Bindings
------------ | ------------------------------------------- | ------------
[ctrlp](https://github.com/kien/ctrlp.vim) | Fuzzy file, buffer, mru and tag finder | `,f`
[airline](https://github.com/bling/vim-airline) | lean & mean status/tabline for vim that's light as air |
[bufexplorer](https://github.com/c9s/bufexplorer) | With bufexplorer, you can quickly and easily switch between buffers. | `,be`
[ack](https://github.com/mileszs/ack.vim) | Vim plugin for the Perl module / CLI script | `,a`
[fugitive](https://github.com/tpope/vim-fugitive) | fugitive.vim: a Git wrapper so awesome, it should be illegal
[syntastic](https://github.com/scrooloose/syntastic) | Syntax checking hacks for vim
[vim-git](https://github.com/tpope/vim-git) | Vim Git runtime files
[ctrlp](https://github.com/kien/ctrlp.vim) | Fuzzy file, buffer, mru and tag finder | `,f`
[sparkup](https://github.com/rstacruz/sparkup) | A parser for a condensed HTML format. | `,e`
[nerdcommenter](https://github.com/scrooloose/nerdcommenter) | The premier commenting tool. | `c<space>`
[supertab](https://github.com/ervandew/supertab) | Perform all your vim insert mode completions with Tab. | `<tab>`

## Screenshot

![](https://camo.githubusercontent.com/eecdcc0e13dec640a9a3becf84759b98d5032689/687474703a2f2f692e696d6775722e636f6d2f653739396333442e706e67)
