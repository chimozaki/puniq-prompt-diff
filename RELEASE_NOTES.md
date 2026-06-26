# Release Notes

[日本語](#jp-日本語) | [English](#en-english)

---

## JP 日本語

### 🎉 Version 1.0.0

**Updated: 2026-06-26**

PuniQ Prompt Diff v1.0.0 は、AI画像生成プロンプトの差分比較・重複確認・整理をブラウザ上で行うための初回公開版です。

### ✨ 新機能・追加

- 🔍 **2つのプロンプト比較に対応**  
  Prompt A と Prompt B を貼り付けるだけで、共通タグ、Aのみ、Bのみのタグを自動で抽出できます。

- 🧠 **類似候補の検出**  
  Aのみ / Bのみ に分かれたタグ同士から、誤字や表記ゆれの可能性がある組み合わせを表示できます。

- 🧩 **プロンプト内重複の検出**  
  Prompt A内、Prompt B内それぞれで、同じタグとして扱われる重複を確認できます。

- ⚖️ **ウェイト違いの検出**  
  同じタグ名でも `(tag:1.2)` のようにウェイト値が違うものを検出できます。

- 🧹 **削除後プレビュー**  
  選択タグ、共通タグ、重複タグ、ウェイト違いの片側削除を反映したプレビューを確認できます。

- 📋 **コピー機能**  
  共通タグ、差分タグ、類似候補、削除後プレビューをワンクリックでコピーできます。

- 💾 **比較セット保存**  
  よく使う比較内容をブラウザの `localStorage` に保存し、あとから呼び出せます。

### 🎨 UI改善

- 🎀 **タイトルフォントを Science Gothic に変更**  
  アプリ見出しに Google Fonts の `Science Gothic` を適用し、横に `ver.1.0.0` を表示しました。

- 🌙 **ライト / ダークテーマ切替**  
  画面右上のボタンから表示テーマを切り替えられます。

- 🧱 **アコーディオン表示を整理**  
  A内重複、B内重複、ウェイト違いのセクションを折りたたみ式にし、該当項目がある時だけ確認しやすくしました。

- 📐 **余白と読みやすさを調整**  
  重複・ウェイト違いセクションの上下余白を調整し、類似候補セクションと近い見た目に整えました。

### 🛠️ 公開準備

- 📚 **READMEを追加**  
  日本語、英語、繁體中文（台灣）、スペイン語の4言語READMEを作成しました。

- 📝 **リリースノートを追加**  
  v1.0.0 の内容を日本語・英語でまとめました。

- 🌐 **GitHub Pages向け構成**  
  `index.html` 単体で動作する静的Webアプリとして公開しやすい構成にしています。

- 🔒 **保存仕様を明記**  
  比較セットはブラウザの `localStorage` に保存され、外部サーバーへ送信されないことをREADMEに記載しました。

---

## EN English

### 🎉 Version 1.0.0

**Updated: 2026-06-26**

PuniQ Prompt Diff v1.0.0 is the first public release of a browser-based tool for comparing, checking, and cleaning AI image generation prompts.

### ✨ New Features

- 🔍 **Two-prompt comparison**  
  Paste Prompt A and Prompt B to automatically extract common tags, A-only tags, and B-only tags.

- 🧠 **Similar candidate detection**  
  Finds possible typos or wording variations between tags that appear only in A or only in B.

- 🧩 **Duplicate detection inside prompts**  
  Detects repeated tags inside Prompt A and Prompt B separately.

- ⚖️ **Weight change detection**  
  Detects tags with the same name but different weights, such as `(tag:1.2)`.

- 🧹 **Cleaned prompt preview**  
  Preview prompts after removing selected tags, common tags, duplicates, or one side of a weight difference.

- 📋 **Copy actions**  
  Copy common tags, diff tags, similar candidates, and cleaned previews with one click.

- 💾 **Saved comparison sets**  
  Save frequently used comparison pairs in browser `localStorage` and load them later.

### 🎨 UI Improvements

- 🎀 **Science Gothic title font**  
  Applied Google Fonts `Science Gothic` to the app title and added a small `ver.1.0.0` label beside it.

- 🌙 **Light / dark theme toggle**  
  Added a top-right button for switching between light and dark themes.

- 🧱 **Accordion sections**  
  Duplicates in A, duplicates in B, and weight changes are organized into collapsible sections.

- 📐 **Spacing and readability polish**  
  Adjusted vertical spacing around duplicate and weight-change sections to better match the similar-candidates section.

### 🛠️ Release Preparation

- 📚 **Added README**  
  Added a multilingual README in Japanese, English, Traditional Chinese for Taiwan, and Spanish.

- 📝 **Added release notes**  
  Added bilingual release notes for v1.0.0.

- 🌐 **GitHub Pages-ready structure**  
  The app is structured as a static single-file web app that can run directly from `index.html`.

- 🔒 **Clarified storage behavior**  
  Documented that saved comparison sets are stored in browser `localStorage` and are not sent to an external server.
