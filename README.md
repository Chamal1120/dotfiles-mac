<div align="center">

# Chamal1120's macOS Dotfiles

_Tryna replicate my GNU/Linux setup_

</div>

## What's in
1. Terminal Emulator -> Alacritty
2. Terminal Multiplexer -> Tmux
3. Shell prompt -> p10k
4. WM Emulator -> Yabai + skhd
5. IDE -> Neovim
6. Font -> Meslo Nerd Font
7. Shell -> zsh (including shell completions, syntax highlighting and etc)

## Installation
I use GNU Stow to manage my dotfiles. It's just a symlink batch processor. You can manually symlink if you want.

1. Make sure the programs of the configs you want to symlink are installed. 

2. Symlink the dotfiles:
```bash
cd configs
stow --target=$HOME <enter the configs you need seperated with spaces>
```

3. Enjoy!

## Uninstallation
You can simply delete the symlinks or use Stow to remove them as a batch.

## LICENSE
[_do what the fuck you want to public license_](./LICENSE).
