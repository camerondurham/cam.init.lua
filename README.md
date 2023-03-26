
I claim no originality for this setup, it's not mine.

This is almost an exact 1:1 copy of https://github.com/ThePrimeagen/init.lua

## notes

1. Install NeoVim `0.9`
2. Force remove any old config if needed: `brew uninstall --force neovim && rm -rf ~/.config/nvim && rm -rf ~/.local/share/nvim`
3. Install [wbthomason/packer.nvim](https://github.com/wbthomason/packer.nvim): `git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim`
4. Run `./dev`
5. Run `:PackerSync` in neovim in `./lua/cam/packer.lua`
6. Profit
