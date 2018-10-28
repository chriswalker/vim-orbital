# Orbital
We're not quite in Deep Space yet... a tweaked version of [Deep Space](https://github.com/tyrannicaltoucan/vim-deep-space), that emphasises data over syntax, highlighting variables and values over more general syntactical elements such as funtions and keywords.

## Installation
**NOTE:** This color scheme requires a terminal that supports true colors!

Install this color scheme using your preferred Vim plugin manager, then add the
following to your (n)vim configuration file:
```vim
set background=dark
set termguicolors
colorscheme orbital
```

### Options
If your terminal supports italics, add:
```vim
let g:orbital_italics=1
```

### Vim Airline
To use the included [vim-airline](https://github.com/vim-airline/vim-airline) theme:
```vim
let g:airline_theme='orbital'
```

### Vim Lightline
To use the included [lightline.vim](https://github.com/itchyny/lightline.vim) theme:
```vim
let g:lightline = {
      \ 'colorscheme': 'orbital',
      \ }
```

