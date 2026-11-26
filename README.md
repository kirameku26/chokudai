# chokudai

ターミナルに chokudai のアスキーアートを表示するコマンドです。

## Homebrew でのインストール

```sh
brew tap kirameku26/tap https://github.com/kirameku26/tap.git
brew install kirameku26/tap/chokudai
chokudai --version
```

リポジトリ名が `tap` なので、`brew tap` には URL も指定します。

配布用の Formula は `kirameku26/tap` で管理しています。[Formula/chokudai.rb](https://github.com/kirameku26/tap/blob/main/Formula/chokudai.rb)

## 使い方

```sh
chokudai
chokudai --deden
chokudai --say "こんにちは"
chokudai --help
```

## 更新

```sh
brew update
brew upgrade kirameku26/tap/chokudai
```

## 旧 tap からの移行

旧 tap からインストール済みの場合は、新しい tap を追加してから配布元を切り替えます。

```sh
brew tap kirameku26/tap https://github.com/kirameku26/tap.git
brew reinstall kirameku26/tap/chokudai
```

## ライセンス

[MIT](LICENSE) © kirameku
