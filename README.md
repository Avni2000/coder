# Coder - Project Launcher

A minimal bash script to launch coding projects in a given directory

## Install/Setup
1. Download the `coder` executable to a directory of your choice
2. Create a symlink to make it globally accessible:
    ```bash
    ln -s <path-to-coder-executable> /usr/bin/coder
    ```
    (Or link to any directory in your `$PATH`)

## Usage
Simply type `coder` in your terminal to launch the interface.

## Features

- Uses gum for clean interface
- Configuration stored in `~/.config/coder/config`

## Navigation

- `type to filter` - Uses gum to quickly filter through folders
- `up/down` - Navigate through projects
- `Enter` - Open selected project in VSCode
- `q` - Quit

## Requirements

- gum
- bash
- VSCode with `code` command in PATH 

## Contributing

Let me know if you have more feature ideas!