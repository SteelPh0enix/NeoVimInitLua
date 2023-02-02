# My NeoVim setup

This repository contains my NeoVim configuration files.

Currently it's a single `init.lua` but it's supposed to change soon™.

This is based on `kickstart.nvim`

## Plugin list

* packer.nvim - package manager
* nvim-lspconfig + mason + mason-lspconfig - LSP
* fidget.nvim - status updates for LSP
* neodev.vim - adnotations and useful utils for config
* nvim-cmp - autocompletion
* nvim-treesitter (with nvim-treesitter-textobjects) - highligh, editing and code navigation
* vim-fugitive + vim-rhubarb + gitsigns.nvim - Git utilities
* lualine.nvim - fancy statusline
* indent-blankline - adding indentation guides even on blank lines
* Comment.nvim - easier commenting when in visual mode
* vim-sleuth - tabstop/shiftwidth detection
* telescope.nvim (with telescope-fzf-native.nvim) - fuzzy finder
* nvim-tree - file manager
* vim-closer - automatic bracket/parenthesis closing
* vim-endwise - similar to vim-closer, but for structures
* rust-tools - rust LSP config
