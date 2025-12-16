<!DOCTYPE html><html lang="vi">
<head>
  <meta charset="UTF-8" />
  <title>FreshDrink - Web bán nước</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <style>
    body { font-family: Arial, sans-serif; margin: 0; background: #f5f5f5; }
    header { background: #00b894; color: white; padding: 20px; text-align: center; }
    nav { background: #0984e3; padding: 10px; text-align: center; }
    nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
    .container { padding: 20px; }
    .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; }
    .card { background: white; border-radius: 10px; padding: 15px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); text-align: center; }
    .card img { width: 100%; height: 150px; object-fit: cover; border-radius: 10px; }
    .price { color: #e17055; font-size: 18px; font-weight: bold; }
    button { background: #00b894; color: white; border: none; padding: 10px 15px; border-radius: 5px; cursor: pointer; }
    button:hover { background: #019875; }
    footer { background: #2d3436; color: white; text-align: center; padding: 15px; margin-top: 20px; }
  </style>
</head>
<body><header>
  <h1>🥤 FreshDrink</h1>
  <p>Nước giải khát mát lạnh mỗi ngày</p>
</header><nav>
  <a href="#">Trang chủ</a>
  <a href="#sanpham">Sản phẩm</a>
  <a href="#lienhe">Liên hệ</a>
</nav><div class="container" id="sanpham">
  <h2>Sản phẩm nổi bật</h2>
  <div class="products">
    <div class="card">
      <img src="https://via.placeholder.com/300x150?text=Tra+Chanh" alt="Trà chanh">
      <h3>Trà chanh</h3>
      <p class="price">15.000đ</p>
      <button>Mua ngay</button>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/300x150?text=Tra+Sua" alt="Trà sữa">
      <h3>Trà sữa</h3>
      <p class="price">25.000đ</p>
      <button>Mua ngay</button>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/300x150?text=Nuoc+Cam" alt="Nước cam">
      <h3>Nước cam</h3>
      <p class="price">20.000đ</p>
      <button>Mua ngay</button>
    </div>
  </div>
</div><div class="container" id="lienhe">
  <h2>Liên hệ</h2>
  <p>📍 Địa chỉ: 123 Đường
