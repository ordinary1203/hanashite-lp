# はなして LP

`LP仕様書.html` をもとに作成した静的ランディングページです。Vercel / GitHub Pages / Netlify などにそのまま公開できます。

## 主なファイル

- `index.html`: LP本体
- `styles.css`: スタイル
- `assets/`: 写真・アイコン素材
- `vercel.json`: Vercel向けの公開設定
- `robots.txt`: 検索エンジン向け設定
- `site.webmanifest`: ブラウザ・ホーム画面用の基本設定

## Vercelで公開する場合

1. このフォルダをGitHubリポジトリにアップロード
2. VercelでそのリポジトリをImport
3. Framework Presetは `Other`
4. Build Commandは空欄
5. Output Directoryも空欄
6. Deploy

フォーム部分は現在見た目のみです。実際にメール登録を受け取る場合は、Supabase / Formspree / Google Forms などへ接続してください。
