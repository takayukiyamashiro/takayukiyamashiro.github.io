# Takayuki Yamashiro — GitHub Pages site

GitHub Pagesへそのまま配置できる静的サイトです。Node.jsやビルド作業は不要です。

## 公開方法

1. このZIPを展開します。
2. 中のファイルとフォルダをすべて `takayukiyamashiro.github.io` リポジトリのルートへ置きます。
3. GitHubで **Settings → Pages** を開きます。
4. **Deploy from a branch**、`main`、`/(root)` を選んで保存します。
5. 数分後に `https://takayukiyamashiro.github.io/` へ反映されます。

## ファイル構成

- `index.html`: トップページ
- `style.css`: 全ページ共通デザイン
- `knowledge/index.html`: 記事一覧
- `knowledge/*/index.html`: 各記事
- `robots.txt` / `sitemap.xml`: Google検索向け設定

GitHub Pagesで公開すると、サイトとリポジトリ内容はインターネット上から閲覧できます。患者情報、未公開研究データ、個人情報は置かないでください。
