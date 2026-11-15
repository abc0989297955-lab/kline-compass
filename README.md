# K線羅盤 · 2330 台積電

近半年 K 線圖：日線／週線／月線切換，MA5／MA10／MA20 勾選。

## 線上預覽（免設定）

https://rawcdn.githack.com/abc0989297955-lab/kline-compass/main/index.html

（若出現 One more step，點 **Open the page**）

## 用 GitHub Pages 正式上線（推薦）

1. 打開倉庫設定：  
   https://github.com/abc0989297955-lab/kline-compass/settings/pages
2. **Build and deployment → Source** 選 **Deploy from a branch**
3. Branch 選 **main**，資料夾選 **/ (root)**
4. 按 **Save**
5. 等 1～2 分鐘，網址會是：

   **https://abc0989297955-lab.github.io/kline-compass/**

## 檔案說明

| 檔案 | 說明 |
|------|------|
| `index.html` | 主頁面（圖表＋均線＋週期切換） |
| `day1.json` `day2.json` `day3.json` | 近半年日線資料（分段存放） |

資料為 2330.TW 歷史行情展示用，不構成投資建議。
