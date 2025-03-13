# class doc

授業資料を格納するリポジトリです。

## 環境構築

macOS での環境構築を記載します。

```sh
# yarn のインストール
# build-mdc.ts を実行するために必要
yarn install

# textlint のインストール
npm install -g textlint

# GitHub CLI のインストール & 認証
# Composer 等で AI に Issue, PR を作成してもらうために必要
brew install gh
gh auth login
```

また、以下ツールの使用を前提としています。

- Cursor
- Git
- GitHub
