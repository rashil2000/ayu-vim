
![ayu-vim](http://i.imgur.com/7vnF4Na.png)

This theme works only if VIM supports `termguicolors` option. This is true for [Neovim](https://neovim.io) and VIM from 7.4.1799.

```VimL
Plug 'ayu-theme/ayu-vim' " or other package manager
"...
set termguicolors     " enable true colors support
let ayucolor="light"  " for light version of theme
let ayucolor="mirage" " for mirage version of theme
let ayucolor="dark"   " for dark version of theme
colorscheme ayu
```

