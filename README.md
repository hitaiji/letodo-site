# Letodo GitHub Pages テンプレート

このディレクトリは、Letodo の紹介ページを別の public repository に切り出して GitHub Pages で公開するための最小テンプレートです。

## 含まれるファイル

- `index.html`
  - 1 ページ完結の紹介サイト本体
- `styles.css`
  - ページのスタイル
- `.nojekyll`
  - GitHub Pages の Jekyll 処理を無効化するための空ファイル

## 使い方

1. GitHub で新しい public repository を作る
   - 例: `letodo-site`
2. その repository を clone する
3. このディレクトリ内のファイルを、新しい repository のルートにコピーする
4. `index.html` のプレースホルダーを差し替える
   - `https://github.com/hitaiji/letodo-site`
   - `mailto:hello@example.com`
5. commit / push する

## 公開設定

GitHub の repository で以下を設定します。

1. `Settings > Pages` を開く
2. `Build and deployment` で `Source` を `Deploy from a branch` にする
3. `Branch` を `main`、`Folder` を `/(root)` にする
4. `Save` を押す

公開 URL は通常 `https://<your-github-username>.github.io/<repository-name>/` です。

## 先に差し替えるとよい箇所

- ヒーローセクションのキャッチコピー
- GitHub リンク
- 連絡先
- 現在の開発状況
- 将来的に使いたい独自ドメイン
