vite.config.ts
で
base: '/svg-animator/',


src/main.tsx
で
「<Router basename="/svg-animator">」

この2つをセットでビルドすればOK！


普通のレンタルサーバーへのFTPアップなら、

base: '/',

<Router>

にもどしてビルド
