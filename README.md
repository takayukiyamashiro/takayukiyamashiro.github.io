# Takayuki Yamashiro — Jekyll版 GitHub Pages

GitHub Pages標準のJekyll機能を使ったサイトです。`_posts` にMarkdownファイルを追加すると、記事ページと記事一覧が自動で更新されます。

## 最初の公開

1. このZIPを展開します。
2. 中のファイルとフォルダをすべて `takayukiyamashiro.github.io` リポジトリのルートへ置きます。
3. 以前の版にあった `.nojekyll` がリポジトリに残っていれば削除します。
4. GitHubの **Settings → Pages** で **Deploy from a branch**、`main`、`/(root)` を選んで保存します。
5. 数分後に `https://takayukiyamashiro.github.io/` へ反映されます。

## GitHub上で新しい記事を書く

1. リポジトリで `_posts` フォルダを開きます。
2. **Add file → Create new file** を選びます。
3. ファイル名を `YYYY-MM-DD-半角英数字の名前.md` にします。
   - 例: `2026-08-20-blood-pressure.md`
4. `POST_TEMPLATE.md` の内容をコピーし、タイトル・説明・本文を書き換えます。
5. **Commit changes** を押すと、通常は数分で記事一覧とサイトへ反映されます。

Markdown本文では `##` が大見出し、`-` が箇条書き、`[文字](URL)` がリンクです。POINT欄はテンプレートの `>` から始まる部分をコピーして使えます。

## 下書きにする

公開前の記事は `_drafts` に置きます。`_drafts/article-template.md` も用意しています。公開するときは、ファイル名を `YYYY-MM-DD-slug.md` に変更して `_posts` へ移します。

すでに `_posts` 内で編集している記事を一時的に非公開にする場合は、先頭の設定部分へ次を追加します。

```yaml
published: false
```

## 主なファイル

- `_posts/`: 公開記事のMarkdown
- `_drafts/`: 下書き
- `_layouts/`: ページの共通レイアウト
- `index.html`: トップページ
- `knowledge/index.html`: 記事一覧
- `style.css`: 全ページ共通デザイン
- `_config.yml`: Jekyllとサイト全体の設定
- `POST_TEMPLATE.md`: 新規投稿用テンプレート

サイトとリポジトリ内容はインターネット上から閲覧できます。患者情報、未公開研究データ、個人情報は置かないでください。

