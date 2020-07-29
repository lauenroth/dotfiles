# Jörg's Dotfiles

This repository helps seting up a Mac by installing all kinds of apps and configurations needed for web development.

## Requirements

- Make sure to update Mac OS to the latest version via App Store
- Xcode needs to be installed from the App Store followed by running this command in the terminal: `xcode-select --install`

## Setting up your Mac

1. Clone this repository to `~/.dotfiles`
2. Run the `install.sh` script
3. Sign in to all things
4. Restart your computer

## More commands

`chflags nohidden ~/Library`
`defaults write com.apple.finder AppleShowAllFiles YES`
`defaults write com.apple.finder ShowPathbar -bool true`
`defaults write com.apple.finder ShowStatusBar -bool true`

## Inspired by...

This repository was inspired by [Duncan's Dotfiles](https://github.com/damcclean/dotfiles).
