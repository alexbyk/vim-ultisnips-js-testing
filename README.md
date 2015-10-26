# vim-ultisnips-mocha
Vim snippets for UltiSnips with basic javascript mocha block using modern ES6 syntax (right now a fat arrow `() => {}`)

## Snippets
* `desc` - **desc**ribe with filebasename as description
* `describe` - describe with verbosive description
* `it` - it
* `bee` - **be**fore**E**ach
* `afe` - **af**ter**E**ach
* `before` - before
* `after` - after

## Assert
* `aeq` - **a**ssert.**eq**ual
* `adeq` - **a**ssert.**d**eep**Eq**ual
* `afalse` - **a**ssert.is**False**
* `atrue` - **a**ssert.is**True**
* `athr` - **a**ssert.**Thr**ows

## Installation
Using Vundle:
```
" install UltiSnips
Plugin 'SirVer/ultisnips'
"let g:UltiSnipsExpandTrigger="<C-J>" "(optional) CTRL-J instead of TAB to avoid conflicts with YCM
Plugin 'alexbyk/vim-ultisnips-mocha'
```
