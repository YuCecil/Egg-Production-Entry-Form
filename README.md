# 蛋產量輸入表單

雞場日常紀錄輸入 App，供飼養員每日登記各雞舍的產蛋量與死亡數，資料寫入 Google Sheets。

## 功能

- 選擇雞舍，依序輸入當日產蛋數與死亡數
- 多步驟表單設計，手機操作最佳化
- 資料透過 Google Apps Script 寫入 Google Sheets

## 技術

- React 18 (CDN) + Babel + Tailwind CSS，單一 HTML 檔案
- Google Apps Script 後端

## 使用方法

1. 部署對應的 GAS Web App
2. 將部署 URL 填入 `eggproductionentryform.html` 的 `API_URL` 常數
3. 直接開啟，或部署至靜態主機（亦可作為 GAS HTML 服務使用）
