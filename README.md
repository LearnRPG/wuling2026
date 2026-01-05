
```markdown
# Wuling 2026 Countdown

這是一個使用 **React + TypeScript + Vite** 開發的網頁專案，提供 **倒數計時功能**，並展示專案中的互動效果。

🔗 **線上預覽**: [https://learnrpg.github.io/wuling2026/](https://learnrpg.github.io/wuling2026/)

---

## 功能特色

- 即時倒數計時至指定目標日期
- 使用 React 元件化結構，方便擴展
- TypeScript 提供完整型別檢查
- 使用 Vite 架構，快速開發與打包

---

## 專案結構

```

wuling2026/
├─ docs/               # GitHub Pages 上線目錄
│  ├─ index.html
│  └─ assets/          # 打包後的 JS/CSS
├─ src/                # 原始碼目錄
│  ├─ App.tsx
│  ├─ index.tsx
│  ├─ constants.ts
│  ├─ types.ts
│  └─ components/
├─ package.json
├─ vite.config.ts
├─ tsconfig.json
└─ README.md

````

---

## 本地開發

> 需要 Node.js 環境（或使用免安裝 portable Node）

1. 下載或 clone 專案：
```bash
git clone https://github.com/learnrpg/wuling2026.git
cd wuling2026
````

2. 安裝相依套件：

```bash
npm install
```

3. 啟動開發伺服器：

```bash
npm run dev
```

4. 在瀏覽器開啟：

```
http://localhost:3000
```

---

## 打包與部署

1. 進行專案打包：

```bash
npm run build
```

2. 將 `dist/` 目錄內容複製或改名為 `docs/`（GitHub Pages 專用）

3. Push 到 GitHub：

```bash
git add docs
git commit -m "deploy build to GitHub Pages"
git push
```

4. 在 GitHub repo 設定 Pages：

* Branch: `main`
* Folder: `/docs`

5. 幾分鐘後即可透過以下網址訪問：

```
https://learnrpg.github.io/wuling2026/
```

---

## 技術棧

* **React 18**
* **TypeScript**
* **Vite**
* **GitHub Pages**（靜態部署）

---

## 注意事項

* 所有倒數計時邏輯在前端執行，不需要後端支援
* 若修改 `src` 內容，記得重新 `npm run build` 並推送至 GitHub Pages
* 專案環境建議使用 **Node.js LTS 或 portable Node** 以確保編譯順利

```

---

我可以幫你加一個 **超簡化版「新手一行指令就能從原始碼到上線」流程**，這樣放 README 就非常完美。  

你想要我直接加上這個嗎？
```
