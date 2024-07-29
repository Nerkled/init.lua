# Neovim Configuration (`init.lua`)

This README provides an overview of my Neovim configuration following Primeagen's guide (0 to LSP). The setup includes essential plugins, settings, and configurations to enhance productivity and code navigation.

This will come to change...

## Table of Contents

1. [Installation](#installation)
2. [File Structure](#file-structure)
3. [Plugins](#plugins)
4. [Keybindings](#keybindings)
5. [LSP Configuration](#lsp-configuration)
6. [Additional Configurations](#additional-configurations)
7. [Troubleshooting](#troubleshooting)
8. [References](#references)

## Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/yourusername/neovim-config ~/.config/nvim
    ```

2. **Install dependencies:**

    Ensure you have `neovim` installed. You can install it via your package manager:

    ```sh
    # For Debian/Ubuntu
    sudo apt install neovim

    # For macOS
    brew install neovim
    ```

3. **Install plugins:**

    Open Neovim and run the following command to install plugins:

    ```vim
    :PackerSync
    ```

