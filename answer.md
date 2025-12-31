# 第2次作業題目-作業-QZ2
>
>學號：112111133
><br />
>姓名：林凱翎
><br />
>作業撰寫時間：180 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2023/09/22
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x] 說明內容
- [x] 個人認為完成作業須具備觀念

## 說明程式與內容

請在撰寫"說明程式與內容"該塊內容，請把原該塊內上述敘述刪除，該塊上述內容只是用來指引該怎麼撰寫內容。

1. HTTP Status Code 有哪些？怎麼分類？

Ans:
1xx（Informational 資訊）：請求已收到，處理中
例：100 Continue

2xx（Success 成功）：請求成功
例：200 OK（最常見）、201 Created（新增成功）

3xx（Redirection 重新導向）：需要轉址或使用快取
例：301 Moved Permanently、302 Found、304 Not Modified

4xx（Client Error 用戶端錯誤）：請求有問題（網址錯、沒權限、找不到）
例：400 Bad Request、401 Unauthorized、403 Forbidden、404 Not Found

5xx（Server Error 伺服器錯誤）：伺服器端處理失敗
例：500 Internal Server Error、502 Bad Gateway、503 Service Unavailable


2. 在 Express 中，設計基本上可以分成幾層？請依上述回答實作一個後端與前端的網站(需有程式碼)，並且將結果和執行畫面顯示於該份md，並逐步說明。

Ans:
