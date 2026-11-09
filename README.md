<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>An Tâm Auto - Garage Sửa Chữa, Bảo Dưỡng & Đồng Sơn Ô Tô Đà Nẵng | antamauto.com</title>
    <meta name="description" content="An Tâm Auto (antamauto.com) - Chuyên sửa chữa máy gầm, điện - điện lạnh, đồng sơn công nghệ cao, bảo dưỡng định kỳ và chăm sóc ô tô uy tín tại 54 Phạm Đình Bân, Phường Ngũ Hành Sơn, TP. Đà Nẵng. Hotline: 0966.645.696.">

    <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link chia sẻ -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://antamauto.com/">
    <meta property="og:title" content="An Tâm Auto - Hệ Thống Sửa Chữa & Chăm Sóc Ô Tô Uy Tín Đà Nẵng">
    <meta property="og:description" content="Địa chỉ: 54 Phạm Đình Bân, Phường Ngũ Hành Sơn, Tp.Đà Nẵng - Hotline/Zalo: 0966.645.696 - Website: antamauto.com">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1fT8wLoYxNz6H-NJR5Kat3OETvli6zdrf&sz=w1200">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="An Tâm Auto - Garage Sửa Chữa & Bảo Dưỡng Ô Tô Đà Nẵng">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1fT8wLoYxNz6H-NJR5Kat3OETvli6zdrf&sz=w1200">
    <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=1fT8wLoYxNz6H-NJR5Kat3OETvli6zdrf&sz=w200">

    <!-- Google Fonts: Inter & Montserrat chuẩn Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            navy: '#0d264c',
                            dark: '#081933',
                            blue: '#164384',
                            red: '#d8232a',
                            redHover: '#b9181e',
                            light: '#f4f6f9'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif']
                    }
                }
            }
        }
    </script>

    <style>
        /* Reset chống tràn viền và chống lệch phải tuyệt đối */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            background-color: #f4f6f9;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Khung giao diện chuẩn Flatsome 1500px trên máy tính */
        .container-1500 {
            width: 100%;
            max-width: 1500px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .container-1500 {
                padding-left: 20px;
                padding-right: 20px;
            }
        }

        /* Tối ưu Menu Danh mục trên máy tính: nằm trên 1 hàng (hoặc xuống hàng 2), mỗi tên danh mục viết liền không xuống dòng */
        .desktop-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            gap: 4px 18px;
        }
        .desktop-nav-item {
            white-space: nowrap;
            font-size: 12.5px;
            font-weight: 700;
            letter-spacing: 0.01em;
            line-height: 1.4;
            padding: 8px 4px;
            color: #ffffff;
            transition: color 0.2s ease;
            text-transform: uppercase;
        }
        .desktop-nav-item:hover,
        .desktop-nav-item.active {
            color: #ffccd0;
        }

        /* Ô danh mục ở trang chủ: chữ nhỏ gọn, tên danh mục viết liền trên 1 hàng không xuống dòng */
        .home-cat-card {
            background: #ffffff;
            border: 1px solid #e2e8f0;
            border-radius: 8px;
            padding: 12px 6px;
            text-align: center;
            transition: all 0.2s ease;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }
        .home-cat-card:hover {
            border-color: #164384;
            box-shadow: 0 4px 12px rgba(13, 38, 76, 0.08);
            transform: translateY(-2px);
        }
        .home-cat-title {
            white-space: nowrap;
            overflow: hidden;
            text-overflow: clip;
            font-size: 11.5px;
            font-weight: 700;
            color: #0d264c;
            line-height: 1.3;
            margin-top: 8px;
            width: 100%;
        }
        @media (min-width: 1280px) {
            .home-cat-title {
                font-size: 12.5px;
            }
        }

        /* Tiêu đề Section chuẩn Flatsome */
        .flatsome-section-title {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #0d264c;
            margin-bottom: 16px;
            padding-bottom: 8px;
            gap: 10px;
        }
        .flatsome-title-main {
            background-color: #0d264c;
            color: #ffffff;
            font-weight: 700;
            font-size: 13px;
            padding: 8px 14px;
            border-radius: 6px 6px 0 0;
            margin-bottom: -10px;
            text-transform: uppercase;
            letter-spacing: 0.02em;
        }
        @media (min-width: 768px) {
            .flatsome-title-main {
                font-size: 15px;
                padding: 9px 18px;
            }
        }

        /* Thẻ Sản phẩm / Dịch vụ: Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ hay tràn ra ngoài */
        .product-box {
            background: #ffffff;
            border: 1px solid #e5e7eb;
            border-radius: 8px;
            overflow: hidden;
            display: flex;
            flex-direction: column;
            height: 100%;
            transition: box-shadow 0.2s ease, border-color 0.2s ease;
        }
        .product-box:hover {
            border-color: #164384;
            box-shadow: 0 6px 16px rgba(13, 38, 76, 0.08);
        }
        .product-box-title {
            font-size: 12.5px;
            font-weight: 700;
            color: #0d264c;
            line-height: 1.4;
            word-wrap: break-word;
            overflow-wrap: break-word;
            white-space: normal;
            margin-bottom: 6px;
        }
        @media (min-width: 768px) {
            .product-box-title {
                font-size: 14px;
            }
        }

        /* Banner Máy tính & Banner Điện thoại kích thước đồng nhất */
        .desktop-banner-stage {
            height: 410px;
            position: relative;
            overflow: hidden;
            border-radius: 10px;
        }
        .mobile-banner-stage {
            height: 235px;
            position: relative;
            overflow: hidden;
            border-radius: 8px;
        }
        .banner-slide {
            position: absolute;
            inset: 0;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.6s ease-in-out, visibility 0.6s ease-in-out;
        }
        .banner-slide.active {
            opacity: 1;
            visibility: visible;
            z-index: 2;
        }

        /* Cụm nút liên hệ nổi cố định (Zalo, Facebook, Hotline) */
        .floating-contact-group {
            position: fixed;
            right: 12px;
            bottom: 18px;
            z-index: 999;
            display: flex;
            flex-direction: column;
            gap: 10px;
            align-items: flex-end;
        }
        @keyframes softPulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }
        .pulse-btn {
            animation: softPulse 2.2s infinite ease-in-out;
        }
    </style>
</head>
<body>

    <!-- ================= HEADER WRAPPER (CHUẨN FLATSOME - KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN) ================= -->
    <header id="header" class="header-wrapper bg-white shadow-sm sticky top-0 z-50 w-full">
        <!-- Top Bar nhỏ gọn -->
        <div class="bg-brand-dark text-white text-[11px] md:text-xs py-1.5 border-b border-slate-800">
            <div class="container-1500 flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-2 truncate">
                    <i class="fa-solid fa-location-dot text-brand-red shrink-0"></i>
                    <span class="truncate">54 Phạm Đình Bân, Phường Ngũ Hành Sơn, Tp.Đà Nẵng</span>
                </div>
                <div class="hidden sm:flex items-center gap-4 shrink-0">
                    <span><i class="fa-solid fa-globe text-sky-400 mr-1"></i>antamauto.com</span>
                    <span><i class="fa-regular fa-clock text-sky-400 mr-1"></i>Thứ 2 - CN: 07:30 - 18:00</span>
                </div>
            </div>
        </div>

        <!-- Header Main: Logo chỉnh gọn nhỏ lại + Thanh tìm kiếm danh mục (Không có nút Gọi ngay) -->
        <div class="header-main py-2.5 bg-white">
            <div class="container-1500 flex items-center justify-between gap-3">
                <!-- Logo An Tâm Auto nhỏ gọn -->
                <a href="#top" class="flex items-center gap-2.5 shrink-0 group">
                    <div class="w-10 h-10 md:w-12 md:h-12 rounded-lg border border-slate-200 bg-white p-0.5 flex items-center justify-center overflow-hidden shrink-0">
                        <img src="https://drive.google.com/thumbnail?id=1fT8wLoYxNz6H-NJR5Kat3OETvli6zdrf&sz=w300"
                             onerror="if(!this.dataset.fb){this.dataset.fb='1';this.src='https://lh3.googleusercontent.com/d/1fT8wLoYxNz6H-NJR5Kat3OETvli6zdrf=w300';}else{this.src='https://placehold.co/120x120/0d264c/ffffff?text=AN+TAM';}"
                             alt="Logo An Tâm Auto"
                             class="w-full h-full object-contain">
                    </div>
                    <div class="leading-tight">
                        <div class="text-sm md:text-lg font-extrabold text-brand-navy tracking-tight">AN TÂM AUTO</div>
                        <div class="text-[10px] md:text-[11px] text-slate-500 font-medium">GARAGE Ô TÔ ĐÀ NẴNG • antamauto.com</div>
                    </div>
                </a>

                <!-- Khung Tìm kiếm dịch vụ / phụ tùng trên máy tính -->
                <div class="hidden md:flex flex-1 max-w-md mx-4">
                    <form onsubmit="event.preventDefault(); filterSearchProducts();" class="w-full flex border border-slate-300 rounded-lg overflow-hidden bg-slate-50 focus-within:border-brand-navy">
                        <input id="searchInput" type="text" placeholder="Tìm dịch vụ sửa chữa, bảo dưỡng, đồng sơn..." class="w-full px-3 py-1.5 text-xs bg-transparent focus:outline-none text-slate-700">
                        <button type="submit" class="px-3.5 py-1.5 bg-brand-navy text-white text-xs font-semibold hover:bg-brand-blue transition">
                            <i class="fa-solid fa-magnifying-glass"></i>
                        </button>
                    </form>
                </div>

                <!-- Địa chỉ tóm tắt trên máy tính & Nút mở Menu trên điện thoại -->
                <div class="hidden lg:flex items-center gap-5 text-xs text-slate-600 shrink-0">
                    <a href="#ban-do" class="flex items-center gap-2 hover:text-brand-navy transition">
                        <i class="fa-solid fa-map-location-dot text-brand-navy text-base"></i>
                        <div>
                            <div class="font-bold text-brand-navy">54 Phạm Đình Bân</div>
                            <div class="text-[11px] text-slate-500">P. Ngũ Hành Sơn, Đà Nẵng</div>
                        </div>
                    </a>
                    <a href="#bao-gia" class="px-3 py-1.5 rounded-md bg-slate-100 hover:bg-slate-200 text-brand-navy font-bold text-xs transition">
                        Nhận Báo Giá
                    </a>
                </div>

                <!-- Nút mở Menu Danh mục trên Điện thoại -->
                <button id="mobileMenuBtn" onclick="toggleMobileMenu()" type="button" aria-label="Mở danh mục" class="md:hidden p-2 rounded-lg border border-slate-200 text-brand-navy hover:bg-slate-100">
                    <i class="fa-solid fa-bars text-base"></i>
                </button>
            </div>
        </div>

        <!-- Header Bottom: Thanh danh mục máy tính viết liền trên 1 hàng chữ nhỏ gọn, không xuống dòng tên danh mục -->
        <div class="header-bottom bg-brand-navy hidden md:block">
            <div class="container-1500">
                <nav class="desktop-nav-list">
                    <a href="#top" class="desktop-nav-item active">Trang Chủ</a>
                    <a href="#danh-muc" class="desktop-nav-item">Danh Mục Dịch Vụ</a>
                    <a href="#dich-vu-sua-chua" onclick="filterCategory('may-gam')" class="desktop-nav-item">Sửa Chữa Máy Gầm</a>
                    <a href="#dich-vu-sua-chua" onclick="filterCategory('dong-son')" class="desktop-nav-item">Đồng Sơn Ô Tô</a>
                    <a href="#dich-vu-sua-chua" onclick="filterCategory('dien-lanh')" class="desktop-nav-item">Điện - Điện Lạnh</a>
                    <a href="#dich-vu-sua-chua" onclick="filterCategory('bao-duong')" class="desktop-nav-item">Bảo Dưỡng Định Kỳ</a>
                    <a href="#dich-vu-sua-chua" onclick="filterCategory('cham-soc')" class="desktop-nav-item">Chăm Sóc & Làm Đẹp</a>
                    <a href="#dich-vu-sua-chua" onclick="filterCategory('phu-tung')" class="desktop-nav-item">Phụ Tùng Ô Tô</a>
                    <a href="#du-an-da-nang" class="desktop-nav-item">Dự Án Đà Nẵng</a>
                    <a href="#bai-viet" class="desktop-nav-item">Bài Viết</a>
                    <a href="#bao-gia" class="desktop-nav-item">Báo Giá</a>
                    <a href="#lien-he" class="desktop-nav-item">Liên Hệ</a>
                </nav>
            </div>
        </div>

        <!-- Menu Danh mục xổ xuống trên Điện thoại -->
        <div id="mobileMenuDrawer" class="hidden md:hidden bg-white border-t border-slate-200 shadow-lg">
            <div class="container-1500 py-3">
                <div class="grid grid-cols-2 gap-2 text-xs font-semibold text-brand-navy">
                    <a href="#danh-muc" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 border border-slate-200 truncate">Danh Mục Dịch Vụ</a>
                    <a href="#dich-vu-sua-chua" onclick="filterCategory('may-gam'); toggleMobileMenu()" class="p-2 rounded bg-slate-50 border border-slate-200 truncate">Sửa Chữa Máy Gầm</a>
                    <a href="#dich-vu-sua-chua" onclick="filterCategory('dong-son'); toggleMobileMenu()" class="p-2 rounded bg-slate-50 border border-slate-200 truncate">Đồng Sơn Ô Tô</a>
                    <a href="#dich-vu-sua-chua" onclick="filterCategory('dien-lanh'); toggleMobileMenu()" class="p-2 rounded bg-slate-50 border border-slate-200 truncate">Điện - Điện Lạnh</a>
                    <a href="#dich-vu-sua-chua" onclick="filterCategory('bao-duong'); toggleMobileMenu()" class="p-2 rounded bg-slate-50 border border-slate-200 truncate">Bảo Dưỡng Định Kỳ</a>
                    <a href="#dich-vu-sua-chua" onclick="filterCategory('cham-soc'); toggleMobileMenu()" class="p-2 rounded bg-slate-50 border border-slate-200 truncate">Chăm Sóc & Làm Đẹp</a>
                    <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 border border-slate-200 truncate">Dự Án Đà Nẵng</a>
                    <a href="#bao-gia" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 border border-slate-200 truncate">Yêu Cầu Báo Giá</a>
                </div>
            </div>
        </div>
    </header>

    <!-- ================= MAIN CONTENT (CHUẨN UX BUILDER FLATSOME) ================= -->
    <main id="main" class="w-full">

        <!-- SECTION 1: BANNER TỰ TRƯỢT CHUYÊN NGHIỆP (2 SLIDE KÍCH THƯỚC BẰNG NHAU, RIÊNG BIỆT MÁY TÍNH & ĐIỆN THOẠI) -->
        <section id="top" class="section py-3 md:py-4">
            <div class="container-1500">

                <!-- 1A. BANNER DÀNH RIÊNG CHO MÁY TÍNH (2 ảnh banner tự trượt kích thước bằng nhau 410px, chữ nhỏ gọn trong khung) -->
                <div class="hidden md:block desktop-banner-stage bg-brand-dark shadow">
                    <!-- Desktop Slide 1 -->
                    <div class="banner-slide desktop-slide active">
                        <div class="w-full h-full grid grid-cols-12 items-center bg-gradient-to-r from-brand-dark via-brand-navy to-brand-blue">
                            <div class="col-span-7 px-10 py-6 text-white flex flex-col justify-center">
                                <div class="text-xs font-semibold text-sky-300 uppercase tracking-wider mb-1.5">
                                    CÔNG TY TNHH MTV AN TÂM AUTO • ANTAMAUTO.COM
                                </div>
                                <h1 class="text-2xl lg:text-3xl font-extrabold leading-snug mb-2.5 text-white">
                                    GARAGE SỬA CHỮA, BẢO DƯỠNG & ĐỒNG SƠN Ô TÔ UY TÍN TẠI ĐÀ NẴNG
                                </h1>
                                <p class="text-xs lg:text-sm text-slate-200 leading-relaxed mb-4 max-w-xl">
                                    Chuyên đại tu máy gầm, chẩn đoán điện - điện lạnh chuyên sâu, đồng sơn công nghệ cao, bảo dưỡng định kỳ và phục hồi xe tai nạn tại Ngũ Hành Sơn, Đà Nẵng.
                                </p>
                                <div class="grid grid-cols-2 gap-2 text-xs text-slate-100 mb-5 max-w-lg">
                                    <div class="flex items-center gap-2"><i class="fa-solid fa-check text-sky-400"></i><span>54 Phạm Đình Bân, Ngũ Hành Sơn</span></div>
                                    <div class="flex items-center gap-2"><i class="fa-solid fa-check text-sky-400"></i><span>Hotline/Zalo: 0966.645.696</span></div>
                                    <div class="flex items-center gap-2"><i class="fa-solid fa-check text-sky-400"></i><span>Máy chẩn đoán đa năng hiện đại</span></div>
                                    <div class="flex items-center gap-2"><i class="fa-solid fa-check text-sky-400"></i><span>Báo giá minh bạch, phụ tùng chuẩn</span></div>
                                </div>
                                <div class="flex items-center gap-3">
                                    <a href="#bao-gia" class="px-4 py-2 rounded-md bg-brand-red hover:bg-brand-redHover text-white font-bold text-xs transition">
                                        Đặt Lịch & Nhận Báo Giá
                                    </a>
                                    <a href="#dich-vu-sua-chua" class="px-4 py-2 rounded-md bg-white/10 hover:bg-white/20 text-white font-semibold text-xs border border-white/25 transition">
                                        Xem Dịch Vụ Thực Tế
                                    </a>
                                </div>
                            </div>
                            <div class="col-span-5 h-full p-5 flex items-center justify-center">
                                <div class="w-full h-full rounded-lg overflow-hidden border-2 border-white/20 shadow-lg bg-slate-900">
                                    <img src="https://drive.google.com/thumbnail?id=1T5aCgV0IJHBhcS-byuLtJrEXwFuAfERZ&sz=w1200"
                                         onerror="if(!this.dataset.fb){this.dataset.fb='1';this.src='https://lh3.googleusercontent.com/d/1T5aCgV0IJHBhcS-byuLtJrEXwFuAfERZ=w1200';}else{this.src='https://placehold.co/800x500/0d264c/ffffff?text=An+Tam+Auto+Garage';}"
                                         alt="Xưởng dịch vụ An Tâm Auto Đà Nẵng"
                                         class="w-full h-full object-cover">
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Desktop Slide 2 (Kích thước bằng hệt Slide 1) -->
                    <div class="banner-slide desktop-slide">
                        <div class="w-full h-full grid grid-cols-12 items-center bg-gradient-to-r from-[#091d3a] via-[#123568] to-[#0d264c]">
                            <div class="col-span-7 px-10 py-6 text-white flex flex-col justify-center">
                                <div class="text-xs font-semibold text-amber-300 uppercase tracking-wider mb-1.5">
                                    CHĂM SÓC TOÀN DIỆN • ĐỒNG SƠN & ĐẠI TU MÁY GẦM Ô TÔ
                                </div>
                                <h2 class="text-2xl lg:text-3xl font-extrabold leading-snug mb-2.5 text-white">
                                    QUY TRÌNH KỸ THUẬT CHUẨN XƯỞNG - BẢO HÀNH RÕ RÀNG TẬN TÂM
                               </h2>
                                <p class="text-xs lg:text-sm text-slate-200 leading-relaxed mb-4 max-w-xl">
                                    Đội ngũ kỹ thuật viên giàu kinh nghiệm thực chiến tại Đà Nẵng. Kiểm tra tổng quát miễn phí, tư vấn đúng bệnh, cam kết tiến độ bàn giao xe nhanh chóng.
                                </p>
                                <div class="grid grid-cols-2 gap-2 text-xs text-slate-100 mb-5 max-w-lg">
                                    <div class="flex items-center gap-2"><i class="fa-solid fa-wrench text-amber-400"></i><span>Đại tu động cơ - hộp số tự động</span></div>
                                    <div class="flex items-center gap-2"><i class="fa-solid fa-spray-can-sparkles text-amber-400"></i><span>Phòng sơn sấy tiêu chuẩn chính hãng</span></div>
                                    <div class="flex items-center gap-2"><i class="fa-solid fa-snowflake text-amber-400"></i><span>Sửa chữa điện - điều hòa chuyên sâu</span></div>
                                    <div class="flex items-center gap-2"><i class="fa-solid fa-shield-halved text-amber-400"></i><span>Hỗ trợ hồ sơ bảo hiểm thân vỏ</span></div>
                                </div>
                                <div class="flex items-center gap-3">
                                    <a href="#du-an-da-nang" class="px-4 py-2 rounded-md bg-brand-red hover:bg-brand-redHover text-white font-bold text-xs transition">
                                        Xem Dự Án Tại Đà Nẵng
                                    </a>
                                    <a href="#ban-do" class="px-4 py-2 rounded-md bg-white/10 hover:bg-white/20 text-white font-semibold text-xs border border-white/25 transition">
                                        Chỉ Đường Đến Xưởng
                                    </a>
                                </div>
                            </div>
                            <div class="col-span-5 h-full p-5 flex items-center justify-center">
                                <div class="w-full h-full rounded-lg overflow-hidden border-2 border-white/20 shadow-lg bg-slate-900">
                                    <img src="https://drive.google.com/thumbnail?id=15s18H6fqmu9Spi2zjvCohaX9QRVWxujb&sz=w1200"
                                         onerror="if(!this.dataset.fb){this.dataset.fb='1';this.src='https://lh3.googleusercontent.com/d/15s18H6fqmu9Spi2zjvCohaX9QRVWxujb=w1200';}else{this.src='https://placehold.co/800x500/164384/ffffff?text=Sua+Chua+May+Gam';}"
                                         alt="Kỹ thuật sửa chữa thực tế tại An Tâm Auto"
                                         class="w-full h-full object-cover">
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Nút điều hướng Slide Máy tính -->
                    <div class="absolute bottom-3 left-10 z-10 flex items-center gap-2">
                        <button onclick="setBannerSlide(0)" class="desktop-dot w-6 h-2 rounded-full bg-white transition-all" aria-label="Slide 1"></button>
                        <button onclick="setBannerSlide(1)" class="desktop-dot w-2.5 h-2 rounded-full bg-white/40 transition-all" aria-label="Slide 2"></button>
                    </div>
                </div>

                <!-- 1B. BANNER THIẾT KẾ MỚI RIÊNG CHO ĐIỆN THOẠI (Khác máy tính, chữ nhỏ gọn nằm hết trong ảnh banner, không tràn viền) -->
                <div class="block md:hidden mobile-banner-stage bg-brand-dark shadow">
                    <!-- Mobile Slide 1 -->
                    <div class="banner-slide mobile-slide active">
                        <div class="relative w-full h-full flex items-center">
                            <img src="https://drive.google.com/thumbnail?id=1T5aCgV0IJHBhcS-byuLtJrEXwFuAfERZ&sz=w800"
                                 onerror="if(!this.dataset.fb){this.dataset.fb='1';this.src='https://lh3.googleusercontent.com/d/1T5aCgV0IJHBhcS-byuLtJrEXwFuAfERZ=w800';}else{this.src='https://placehold.co/600x360/0d264c/ffffff?text=An+Tam+Auto';}"
                                 alt="An Tâm Auto Đà Nẵng"
                                 class="absolute inset-0 w-full h-full object-cover">
                            <div class="absolute inset-0 bg-gradient-to-r from-[#081933]/95 via-[#0d264c]/85 to-[#0d264c]/65"></div>
                            <div class="relative z-10 w-full px-4 py-3 text-white">
                                <div class="text-[10px] font-semibold text-sky-300 uppercase mb-1">
                                    AN TÂM AUTO • ANTAMAUTO.COM
                                </div>
                                <h2 class="text-[14px] font-extrabold leading-snug text-white mb-1.5">
                                    GARAGE SỬA CHỮA & BẢO DƯỠNG Ô TÔ ĐÀ NẴNG
                                </h2>
                                <p class="text-[11px] text-slate-200 leading-normal mb-2">
                                    Chuyên Máy Gầm • Đồng Sơn • Điện Lạnh • Bảo Dưỡng Định Kỳ.
                                </p>
                                <div class="text-[10.5px] text-amber-300 font-medium mb-2.5">
                                    Đ/c: 54 Phạm Đình Bân, P. Ngũ Hành Sơn • ĐT: 0966.645.696
                                </div>
                                <div class="flex items-center gap-2">
                                    <a href="#bao-gia" class="px-3 py-1.5 rounded bg-brand-red text-white font-bold text-[11px]">
                                        Nhận Báo Giá
                                    </a>
                                    <a href="#dich-vu-sua-chua" class="px-3 py-1.5 rounded bg-white/15 border border-white/30 text-white font-semibold text-[11px]">
                                        Xem Dịch Vụ
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Mobile Slide 2 (Kích thước bằng hệt Mobile Slide 1, chữ nhỏ gọn nằm hết trong ảnh) -->
                    <div class="banner-slide mobile-slide">
                        <div class="relative w-full h-full flex items-center">
                            <img src="https://drive.google.com/thumbnail?id=15s18H6fqmu9Spi2zjvCohaX9QRVWxujb&sz=w800"
                                 onerror="if(!this.dataset.fb){this.dataset.fb='1';this.src='https://lh3.googleusercontent.com/d/15s18H6fqmu9Spi2zjvCohaX9QRVWxujb=w800';}else{this.src='https://placehold.co/600x360/164384/ffffff?text=Dong+Son+O+To';}"
                                 alt="Đồng sơn và đại tu máy gầm An Tâm Auto"
                                 class="absolute inset-0 w-full h-full object-cover">
                            <div class="absolute inset-0 bg-gradient-to-r from-[#081933]/95 via-[#0d264c]/85 to-[#0d264c]/65"></div>
                            <div class="relative z-10 w-full px-4 py-3 text-white">
                                <div class="text-[10px] font-semibold text-amber-300 uppercase mb-1">
                                    ĐỒNG SƠN CÔNG NGHỆ CAO & ĐẠI TU MÁY
                                </div>
                                <h2 class="text-[14px] font-extrabold leading-snug text-white mb-1.5">
                                    CHẨN ĐOÁN CHÍNH XÁC - PHỤ TÙNG CHÍNH HÃNG
                                </h2>
                                <p class="text-[11px] text-slate-200 leading-normal mb-2">
                                    Kiểm tra xe tổng quát miễn phí, báo giá minh bạch trước khi sửa chữa.
                                </p>
                                <div class="text-[10.5px] text-sky-300 font-medium mb-2.5">
                                    Hỗ trợ bảo hiểm thân vỏ & Cứu hộ ô tô Đà Nẵng 24/7
                                </div>
                                <div class="flex items-center gap-2">
                                    <a href="#du-an-da-nang" class="px-3 py-1.5 rounded bg-brand-red text-white font-bold text-[11px]">
                                        Dự Án Thực Tế
                                    </a>
                                    <a href="#ban-do" class="px-3 py-1.5 rounded bg-white/15 border border-white/30 text-white font-semibold text-[11px]">
                                        Bản Đồ Xưởng
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Chấm chuyển Slide Điện thoại -->
                    <div class="absolute bottom-2 right-3 z-10 flex items-center gap-1.5">
                        <button onclick="setBannerSlide(0)" class="mobile-dot w-4 h-1.5 rounded-full bg-white transition-all" aria-label="Slide 1"></button>
                        <button onclick="setBannerSlide(1)" class="mobile-dot w-2 h-1.5 rounded-full bg-white/40 transition-all" aria-label="Slide 2"></button>
                    </div>
                </div>

            </div>
        </section>

        <!-- SECTION 2: DANH MỤC SẢN PHẨM & DỊCH VỤ (CHUẨN WEB MẪU GARAGEOTODANANG.COM.VN - TÊN DANH MỤC GỌN TRÊN 1 HÀNG) -->
        <section id="danh-muc" class="section py-3">
            <div class="container-1500">
                <div class="flatsome-section-title">
                    <h2 class="flatsome-title-main">Danh Mục Dịch Vụ & Sản Phẩm</h2>
                    <span class="text-xs text-slate-500 hidden sm:inline">Chọn danh mục để lọc nhanh dịch vụ tại An Tâm Auto</span>
                </div>

                <!-- Lưới 8 danh mục: Trên điện thoại 2 cột, trên máy tính 8 cột nằm gọn trên 1 hàng, chữ nhỏ gọn không xuống dòng -->
                <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5">
                    <a href="#dich-vu-sua-chua" onclick="filterCategory('may-gam')" class="home-cat-card">
                        <div class="w-10 h-10 rounded-full bg-blue-50 text-brand-navy flex items-center justify-center text-base">
                            <i class="fa-solid fa-gears"></i>
                        </div>
                        <div class="home-cat-title">Sửa Chữa Máy Gầm</div>
                    </a>

                    <a href="#dich-vu-sua-chua" onclick="filterCategory('dong-son')" class="home-cat-card">
                        <div class="w-10 h-10 rounded-full bg-red-50 text-brand-red flex items-center justify-center text-base">
                            <i class="fa-solid fa-spray-can-sparkles"></i>
                        </div>
                        <div class="home-cat-title">Đồng Sơn Ô Tô</div>
                    </a>

                    <a href="#dich-vu-sua-chua" onclick="filterCategory('dien-lanh')" class="home-cat-card">
                        <div class="w-10 h-10 rounded-full bg-sky-50 text-sky-700 flex items-center justify-center text-base">
                            <i class="fa-solid fa-snowflake"></i>
                        </div>
                        <div class="home-cat-title">Điện - Điện Lạnh</div>
                    </a>

                    <a href="#dich-vu-sua-chua" onclick="filterCategory('bao-duong')" class="home-cat-card">
                        <div class="w-10 h-10 rounded-full bg-amber-50 text-amber-700 flex items-center justify-center text-base">
                            <i class="fa-solid fa-oil-can"></i>
                        </div>
                        <div class="home-cat-title">Bảo Dưỡng Định Kỳ</div>
                    </a>

                    <a href="#dich-vu-sua-chua" onclick="filterCategory('cham-soc')" class="home-cat-card">
                        <div class="w-10 h-10 rounded-full bg-emerald-50 text-emerald-700 flex items-center justify-center text-base">
                            <i class="fa-solid fa-wand-magic-sparkles"></i>
                        </div>
                        <div class="home-cat-title">Chăm Sóc Nội Thất</div>
                    </a>

                    <a href="#dich-vu-sua-chua" onclick="filterCategory('phu-tung')" class="home-cat-card">
                        <div class="w-10 h-10 rounded-full bg-indigo-50 text-indigo-700 flex items-center justify-center text-base">
                            <i class="fa-solid fa-car-battery"></i>
                        </div>
                        <div class="home-cat-title">Phụ Tùng Chính Hãng</div>
                    </a>

                    <a href="#dich-vu-sua-chua" onclick="filterCategory('bao-hiem')" class="home-cat-card">
                        <div class="w-10 h-10 rounded-full bg-rose-50 text-rose-700 flex items-center justify-center text-base">
                            <i class="fa-solid fa-shield-halved"></i>
                        </div>
                        <div class="home-cat-title">Sửa Chữa Bảo Hiểm</div>
                    </a>

                    <a href="#du-an-da-nang" class="home-cat-card">
                        <div class="w-10 h-10 rounded-full bg-slate-100 text-brand-navy flex items-center justify-center text-base">
                            <i class="fa-solid fa-screwdriver-wrench"></i>
                        </div>
                        <div class="home-cat-title">Dự Án Tại Đà Nẵng</div>
                    </a>
                </div>
            </div>
        </section>

        <!-- SECTION 3: SẢN PHẨM & DỊCH VỤ SỬA CHỮA Ô TÔ THỰC TẾ (2 CỘT TRÊN ĐIỆN THOẠI, 4 CỘT TRÊN MÁY TÍNH, KHÔNG NHÃN DÁN) -->
        <section id="dich-vu-sua-chua" class="section py-4">
            <div class="container-1500">
                <div class="flatsome-section-title flex-wrap">
                    <h2 class="flatsome-title-main">Dịch Vụ & Sản Phẩm Tại An Tâm Auto</h2>
                    <div class="flex flex-wrap items-center gap-1.5 pt-2 sm:pt-0">
                        <button onclick="filterCategory('all')" data-cat-btn="all" class="cat-filter-btn px-2.5 py-1 rounded text-xs font-semibold bg-brand-navy text-white">Tất cả</button>
                        <button onclick="filterCategory('may-gam')" data-cat-btn="may-gam" class="cat-filter-btn px-2.5 py-1 rounded text-xs font-semibold bg-white border border-slate-300 text-slate-700 hover:border-brand-navy">Máy Gầm</button>
                        <button onclick="filterCategory('dong-son')" data-cat-btn="dong-son" class="cat-filter-btn px-2.5 py-1 rounded text-xs font-semibold bg-white border border-slate-300 text-slate-700 hover:border-brand-navy">Đồng Sơn</button>
                        <button onclick="filterCategory('dien-lanh')" data-cat-btn="dien-lanh" class="cat-filter-btn px-2.5 py-1 rounded text-xs font-semibold bg-white border border-slate-300 text-slate-700 hover:border-brand-navy">Điện Lạnh</button>
                        <button onclick="filterCategory('bao-duong')" data-cat-btn="bao-duong" class="cat-filter-btn px-2.5 py-1 rounded text-xs font-semibold bg-white border border-slate-300 text-slate-700 hover:border-brand-navy">Bảo Dưỡng</button>
                    </div>
                </div>

                <!-- Lưới 8 Sản phẩm/Dịch vụ: Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4) -->
                <div id="productGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">

                    <!-- Sản phẩm 1: Ảnh thực tế 15s18H6fqmu9Spi2zjvCohaX9QRVWxujb -->
                    <div class="product-box" data-category="may-gam">
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=15s18H6fqmu9Spi2zjvCohaX9QRVWxujb&sz=w800"
                                 onerror="if(!this.dataset.fb){this.dataset.fb='1';this.src='https://lh3.googleusercontent.com/d/15s18H6fqmu9Spi2zjvCohaX9QRVWxujb=w800';}else{this.src='https://placehold.co/600x450/0d264c/ffffff?text=Dai+Tu+Dong+Co';}"
                                 alt="Đại Tu Động Cơ Và Hộp Số Tự Động Ô Tô"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                            <div>
                                <div class="text-[11px] text-slate-500 mb-1">Danh mục: Sửa Chữa Máy Gầm</div>
                                <h3 class="product-box-title">Đại Tu Động Cơ Và Hộp Số Tự Động Ô Tô Chuyên Sâu</h3>
                                <p class="text-[11.5px] text-slate-600 leading-relaxed mb-2.5">
                                    Kiểm tra, phục hồi động cơ, xử lý chảy dầu, hao nước làm mát và đại tu hộp số chuẩn kỹ thuật.
                                </p>
                            </div>
                            <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                                <span class="text-xs font-bold text-brand-red">Liên hệ: 0966.645.696</span>
                                <a href="#bao-gia" onclick="prefillService('Đại Tu Động Cơ Và Hộp Số Tự Động Ô Tô Chuyên Sâu')" class="px-2.5 py-1 rounded bg-brand-navy text-white text-[11px] font-semibold hover:bg-brand-blue">Báo giá</a>
                            </div>
                        </div>
                    </div>

                    <!-- Sản phẩm 2: Ảnh thực tế 1DXmHlRZXFBsaE8uW7c4Jdm7LJ7IcS9L9 -->
                    <div class="product-box" data-category="may-gam">
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1DXmHlRZXFBsaE8uW7c4Jdm7LJ7IcS9L9&sz=w800"
                                 onerror="if(!this.dataset.fb){this.dataset.fb='1';this.src='https://lh3.googleusercontent.com/d/1DXmHlRZXFBsaE8uW7c4Jdm7LJ7IcS9L9=w800';}else{this.src='https://placehold.co/600x450/0d264c/ffffff?text=Sua+Chua+Khung+Gam';}"
                                 alt="Sửa Chữa Hệ Thống Khung Gầm, Giảm Xóc Và Thước Lái"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                            <div>
                                <div class="text-[11px] text-slate-500 mb-1">Danh mục: Sửa Chữa Máy Gầm</div>
                                <h3 class="product-box-title">Sửa Chữa Hệ Thống Khung Gầm, Giảm Xóc Và Thước Lái</h3>
                                <p class="text-[11.5px] text-slate-600 leading-relaxed mb-2.5">
                                    Xử lý tiếng kêu gầm, thay thế rotuyn, cao su càng A, phục hồi thước lái và cân chỉnh độ chụm.
                                </p>
                            </div>
                            <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                                <span class="text-xs font-bold text-brand-red">Liên hệ: 0966.645.696</span>
                                <a href="#bao-gia" onclick="prefillService('Sửa Chữa Hệ Thống Khung Gầm, Giảm Xóc Và Thước Lái')" class="px-2.5 py-1 rounded bg-brand-navy text-white text-[11px] font-semibold hover:bg-brand-blue">Báo giá</a>
                            </div>
                        </div>
                    </div>

                    <!-- Sản phẩm 3: Ảnh thực tế 1BL4Y0XR81FYBdu-UN2H6hKoAHvn5rndC -->
                    <div class="product-box" data-category="dong-son bao-hiem">
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1BL4Y0XR81FYBdu-UN2H6hKoAHvn5rndC&sz=w800"
                                 onerror="if(!this.dataset.fb){this.dataset.fb='1';this.src='https://lh3.googleusercontent.com/d/1BL4Y0XR81FYBdu-UN2H6hKoAHvn5rndC=w800';}else{this.src='https://placehold.co/600x450/0d264c/ffffff?text=Dong+Son+O+To';}"
                                 alt="Đồng Sơn Công Nghệ Cao Và Sơn Quây Toàn Bộ Xe Ô Tô"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                            <div>
                                <div class="text-[11px] text-slate-500 mb-1">Danh mục: Đồng Sơn Ô Tô</div>
                                <h3 class="product-box-title">Đồng Sơn Công Nghệ Cao Và Sơn Quây Toàn Bộ Xe Ô Tô</h3>
                                <p class="text-[11.5px] text-slate-600 leading-relaxed mb-2.5">
                                    Pha màu vi tính chuẩn mã sơn gốc, sơn dặm xóa xước, sơn đổi màu và phục hồi thân vỏ va quẹt.
                                </p>
                            </div>
                            <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                                <span class="text-xs font-bold text-brand-red">Liên hệ: 0966.645.696</span>
                                <a href="#bao-gia" onclick="prefillService('Đồng Sơn Công Nghệ Cao Và Sơn Quây Toàn Bộ Xe Ô Tô')" class="px-2.5 py-1 rounded bg-brand-navy text-white text-[11px] font-semibold hover:bg-brand-blue">Báo giá</a>
                            </div>
                        </div>
                    </div>

                    <!-- Sản phẩm 4: Ảnh thực tế 1qizICezKsa1KV2M7Aus0s223plmk76oz -->
                    <div class="product-box" data-category="dien-lanh">
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1qizICezKsa1KV2M7Aus0s223plmk76oz&sz=w800"
                                 onerror="if(!this.dataset.fb){this.dataset.fb='1';this.src='https://lh3.googleusercontent.com/d/1qizICezKsa1KV2M7Aus0s223plmk76oz=w800';}else{this.src='https://placehold.co/600x450/0d264c/ffffff?text=Dien+Lanh+O+To';}"
                                 alt="Chẩn Đoán Điện Ô Tô Và Bảo Dưỡng Hệ Thống Điều Hòa"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                            <div>
                                <div class="text-[11px] text-slate-500 mb-1">Danh mục: Điện - Điện Lạnh</div>
                                <h3 class="product-box-title">Chẩn Đoán Điện Ô Tô Và Bảo Dưỡng Hệ Thống Điều Hòa</h3>
                                <p class="text-[11.5px] text-slate-600 leading-relaxed mb-2.5">
                                    Đọc xóa lỗi ECU bằng máy chuyên hãng, nạp gas lạnh, vệ sinh dàn lạnh nội soi và thay lốc điều hòa.
                                </p>
                            </div>
                            <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                                <span class="text-xs font-bold text-brand-red">Liên hệ: 0966.645.696</span>
                                <a href="#bao-gia" onclick="prefillService('Chẩn Đoán Điện Ô Tô Và Bảo Dưỡng Hệ Thống Điều Hòa')" class="px-2.5 py-1 rounded bg-brand-navy text-white text-[11px] font-semibold hover:bg-brand-blue">Báo giá</a>
                            </div>
                        </div>
                    </div>

                    <!-- Sản phẩm 5: Ảnh thực tế 1JNNXMxq6VGXwkwvrGose_yeH8TbBEIcF -->
                    <div class="product-box" data-category="bao-duong">
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1JNNXMxq6VGXwvrGose_yeH8TbBEIcF&sz=w800"
                                 onerror="if(!this.dataset.fb){this.dataset.fb='1';this.src='https://lh3.googleusercontent.com/d/1JNNXMxq6VGXwkwvrGose_yeH8TbBEIcF=w800';}else{this.src='https://drive.google.com/thumbnail?id=1JNNXMxq6VGXwkwvrGose_yeH8TbBEIcF&sz=w800';}"
                                 alt="Bảo Dưỡng Định Kỳ Ô Tô Các Cấp Và Thay Dầu Nhớt Chính Hãng"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                            <div>
                                <div class="text-[11px] text-slate-500 mb-1">Danh mục: Bảo Dưỡng Định Kỳ</div>
                                <h3 class="product-box-title">Bảo Dưỡng Định Kỳ Ô Tô Các Cấp Và Thay Dầu Nhớt Chính Hãng</h3>
                                <p class="text-[11.5px] text-slate-600 leading-relaxed mb-2.5">
                                    Bảo dưỡng mốc 5.000km - 100.000km, thay nhớt máy, nhớt hộp số, lọc gió, lọc nhớt và nước làm mát.
                                </p>
                            </div>
                            <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                                <span class="text-xs font-bold text-brand-red">Liên hệ: 0966.645.696</span>
                                <a href="#bao-gia" onclick="prefillService('Bảo Dưỡng Định Kỳ Ô Tô Các Cấp Và Thay Dầu Nhớt Chính Hãng')" class="px-2.5 py-1 rounded bg-brand-navy text-white text-[11px] font-semibold hover:bg-brand-blue">Báo giá</a>
                            </div>
                        </div>
                    </div>

                    <!-- Sản phẩm 6: Ảnh thực tế 13XCzs0Uwt2lG03Asz2LvSYMs_M8XbMFz -->
                    <div class="product-box" data-category="bao-duong may-gam">
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=13XCzs0Uwt2lG03Asz2LvSYMs_M8XbMFz&sz=w800"
                                 onerror="if(!this.dataset.fb){this.dataset.fb='1';this.src='https://lh3.googleusercontent.com/d/13XCzs0Uwt2lG03Asz2LvSYMs_M8XbMFz=w800';}else{this.src='https://placehold.co/600x450/0d264c/ffffff?text=Bao+Duong+Phanh';}"
                                 alt="Bảo Dưỡng Hệ Thống Phanh ABS, Láng Đĩa Phanh Và Thay Má Phanh"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                            <div>
                                <div class="text-[11px] text-slate-500 mb-1">Danh mục: Bảo Dưỡng Định Kỳ</div>
                                <h3 class="product-box-title">Bảo Dưỡng Hệ Thống Phanh ABS, Láng Đĩa Phanh Và Thay Má Phanh</h3>
                                <p class="text-[11.5px] text-slate-600 leading-relaxed mb-2.5">
                                    Vệ sinh bảo dưỡng 4 cụm phanh, thay dầu thắng DOT4, láng đĩa phanh chống rung lắc khi đạp phanh.
                                </p>
                            </div>
                            <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                                <span class="text-xs font-bold text-brand-red">Liên hệ: 0966.645.696</span>
                                <a href="#bao-gia" onclick="prefillService('Bảo Dưỡng Hệ Thống Phanh ABS, Láng Đĩa Phanh Và Thay Má Phanh')" class="px-2.5 py-1 rounded bg-brand-navy text-white text-[11px] font-semibold hover:bg-brand-blue">Báo giá</a>
                            </div>
                        </div>
                    </div>

                    <!-- Sản phẩm 7: Ảnh thực tế 1lf-uS1G4q1XOOOHor-ieo0c4w9D4ra5R -->
                    <div class="product-box" data-category="cham-soc">
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1lf-uS1G4q1XOOOHor-ieo0c4w9D4ra5R&sz=w800"
                                 onerror="if(!this.dataset.fb){this.dataset.fb='1';this.src='https://lh3.googleusercontent.com/d/1lf-uS1G4q1XOOOHor-ieo0c4w9D4ra5R=w800';}else{this.src='https://placehold.co/600x450/0d264c/ffffff?text=Ve+Sinh+Khoang+May';}"
                                 alt="Vệ Sinh Khoang Máy Hơi Nước Nóng, Dọn Nội Thất Và Đánh Bóng Sơn"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                            <div>
                                <div class="text-[11px] text-slate-500 mb-1">Danh mục: Chăm Sóc & Làm Đẹp</div>
                                <h3 class="product-box-title">Vệ Sinh Khoang Máy Hơi Nước Nóng, Dọn Nội Thất Và Đánh Bóng Sơn</h3>
                                <p class="text-[11.5px] text-slate-600 leading-relaxed mb-2.5">
                                    Tẩy ố kính, vệ sinh khoang động cơ an toàn, khử mùi nội thất chuyên sâu và hiệu chỉnh bề mặt sơn.
                                </p>
                            </div>
                            <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                                <span class="text-xs font-bold text-brand-red">Liên hệ: 0966.645.696</span>
                                <a href="#bao-gia" onclick="prefillService('Vệ Sinh Khoang Máy Hơi Nước Nóng, Dọn Nội Thất Và Đánh Bóng Sơn')" class="px-2.5 py-1 rounded bg-brand-navy text-white text-[11px] font-semibold hover:bg-brand-blue">Báo giá</a>
                            </div>
                        </div>
                    </div>

                    <!-- Sản phẩm 8: Ảnh thực tế 1izyERJ3_aHjcInI0eC2crI2Fo2cPg7e2 -->
                    <div class="product-box" data-category="phu-tung dien-lanh">
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1izyERJ3_aHjcInI0eC2crI2Fo2cPg7e2&sz=w800"
                                 onerror="if(!this.dataset.fb){this.dataset.fb='1';this.src='https://lh3.googleusercontent.com/d/1izyERJ3_aHjcInI0eC2crI2Fo2cPg7e2=w800';}else{this.src='https://placehold.co/600x450/0d264c/ffffff?text=Phu+Tung+Chinh+Hang';}"
                                 alt="Thay Thế Phụ Tùng Chính Hãng, Bình Ắc Quy Và Nâng Cấp Phụ Kiện"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                            <div>
                                <div class="text-[11px] text-slate-500 mb-1">Danh mục: Phụ Tùng Chính Hãng</div>
                                <h3 class="product-box-title">Thay Thế Phụ Tùng Chính Hãng, Bình Ắc Quy Và Nâng Cấp Phụ Kiện</h3>
                                <p class="text-[11.5px] text-slate-600 leading-relaxed mb-2.5">
                                    Cung cấp phụ tùng máy gầm, bugi, bơm xăng, ắc quy chính hãng và nâng cấp ánh sáng, màn hình ô tô.
                                </p>
                            </div>
                            <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                                <span class="text-xs font-bold text-brand-red">Liên hệ: 0966.645.696</span>
                                <a href="#bao-gia" onclick="prefillService('Thay Thế Phụ Tùng Chính Hãng, Bình Ắc Quy Và Nâng Cấp Phụ Kiện')" class="px-2.5 py-1 rounded bg-brand-navy text-white text-[11px] font-semibold hover:bg-brand-blue">Báo giá</a>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- SECTION 4: DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG TRÊN TRANG CHỦ (SỬ DỤNG ẢNH THỰC TẾ TRONG FILE GOOGLE DRIVE) -->
        <section id="du-an-da-nang" class="section py-4">
            <div class="container-1500">
                <div class="flatsome-section-title">
                    <h2 class="flatsome-title-main">Các Dự Án Sửa Chữa & Bảo Dưỡng Thực Tế Tại Đà Nẵng</h2>
                    <span class="text-xs text-slate-500 hidden md:inline">Hình ảnh thực tế tại xưởng An Tâm Auto - 54 Phạm Đình Bân, Đà Nẵng</span>
                </div>

                <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">

                    <!-- Dự án 1: Ảnh thực tế 1Mfx2TZPCrL9enWKjYBhn1WLOyNUcnOW9 -->
                    <div class="product-box">
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1Mfx2TZPCrL9enWKjYBhn1WLOyNUcnOW9&sz=w800"
                                 onerror="if(!this.dataset.fb){this.dataset.fb='1';this.src='https://lh3.googleusercontent.com/d/1Mfx2TZPCrL9enWKjYBhn1WLOyNUcnOW9=w800';}else{this.src='https://placehold.co/600x450/0d264c/ffffff?text=Du+An+Da+Nang+1';}"
                                 alt="Dự Án Bảo Dưỡng Toàn Diện Và Kiểm Tra Gầm Máy Tại Ngũ Hành Sơn Đà Nẵng"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                            <div>
                                <div class="text-[11px] text-slate-500 mb-1">Khu vực: Ngũ Hành Sơn, Đà Nẵng</div>
                                <h3 class="product-box-title">Dự Án Bảo Dưỡng Toàn Diện Và Kiểm Tra Gầm Máy Tại Ngũ Hành Sơn Đà Nẵng</h3>
                                <p class="text-[11.5px] text-slate-600 leading-relaxed">
                                    Hoàn thiện bảo dưỡng định kỳ, thay dầu nhớt và cân chỉnh hệ thống lái an toàn trước khi bàn giao.
                                </p>
                            </div>
                        </div>
                    </div>

                    <!-- Dự án 2: Ảnh thực tế 1BTEYOmhfqgCoFUF_GANaNGOE9srfZSZg -->
                    <div class="product-box">
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1BTEYOmhfqgCoFUF_GANaNGOE9srfZSZg&sz=w800"
                                 onerror="if(!this.dataset.fb){this.dataset.fb='1';this.src='https://lh3.googleusercontent.com/d/1BTEYOmhfqgCoFUF_GANaNGOE9srfZSZg=w800';}else{this.src='https://placehold.co/600x450/0d264c/ffffff?text=Du+An+Da+Nang+2';}"
                                 alt="Dự Án Phục Hồi Đồng Sơn Thân Vỏ Cho Khách Hàng Hải Châu Đà Nẵng"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                            <div>
                                <div class="text-[11px] text-slate-500 mb-1">Khu vực: Hải Châu, Đà Nẵng</div>
                                <h3 class="product-box-title">Dự Án Phục Hồi Đồng Sơn Thân Vỏ Cho Khách Hàng Hải Châu Đà Nẵng</h3>
                                <p class="text-[11.5px] text-slate-600 leading-relaxed">
                                    Gò phục hồi form chuẩn, sơn hấp công nghệ cao và đánh bóng hoàn thiện bề mặt sơn bóng đẹp như mới.
                                </p>
                            </div>
                        </div>
                    </div>

                    <!-- Dự án 3: Ảnh thực tế 1Rc9ckk9fq412dhkb68sMwk0AQTDLPuqA -->
                    <div class="product-box">
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1Rc9ckk9fq412dhkb68sMwk0AQTDLPuqA&sz=w800"
                                 onerror="if(!this.dataset.fb){this.dataset.fb='1';this.src='https://lh3.googleusercontent.com/d/1Rc9ckk9fq412dhkb68sMwk0AQTDLPuqA=w800';}else{this.src='https://placehold.co/600x450/0d264c/ffffff?text=Du+An+Da+Nang+3';}"
                                 alt="Dự Án Đại Tu Máy Và Xử Lý Hệ Thống Làm Mát Tại Cẩm Lệ Đà Nẵng"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                            <div>
                                <div class="text-[11px] text-slate-500 mb-1">Khu vực: Cẩm Lệ, Đà Nẵng</div>
                                <h3 class="product-box-title">Dự Án Đại Tu Máy Và Xử Lý Hệ Thống Làm Mát Tại Cẩm Lệ Đà Nẵng</h3>
                                <p class="text-[11.5px] text-slate-600 leading-relaxed">
                                    Kiểm tra áp suất buồng đốt, thay thế gioăng phớt chính hãng và xúc rửa két nước làm mát động cơ.
                                </p>
                            </div>
                        </div>
                    </div>

                    <!-- Dự án 4: Ảnh thực tế Garage 1T5aCgV0IJHBhcS-byuLtJrEXwFuAfERZ -->
                    <div class="product-box">
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1T5aCgV0IJHBhcS-byuLtJrEXwFuAfERZ&sz=w800"
                                 onerror="if(!this.dataset.fb){this.dataset.fb='1';this.src='https://lh3.googleusercontent.com/d/1T5aCgV0IJHBhcS-byuLtJrEXwFuAfERZ=w800';}else{this.src='https://placehold.co/600x450/0d264c/ffffff?text=Xuong+An+Tam+Auto';}"
                                 alt="Tiếp Nhận Kiểm Tra Và Chăm Sóc Xe Định Kỳ Tại Xưởng An Tâm Auto Đà Nẵng"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                            <div>
                                <div class="text-[11px] text-slate-500 mb-1">Xưởng: 54 Phạm Đình Bân, Đà Nẵng</div>
                                <h3 class="product-box-title">Tiếp Nhận Kiểm Tra Và Chăm Sóc Xe Định Kỳ Tại Xưởng An Tâm Auto Đà Nẵng</h3>
                                <p class="text-[11.5px] text-slate-600 leading-relaxed">
                                    Không gian nhà xưởng rộng rãi, cầu nâng tiêu chuẩn phục vụ các dòng xe du lịch 4 - 7 chỗ tại Đà Nẵng.
                                </p>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- SECTION 5: FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ -->
        <section id="bao-gia" class="section py-4">
            <div class="container-1500">
                <div class="bg-white border border-slate-200 rounded-xl p-4 md:p-6 shadow-sm">
                    <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                        <!-- Thông tin cam kết bên trái -->
                        <div class="lg:col-span-5">
                            <h2 class="text-lg md:text-xl font-extrabold text-brand-navy uppercase mb-2">
                                Đăng Ký Tư Vấn & Nhận Báo Giá Sửa Chữa Ô Tô
                            </h2>
                            <p class="text-xs md:text-sm text-slate-600 leading-relaxed mb-4">
                                Quý khách vui lòng để lại thông tin dòng xe và tình trạng cần kiểm tra. Kỹ thuật viên trưởng của <strong>An Tâm Auto</strong> sẽ liên hệ tư vấn phương án xử lý tối ưu và báo giá chi tiết ngay lập tức.
                            </p>
                            <div class="space-y-2.5 text-xs md:text-sm text-slate-700 bg-slate-50 p-3.5 rounded-lg border border-slate-200">
                                <div class="flex items-center gap-2.5">
                                    <i class="fa-solid fa-phone-volume text-brand-red w-4 text-center"></i>
                                    <span>Hotline / Zalo hỗ trợ 24/7: <strong class="text-brand-navy">0966.645.696</strong></span>
                                </div>
                                <div class="flex items-center gap-2.5">
                                    <i class="fa-solid fa-location-dot text-brand-navy w-4 text-center"></i>
                                    <span>Địa chỉ: <strong>54 Phạm Đình Bân, Phường Ngũ Hành Sơn, Tp.Đà Nẵng</strong></span>
                                </div>
                                <div class="flex items-center gap-2.5">
                                    <i class="fa-solid fa-globe text-brand-blue w-4 text-center"></i>
                                    <span>Website chính thức: <strong>antamauto.com</strong></span>
                                </div>
                            </div>
                        </div>

                        <!-- Form yêu cầu & báo giá bên phải -->
                        <div class="lg:col-span-7">
                            <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-bold text-brand-navy mb-1">Họ và tên khách hàng *</label>
                                    <input id="qName" type="text" required placeholder="Nhập họ và tên của bạn" class="w-full px-3 py-2 text-xs md:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-navy">
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-brand-navy mb-1">Số điện thoại / Zalo *</label>
                                    <input id="qPhone" type="tel" required placeholder="Ví dụ: 0966645696" class="w-full px-3 py-2 text-xs md:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-navy">
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-brand-navy mb-1">Dòng xe & Đời xe</label>
                                    <input id="qCar" type="text" placeholder="Ví dụ: Mazda 3, Toyota Vios, Hyundai Accent..." class="w-full px-3 py-2 text-xs md:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-navy">
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-brand-navy mb-1">Danh mục cần báo giá</label>
                                    <select id="qService" class="w-full px-3 py-2 text-xs md:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-navy bg-white">
                                        <option value="Bảo Dưỡng Định Kỳ Ô Tô">Bảo Dưỡng Định Kỳ Ô Tô</option>
                                        <option value="Sửa Chữa Máy Gầm - Động Cơ">Sửa Chữa Máy Gầm - Động Cơ</option>
                                        <option value="Đồng Sơn Công Nghệ Cao">Đồng Sơn Công Nghệ Cao</option>
                                        <option value="Sửa Chữa Điện - Điện Lạnh Ô Tô">Sửa Chữa Điện - Điện Lạnh Ô Tô</option>
                                        <option value="Chăm Sóc Nội Thất & Vệ Sinh Khoang Máy">Chăm Sóc Nội Thất & Vệ Sinh Khoang Máy</option>
                                        <option value="Thay Thế Phụ Tùng Chính Hãng">Thay Thế Phụ Tùng Chính Hãng</option>
                                        <option value="Tư Vấn Bảo Hiểm Thân Vỏ">Tư Vấn Bảo Hiểm Thân Vỏ</option>
                                    </select>
                                </div>
                                <div class="sm:col-span-2">
                                    <label class="block text-xs font-bold text-brand-navy mb-1">Mô tả tình trạng xe hoặc yêu cầu chi tiết</label>
                                    <textarea id="qNote" rows="2" placeholder="Nhập triệu chứng xe hoặc hạng mục bạn muốn báo giá..." class="w-full px-3 py-2 text-xs md:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-navy"></textarea>
                                </div>
                                <div class="sm:col-span-2 flex flex-wrap items-center gap-3 pt-1">
                                    <button type="submit" class="px-5 py-2.5 rounded-lg bg-brand-red hover:bg-brand-redHover text-white font-bold text-xs md:text-sm transition">
                                        <i class="fa-solid fa-paper-plane mr-1.5"></i>Gửi Yêu Cầu Báo Giá
                                    </button>
                                    <a href="https://zalo.me/0966645696" target="_blank" rel="noopener" class="px-4 py-2.5 rounded-lg bg-brand-navy hover:bg-brand-blue text-white font-semibold text-xs md:text-sm transition">
                                        Chat Báo Giá Qua Zalo: 0966.645.696
                                    </a>
                                </div>
                            </form>

                            <!-- Hộp thông báo xác nhận gửi form (Không dùng alert) -->
                            <div id="quoteSuccessBox" class="hidden mt-3 p-3 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs"></div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 6: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ -->
        <section id="bai-viet" class="section py-4">
            <div class="container-1500">
                <div class="flatsome-section-title">
                    <h2 class="flatsome-title-main">Danh Mục Bài Viết & Kinh Nghiệm Chăm Sóc Ô Tô</h2>
                    <span class="text-xs text-slate-500 hidden sm:inline">Cẩm nang kỹ thuật từ An Tâm Auto Đà Nẵng</span>
                </div>

                <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">

                    <article class="product-box">
                        <div class="aspect-[16/10] w-full bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1JNNXMxq6VGXwkwvrGose_yeH8TbBEIcF&sz=w600"
                                 onerror="this.src='https://placehold.co/600x380/0d264c/ffffff?text=Bao+Duong+O+To'"
                                 alt="Các Mốc Bảo Dưỡng Ô Tô Định Kỳ Quan Trọng Chủ Xe Tại Đà Nẵng Cần Nhớ"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                            <div>
                                <div class="text-[10.5px] text-slate-500 mb-1">Kinh Nghiệm Bảo Dưỡng</div>
                                <h3 class="product-box-title">Các Mốc Bảo Dưỡng Ô Tô Định Kỳ Quan Trọng Chủ Xe Tại Đà Nẵng Cần Nhớ</h3>
                                <p class="text-[11.5px] text-slate-600 leading-relaxed">
                                    Hướng dẫn chi tiết lịch thay dầu máy, lọc nhớt, lọc gió và kiểm tra phanh ở các cấp 5.000km, 20.000km và 40.000km.
                                </p>
                            </div>
                        </div>
                    </article>

                    <article class="product-box">
                        <div class="aspect-[16/10] w-full bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1DXmHlRZXFBsaE8uW7c4Jdm7LJ7IcS9L9&sz=w600"
                                 onerror="this.src='https://placehold.co/600x380/0d264c/ffffff?text=Kiem+Tra+Khung+Gam'"
                                 alt="Dấu Hiệu Nhận Biết Hệ Thống Khung Gầm Và Thước Lái Ô Tô Đang Gặp Sự Cố"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                            <div>
                                <div class="text-[10.5px] text-slate-500 mb-1">Kỹ Thuật Máy Gầm</div>
                                <h3 class="product-box-title">Dấu Hiệu Nhận Biết Hệ Thống Khung Gầm Và Thước Lái Ô Tô Đang Gặp Sự Cố</h3>
                                <p class="text-[11.5px] text-slate-600 leading-relaxed">
                                    Cách phát hiện sớm tiếng kêu lục cục dưới gầm, xe bị nhao lái hoặc mòn lốp không đều để xử lý kịp thời.
                                </p>
                            </div>
                        </div>
                    </article>

                    <article class="product-box">
                        <div class="aspect-[16/10] w-full bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1BL4Y0XR81FYBdu-UN2H6hKoAHvn5rndC&sz=w600"
                                 onerror="this.src='https://placehold.co/600x380/0d264c/ffffff?text=Quy+Trinh+Dong+Son'"
                                 alt="Quy Trình Đồng Sơn Ô Tô Chuẩn Màu Gốc Và Kinh Nghiệm Làm Bảo Hiểm Thân Vỏ"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                            <div>
                                <div class="text-[10.5px] text-slate-500 mb-1">Đồng Sơn & Bảo Hiểm</div>
                                <h3 class="product-box-title">Quy Trình Đồng Sơn Ô Tô Chuẩn Màu Gốc Và Kinh Nghiệm Làm Bảo Hiểm Thân Vỏ</h3>
                                <p class="text-[11.5px] text-slate-600 leading-relaxed">
                                    Tìm hiểu các bước làm nền, pha sơn vi tính và sấy nhiệt giúp lớp sơn bền màu, bóng sâu dưới thời tiết miền Trung.
                                </p>
                            </div>
                        </div>
                    </article>

                    <article class="product-box">
                        <div class="aspect-[16/10] w-full bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1qizICezKsa1KV2M7Aus0s223plmk76oz&sz=w600"
                                 onerror="this.src='https://placehold.co/600x380/0d264c/ffffff?text=Dieu+Hoa+O+To'"
                                 alt="Nguyên Nhân Điều Hòa Ô Tô Kém Mát Và Lịch Vệ Sinh Dàn Lạnh Định Kỳ"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                            <div>
                                <div class="text-[10.5px] text-slate-500 mb-1">Điện - Điện Lạnh</div>
                                <h3 class="product-box-title">Nguyên Nhân Điều Hòa Ô Tô Kém Mát Và Lịch Vệ Sinh Dàn Lạnh Định Kỳ</h3>
                                <p class="text-[11.5px] text-slate-600 leading-relaxed">
                                    Bảo vệ lốc lạnh và giữ không khí trong khoang xe luôn mát sâu, sạch khuẩn nhờ vệ sinh nội soi dàn lạnh.
                                </p>
                            </div>
                        </div>
                    </article>

                </div>
            </div>
        </section>

        <!-- SECTION 7: ĐƯA FANPAGE FACEBOOK VÀ BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ -->
        <section id="ban-do" class="section py-4">
            <div class="container-1500">
                <div class="flatsome-section-title">
                    <h2 class="flatsome-title-main">Kết Nối Fanpage & Bản Đồ Đường Đi Đến An Tâm Auto</h2>
                    <span class="text-xs text-slate-500 hidden sm:inline">54 Phạm Đình Bân, Phường Ngũ Hành Sơn, Tp.Đà Nẵng</span>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">

                    <!-- Cột 1: Fanpage Facebook hiển thị trực tiếp ngoài trang chủ -->
                    <div class="lg:col-span-5 bg-white border border-slate-200 rounded-xl p-4 shadow-sm flex flex-col justify-between">
                        <div>
                            <div class="flex items-center justify-between border-b border-slate-100 pb-3 mb-3">
                                <div class="flex items-center gap-2.5">
                                    <img src="https://drive.google.com/thumbnail?id=1fT8wLoYxNz6H-NJR5Kat3OETvli6zdrf&sz=w200"
                                         onerror="this.src='https://placehold.co/100x100/0d264c/ffffff?text=AT'"
                                         alt="Logo An Tâm Auto"
                                         class="w-11 h-11 rounded-full border border-slate-200 object-contain p-0.5 bg-white">
                                    <div>
                                        <h3 class="text-sm font-extrabold text-brand-navy flex items-center gap-1.5">
                                            <span>An Tâm Auto - Nguyễn Tâm</span>
                                            <i class="fa-solid fa-circle-check text-blue-600 text-xs"></i>
                                        </h3>
                                        <p class="text-[11px] text-slate-500">Facebook Chính Thức • Sửa Chữa & Bảo Dưỡng Ô Tô Đà Nẵng</p>
                                    </div>
                                </div>
                                <a href="https://www.facebook.com/nguyen.tam.847786/" target="_blank" rel="noopener" class="px-3 py-1.5 rounded-md bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs flex items-center gap-1.5 shrink-0">
                                    <i class="fa-brands fa-facebook-f"></i>
                                    <span>Mở Trang</span>
                                </a>
                            </div>

                            <!-- Ảnh bìa thực tế & thông tin Fanpage ngoài trang chủ -->
                            <div class="rounded-lg overflow-hidden border border-slate-200 mb-3">
                                <div class="aspect-[16/9] w-full bg-slate-100 relative">
                                    <img src="https://drive.google.com/thumbnail?id=1T5aCgV0IJHBhcS-byuLtJrEXwFuAfERZ&sz=w800"
                                         onerror="this.src='https://placehold.co/700x400/0d264c/ffffff?text=Fanpage+An+Tam+Auto'"
                                         alt="Fanpage An Tâm Auto"
                                         class="w-full h-full object-cover">
                                </div>
                                <div class="p-3 bg-slate-50 text-xs text-slate-700 space-y-1.5">
                                    <div class="font-bold text-brand-navy">CÔNG TY TNHH MTV AN TÂM AUTO</div>
                                    <div><i class="fa-solid fa-location-dot text-brand-red mr-1.5"></i>54 Phạm Đình Bân, Phường Ngũ Hành Sơn, Tp.Đà Nẵng</div>
                                    <div><i class="fa-solid fa-phone text-emerald-600 mr-1.5"></i>Hotline / Zalo: <strong>0966.645.696</strong></div>
                                    <div><i class="fa-brands fa-facebook text-[#1877F2] mr-1.5"></i>fb.com/nguyen.tam.847786</div>
                                </div>
                            </div>
                        </div>

                        <div class="flex flex-wrap items-center gap-2 pt-1">
                            <a href="https://www.facebook.com/nguyen.tam.847786/" target="_blank" rel="noopener" class="flex-1 text-center py-2 px-3 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs transition">
                                <i class="fa-brands fa-facebook mr-1.5"></i>Theo Dõi Trên Facebook
                            </a>
                            <a href="https://zalo.me/0966645696" target="_blank" rel="noopener" class="flex-1 text-center py-2 px-3 rounded-lg bg-brand-navy hover:bg-brand-blue text-white font-bold text-xs transition">
                                <i class="fa-solid fa-comment-dots mr-1.5"></i>Nhắn Tin Zalo
                            </a>
                        </div>
                    </div>

                    <!-- Cột 2: Ảnh & Bản Đồ Google Map hiển thị trực tiếp ngoài trang chủ -->
                    <div class="lg:col-span-7 bg-white border border-slate-200 rounded-xl p-4 shadow-sm flex flex-col justify-between">
                        <div class="flex flex-wrap items-center justify-between gap-2 mb-3">
                            <div>
                                <h3 class="text-sm font-extrabold text-brand-navy uppercase">
                                    Bản Đồ Google Map: 54 Phạm Đình Bân, Phường Ngũ Hành Sơn, Tp.Đà Nẵng
                                </h3>
                                <p class="text-xs text-slate-500">Nhấn vào bản đồ hoặc nút Mở Google Map để dẫn đường trực tiếp đến xưởng</p>
                            </div>
                            <a href="https://share.google/ccvhovH77WkAUJXfS" target="_blank" rel="noopener" class="px-3.5 py-1.5 rounded-md bg-brand-red hover:bg-brand-redHover text-white font-bold text-xs flex items-center gap-1.5">
                                <i class="fa-solid fa-diamond-turn-right"></i>
                                <span>Mở Google Maps</span>
                            </a>
                        </div>

                        <!-- Khung Google Map trực tiếp ngoài trang chủ -->
                        <div class="w-full h-[290px] md:h-[320px] rounded-lg overflow-hidden border border-slate-200 relative bg-slate-100">
                            <iframe
                                title="Bản đồ An Tâm Auto 54 Phạm Đình Bân, Phường Ngũ Hành Sơn, Tp.Đà Nẵng"
                                src="https://maps.google.com/maps?q=54%20Ph%E1%BA%A1m%20%C4%90%C3%ACnh%20B%C3%A2n,%20Ng%C5%A9%20H%C3%A0nh%20S%C6%A1n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                class="w-full h-full border-0"
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>

                        <div class="mt-3 pt-2.5 border-t border-slate-100 flex flex-wrap items-center justify-between gap-2 text-xs text-slate-600">
                            <span><i class="fa-solid fa-map-pin text-brand-red mr-1"></i><strong>Địa chỉ:</strong> 54 Phạm Đình Bân, Phường Ngũ Hành Sơn, Tp.Đà Nẵng</span>
                            <a href="https://share.google/ccvhovH77WkAUJXfS" target="_blank" rel="noopener" class="font-bold text-brand-navy hover:underline">
                                Xem vị trí trên Google Map (share.google/ccvhovH77WkAUJXfS) →
                            </a>
                        </div>
                    </div>

                </div>
            </div>
        </section>

    </main>

    <!-- ================= FOOTER WRAPPER (CHUẨN FLATSOME) ================= -->
    <footer id="lien-he" class="footer-wrapper bg-brand-dark text-slate-200 pt-8 pb-6 mt-4 border-t-4 border-brand-red">
        <div class="container-1500">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-slate-800">

                <!-- Cột 1: Thông tin An Tâm Auto -->
                <div>
                    <div class="flex items-center gap-2.5 mb-3">
                        <img src="https://drive.google.com/thumbnail?id=1fT8wLoYxNz6H-NJR5Kat3OETvli6zdrf&sz=w200"
                             onerror="this.src='https://placehold.co/100x100/ffffff/0d264c?text=AT'"
                             alt="Logo An Tâm Auto"
                             class="w-10 h-10 rounded bg-white p-0.5 object-contain shrink-0">
                        <div>
                            <div class="text-base font-extrabold text-white">AN TÂM AUTO</div>
                            <div class="text-[11px] text-sky-400">Website: antamauto.com</div>
                        </div>
                    </div>
                    <p class="text-xs text-slate-300 leading-relaxed mb-3">
                        CÔNG TY TNHH MTV AN TÂM AUTO - Chuyên sửa chữa máy gầm, đồng sơn ô tô, điện - điện lạnh, bảo dưỡng định kỳ và chăm sóc xe toàn diện tại Đà Nẵng.
                    </p>
                    <div class="space-y-1.5 text-xs text-slate-200">
                        <div><i class="fa-solid fa-location-dot text-brand-red mr-2"></i>54 Phạm Đình Bân, Phường Ngũ Hành Sơn, Tp.Đà Nẵng</div>
                        <div><i class="fa-solid fa-phone text-sky-400 mr-2"></i>Hotline / Zalo: <strong>0966.645.696</strong></div>
                        <div><i class="fa-solid fa-globe text-sky-400 mr-2"></i>Website: <strong>antamauto.com</strong></div>
                    </div>
                </div>

                <!-- Cột 2: Danh mục dịch vụ -->
                <div>
                    <h4 class="text-xs font-extrabold text-white uppercase tracking-wider mb-3 pb-1.5 border-b border-slate-700">
                        Danh Mục Dịch Vụ
                    </h4>
                    <ul class="space-y-2 text-xs text-slate-300">
                        <li><a href="#dich-vu-sua-chua" onclick="filterCategory('may-gam')" class="hover:text-white">› Sửa Chữa Máy Gầm - Động Cơ</a></li>
                        <li><a href="#dich-vu-sua-chua" onclick="filterCategory('dong-son')" class="hover:text-white">› Đồng Sơn Ô Tô Công Nghệ Cao</a></li>
                        <li><a href="#dich-vu-sua-chua" onclick="filterCategory('dien-lanh')" class="hover:text-white">› Sửa Chữa Điện - Điện Lạnh Ô Tô</a></li>
                        <li><a href="#dich-vu-sua-chua" onclick="filterCategory('bao-duong')" class="hover:text-white">› Bảo Dưỡng Định Kỳ Các Cấp</a></li>
                        <li><a href="#dich-vu-sua-chua" onclick="filterCategory('cham-soc')" class="hover:text-white">› Chăm Sóc Nội Thất & Khoang Máy</a></li>
                        <li><a href="#dich-vu-sua-chua" onclick="filterCategory('phu-tung')" class="hover:text-white">› Phụ Tùng Ô Tô Chính Hãng</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Hỗ trợ khách hàng -->
                <div>
                    <h4 class="text-xs font-extrabold text-white uppercase tracking-wider mb-3 pb-1.5 border-b border-slate-700">
                        Chính Sách & Cam Kết
                    </h4>
                    <ul class="space-y-2 text-xs text-slate-300">
                        <li>› Kiểm tra & đọc lỗi xe tổng quát miễn phí</li>
                        <li>› Báo giá minh bạch trước khi sửa chữa</li>
                        <li>› Cam kết phụ tùng chính hãng, rõ nguồn gốc</li>
                        <li>› Bảo hành dịch vụ sửa chữa & đồng sơn dài hạn</li>
                        <li>› Hỗ trợ tư vấn bảo hiểm & cứu hộ Đà Nẵng 24/7</li>
                    </ul>
                </div>

                <!-- Cột 4: Liên kết nhanh -->
                <div>
                    <h4 class="text-xs font-extrabold text-white uppercase tracking-wider mb-3 pb-1.5 border-b border-slate-700">
                        Kết Nối Nhanh
                    </h4>
                    <div class="space-y-2.5 text-xs">
                        <a href="https://www.facebook.com/nguyen.tam.847786/" target="_blank" rel="noopener" class="flex items-center gap-2.5 p-2.5 rounded-lg bg-slate-800/90 hover:bg-slate-700 text-white transition">
                            <i class="fa-brands fa-facebook text-lg text-[#1877F2]"></i>
                            <div>
                                <div class="font-bold">Facebook An Tâm Auto</div>
                                <div class="text-[11px] text-slate-400">fb.com/nguyen.tam.847786</div>
                            </div>
                        </a>
                        <a href="https://share.google/ccvhovH77WkAUJXfS" target="_blank" rel="noopener" class="flex items-center gap-2.5 p-2.5 rounded-lg bg-slate-800/90 hover:bg-slate-700 text-white transition">
                            <i class="fa-solid fa-map-location-dot text-lg text-brand-red"></i>
                            <div>
                                <div class="font-bold">Chỉ Đường Google Maps</div>
                                <div class="text-[11px] text-slate-400">54 Phạm Đình Bân, Ngũ Hành Sơn</div>
                            </div>
                        </a>
                    </div>
                </div>

            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
                <div>© 2026 <strong>AN TÂM AUTO (antamauto.com)</strong> - 54 Phạm Đình Bân, Phường Ngũ Hành Sơn, Tp.Đà Nẵng.</div>
                <div>Hotline / Zalo: <strong class="text-white">0966.645.696</strong></div>
            </div>
        </div>
    </footer>

    <!-- ================= CÁC NÚT LIÊN HỆ NỔI BẬT ZALO, FACEBOOK, HOTLINE TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI ================= -->
    <div class="floating-contact-group">
        <!-- Nút Zalo nổi bật -->
        <a href="https://zalo.me/0966645696" target="_blank" rel="noopener" aria-label="Chat Zalo 0966.645.696"
           class="pulse-btn flex items-center gap-2 px-3 py-2 rounded-full bg-[#0068ff] hover:bg-blue-700 text-white shadow-lg border border-white/30">
            <span class="w-6 h-6 rounded-full bg-white text-[#0068ff] font-extrabold text-[11px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="text-xs font-bold pr-1">Chat Zalo</span>
        </a>

        <!-- Nút Facebook nổi bật -->
        <a href="https://www.facebook.com/nguyen.tam.847786/" target="_blank" rel="noopener" aria-label="Facebook An Tâm Auto"
           class="flex items-center gap-2 px-3 py-2 rounded-full bg-[#1877F2] hover:bg-blue-800 text-white shadow-lg border border-white/30">
            <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
                <i class="fa-brands fa-facebook-f text-xs"></i>
            </span>
            <span class="text-xs font-bold pr-1">Facebook</span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <a href="tel:0966645696" aria-label="Gọi Hotline 0966.645.696"
           class="pulse-btn flex items-center gap-2 px-3.5 py-2 rounded-full bg-brand-red hover:bg-brand-redHover text-white shadow-lg border border-white/30">
            <span class="w-6 h-6 rounded-full bg-white text-brand-red flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone text-xs"></i>
            </span>
            <span class="text-xs font-extrabold pr-1">0966.645.696</span>
        </a>
    </div>

    <!-- ================= JAVASCRIPT XỬ LÝ SLIDER TỰ TRƯỢT, LỌC DANH MỤC & FORM BÁO GIÁ ================= -->
    <script>
        // 1. Tự động trượt 2 ảnh Banner trên cả Máy tính và Điện thoại
        let currentSlideIndex = 0;
        let bannerInterval = null;

        function setBannerSlide(index) {
            currentSlideIndex = index;
            const desktopSlides = document.querySelectorAll('.desktop-slide');
            const mobileSlides = document.querySelectorAll('.mobile-slide');
            const desktopDots = document.querySelectorAll('.desktop-dot');
            const mobileDots = document.querySelectorAll('.mobile-dot');

            desktopSlides.forEach((slide, i) => {
                slide.classList.toggle('active', i === index);
            });
            mobileSlides.forEach((slide, i) => {
                slide.classList.toggle('active', i === index);
            });

            desktopDots.forEach((dot, i) => {
                if (i === index) {
                    dot.className = 'desktop-dot w-6 h-2 rounded-full bg-white transition-all';
                } else {
                    dot.className = 'desktop-dot w-2.5 h-2 rounded-full bg-white/40 transition-all';
                }
            });

            mobileDots.forEach((dot, i) => {
                if (i === index) {
                    dot.className = 'mobile-dot w-4 h-1.5 rounded-full bg-white transition-all';
                } else {
                    dot.className = 'mobile-dot w-2 h-1.5 rounded-full bg-white/40 transition-all';
                }
            });
        }

        function startBannerAutoSlide() {
            bannerInterval = setInterval(() => {
                const nextIndex = (currentSlideIndex + 1) % 2;
                setBannerSlide(nextIndex);
            }, 4500);
        }

        // 2. Bật/tắt Menu Danh mục trên Điện thoại
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            if (drawer) {
                drawer.classList.toggle('hidden');
            }
        }

        // 3. Lọc Sản phẩm / Dịch vụ theo Danh mục
        function filterCategory(cat) {
            const cards = document.querySelectorAll('#productGrid .product-box');
            const buttons = document.querySelectorAll('.cat-filter-btn');

            buttons.forEach(btn => {
                if (btn.dataset.catBtn === cat) {
                    btn.className = 'cat-filter-btn px-2.5 py-1 rounded text-xs font-semibold bg-brand-navy text-white';
                } else {
                    btn.className = 'cat-filter-btn px-2.5 py-1 rounded text-xs font-semibold bg-white border border-slate-300 text-slate-700 hover:border-brand-navy';
                }
            });

            cards.forEach(card => {
                const cardCats = card.getAttribute('data-category') || '';
                if (cat === 'all' || cardCats.includes(cat)) {
                    card.style.display = 'flex';
                } else {
                    card.style.display = 'none';
                }
            });
        }

        // 4. Tìm kiếm nhanh dịch vụ
        function filterSearchProducts() {
            const query = (document.getElementById('searchInput').value || '').trim().toLowerCase();
            const cards = document.querySelectorAll('#productGrid .product-box');
            cards.forEach(card => {
                const text = card.innerText.toLowerCase();
                card.style.display = text.includes(query) ? 'flex' : 'none';
            });
            const section = document.getElementById('dich-vu-sua-chua');
            if (section) {
                section.scrollIntoView({ behavior: 'smooth' });
            }
        }

        // 5. Điền nhanh hạng mục vào Form Báo giá
        function prefillService(serviceName) {
            const noteEl = document.getElementById('qNote');
            if (noteEl) {
                noteEl.value = 'Yêu cầu tư vấn & báo giá: ' + serviceName;
            }
        }

        // 6. Xử lý gửi Form Yêu cầu & Báo giá
        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const car = document.getElementById('qCar').value.trim() || 'Chưa rõ dòng xe';
            const service = document.getElementById('qService').value;
            const box = document.getElementById('quoteSuccessBox');

            if (box) {
                box.classList.remove('hidden');
                box.innerHTML = '<strong>Đã ghi nhận yêu cầu báo giá!</strong> Cảm ơn anh/chị <strong>' + name + '</strong> (' + phone + ') - Dòng xe: <strong>' + car + '</strong> - Hạng mục: <strong>' + service + '</strong>. Kỹ thuật viên <strong>An Tâm Auto (0966.645.696)</strong> sẽ liên hệ lại ngay.';
            }
        }

        window.onload = function () {
            startBannerAutoSlide();
        };
    </script>
</body>
</html>
