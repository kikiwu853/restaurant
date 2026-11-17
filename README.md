# 永樂街鱔魚麵｜阿公的店家介紹網站

> 以家人經營的餐飲店為主題，使用 HTML、CSS、JavaScript 與 Bootstrap 5 製作的多頁式響應式（RWD）網站。

**專案類型：** 前端靜態網站／個人作品集  
**開發技術：** `HTML5` `CSS3` `JavaScript` `Bootstrap 5`  
**線上展示：** 待 GitHub Pages 啟用後補上連結

## 專案介紹

希望讓第一次認識「永樂街鱔魚麵」的訪客，能透過簡單清楚的網頁了解店家故事、瀏覽餐點及找到店家位置。網站共四個主要頁面，另外加入趣味的「美食扭蛋機」，練習 DOM 操作、隨機選取和 Bootstrap Modal 互動。

## 主要功能

| 功能 | 實作內容 |
| --- | --- |
| 響應式導覽列 | 使用 Bootstrap Navbar / Collapse，在不同螢幕尺寸切換選單 |
| 首頁展示 | 店家介紹與料理圖片展示 |
| 菜單瀏覽 | 依餐點類別呈現菜色，搭配圖片及輪播元件 |
| 美食扭蛋機 | 以 JavaScript 從主食、熱炒和配菜類別各隨機挑選一項，計算總價並顯示在 Modal 中；支援重新抽選 |
| 店家介紹與地圖 | 提供店家介紹並嵌入 Google Maps |
| 聯絡表單 | 使用 HTML 表單驗證、JavaScript 確認提示及表單重設，展示前端互動流程 |

## 使用技術與實作重點

- **HTML5 / CSS3**：多頁網站架構、排版、版面樣式與互動狀態。
- **Bootstrap 5**：Grid、Navbar、Collapse、Carousel 與 Modal 元件。
- **JavaScript（Vanilla JS）**：`Math.random()` 隨機抽取菜色、動態更新 DOM、計算推薦餐點總價及表單事件處理。
- **Bootstrap Icons / Google Fonts**：透過 CDN 載入圖示與字型。
- **Google Maps Embed**：嵌入地圖供訪客查找位置。

## 網站頁面

| 檔案 | 頁面 |
| --- | --- |
| `index.html` | 首頁 |
| `menu.html` | 美味佳餚／菜單與美食扭蛋機 |
| `about.html` | 我們的店／店家介紹 |
| `contact.html` | 聯絡我們／前端表單示範 |

## 專案結構

```text
restaurant/
├── index.html               # 首頁（GitHub Pages 預設入口）
├── menu.html                # 菜單、隨機推薦功能
├── about.html               # 店家介紹與地圖
├── contact.html             # 聯絡表單示範
├── css/
│   └── bootstrap.min.css    # Bootstrap 樣式
├── js/
│   └── bootstrap.bundle.min.js  # Bootstrap 互動元件
├── image/                   # 網站圖片素材
└── README.md
```

## 本機執行方式

本專案不需要 Node.js、Java 或資料庫。

1. 下載整個專案並解壓縮。
2. 使用 Chrome、Edge 等瀏覽器開啟 `index.html`。
3. 透過上方導覽列切換其他頁面，也可使用 VS Code 的 Live Server 啟動。

> 提醒：Google Maps、Google Fonts、Bootstrap Icons 等外部資源需要網路連線。

## 部署至 GitHub Pages

在 GitHub 儲存庫中進入 **Settings → Pages**，將來源設定為 **Deploy from a branch**，選擇 **main / (root)** 並儲存。網站會使用根目錄的 `index.html` 作為首頁。

部署成功後，可將本 README 上方的「線上展示」更新成實際網址。

## 目前限制與後續方向

- **聯絡表單目前只有前端驗證與示範提示**：未串接後端、資料庫或寄信服務，**不會實際寄送留言**。
- 專案為課程學習與個人實作作品；目前沒有線上訂位、下單或金流服務。
- 未來可增加菜單資料管理、表單寄信服務與更完整的裝置尺寸測試。

## 作品集重點

本專案著重在 HTML / CSS 基礎、Bootstrap 響應式元件整合，以及 JavaScript 實際操作畫面元素與實作互動邏輯。另有 Java / Spring Boot / React 全端專題，可呈現不同開發階段與技術能力。