<div align="center">

# Chamal1120's OSX otfiles
Trying to see if I can replicate what I have on linux with hyprland.

</div>

## What's in
1. Terminal Emulator -> Alacritty
2. Shell prompt -> p10k
3. Terminal Multiplexer -> Tmux
4. WM Emulator -> Yabai + skhd
5. IDE -> Neovim
6. Font -> Meslo Nerd Font

## Installation
I use GNU Stow to manage my dotfiles. Look up `man stow` for more info.

1. Make sure the programs are installed before proceeding.

1. Stow using following command.

```bash
cd configs
stow --target=$HOME <enter the configs you need seperated with spaces>
```

2. Enjoy!

## Uninstallation
You can simply delete the symlinks or use Stow to remove them as a batch.

## LICENSE
Lincesed under [_do what the fuck you want to public license_](./LICENSE).
