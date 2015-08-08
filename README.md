# vim-ultisnips-mocha
Vim snippets for UltiSnips with basic javascript mocha block using modern ES6 syntax (right now a fat arrow `() => {}`)

## Snippets
* desc `describe` with current filename without extention(s)
* desc `describe` verbose
* it
* bee `beforeEach`
* afe `afterEach`
* be
* af

## Installation
Using Vundle:
```
" install UltiSnips
Plugin 'SirVer/ultisnips'
"let g:UltiSnipsExpandTrigger="<C-J>" "(optional) CTRL-J instead of TAB to avoid conflicts with YCM
Plugin 'honza/vim-snippets.git' " (optional)
Plugin 'alexbyk/vim-ultisnips-mocha'
```
