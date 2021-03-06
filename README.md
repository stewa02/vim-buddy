# Buddy colorscheme for Vim

## Introduction
![Buddy screenshot][buddy]
This is the Buddy color scheme for Vim. It is a based on a palette of yellow to 
red tones. The colorscheme looks best with 24-bit colour support (meaning GVim 
or terminals with 24-bit colour support and `set termguicolors` set in your 
`.vimrc`. In a normal 256-colour terminal the closest colours from the fixed 
palette will be used.

## Lightline colorscheme
![Lightline Buddy colorscheme][normal]
![Lightline Buddy colorscheme][insert]
![Lightline Buddy colorscheme][visual]
![Lightline Buddy colorscheme][replace]
In addition to the colorscheme for basic Vim, there is a colorscheme for the 
users of the [lightline.vim][1] plugin. Screenshots of the statusline in the 
different modes and the tabline are included above.

It is based on the wombat colorscheme for `lightline.vim` by itchyny (basically 
the different colours were just adapted to the Buddy palette.

## Possible Issues
 - If you are using tmux and the background colour looks differently behind text 
   and elsewhere it is **not** a bug in the colorscheme, but [this][2] article 
   might help you.
 - If italics in comments don't show up correctly in your terminal emulator you 
   can turn them off by setting `let g:buddy_notermitalics = 1`.

## Contributors
The colorscheme was originally generated by @DrSpatula using the vivify online 
editor and later changed to fit the purposes of @stewa02 by @stewa02.

[1]: https://github.com/itchyny/lightline.vim
[2]: https://sunaku.github.io/vim-256color-bce.html

[visual]: https://github.com/stewa02/vim-buddy/blob/master/md/img/visual.png
[replace]: https://github.com/stewa02/vim-buddy/blob/master/md/img/replace.png
[normal]: https://github.com/stewa02/vim-buddy/blob/master/md/img/normal.png
[insert]: https://github.com/stewa02/vim-buddy/blob/master/md/img/insert.png
[buddy]: https://github.com/stewa02/vim-buddy/blob/master/md/img/buddy.png

