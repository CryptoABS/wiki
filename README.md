# Developer Q&A #
基於踩了很多坑，為了以後的避免再度採坑所建立的repos。

## 開發者可能遇到的坑 ##

凡是跟開發有相關的技術問題都可此紀錄，避免下次又遇到同樣的問題

## 前端 ##

1. 常遇到的前端與後端`POST`介接，明明後端已經開通`CROS`，卻還是無法使用`XMLHttpRequest`拿到資料。

```javascript
// 出現 No-Access-Control-Origin的時候，以下可能是一種解法
記得使用JSON.stringify(params)將javascript object包裝成JSON，即便他已經是JSON object了。
```

## 後端 ##
...

## 資料庫 ##
... 
