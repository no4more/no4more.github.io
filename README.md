# no4more の個人発信スペース（管理用）

ここは、GitHub Pages を用いて公開している個人の思考ログ・小論文サイトのリポジトリです。
アルゴリズムや既存のプラットフォームに依存せず、純粋なテキスト空間を構築することを目的としています。

## サイトURL
https://no4more.github.io/

## 運用ルール
* 無駄な装飾やトラッキングスクリプトは一切入れない
* 純粋なHTMLとCSSのみで構成する
* 記事を追加する際は、必ず `index.html` にリンクを追記する

## 記事作成テンプレート
新しい記事を作る時は、この構造をコピーして使うこと。

```html
<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <title>記事のタイトル</title>
    <!-- cssは省略 -->
</head>
<body>
    <h1>記事のタイトル</h1>
    <p>本文をここに書く...</p>
    <p><a href="index.html">← トップに戻る</a></p>
</body>
</html>
