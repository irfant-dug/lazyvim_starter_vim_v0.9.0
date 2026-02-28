# 💤 LazyVim

A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.

Wipe after install:
Delete: (paths may be different for your OS)

    ~/.local/share/nvim/lazy/LazyVim
    ~/.config/nvim/lazy-lock.json

lazy/nvim-treesitter-context/lua/treesitter-context.lua:  local node_text = vim.treesitter.query.get_node_text(node, 0). Replace with vim.treesitter.get_node_text(node, 0)
