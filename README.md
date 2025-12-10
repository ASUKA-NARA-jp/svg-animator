SVG から中間フレームを生成して APNG を作れるツールです

# デプロイ時の設定メモ

## GitHub Pages（/svg-animator/ 配下で公開する場合）

### vite.config.ts
```ts
base: '/svg-animator/',
```

### src/main.tsx
```tsx
<Router basename="/svg-animator">
```

---

## FTP で普通のサーバーにアップロードする場合

### vite.config.ts
```ts
base: '/',
```

### src/main.tsx
```tsx
<Router>
```
