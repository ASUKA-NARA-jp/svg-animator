# デプロイ時の設定メモ

## GitHub Pages（/svg-animator/ 配下で公開する場合）

vite.config.ts
- base: '/svg-animator/'

src/main.tsx
- <Router basename="/svg-animator">

## FTP で普通のサーバーにアップロードする場合

vite.config.ts
- base: '/'

src/main.tsx
- <Router>（basename なし）
