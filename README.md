<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>صفحة هبوط - حقيبة عسكرية</title>
  <style>
    body {
      font-family: Tahoma, Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(to right, #d9a441, #f5e3c3);
      color: #333;
    }
    header {
      text-align: center;
      padding: 20px;
      background: #222;
      color: #fff;
    }
    header h1 {
      margin: 0;
    }
    .container {
      max-width: 1000px;
      margin: auto;
      padding: 20px;
    }
    .product {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: center;
    }
    .slider {
      width: 350px;
      height: 400px;
      overflow: hidden;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.3);
      margin: 20px;
    }
    .slides {
      display: flex;
      width: 1400px;
      animation: slide 12s infinite;
    }
    .slides img {
      width: 350px;
      height: 400px;
      object-fit: cover;
    }
    @keyframes slide {
      0% { transform: translateX(0); }
      25% { transform: translateX(-350px); }
      50% { transform: translateX(-700px); }
      75% { transform: translateX(-1050px); }
      100% { transform: translateX(0); }
    }
    .details {
      max-width: 400px;
      margin: 20px;
    }
    .price {
      font-size: 28px;
      color: #c0392b;
      font-weight: bold;
      margin: 15px 0;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 10px;
      margin-top: 20px;
    }
    input {
      padding: 10px;
      border: 1px solid #aaa;
      border-radius: 6px;
      font-size: 16px;
    }
    button {
      padding: 12px;
      background: #27ae60;
      color: white;
      font-size: 18px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: 0.3s;
    }
    button:hover {
      background: #1e8449;
    }
  </style>
</head>
<body>

<header>
  <h1>✪ حقيبة عسكرية تكتيكية عالية الجودة</h1>
</header>

<div class="container">
  <div class="product">
    <!-- معرض صور متحرك -->
    <div class="slider">
      <div class="slides">
        <img src="410ddcca-4462-4bf9-87c4-d7b1b5617503.jpg" alt="حقيبة 1">
        <img src="https://m.media-amazon.com/images/I/71OKx04zFNL._AC_SL1500_.jpg" alt="حقيبة 2">
        <img src="https://m.media-amazon.com/images/I/71A7N0h8jjL._AC_SL1500_.jpg" alt="حقيبة 3">
        <img src="https://m.media-amazon.com/images/I/61RDLXz5I8L._AC_SL1001_.jpg" alt="حقيبة 4">
      </div>
    </div>

    <!-- تفاصيل المنتج -->
    <div class="details">
      <h2>حقيبة ظهر عسكرية تكتيكية</h2>
      <p>✔ متينة ومقاومة للماء<br>
         ✔ متعددة الجيوب والتنظيم<br>
         ✔ مناسبة للسفر، التخييم، والمهام اليومية</p>
      <div class="price">السعر: 99 د</div>

      <!-- استمارة الطلب -->
      <form>
        <input type="text" placeholder="الإسم" required>
        <input type="text" placeholder="اللقب" required>
        <input type="tel" placeholder="رقم الهاتف" required>
        <input type="text" placeholder="مكان الإقامة" required>
        <button type="submit">إضغط هنا للطلب</button>
      </form>
    </div>
  </div>
</div>

</body>
</html>
