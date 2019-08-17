# dotfiles

setup MacPC

# procedure
homedirectory
1. install [Homebrew](https://brew.sh/index_ja)
2. `mkdir -p ~/.config/brewfile`
3. `cd ~/.config/brewfile` `touch Brewfile`
4. XCODEをインストールしてBrewfile作成
5. `brew install rcmdnk/file/brew-file`
6. `brew file install`

# after install

1. homeで`mkdir ~/dev`
2. install security soft
3. set gitHub sshKeys
4. .gitconfig の TODO

# goで環境設定
1. AppStoreでXCodeインストール
1. mkdir -p ~/dev/{bin,src,pkg}
1. 環境変数 GOPATH を ~/dev/ に設定
1. 環境変数 PATH に /usr/local/opt/node@10/bin を追加
1. 環境変数 PATH に $GOPATH/bin を追加
1. /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
1. brew install rcmdnk/file/brew-file
1. mkdir -p ~/.config/brewfile
1. vim ~/.config/brewfile/Brewfile で当リポジトリのBrewfileをコピペ
1. [i] -> [Command]+[v] -> [ESC] -> [:][w][q]
1. brew file install
1. go get -u golang.org/x/tools/...
1. OpenVPN接続
1. .gitconfig に以下追記(プライベートリポジトリからのgo get対策)
[url "git@github.com:"]
    insteadOf = https://github.com/
1. git config "user.name" "githubのアカウント名"
1. git config "user.email" "githubの秘匿メールアドレス"
1. ssh-keygen -t ed25519 -N "" -C "コンピューター名" -f ~/.ssh/github
1. ~/.ssh/github.pub をGitHubに登録
