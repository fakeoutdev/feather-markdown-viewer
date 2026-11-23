# 変更履歴 / Changelog

[日本語](#日本語) | [English](#english)

## 日本語

### 1.2.0（未公開）

- YAML の Frontmatter（文書先頭の `---` で囲んだ部分）を本文の前に表で表示。表示設定の「Frontmatter」で、縦並び・横並び（GitHub と同じ）・コードブロック（書いたままの YAML）から選べる
- 修正: 1920×1080 などのディスプレイで、新しいウィンドウの下端がタスクバーに隠れることがある問題

### 1.1.0（2026-11-21）

- ステータスバーに文書の行数とファイルサイズを表示（ファイルサイズにマウスを乗せるとバイト数）
- 修正: エクスプローラーで `.md` ファイルを続けてすばやく開くと、応答しなくなることがある問題
- 修正: 同じファイルをすばやく続けて開くと、ウィンドウが 2 つ開くことがある問題
- 修正: すでに Feather を起動しているときに別のファイルを開くと、新しいウィンドウが前面に出ないことがある問題

### 1.0.0（2026-11-16）

最初のリリースです。

- エクスプローラーで `.md` ファイルをダブルクリックするとすぐに表示（2 つ目以降のファイルは別のウィンドウでさらに速く開く）
- GitHub Flavored Markdown（表・タスクリスト・脚注・取り消し線・自動リンク）とコードの色分け
- Mermaid の図（フローチャート、シーケンス図など）
- 読みやすさの設定: 本文の幅（制限なしも可）、文字サイズ、行間、段落内の改行（スペース／改行）、本文とコードのフォント、ライト／ダーク／システム（Windows の設定に合わせる）
- Shift_JIS・EUC-JP などの文字コードを自動判定
- ファイルが保存されると自動で再読み込み（スクロール位置を保持）
- 外部エディタで開く
- ページ内検索、拡大縮小、Markdown 間のリンク移動と戻る／進む
- ようこそ画面、最近開いたファイル、ドラッグ＆ドロップ
- Windows 11 のスナップ レイアウト、ハイコントラスト、キーボード操作
- 日本語と英語の表示
- 文書内のスクリプトは実行せず、実行ファイルへのリンクは開かない
- データを収集・送信しない

## English

### 1.2.0 (unreleased)

- YAML front matter (the block between `---` lines at the top of a document) is shown as a table before the text. Choose Vertical, Horizontal (as on GitHub) or Code block (the YAML as written) under "Front matter" in the view settings
- Fixed: on displays such as 1920×1080, the bottom of a new window could be hidden behind the taskbar

### 1.1.0 (2026-11-21)

- The status bar shows the line count and file size of the document (point at the size to see the exact number of bytes)
- Fixed: opening `.md` files from File Explorer in quick succession could make Feather stop responding
- Fixed: opening the same file twice in quick succession could open two windows
- Fixed: while Feather was already running, the window for another file could open behind other windows

### 1.0.0 (2026-11-16)

First release.

- Double-click a `.md` file in File Explorer and it is on screen right away (further files open even faster, each in its own window)
- GitHub Flavored Markdown (tables, task lists, footnotes, strikethrough, autolinks) and syntax highlighting
- Mermaid diagrams (flowcharts, sequence diagrams and more)
- Readability settings: text width (including unlimited), font size, line spacing, line breaks in paragraphs (space or line break), text and code fonts, light / dark / system (follows Windows)
- Automatic text encoding detection (UTF-8, Shift_JIS, EUC-JP and others)
- Reloads automatically when the file is saved, keeping the scroll position
- Open in external editor
- Find in page, zoom, follow links between Markdown files with back and forward
- Welcome screen, recent files, drag and drop
- Windows 11 Snap Layouts, high contrast, keyboard navigation
- Japanese and English user interface
- Scripts in documents never run, and links to programs are never opened
- Collects and sends no data
