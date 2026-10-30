# SL-Gravis 士林帛宏客變提案

慕恩空間設計的一頁式互動提案網站。使用靜態 HTML、CSS、JavaScript，無需安裝套件或建置。

## 功能

- 建商現況圖與 PLAN A–D；雙圖比較及全螢幕縮放。
- 20 張風格、材質、磁磚參考圖片；喜好及逐張備註。
- 下掀床及旋轉桌 YouTube 嵌入影片。
- 討論摘要複製、下載；紀錄僅存在各自瀏覽器的 localStorage，不會自動傳到公司。

## GitHub Pages

將本資料夾內容置於儲存庫根目錄，在 Settings → Pages 選擇 Deploy from a branch，main 分支、/(root)。

自訂網域：gravis.moon-design.com.tw。

先在 GitHub Pages 設定上述自訂網域，再於 Cloudflare 設定：

| 類型 | 名稱 | 目標 |
| --- | --- | --- |
| CNAME | gravis | raymond5995.github.io |

不要把儲存庫名稱附加到 CNAME 目標。待 GitHub 完成 DNS 與憑證驗證後開啟 Enforce HTTPS。

切換網域後，舊網域的瀏覽器紀錄不會自動轉移。請先在舊網站複製或下載重要討論摘要。

## 素材

圖片、LOGO 與圖面由慕恩空間設計提供；儲存庫公開不代表授予素材再使用授權。
