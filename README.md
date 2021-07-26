# Middleware Practice

實作一個中介軟體，當伺服器收到任何來自瀏覽器的 request 時，都會自動把資訊紀錄到 server log 裡。

## Features

伺服器接到任一請求時，server log 上能正確印出：

- 伺服器收到請求的時間戳記
- 請求的 HTTP 方法
- URL
- 伺服器回應的時間長度

## Preview

印出結果：

```
2021-7-26 20:32:02 | GET from / | total time: 17 ms
```

## Installing

1. 打開終端機 (Terminal) 輸入以下訊息，下載專案至本機

```
git clone https://github.com/ravenera0317/middleware-practice.git
```

2. 進入專案目錄資料夾

```
cd middleware-practice
```

3. 安裝 npm 套件

```
npm install
```

4. 啟動伺服器來執行專案

```
npm run dev
```

6. 出現以下訊息即可打開瀏覽器輸入 http://localhost:3000 開始使用

```
App is running on http://localhost:3000
```
