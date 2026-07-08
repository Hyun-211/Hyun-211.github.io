# 研究者ホームページ — 公開手順（GitHub Pages）

日英切替対応の静的サイトです。ビルド不要・完全無料で公開できます。

## ファイル構成

```
index.html          ホーム（自己紹介・研究テーマ・ニュース）
publications.html   論文リスト
talks.html          講演・発表リスト
cv.html             CV（学歴・研究歴・受賞など）
assets/style.css    デザイン
assets/main.js      日英切替
assets/photo.jpg    顔写真（任意。この名前で置くと表示されます）
```

## 公開手順（約10分）

1. [github.com](https://github.com) でアカウント作成（無料）。
2. 右上の「+」→「New repository」。リポジトリ名を **`ユーザー名.github.io`** にする（例: `hyunjeong.github.io`）。Public のまま「Create repository」。
3. リポジトリページで「uploading an existing file」（または Add file → Upload files）をクリックし、このフォルダの中身（`index.html` 等と `assets` フォルダ）をすべてドラッグ&ドロップ →「Commit changes」。
4. 数分後、`https://ユーザー名.github.io` でサイトが公開されます。

リポジトリ名を `ユーザー名.github.io` 以外（例: `homepage`）にした場合は、Settings → Pages → Branch を `main` にすると `https://ユーザー名.github.io/homepage/` で公開されます。

## 更新方法

GitHub のリポジトリページで該当ファイルを開き、鉛筆アイコンで直接編集 → Commit。論文追加は `publications.html` の `<li>` ブロックをコピーして書き換えるだけです。

## メモ

- 携帯番号と Referees は非公開情報のためサイトに含めていません。
- 顔写真は `assets/photo.jpg` として追加してください（なければ自動的に非表示）。
- 独自ドメイン（例: hyunjeong.com）も Settings → Pages から設定可能（ドメイン代のみ有料）。
