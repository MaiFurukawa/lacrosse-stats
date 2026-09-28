# ラクロス スタッツ

試合を見ながらiPadでスタッツを入力し、試合ごと・選手ごとに集計するアプリです。

## GitHub Pages での公開手順（ブラウザだけでできます）

1. GitHub にログインし、右上の「＋」→「New repository」を選ぶ
   - Repository name：例 `lacrosse-stats`
   - **Public** を選ぶ（無料プランで Pages を使うため）
   - 「Create repository」を押す
2. 作ったリポジトリの画面で「uploading an existing file」をクリック
3. この `github` フォルダの中身をすべてドラッグ＆ドロップ
   （`index.html` `sw.js` `manifest.webmanifest` と画像3つ、この `README.md`）
4. 下の「Commit changes」を押す
5. 「Settings」→ 左メニューの「Pages」を開く
   - Source：**Deploy from a branch**
   - Branch：**main** / **/(root)** を選んで「Save」
6. 1〜2分待つと、画面上部に `https://<ユーザー名>.github.io/lacrosse-stats/` のURLが表示されます

## iPadで使う

- Safariで上のURLを開き、共有ボタン →「ホーム画面に追加」
- 一度開いておけば、電波がないグラウンドでも起動できます
- データはそれぞれのiPadの中に保存されます

## 複数人でデータを集めるとき

1. 各自が「設定」→「バックアップ保存」でファイルを保存し、まとめ役に送る
2. まとめ役が「設定」→「バックアップを読み込む」→「合体する」
   - 同じ日付・同じ相手の試合は1つにまとまります（例：OF担当とクリア担当の分担入力）

## 注意

- リポジトリを Public にすると、アプリの**プログラム**は誰でも見られます。
  入力した**試合データ**は各iPadの中にだけあり、GitHubには上がりません。
- アプリを更新したときは、同じ手順で `index.html` などを上書きアップロードします。
  iPadでは、次に電波があるときに開くと新しい版に切り替わります。
