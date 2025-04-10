# kaksss
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>nvg</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Montserrat', sans-serif;
    }
    body {
      background: #111;
      color: #fff;
    }
    header {
      background: #1e1e1e;
      padding: 20px;
      text-align: center;
      font-size: 2rem;
      font-weight: 700;
      letter-spacing: 2px;
      animation: fadeInDown 1s ease-out;
    }
    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      padding: 40px;
      animation: fadeIn 2s ease-in;
    }
    .product {
      background: #222;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 0 10px rgba(0,0,0,0.5);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .product:hover {
      transform: translateY(-5px);
      box-shadow: 0 0 20px rgba(255,255,255,0.1);
    }
    .product img {
      width: 100%;
      border-radius: 8px;
    }
    .product h3 {
      margin: 10px 0 5px;
      font-size: 1.2rem;
    }
    .product p {
      font-size: 0.9rem;
      color: #ccc;
      text-align: center;
    }
    .buy-btn {
      margin-top: 10px;
      background: #fff;
      color: #111;
      border: none;
      padding: 10px 20px;
      border-radius: 20px;
      cursor: pointer;
      font-weight: bold;
      transition: background 0.3s ease;
    }
    .buy-btn:hover {
      background: #ff4081;
      color: white;
    }@keyframes fadeInDown {
  from { opacity: 0; transform: translateY(-20px); }
  to { opacity: 1; transform: translateY(0); }
}

@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

  </style>
</head>
<body>
  <header>nvg</header>
  <section class="product-grid">
    <div class="product">
      <
      <h3>Product Name</h3>
      <p>Description here</p>
      <button class="buy-btn">Beli</button>
    </div>
    <div class="product">
      <img src="https://github.com/kaka6ix/kaksss/blob/16b35c92ba5d6621aef3c179f65546a4c9840cf2/PXL_10-04-2025_15-23-37_UtanKaliki_MTSL8.3_V6_Gopix_Redmi9.jpg" alt="Product 2">
      <h3>Product Name</h3>
      <p>Description here</p>
      <button class="buy-btn">Beli</button>
    </div>
      <h3>Product Name</h3>
      <p>Description here</p>
      <button class="buy-btn">Beli</button>
      <img> src="https://github.com/kaka6ix/kaksss/blob/16b35c92ba5d6621aef3c179f65546a4c9840cf2/PXL_10-04-2025_15-23-37_UtanKaliki_MTSL8.3_V6_Gopix_Redmi9.jpg"
    <div class="product">
      <img src="assets/placeholder.png" alt="Product 3">
    <!-- Tambahin produk lain di sini -->
  </section>
</body>
</html>
