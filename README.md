# dotfiles

setup MacPC

# procedure

1. install [Homebrew](https://brew.sh/index_ja)
2. `git clone https://github.com/holman/dotfiles.git ~/.dotfiles`
3. `cd ~/.dotfiles`
4. `brew install rcmdnk/file/brew-file`
5. `mkdir -p ~/.config/brewfile`
6. `mv ~/.dotfiles/.config/brewfile/Brewfile ~/.config/brewfile`
7. `brew file install`

# after install

1. `mkdir ~/dev`
2. security soft インストール
3. set gitHub sshKeys
4. .gitconfigのTODOを埋める
