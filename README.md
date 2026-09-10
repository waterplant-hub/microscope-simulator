# 複式顯微鏡操作模擬器

給國中生物課使用的互動式顯微鏡操作練習工具，讓學生在實際使用顯微鏡前，先建立正確的操作順序、成像方向與安全觀念。

目前版本：**v1.8.1 行動學習版**

## 線上使用

- 線上網站：[https://waterplant-hub.github.io/microscope-simulator/](https://waterplant-hub.github.io/microscope-simulator/)
- GitHub 儲存庫：[https://github.com/waterplant-hub/microscope-simulator](https://github.com/waterplant-hub/microscope-simulator)

支援電腦雙欄、平板與 iPhone 直式操作；iPhone／iPad 建議 Safari，Android、Chromebook 與電腦建議 Chrome。

## 學習目標

- 認識目鏡、物鏡、載物台、粗調節輪、細調節輪、光圈與反光鏡。
- 練習對光、低倍找像、移至視野中央，再切換高倍細調。
- 理解目鏡視野上下、左右相反。
- 理解玻片移動方向與視野影像移動方向相反。
- 在高倍物鏡下避免使用粗調節輪。

## 練習模式

- **學生任務**：依任務流程完成對光、4X 找像、置中與 60X 細調。
- **池水追蹤**：練習在顯微鏡視野中追蹤移動中的微生物。
- **故障診斷**：從視野症狀判斷操作問題。
- **操作紀錄**：整理操作次數、提示使用與學習狀態。

## 專案結構

- `index.html`：正式網站與模擬器的唯一入口，HTML、CSS、JavaScript 均收在同一檔案。
- `README.md`：專案用途、版本與發布紀錄。

下載後可直接以瀏覽器開啟 `index.html`；發布版本以根目錄的 `index.html` 為準。

## 資料與使用分析

本模擬器不要求登入，也沒有姓名、班級或成績欄位。網站使用 Google Analytics 4 統計整體瀏覽與操作事件，作為課堂測試與介面改良參考；不主動傳送學生姓名或可直接識別學生身分的資料。

## 維護與發布

每次發布新版本時：

1. 先在 `index.html` 完成修改，並同步更新頁面標題、畫面版號、頁尾版號與本 README。
2. 至少測試電腦與平板橫向版面，確認顯微鏡、視野、操作控制不互相遮擋。
3. 完整走過入門操作，再抽查池水追蹤與故障診斷模式。
4. 確認瀏覽器主控台沒有新的錯誤，並提交至 `main` 分支。
5. 等待 GitHub Pages 更新後，再開啟正式網址確認標題、版號與主要操作。

## 版權

© 2026 林顯豪規劃設計｜複式顯微鏡操作模擬器｜v1.8.1 行動學習版
