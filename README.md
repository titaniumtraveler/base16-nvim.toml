# base16-vim.toml

[base16-vim] port to be build with [colorgen-nvim](https://github.com/LunarVim/colorgen-nvim). \
It is specifically using [this pr](https://github.com/titaniumtraveler/colorgen-nvim/tree/pr/global-variables) for it.

```console
$ colorgen-nvim ./base16.toml --single-file --output base16.lua
```

Currently it is not a general base16 theme, but specialised to use atelier-dune, but I can't be bothered to fix that right now.

- In branch `base16-vim` are the exact values used in [base16-vim].
- In `main` are my own modifications.

[base16-vim]: https://github.com/chriskempson/base16-vim

## License

Released under MIT License
