# 📝 Mermaid Markdown Studio

ブラウザのクライアントサイドのみで完結する、軽量・高機能なMarkdownエディタ ＆ Mermaidリアルタイムプレビューワーです。  
外部サーバーへのデータ通信は一切行われないため、社外秘の設計図や仕様メモ、プライベートな思考整理も安心して作業できます。

> **🌐 Live Demo:**  
> ブラウザで今すぐ使える本番版はこちら 👉 **[https://selfup.net/md/](https://selfup.net/md/)**

---

## 🌟 主な機能 (Features)

### 1. 左右2分割スプリット表示
- **リアルタイムレンダリング:** 左ペインでMarkdownを入力すると、右ペインへ即座に整形表示
- **モバイル最適化:** スマートフォン表示時は「入力」「表示」のワンタップ切替に対応
- **自動保存 (localStorage):** 入力途中のテキストはブラウザ内に自動保持

### 2. Mermaid.js リアルタイムダイアグラム描画
- **多様なダイアグラム対応:** フローチャート、シーケンス図、ガントチャート、クラス図、ステートマシン図、ER図、マインドマップ、円グラフ等を ` ```mermaid ` ブロックから自動生成
- **高解像度画像エクスポート:** 各図の右上に配置されたアクションボタンから、SVG形式およびRetina対応の高解像度PNG画像（見切れ防止・実寸バウンディングボックス計算）をワンクリック保存

### 3. 多彩なエクスポート＆連携
- **リッチテキストコピー:** noteや各種ブログプラットフォームへ書式付きで直接ペースト可能
- **単一HTML保存:** レンダリング済みスタイルを内包したスタンドアロンHTMLファイル書き出し
- **標準Markdown完全対応:** GFM準拠テーブル、コードシンタックスハイライト、ToDoチェックボックス、引用

---

## 🛠 開発について (About)

このプロジェクトは、**生成AI（Gemini）を活用したバイブコーディング（対話型プログラミング）**によって制作されたシングルファイルWebアプリケーションです。

- **企画・仕様設計・ディレクション:** teratere
- **コード実装・AIアシスタント:** Gemini
- **コア技術:** HTML5 / Tailwind CSS / Vanilla JavaScript / [marked.js](https://github.com/markedjs/marked) / [mermaid.js](https://github.com/mermaid-js/mermaid) / [highlight.js](https://github.com/highlightjs/highlight.js)

---

## 📄 ライセンス (License)

[MIT License](LICENSE)

---

## 🔗 関連リンク (Related Links)

- 🏠 **Apps Hub (ポータル):** [https://selfup.net/](https://selfup.net/)
- 📱 **Web App:** [https://selfup.net/md/](https://selfup.net/md/)
