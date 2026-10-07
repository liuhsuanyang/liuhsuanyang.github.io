# 劉軒仰的個人網站

網址：https://liuhsuanyang.github.io/　（名片背面的 QR code 就是連到這裡）

## 怎麼修改內容

打開 https://liuhsuanyang.github.io/admin/ ，貼上 GitHub 金鑰登入，改完按「儲存並發布」。通常 1～3 分鐘後網站就會更新。

編輯器可以改：基本資料、第一頁的聯絡捷徑（LINE、Instagram、Facebook…）、照片、開場白、故事章節（最多 6 章，每章會在橋上砌一對石頭）、拱心石、最新動態、作品相簿、影片、推薦、常見問題、行事曆與預約、留言表單、履歷下載。沒有填的段落不會顯示。

整理好的內容檔（.json）可以在編輯器的「匯入內容」一次匯入，檢查後再按「儲存並發布」。

## 目錄與段落網址

訪客可以順著故事往下滑，也可以按左上角（或上方橫條右邊）的「目錄」直接跳到任何段落。每個段落都有自己的網址，可以單獨分享，例如：

- 專案：https://liuhsuanyang.github.io/#projects
- 證照：https://liuhsuanyang.github.io/#certificates
- 我的時間：https://liuhsuanyang.github.io/#calendar
- 聯絡我：https://liuhsuanyang.github.io/#contact

每一章的網址會顯示在編輯器「故事章節」的章節標題下面。

## 以後要加新功能

把收到的更新檔（.zip）在編輯器最下面的「網站更新」安裝即可，你的內容、照片、履歷不會被覆蓋。

## 檔案說明

| 檔案 | 用途 |
| --- | --- |
| `index.html` | 網站本體（版面、砌橋動畫） |
| `content.json` | 網站上的所有文字內容，由編輯器自動更新 |
| `admin/index.html` | 網站編輯器 |
| `contact.vcf` | 「存入聯絡人」下載的聯絡人檔，由編輯器自動產生 |
| `images/` | 大頭照與作品相簿，用編輯器上傳後才會出現 |
| `files/resume.pdf` | 履歷，用編輯器上傳後才會出現 |
| `404.html` | 找不到頁面時顯示的畫面 |
| `version.json` | 網站版本號 |
| `assets/` | 字型、網站小圖示、分享預覽圖（`assets/kx/` 是備用字型分塊） |
| `robots.txt`、`.nojekyll` | 網站設定，不用動 |

## 重要提醒

- 不要改 GitHub 帳號名稱，也不要改這個儲存庫的名稱：網址會跟著變，已經印出去的名片 QR code 就會失效。
- 金鑰弄丟或過期，到 GitHub 重新產生一把即可，網站內容不受影響。
- 每次儲存都會留下紀錄，改壞了可以從 GitHub 的歷史紀錄還原。
- 行事曆建議只公開「有空／忙碌」，不要公開上課地點等細節。

## 字型

- 網站上的中文全部是「全字庫正楷體」。英文姓名用 Cinzel（和名片上的英文名同一種字）；其他英文與數字用 EB Garamond（有正常的大小寫）。
- `assets/kai.woff2` 只包含網站目前用到的字，所以載入很快。之後在編輯器新增的字，會自動從 `assets/kx/` 的備用分塊補上，一樣顯示成正楷體，不需要另外處理。
- 如果一次新增很多內容，網站會多下載幾個備用分塊。想讓網站再變快，可以請人依新內容重新產生 `assets/kai.woff2`。

## 字型授權

- 全字庫正楷體（© 數位發展部），依「政府資料開放授權條款－第 1 版」使用。
- EB Garamond（Copyright 2017 The EB Garamond Project Authors，https://github.com/octaviopardo/EBGaramond12 ）與 Cinzel（Copyright 2020 The Cinzel Project Authors，https://github.com/NDISCOVER/Cinzel ），依 SIL Open Font License 1.1 使用：https://openfontlicense.org
