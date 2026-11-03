早安廚房多頁網站

開啟方式：直接用 Chrome / Edge 開啟 index.html。

頁面：index.html 首頁、menu.html 菜單、cart.html 購物車、checkout.html 結帳、order.html 訂單結果、lookup.html 查詢訂單、login.html 登入、register.html 註冊。

共用元件：
- Header / Footer：由 assets/app.js 的 header()、footer() 共用注入
- FoodCard：foodCard()
- CartItem / OrderSummary：renderCart()
- CouponInput：applyCoupon()
- OrderProgress / OrderInfo：renderOrder()

圖片：assets/images/*.jpg，為本地製作的風格化餐點插畫圖，不是實拍照片。

注意：目前純前端模擬，沒有資料庫、真實會員驗證或金流。訂單暫存於 sessionStorage。
