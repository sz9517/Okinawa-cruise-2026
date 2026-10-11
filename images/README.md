# 商品圖片

這個資料夾放購物清單裡的商品圖片，逛街時可以拿來對照。

## 新增一張圖片

1. 把圖片存進這個資料夾，檔名用英文小寫，不要有空格，例如 `suisavon.jpg`
2. 在 `index.html` 找到那個品項，在最後加上 `img:'images/檔名'`

```js
{id:'nc1', name:'首里石鹼 SuiSavon 天然肥皂', ..., img:'images/suisavon.jpg'}
```

## 小提醒

- 檔名大小寫要完全一樣，GitHub Pages 會區分大小寫（`Suisavon.JPG` ≠ `suisavon.jpg`）
- 建議圖片寬度 600px 以內、檔案 200KB 以下，手機開起來比較快
- 有填 `img` 但還沒放檔案的品項，右側會顯示虛線的「📷 放圖片」框
