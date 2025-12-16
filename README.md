<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Đồ Án Web Bán Nước - Nhóm 11</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Quicksand', sans-serif;
            scroll-behavior: smooth;
        }
        .gradient-text {
            background: linear-gradient(to right, #0d9488, #f97316);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1), 0 8px 10px -6px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <nav class="bg-white shadow-md fixed w-full z-50 transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16 items-center">
                <div class="flex-shrink-0 flex items-center gap-2">
                    <i class="fas fa-glass-citrus text-teal-600 text-2xl"></i>
                    <span class="font-bold text-xl tracking-tight text-gray-900">FreshDrink <span class="text-teal-600">N11</span></span>
                </div>
                <div class="hidden md:flex space-x-8">
                    <a href="#gioi-thieu" class="text-gray-600 hover:text-teal-600 font-medium transition">Giới thiệu</a>
                    <a href="#menu" class="text-gray-600 hover:text-teal-600 font-medium transition">Menu</a>
                    <a href="#nguyen-lieu" class="text-gray-600 hover:text-teal-600 font-medium transition">Nguyên liệu</a>
                    <a href="#phan-tich" class="text-gray-600 hover:text-teal-600 font-medium transition">Phân tích</a>
                </div>
                <div class="md:hidden">
                    <button class="text-gray-600 hover:text-teal-600 focus:outline-none">
                        <i class="fas fa-bars text-xl"></i>
                    </button>
                </div>
            </div>
        </div>
    </nav>

    <section id="gioi-thieu" class="pt-24 pb-16 bg-gradient-to-br from-teal-50 to-orange-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h1 class="text-4xl md:text-5xl font-bold mb-6">
                Đồ Án Xây Dựng Website <br>
                <span class="gradient-text">Bán Nước Giải Khát Trực Tuyến</span>
            </h1>
            <p class="text-lg text-gray-600 mb-10 max-w-2xl mx-auto">
                Một giải pháp thương mại điện tử hiện đại, mang đến sự tiện lợi và trải nghiệm đặt đồ uống tươi ngon nhất cho khách hàng.
            </p>

            <div class="bg-white p-8 rounded-2xl shadow-lg max-w-4xl mx-auto border-t-4 border-teal-500">
                <h3 class="text-2xl font-bold text-gray-800 mb-6 border-b pb-4">Thành Viên Nhóm 11</h3>
                <div class="grid grid-cols-2 md:grid-cols-5 gap-6">
                    <div class="flex flex-col items-center group">
                        <div class="w-16 h-16 rounded-full bg-teal-100 flex items-center justify-center text-teal-600 mb-3 group-hover:bg-teal-600 group-hover:text-white transition">
                            <i class="fas fa-user"></i>
                        </div>
                        <span class="font-semibold text-sm">Duy Thái</span>
                    </div>
                    <div class="flex flex-col items-center group">
                        <div class="w-16 h-16 rounded-full bg-teal-100 flex items-center justify-center text-teal-600 mb-3 group-hover:bg-teal-600 group-hover:text-white transition">
                            <i class="fas fa-user"></i>
                        </div>
                        <span class="font-semibold text-sm">Đình Thái</span>
                    </div>
                    <div class="flex flex-col items-center group">
                        <div class="w-16 h-16 rounded-full bg-teal-100 flex items-center justify-center text-teal-600 mb-3 group-hover:bg-teal-600 group-hover:text-white transition">
                            <i class="fas fa-user-tie"></i>
                        </div>
                        <span class="font-semibold text-sm">Cảnh Sang</span>
                    </div>
                    <div class="flex flex-col items-center group">
                        <div class="w-16 h-16 rounded-full bg-teal-100 flex items-center justify-center text-teal-600 mb-3 group-hover:bg-teal-600 group-hover:text-white transition">
                            <i class="fas fa-user"></i>
                        </div>
                        <span class="font-semibold text-sm">Tấn Sang</span>
                    </div>
                    <div class="flex flex-col items-center group">
                        <div class="w-16 h-16 rounded-full bg-teal-100 flex items-center justify-center text-teal-600 mb-3 group-hover:bg-teal-600 group-hover:text-white transition">
                            <i class="fas fa-code"></i>
                        </div>
                        <span class="font-semibold text-sm">Anh Quân</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="py-16 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row items-center gap-12">
                <div class="md:w-1/2">
                    <img src="https://images.unsplash.com/photo-1579372786545-d24232daf58c?q=80&w=2070&auto=format&fit=crop" 
                         alt="Nhu cầu thị trường" 
                         class="rounded-2xl shadow-xl w-full h-80 object-cover hover:scale-[1.02] transition duration-500">
                </div>
                <div class="md:w-1/2">
                    <h2 class="text-3xl font-bold text-gray-900 mb-4 flex items-center gap-3">
                        <span class="bg-orange-100 text-orange-600 p-2 rounded-lg"><i class="fas fa-chart-line"></i></span>
                        Nhu Cầu Chung Thị Trường
                    </h2>
                    <p class="text-gray-600 leading-relaxed mb-4">
                        Thị trường F&B (Food & Beverage) tại Việt Nam đang chứng kiến sự bùng nổ mạnh mẽ, đặc biệt là xu hướng đặt đồ uống trực tuyến.
                    </p>
                    <ul class="space-y-3">
                        <li class="flex items-start gap-3">
                            <i class="fas fa-check-circle text-teal-500 mt-1"></i>
                            <span class="text-gray-700"><strong>Giới trẻ (Gen Z):</strong> Ưa chuộng sự tiện lợi, thích trải nghiệm các loại trà sữa, trà trái cây mới lạ.</span>
                        </li>
                        <li class="flex items-start gap-3">
                            <i class="fas fa-check-circle text-teal-500 mt-1"></i>
                            <span class="text-gray-700"><strong>Văn phòng:</strong> Nhu cầu đặt số lượng lớn cho các buổi họp, teabreak tăng cao.</span>
                        </li>
                        <li class="flex items-start gap-3">
                            <i class="fas fa-check-circle text-teal-500 mt-1"></i>
                            <span class="text-gray-700"><strong>Xu hướng Health-conscious:</strong> Khách hàng ngày càng quan tâm đến đồ uống ít đường, organic và tốt cho sức khỏe.</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <section id="menu" class="py-16 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-900">Menu Nước Đa Dạng</h2>
                <p class="text-gray-600 mt-2">Sự kết hợp hoàn hảo giữa hương vị truyền thống và hiện đại</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="bg-white rounded-2xl shadow-sm overflow-hidden card-hover transition duration-300">
                    <img src="https://images.unsplash.com/photo-1558160074-4d7d8bdf4256?q=80&w=2070&auto=format&fit=crop" alt="Trà Sữa" class="w-full h-48 object-cover">
                    <div class="p-5">
                        <h3 class="font-bold text-xl mb-2 text-gray-800">Trà Sữa Truyền Thống</h3>
                        <p class="text-sm text-gray-500 mb-3">Hương vị trà đậm đà kết hợp sữa béo ngậy và trân châu dai giòn.</p>
                        <span class="text-teal-600 font-bold">25.000đ</span>
                    </div>
                </div>
                <div class="bg-white rounded-2xl shadow-sm overflow-hidden card-hover transition duration-300">
                    <img src="https://images.unsplash.com/photo-1623593688280-a50d4085f34e?q=80&w=1964&auto=format&fit=crop" alt="Trà Trái Cây" class="w-full h-48 object-cover">
                    <div class="p-5">
                        <h3 class="font-bold text-xl mb-2 text-gray-800">Trà Đào Cam Sả</h3>
                        <p class="text-sm text-gray-500 mb-3">Thanh mát, giải nhiệt với những miếng đào tươi giòn ngọt.</p>
                        <span class="text-teal-600 font-bold">35.000đ</span>
                    </div>
                </div>
                <div class="bg-white rounded-2xl shadow-sm overflow-hidden card-hover transition duration-300">
                    <img src="https://images.unsplash.com/photo-1541167760496-1628856ab772?q=80&w=1937&auto=format&fit=crop" alt="Cà Phê" class="w-full h-48 object-cover">
                    <div class="p-5">
                        <h3 class="font-bold text-xl mb-2 text-gray-800">Cà Phê Sữa Đá</h3>
                        <p class="text-sm text-gray-500 mb-3">Đậm chất Việt Nam, tỉnh táo cho ngày làm việc năng động.</p>
                        <span class="text-teal-600 font-bold">20.000đ</span>
                    </div>
                </div>
                 <div class="bg-white rounded-2xl shadow-sm overflow-hidden card-hover transition duration-300">
                    <img src="https://images.unsplash.com/photo-1620916566398-39f1143ab7be?q=80&w=1887&auto=format&fit=crop" alt="Sinh Tố" class="w-full h-48 object-cover">
                    <div class="p-5">
                        <h3 class="font-bold text-xl mb-2 text-gray-800">Sinh Tố Bơ</h3>
                        <p class="text-sm text-gray-500 mb-3">Béo ngậy, giàu dinh dưỡng, nguyên liệu organic chọn lọc.</p>
                        <span class="text-teal-600 font-bold">30.000đ</span>
                    </div>
                </div>
                <div class="bg-white rounded-2xl shadow-sm overflow-hidden card-hover transition duration-300">
                    <img src="https://images.unsplash.com/photo-1572490122747-3968b75cc699?q=80&w=1887&auto=format&fit=crop" alt="Sữa Tươi Trân Châu" class="w-full h-48 object-cover">
                    <div class="p-5">
                        <h3 class="font-bold text-xl mb-2 text-gray-800">Sữa Tươi Đường Đen</h3>
                        <p class="text-sm text-gray-500 mb-3">Vị ngọt thơm của đường đen kết hợp sữa tươi thanh trùng.</p>
                        <span class="text-teal-600 font-bold">32.000đ</span>
                    </div>
                </div>
                <div class="bg-white rounded-2xl shadow-sm overflow-hidden card-hover transition duration-300">
                    <img src="https://images.unsplash.com/photo-1515823064-d6e0c04616a7?q=80&w=2071&auto=format&fit=crop" alt="Matcha" class="w-full h-48 object-cover">
                    <div class="p-5">
                        <h3 class="font-bold text-xl mb-2 text-gray-800">Matcha Đá Xay</h3>
                        <p class="text-sm text-gray-500 mb-3">Trà xanh Nhật Bản xay nhuyễn với lớp kem cheese béo mặn.</p>
                        <span class="text-teal-600 font-bold">40.000đ</span>
                    </div>
                </div>
                <div class="bg-white rounded-2xl shadow-sm overflow-hidden card-hover transition duration-300">
                    <img src="https://images.unsplash.com/photo-1513558161293-cdaf765ed2fd?q=80&w=1887&auto=format&fit=crop" alt="Soda" class="w-full h-48 object-cover">
                    <div class="p-5">
                        <h3 class="font-bold text-xl mb-2 text-gray-800">Soda Blue Ocean</h3>
                        <p class="text-sm text-gray-500 mb-3">Mát lạnh màu biển xanh, vị chanh dây sảng khoái.</p>
                        <span class="text-teal-600 font-bold">28.000đ</span>
                    </div>
                </div>
                <div class="bg-white rounded-2xl shadow-sm overflow-hidden card-hover transition duration-300">
                    <img src="https://images.unsplash.com/photo-1626082927389-6cd097cdc6ec?q=80&w=2070&auto=format&fit=crop" alt="Trà Sen" class="w-full h-48 object-cover">
                    <div class="p-5">
                        <h3 class="font-bold text-xl mb-2 text-gray-800">Trà Sen Vàng</h3>
                        <p class="text-sm text-gray-500 mb-3">Thanh tao vị sen, kết hợp hạt sen bùi bùi và kem sữa.</p>
                        <span class="text-teal-600 font-bold">38.000đ</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="nguyen-lieu" class="py-16 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row-reverse items-center gap-12">
                <div class="md:w-1/2">
                    <img src="https://images.unsplash.com/photo-1610832958506-aa56368176cf?q=80&w=2070&auto=format&fit=crop" 
                         alt="Nguyên liệu tươi sạch" 
                         class="rounded-2xl shadow-xl w-full h-80 object-cover hover:scale-[1.02] transition duration-500">
                </div>
                <div class="md:w-1/2">
                    <h2 class="text-3xl font-bold text-gray-900 mb-4 flex items-center gap-3">
                        <span class="bg-green-100 text-green-600 p-2 rounded-lg"><i class="fas fa-leaf"></i></span>
                        Nguyên Liệu Chọn Lọc
                    </h2>
                    <p class="text-gray-600 mb-6">
                        Chất lượng đồ uống bắt đầu từ nguồn nguyên liệu. Nhóm 11 cam kết xây dựng hệ thống quản lý nguồn gốc chặt chẽ trên website.
                    </p>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                        <div class="bg-green-50 p-4 rounded-lg border border-green-100">
                            <h4 class="font-bold text-green-800 mb-1">Trái cây tươi mỗi ngày</h4>
                            <p class="text-sm text-green-700">Nhập trực tiếp từ nông trại Đà Lạt.</p>
                        </div>
                        <div class="bg-green-50 p-4 rounded-lg border border-green-100">
                            <h4 class="font-bold text-green-800 mb-1">Trà thượng hạng</h4>
                            <p class="text-sm text-green-700">Lá trà Bảo Lộc được ủ theo quy trình chuẩn.</p>
                        </div>
                        <div class="bg-green-50 p-4 rounded-lg border border-green-100">
                            <h4 class="font-bold text-green-800 mb-1">Topping nhà làm</h4>
                            <p class="text-sm text-green-700">Đảm bảo vệ sinh an toàn thực phẩm.</p>
                        </div>
                        <div class="bg-green-50 p-4 rounded-lg border border-green-100">
                            <h4 class="font-bold text-green-800 mb-1">Sữa tiệt trùng</h4>
                            <p class="text-sm text-green-700">Thương hiệu uy tín, date mới nhất.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="phan-tich" class="py-16 bg-gray-900 text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="mb-16">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
                    <div>
                        <h2 class="text-3xl font-bold mb-6 flex items-center gap-3">
                            <i class="fas fa-store text-yellow-400"></i> Đánh Giá Chung Các Cửa Hàng
                        </h2>
                        <p class="text-gray-300 mb-4 text-justify">
                            Hiện nay, đa số các cửa hàng bán nước đều đã có mặt trên các app giao hàng (Grab, ShopeeFood). Tuy nhiên, việc sở hữu một website riêng biệt mang lại lợi thế về thương hiệu và quản lý dữ liệu khách hàng.
                        </p>
                        <div class="space-y-4">
                            <div class="flex items-center justify-between bg-gray-800 p-3 rounded">
                                <span>Chất lượng phục vụ</span>
                                <div class="flex text-yellow-400 text-sm">
                                    <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star-half-alt"></i>
                                </div>
                            </div>
                            <div class="flex items-center justify-between bg-gray-800 p-3 rounded">
                                <span>Tốc độ giao hàng</span>
                                <div class="flex text-yellow-400 text-sm">
                                    <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="far fa-star"></i>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div>
                        <img src="https://images.unsplash.com/photo-1556742049-0cfed4f7a07d?q=80&w=2070&auto=format&fit=crop" alt="Cửa hàng bận rộn" class="rounded-xl shadow-2xl opacity-90 hover:opacity-100 transition">
                    </div>
                </div>
            </div>

            <hr class="border-gray-700 my-12">

            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
                <div class="order-2 md:order-1">
                    <img src="https://images.unsplash.com/photo-1594302946258-0027f311c470?q=80&w=2070&auto=format&fit=crop" alt="Vấn đề giao hàng" class="rounded-xl shadow-2xl opacity-90 hover:opacity-100 transition grayscale hover:grayscale-0">
                </div>
                <div class="order-1 md:order-2">
                    <h2 class="text-3xl font-bold mb-6 flex items-center gap-3 text-red-400">
                        <i class="fas fa-exclamation-triangle"></i> Những Hạn Chế Còn Tồn Tại
                    </h2>
                    <ul class="space-y-4">
                        <li class="flex gap-4">
                            <div class="flex-shrink-0 w-8 h-8 rounded-full bg-red-900 flex items-center justify-center text-red-400 font-bold">1</div>
                            <p class="text-gray-300"><strong>Bảo quản sản phẩm:</strong> Nước đá tan nhanh trong quá trình vận chuyển làm giảm hương vị gốc.</p>
                        </li>
                        <li class="flex gap-4">
                            <div class="flex-shrink-0 w-8 h-8 rounded-full bg-red-900 flex items-center justify-center text-red-400 font-bold">2</div>
                            <p class="text-gray-300"><strong>Cạnh tranh gay gắt:</strong> Chi phí marketing cao để cạnh tranh với các chuỗi lớn.</p>
                        </li>
                        <li class="flex gap-4">
                            <div class="flex-shrink-0 w-8 h-8 rounded-full bg-red-900 flex items-center justify-center text-red-400 font-bold">3</div>
                            <p class="text-gray-300"><strong>Phụ thuộc shipper:</strong> Khó kiểm soát thái độ của shipper bên thứ 3 đối với khách hàng.</p>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <section class="py-16 bg-teal-600 text-white relative overflow-hidden">
        <div class="absolute top-0 right-0 -mr-20 -mt-20 w-64 h-64 rounded-full bg-teal-500 opacity-50"></div>
        <div class="absolute bottom-0 left-0 -ml-20 -mb-20 w-80 h-80 rounded-full bg-teal-700 opacity-50"></div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="flex flex-col md:flex-row items-center gap-12">
                <div class="md:w-3/5">
                    <h2 class="text-3xl md:text-4xl font-bold mb-6">Tiềm Năng Phát Triển Của Dự Án</h2>
                    <p class="text-teal-100 text-lg mb-8">
                        Dự án không chỉ dừng lại ở việc bán hàng, mà còn hướng tới xây dựng một hệ sinh thái F&B thông minh.
                    </p>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                        <div class="bg-white/10 backdrop-blur-md p-6 rounded-xl border border-white/20">
                            <i class="fas fa-brain text-2xl mb-3 text-yellow-300"></i>
                            <h4 class="font-bold text-lg mb-2">Tích hợp AI</h4>
                            <p class="text-sm text-teal-50">Gợi ý đồ uống dựa trên tâm trạng và lịch sử mua hàng của người dùng.</p>
                        </div>
                        <div class="bg-white/10 backdrop-blur-md p-6 rounded-xl border border-white/20">
                            <i class="fas fa-recycle text-2xl mb-3 text-green-300"></i>
                            <h4 class="font-bold text-lg mb-2">Green Campaign</h4>
                            <p class="text-sm text-teal-50">Chương trình đổi vỏ ly lấy điểm thưởng, bảo vệ môi trường.</p>
                        </div>
                        <div class="bg-white/10 backdrop-blur-md p-6 rounded-xl border border-white/20">
                            <i class="fas fa-users text-2xl mb-3 text-pink-300"></i>
                            <h4 class="font-bold text-lg mb-2">Cộng đồng</h4>
                            <p class="text-sm text-teal-50">Tính năng "Mời bạn bè" mua chung để giảm phí ship (Group Buying).</p>
                        </div>
                    </div>
                </div>
                <div class="md:w-2/5">
                    <img src="https://images.unsplash.com/photo-1519389950473-47ba0277781c?q=80&w=2070&auto=format&fit=crop" 
                         alt="Công nghệ tương lai" 
                         class="rounded-2xl shadow-2xl rotate-3 hover:rotate-0 transition duration-500 border-4 border-white/30">
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-gray-800 text-gray-400 py-8">
        <div class="max-w-7xl mx-auto px-4 text-center">
            <div class="mb-4">
                <i class="fas fa-glass-citrus text-teal-500 text-3xl mb-2"></i>
                <h3 class="text-white font-bold text-xl">Đồ Án Nhóm 11</h3>
            </div>
            <p class="mb-2">Thành viên: Duy Thái, Đình Thái, Cảnh Sang, Tấn Sang, Anh Quân</p>
            <p class="text-sm">© 2024 Project Web Bán Nước. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>
