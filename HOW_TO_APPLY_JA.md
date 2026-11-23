# 日本語サイトへの更新方法

1. このZIPを解凍し、GitHub Pages のリポジトリ `yuhei-takahashi/yuhei-takahashi.github.io` に、フォルダー構造を保ったままファイルを追加・上書きしてください。
2. 別途作成する **業績一覧PDF** を `assets/pdf/publications.pdf` に配置してください。ファイル名は小文字で正確に `publications.pdf` とします。
3. GitHubにコミットすると、GitHub Pagesが更新されます。PDFを追加する前はPDFボタンが404になります。

## PDFボタンの配置場所

- トップページ `index.md`
- 「研究業績」ページ `_pages/publications.md`

いずれも `{{ '/assets/pdf/publications.pdf' | relative_url }}` を使い、PDFを新しいタブで開きます。業績一覧のPDFを更新する際は、同じファイル名で上書きしてください。コードの修正は不要です。

## 主な変更ファイル

- `_config.yml`: 言語設定（`ja-JP`）、サイト説明、プロフィール
- `_data/navigation.yml`: 日本語メニュー
- `index.md`: 日本語トップページとPDFボタン
- `_pages/*.md`: 経歴・研究業績・公開コード・お知らせの日本語化
- `assets/css/main.scss`: 日本語フォントとPDFボタン周りのデザイン
- `Gemfile`: 添付されたファイルと同一内容

## 注意点

- 論文の英語タイトル・著者・論文リンクは元のファイルのまま維持しました。掲載済みの業績を新規追加することはしていません。
- 元のリポジトリにある他のファイル（例：README.md）は変更しません。
- 最新の所属・経歴・業績が反映されているかは公開前に確認してください。
