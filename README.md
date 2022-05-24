# Base16 Theme for [Cider](https://cider.sh)

> A [base16](https://github.com/chriskempson/base16) compatible styling for [Cider](https://cider.sh).

<p align="center"><img width=600 src="https://i.imgur.com/N43PzRk.png"></p>

The color definition of this theme is contained in the [`colors.less`](./colors.less) file.

This file should be rewritten using the [`base16-styles`](https://github.com/samme/base16-styles) `less` template using your prefered base16 builder.

This theme comes with the [`gruvbox-dark-hard`](https://github.com/dawikur/base16-gruvbox-scheme) scheme by default.

# Installing

## Download the theme

1. Go to Cider Music Settings.
2. Click on the `Explore GitHub Themes` button in the Theme section.
3. Look for `Base16 Theme for Cider` and click on it.
4. Click on the `Install` button and select the theme (if you have to). The theme should be applied.

This will download the repo to `~/.config/Cider/Themes/gh_495921395/`

## Intergrate with your base16 builder

The intergration with your prefered base16 builder depends on which builder you use, but
your builder should relace the `~/.config/Cider/Themes/gh_495921395/colors.less` file with [`base16-styles`](https://github.com/samme/base16-styles)'s `less` template completed with your chosen theme.

I use the [`flavours`](https://github.com/Misterio77/flavours) builder with the following config snippet:

```toml
[[items]]
file='$XDG_CONFIG_HOME/Cider/Themes/gh_495921395/colors.less'
template='styles'
subtemplate='less'
rewrite=true
```

# License

[MIT License](./LICENSE)
