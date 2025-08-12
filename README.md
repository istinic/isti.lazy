# 💤 LazyVim

A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.

All above are from the Starter LazyVim.
All bellow are from the:
# [documentation](https://lazyvim.github.io/installation):
## 1. ⌨️ [Keymaps](https://www.lazyvim.org/keymaps)

LazyVim uses [which-key.nvim] to help you remember your keymaps. Just press any key like <space> and you'll see a popup with all possible keymaps starting with <space>.

    default <leader> is <space>
    default <localleader> is \

Here comes all the default keymas grouped by usage ...

## 2. [Configuration](https://www.lazyvim.org/configuration)
### 📂 File Structure

The files under config will be automatically loaded at the appropriate time, so
you don't need to require those files manually. For more information, see [general settings].

You can add your custom plugin specs under lua/plugins/. All files there will be
automatically loaded by [lazy.nvim]. For more information, see [configuring plugins].

### Icons & Colorscheme #

Icons & colorscheme can be configured as options for the LazyVim plugin.
For example in lua/plugins/core.lua

### Default Settings #

## 3. [Core Plugins](https://www.lazyvim.org/plugins)
LazyVim provides a set of preconfigured plugins enabled by default. All you need to do to utilize these plugins is install the LazyVim starter template.
    [Coding](https://www.lazyvim.org/plugins/coding): Faster coding with features such as snippets, autocompletion, and more.
    [Colorscheme](https://www.lazyvim.org/plugins/colorscheme): Default color schemes (TokyoNight and Catppuccin).
    [Editor](https://www.lazyvim.org/plugins/editor): Provides functionality like a file explorer, search and replace, fuzzy finding, git integration.
    [Formatting](https://www.lazyvim.org/plugins/formatting): Set up formatters using conform.nvim.
    [Linting](https://www.lazyvim.org/plugins/linting): Manage linters with the nvim-lint plugin.
    [LSP](https://www.lazyvim.org/plugins/lsp): configure the Language Server Protocol (LSP) client.
    [TreeSitter](https://www.lazyvim.org/plugins/treesitter): advanced syntax highlighting and plugins that use Treesitter parsers
    [UI](https://www.lazyvim.org/plugins/ui): Enhance the user interface with features such as status line, buffer line, indentation guides, dashboard, and icons.
    [Util](https://www.lazyvim.org/plugins/util): Contains utilities for session management, shared functionality, and other handy tools.
    
For detailed information on the default configurations of each plugin set and instructions on customizing them, refer to the respective documentation linked above.

## 4.[Extras](https://www.lazyvim.org/extras)

The easiest way to install extras in LazyVim is with the :LazyExtras command.