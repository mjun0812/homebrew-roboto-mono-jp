# mjun0812/homebrew-roboto-mono-jp

[RobotoMonoJP](https://github.com/mjun0812/RobotoMonoJP) 合成フォントの Homebrew tap。

Roboto Mono と日本語フォントを合成し、Nerd Fonts の glyph を追加した TTF (6 family × 4 style = 24 ファイル) を一括インストールします。

## Install

```bash
brew tap mjun0812/roboto-mono-jp
brew install --cask font-roboto-mono-jp
```

`brew install` の1回で下記の 6 family すべてがインストールされます。

| family             | 日本語フォント      |
| ------------------ | ------------------- |
| RobotoMonoPlex     | IBM Plex Sans JP    |
| RobotoMonoBizUd    | BIZ UDGothic        |
| RobotoMonoLineSeed | LINE Seed JP        |
| RobotoMonoNoto     | Noto Sans JP        |
| RobotoMonoZenKaku  | Zen Kaku Gothic New |
| RobotoMonoGenJyuu  | 源柔ゴシック        |

各 family は `Regular` / `Bold` / `Italic` / `BoldItalic` の TTF を含みます。

## Uninstall

```bash
brew uninstall --cask font-roboto-mono-jp
brew untap mjun0812/roboto-mono-jp
```

## Update

新しい version が RobotoMonoJP の release で公開されると、この tap の cask が自動更新されます。ユーザー側は次のコマンドで最新版に更新できます。

```bash
brew update
brew upgrade --cask font-roboto-mono-jp
```

## その他の入手方法

- 個別 family の ttf / otf を GitHub Releases から直接ダウンロード: <https://github.com/mjun0812/RobotoMonoJP/releases>
- ソースから生成: <https://github.com/mjun0812/RobotoMonoJP>

## License

配布物のフォントは [RobotoMonoJP のライセンス](https://github.com/mjun0812/RobotoMonoJP) (SIL Open Font License 1.1) に従います。
