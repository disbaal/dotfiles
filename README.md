# dotfiles

## Fresh install

1. `xcode-select --install`
2. `/usr/sbin/softwareupdate --install-rosetta --agree-to-license`
3. `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
4. add `export PATH=/opt/homebrew/bin:/usr/local/bin:/usr/local/sbin:~/bin:$PATH` to `~/.zshrc`
5. After openning iTerm2, do iTerm2 > Make iTerm2 Default Term
6. open iTerm2 prefs > import iTerm2 preferences
7. `brew install gpg`
8. `git config --global --edit`
9. 

## Fish shell
https://fishshell.com/

1. `brew install fish`
2. add `/opt/homebrew/bin/fish` to `/etc/shells`
3. change default shell `chsh -s /opt/homebrew/bin/fish`
4. Change the default login shell in Users and Groups > Advanced Options to `/opt/homebrew/bin/fish`
5. `fish_add_path /opt/homebrew/bin`

## Setup dev

1. Install rust `curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`
2. 

