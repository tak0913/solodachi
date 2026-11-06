# Solodachi(ホーム画面に置けるWebアプリ版)

## 中身
- index.html … アプリ本体
- manifest.webmanifest … アプリ名・アイコン・色の設定
- sw.js … オフラインでも開けるようにする仕組み
- icons/ … ホーム画面のアイコン

## 使い方
1. このフォルダごと、Webサイトとして公開する(GitHub Pages、Netlify、Cloudflare Pages など。どれも無料枠あり)
2. iPhoneのSafariで公開したURLを開く
3. 共有ボタン → 「ホーム画面に追加」
4. ホーム画面のアイコンから開くと、Safariのバーがない全画面のアプリとして動く

※ ファイルを直接開く(file://)と、オフライン機能は動かない。必ずWebサイトとして公開すること。
