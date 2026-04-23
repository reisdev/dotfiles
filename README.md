# dotfiles

A personal collection of configuration files for development environment setup, featuring vim, shell, status bars, and window management configurations.

## Overview

This repository contains dotfiles for customizing and optimizing a development environment. It includes configurations for multiple tools to create an efficient, aesthetic, and productive setup.

## Included Configurations

### Neovim
Modern editor configuration using `lazy.nvim` plugin manager.

**Features:**
- **Theme:** Nord color scheme for aesthetically pleasing interface
- **Plugins:**
  - `nord.nvim` - Nord color scheme
  - `git-conflict.nvim` - Git conflict resolution helpers
  - `grug-far.nvim` - Project-wide search and replace
  - `time-bomb.nvim` - Productivity timer with built-in keymaps
- **Settings:**
  - Relative line numbers enabled
  - Automatic plugin update checks

### Zsh
Shell configuration with Oh My Zsh and Powerlevel10k prompt.

**Features:**
- **Theme:** Powerlevel10k for enhanced prompt experience
- **Plugins:**
  - `git` - Git command helpers
  - `git-prompt` - Git status in prompt
  - `zsh-autosuggestions` - Command autosuggestions
- **Environment:**
  - Java 17 (OpenJDK) configured
  - Neovim set as default editor

### Polybar
Customizable status bar configuration.

**Included Polybars:**
- `first` - Uses Font Awesome TTF for icons

### i3
Window manager configuration files located in:
- `global/` - Global i3 settings
- `i3status/` - System status bar configuration

## Installation

Clone this repository to your local machine:

```bash
git clone https://github.com/reisdev/dotfiles.git
cd dotfiles
```

Then symlink the configuration files to your home directory as needed:

```bash
# Neovim
ln -s $(pwd)/nvim ~/.config/nvim

# Zsh
ln -s $(pwd)/zsh/.zshrc ~/.zshrc

# Polybar
ln -s $(pwd)/polybar ~/.config/polybar

# i3
ln -s $(pwd)/i3 ~/.config/i3
```

## License

MIT License - Copyright (c) 2019 Matheus dos Reis de Jesus

See [LICENSE](LICENSE) file for more details.
