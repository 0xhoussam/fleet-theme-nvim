# Fleet theme for Neovim

A port of the default theme from Jetbrains' Fleet IDE for Neovim with Treesitter support.

![Screenshot](https://user-images.githubusercontent.com/17355488/235284483-77920361-b1b7-4c12-8b1a-d81952aeb947.png)

Includes support for:

- Tree-sitter
- LSP semantic highlighting
- [rainbow-delimiters.nvim](https://gitlab.com/HiPhish/rainbow-delimiters.nvim)
- [lukas-reineke/indent-blankline.nvim](https://github.com/lukas-reineke/indent-blankline.nvim)
- [hrsh7th/nvim-cmp](https://github.com/hrsh7th/nvim-cmp)

## Installation

Using [lazy.nvim](https://github.com/folke/lazy.nvim):

```lua
{
  "0xhoussam/fleet.nvim",
  config = function() vim.cmd("colorscheme fleet") end
}
```

## Credits

Colors were initially taken from the [Helix editor](https://github.com/helix-editor/helix)'s builtin [fleet dark theme](https://github.com/helix-editor/helix/blob/b0ceac608ebc117399af89b81fbd0837d370161d/runtime/themes/fleet_dark.toml).

## License

[MIT](./LICENSE)
