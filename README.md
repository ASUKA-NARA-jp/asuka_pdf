# asuka_pdf
Rust製の超軽量PDF ビューア・編集ツール。Acrobatの1/140（※当社調べ）のメモリで動作します。
余計な機能を省いたすっきりとした UI で、PDF を素早く開いて閲覧・編集できます。

### 🚀 Windows版 (Microsoft Store)
Windowsでご利用の方は、ストアから入手いただけます。
[Microsoft Store で手に入れる](https://apps.microsoft.com/detail/9nls0g7kx7ln?hl=ja-JP&gl=JP)

### 🐧 Linux版 (GitHub Release)
Linux (x86_64) 環境の方は、こちらから AppImage 版を無料でご利用いただけます。
[最新の AppImage をダウンロード](https://github.com/ASUKA-NARA-jp/asuka_pdf/releases/download/v0.6.3/asuka_pdf-0.6.3-x86_64.AppImage)

![asuka_pdf スクリーンショット](https://github.com/user-attachments/assets/2e40bf5d-fc2b-41db-8d46-56a5391b9e9c)

> [!NOTE]
> スクリーンショットは開発中のWindows版のものです。
> 一部の機能はプラットフォームやバージョンにより順次実装・更新されます。

## ✨ 主な機能

### 📖 PDF 閲覧
* **スムーズな操作:** マウスホイールでのページ移動、Ctrl + ホイールでの自在な拡大縮小（Ctrl+0でリセット）
* **テキスト操作:** テキスト選択モードでPDF上の文字をドラッグ選択・コピー可能。画像PDFへのOCRテキスト追加にも対応。
* **直感的なUI:** ページ番号直接入力によるジャンプ、ドラッグによるパン表示の切り替え。
* **OS連携:** エクスプローラーからのダブルクリック起動に対応。

### 🛠 PDF 編集・加工
* **ページ操作:** 回転（現在・全ページ）、削除（現在・前後指定）
* **構成変更:** ページ抽出（範囲指定）、ページ挿入（前後・先頭・末尾）
* **ファイル結合:** 複数のPDFをドラッグ＆ドロップで順番指定して一つのファイルに結合。

### 💾 保存・書き出し
* **高度な保存:** 上書き・別名保存に加え、パスワード保護（新規設定・維持）に対応。
* **画像化:** 各ページを PNG / JPEG として書き出し可能（DPI・色指定・範囲指定対応）。

### 🛠 便利な補助機能
* **テーマ:** ダーク / ライト / システム設定追従の3モード。
* **多言語:** 日本語 / English 切り替え対応。
* **フォルダ連携:** ステータス欄のファイル名クリックで保存先フォルダを即座に開く。

---
![サブ画像](https://github.com/user-attachments/assets/6bdb6dd2-3439-4952-b5c1-3b343b884d70)
