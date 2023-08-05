# ターミナル系の設定
順にコマンドを実行するのではなく、リンク貼っておくからこのドキュメント通りにインストールよろしく!の方針にしています。  

## 1. brew
[brew](https://brew.sh/index_ja)のインストール手順を参考にする  
next stepにpathを通す手順が表示されるので、そのコマンドを実行する

## 2. oh-my-zsh
まず、zshのインストールから
```shell
brew install zsh
```
[ohmyzsh](https://github.com/ohmyzsh/ohmyzsh)をインストール手順通りに実施する

## 3. alias
```shell
alias ll="ll -a"
alias cc="clear"
alias czh="code ~/.zshrc"
```