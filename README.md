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

1. arrange directories
2. 環境変数 `GOPATH` を設定
3. security soft インストール
4. set gitHub sshKeys
