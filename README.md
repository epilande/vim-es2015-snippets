# Vim ES2015 Snippets

A Vim snippet library for ES2015. You may also want to check out [vim-react-snippets](https://github.com/epilande/vim-react-snippets).

Requires [UltiSnips](https://github.com/SirVer/ultisnips).

![vim-es2015-snippets](http://i.imgur.com/7EnLr1m.gif)

## Installation

Using vim-plug:

```vim
" ES2015 code snippets
Plug 'epilande/vim-es2015-snippets'

" React code snippets (Optional)
Plug 'epilande/vim-react-snippets'

" Ultisnips
Plug 'SirVer/ultisnips'

" Trigger configuration (Optional)
" let g:UltiSnipsExpandTrigger="<C-l>"
```

## Usage
In a JavaScript or JSX file, type a trigger name while in Insert mode, then press Ultisnips trigger key. In my case I have it mapped to `<C-l>`.

In Insert mode

```javascript
c=><C-l>
```

Will expand to

```javascript
const name = (args) => {
  return ;
};
```

Check out [`UltiSnips/javascript.snippets`](UltiSnips/javascript.snippets) to see all snippets.

