# 出張承認伺 v0.8.1 PWA_ISOLATED OFFICIAL_LATEST

業務管理ポータルとPWA識別・Service Worker・キャッシュを分離した修正版です。

GitHub repository `travel-approval-app` の直下に、このフォルダ内の `index.html`、`manifest.webmanifest`、`sw.js`、`README.md` を上書きしてください。

主な修正:
- manifest `id`: `/travel-approval-app/`
- `start_url`: `/travel-approval-app/index.html?pwa=travel-approval`
- `scope`: `/travel-approval-app/`
- Service Worker scope: `/travel-approval-app/`
- cache: `travel-approval-app-v0.8.1-isolated`
- 他アプリのCacheStorageを削除しないよう修正
