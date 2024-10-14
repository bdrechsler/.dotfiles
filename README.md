# dotfiles

## Prerequisites
- Terminal: full color terminal such as iterm2
- Set zsh as default shell with: `chsh -s /bin/zsh`
- Homebrew: install with `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
- NerdFonts: Need a nerd font, such as meslo, to show icons and other symbols
  - Can install with homebrew `brew install --cask font-meslo-lg-nerd-font`
  - Set as font in iterm2 settings (Cmd + ,)
- Stow: Used to set up symlinks install with `brew install stow`
- Micromamba: alternative to conda, install with `brew install micromamba` then follow directions

## Usage
- Use `stow` to set up symbolic links and setup configuration
- Example: Nvim:
  - from the `.dotfiles` directory, use `stow nvim` to create the ~/.config/nvim symlink
  - This will set the nvim configuration defined this repo
- Example: .zshrc
  - Use `stow zsh` to create the .zshrc symlink
