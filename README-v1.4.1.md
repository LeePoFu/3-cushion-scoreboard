# Scoreboard v1.4.1 iOS 同步橋接版

iOS Safari 分頁與加入主畫面的 Web App 可能使用不同的網站儲存空間，
因此只靠 localStorage 直接同步可能失敗。

新增「同步並開啟 Records」：
- 仍先嘗試直接寫入 Records。
- 若儲存空間被隔離，按此按鈕會將該場比賽帶到 Records。
- Records 開啟後會自動匯入並避免重複紀錄。
