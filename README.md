# my-tool

毎日の作業をもっとシンプルにするツール「my-tool」のリポジトリです。

現在は、紹介用のランディングページ（静的な HTML / CSS）が入っています。

## ファイル構成

```
.
├── index.html   # ランディングページ本体
├── style.css    # ランディングページのスタイル
└── README.md
```

## ローカルで確認する

ビルドは必要ありません。`index.html` をブラウザで開けば表示できます。

```sh
open index.html
```

## 開発の流れ

1. `main` から作業用ブランチを作る
   ```sh
   git switch main
   git pull
   git switch -c feature/作業内容
   ```
2. 変更してコミットする
3. ブランチを push して、GitHub でプルリクエストを作る
4. 内容を確認して `main` にマージする
