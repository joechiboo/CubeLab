# CubeLab

> 給兒子玩的 3×3 魔術方塊網頁版。Three.js · 單檔 HTML · 不需 build。

## Live

https://joechiboo.github.io/CubeLab/

## 本機開發

雙擊 `index.html` 就能直接在瀏覽器跑(importmap 從 CDN 載 Three.js)。

想用本機伺服器:

```powershell
python -m http.server 8000
# 或
npx serve .
```

## 部署

Push 到 `main` 由 [GitHub Actions](.github/workflows/deploy.yml) 自動部署到 Pages。

## 檔案

- [`index.html`](index.html) — 整個應用,含 CSS + Three.js 邏輯
- [`REQUIREMENTS.md`](REQUIREMENTS.md) — 需求文件
- [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml) — 部署 workflow
