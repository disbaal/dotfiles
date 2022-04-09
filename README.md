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


## Install Fonts

1. Install pragmata pro - http://files.catbox.moe/3nh2tk.zip (sha256sums=('5a73549e4349ea914de7eabdfe264405aec23c8c281bdd644b6ece34790757da' '71a14f207ca21d1ce2b168ce974341e54792e99036599af4582530b1277441f6'))
2. Install Operator Mono: download Fonts
3. Build Operator Mono + Ligatures: https://github.com/kiliman/operator-mono-lig
