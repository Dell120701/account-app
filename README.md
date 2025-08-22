# 簡易記帳軟體
## Getting Start
這是簡易記帳軟體，使用者可以透過此軟體記錄自己的收支情況。

此專案使用react 與 next.js 開發，並以sqlite 作為資料庫。

## How to use
```bash
docker build -t accounting-app .
docker run -p 3000:3000 accounting-app 
```
接著在瀏覽器打開 `http://localhost:3000` 即可使用。

## 介面
這是看全部月份消費的介面，使用者可以在此介面查看每個月的收支情況。
<img width="2189" height="1528" alt="image" src="https://github.com/user-attachments/assets/0ca60cda-8cdc-40fc-962b-37b6f0a00e84" />


這是可以看單一月份消費的介面，使用者可以在此介面查看單一月份的收支情況。
<img width="2468" height="2235" alt="image" src="https://github.com/user-attachments/assets/9c695006-2eb4-4c4f-8a4e-ccd7fd20b8c0" />

