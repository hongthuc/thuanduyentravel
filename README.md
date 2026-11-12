<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>THUẬN DUYÊN TRAVEL - Công Ty Cho Thuê Xe Du Lịch Tại Đà Nẵng Uy Tín</title>
    <meta name="description" content="CÔNG TY TNHH THUẬN DUYÊN TRAVEL (thuanduyentravel.com) chuyên cho thuê xe du lịch 4 chỗ, 7 chỗ, 16 chỗ, 29 chỗ, 35 chỗ, 45 chỗ, Limousine tại Đà Nẵng. Địa chỉ: H12/4 K78 Nguyễn Xuân Hữu, Phường Cẩm Lệ, TP Đà Nẵng. Hotline: 0988.399.855">
    
    <!-- Open Graph Thumbnail là ảnh Logo / Hình đại diện trang web khi gửi link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://thuanduyentravel.com/">
    <meta property="og:site_name" content="THUẬN DUYÊN TRAVEL - thuanduyentravel.com">
    <meta property="og:title" content="CÔNG TY TNHH THUẬN DUYÊN TRAVEL - Dịch Vụ Thuê Xe Du Lịch Đà Nẵng">
    <meta property="og:description" content="Chuyên cho thuê xe 4 - 7 - 16 - 29 - 35 - 45 chỗ tại Đà Nẵng đi Hội An, Bà Nà Hills, Huế, Núi Thần Tài. Hotline/Zalo: 0988.399.855">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1Setz60zZwRn3108dhggT6O927qYHhej5">
    <meta property="og:image:alt" content="Logo Công Ty TNHH Thuận Duyên Travel">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1Setz60zZwRn3108dhggT6O927qYHhej5">
    <link rel="icon" href="https://lh3.googleusercontent.com/d/1Setz60zZwRn3108dhggT6O927qYHhej5" type="image/png">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <!-- Google Fonts: Inter & Montserrat chuẩn Flatsome -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Montserrat:wght@600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            DEFAULT: '#0B4F94',
                            dark: '#073666',
                            light: '#1668B8',
                            accent: '#E11D48',
                            gold: '#F59E0B'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        heading: ['Montserrat', 'sans-serif']
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền và chống lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden !important;
            margin: 0;
            padding: 0;
            scroll-behavior: smooth;
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
        }

        /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
        .container-flatsome {
            width: 100%;
            padding-left: 12px;
            padding-right: 12px;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .container-flatsome {
                width: 95%;
                max-width: 95vw;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Menu danh mục trên máy tính: chữ nhỏ gọn, viết liền không xuống dòng trong 1 mục, tự nằm trên 1 hàng hoặc xuống hàng 2 */
        .desktop-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            gap: 4px 14px;
        }
        .desktop-nav-item {
            white-space: nowrap !important;
            font-size: 12.5px;
            font-weight: 700;
            letter-spacing: 0.01em;
            padding: 6px 4px;
            transition: color 0.2s ease;
            position: relative;
        }
        .desktop-nav-item:hover > a {
            color: #fbbf24;
        }

        /* Dropdown menu chuẩn Flatsome */
        .nav-dropdown {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 230px;
            background: #ffffff;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.14);
            border-top: 3px solid #0B4F94;
            border-radius: 0 0 8px 8px;
            z-index: 100;
            padding: 6px 0;
        }
        .desktop-nav-item:hover .nav-dropdown {
            display: block;
        }
        .nav-dropdown a {
            display: block;
            padding: 8px 14px;
            font-size: 12.5px;
            font-weight: 500;
            color: #334155;
            white-space: nowrap;
            border-bottom: 1px solid #f1f5f9;
            transition: all 0.15s ease;
        }
        .nav-dropdown a:last-child {
            border-bottom: none;
        }
        .nav-dropdown a:hover {
            background-color: #f0f7ff;
            color: #0B4F94;
            padding-left: 18px;
        }

        /* Nhãn % giảm giá góc trên bên trái chuẩn Flatsome */
        .badge-sale-flatsome {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
            background: #e11d48;
            color: #ffffff;
            font-weight: 800;
            font-size: 11px;
            line-height: 1;
            padding: 6px 8px;
            border-radius: 4px;
            box-shadow: 0 2px 6px rgba(225, 29, 72, 0.35);
        }

        /* Tên sản phẩm đầy đủ không bị cắt chữ hay tràn ra ngoài */
        .product-title-full {
            white-space: normal !important;
            overflow: visible !important;
            text-overflow: unset !important;
            word-break: break-word;
            line-height: 1.38;
        }

        /* Hiệu ứng nút liên hệ nổi bật */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(225, 29, 72, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(225, 29, 72, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(225, 29, 72, 0); }
        }
        .floating-pulse {
            animation: pulse-ring 2s infinite;
        }

        /* Tiêu đề Section kiểu Flatsome */
        .section-title-container {
            margin-bottom: 1.25rem;
        }
        .section-title-main {
            position: relative;
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #e2e8f0;
            padding-bottom: 8px;
        }
        .section-title-main::after {
            content: '';
            position: absolute;
            bottom: -2px;
            left: 0;
            width: 120px;
            height: 3px;
            background-color: #0B4F94;
        }
    </style>

    <script>
        // Hàm tự động xử lý ảnh Google Drive để luôn hiển thị mượt mà
        function handleDriveImageError(imgElement, fileId, fallbackUrl) {
            const currentStep = imgElement.getAttribute('data-retry-step') || '0';
            if (currentStep === '0') {
                imgElement.setAttribute('data-retry-step', '1');
                imgElement.src = 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w1000';
            } else if (currentStep === '1') {
                imgElement.setAttribute('data-retry-step', '2');
                imgElement.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
            } else {
                imgElement.onerror = null;
                imgElement.src = fallbackUrl;
            }
        }
    </script>
</head>
<body class="bg-slate-50 text-slate-800 antialiased">

    <!-- ================= TOP BAR (FLATSOME TOP BAR) ================= -->
    <div class="bg-brand-dark text-white text-xs py-1.5 border-b border-white/10">
        <div class="container-flatsome flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3 overflow-hidden">
                <span class="font-semibold tracking-wide truncate">
                    <i class="fa-solid fa-building-shield text-amber-400 mr-1"></i>
                    CÔNG TY TNHH THUẬN DUYÊN TRAVEL - DỊCH VỤ THUÊ XE DU LỊCH ĐÀ NẴNG
                </span>
            </div>
            <div class="hidden md:flex items-center gap-4 text-[11.5px] text-slate-200">
                <span><i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>H12/4 K78 Nguyễn Xuân Hữu, P. Cẩm Lệ, TP Đà Nẵng</span>
                <span>|</span>
                <a href="tel:0988399855" class="hover:text-amber-300 font-semibold"><i class="fa-solid fa-phone-volume text-amber-400 mr-1"></i>Hotline/Zalo: 0988.399.855</a>
                <span>|</span>
                <a href="https://www.facebook.com/thuong.huynh.892119/" target="_blank" rel="noopener" class="hover:text-amber-300"><i class="fa-brands fa-facebook text-amber-400 mr-1"></i>Facebook</a>
            </div>
        </div>
    </div>

    <!-- ================= HEADER (FLATSOME HEADER - LOGO GỌN NHỎ, KHÔNG ĐỂ NÚT GỌI NGAY TRÁNH TRÀN VIỀN) ================= -->
    <header class="bg-white sticky top-0 z-40 shadow-sm border-b border-slate-200">
        <div class="container-flatsome py-2.5 flex items-center justify-between gap-3">
            <!-- Nút mở Menu trên Điện Thoại -->
            <button id="mobileMenuBtn" onclick="toggleMobileMenu()" aria-label="Menu" class="lg:hidden p-2 rounded-lg text-brand hover:bg-slate-100 focus:outline-none">
                <i class="fa-solid fa-bars text-xl"></i>
            </button>

            <!-- Logo chỉnh gọn nhỏ lại -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group">
                <div class="w-10 h-10 md:w-11 md:h-11 rounded-lg overflow-hidden border border-slate-200 bg-white flex items-center justify-center shrink-0 shadow-sm">
                    <img src="https://lh3.googleusercontent.com/d/1Setz60zZwRn3108dhggT6O927qYHhej5"
                         onerror="handleDriveImageError(this, '1Setz60zZwRn3108dhggT6O927qYHhej5', 'https://placehold.co/120x120/0B4F94/FFFFFF?text=TD+TRAVEL')"
                         alt="Logo Thuận Duyên Travel"
                         class="w-full h-full object-contain p-0.5">
                </div>
                <div class="flex flex-col">
                    <span class="font-heading font-extrabold text-brand text-sm sm:text-base md:text-lg leading-tight tracking-tight">
                        THUẬN DUYÊN TRAVEL
                    </span>
                    <span class="text-[10px] sm:text-[11px] text-slate-500 font-medium leading-tight">
                        thuanduyentravel.com • Uy Tín Tại Đà Nẵng
                    </span>
                </div>
            </a>

            <!-- Thanh tìm kiếm gọn nhẹ trên máy tính -->
            <div class="hidden xl:flex items-center flex-1 max-w-xs mx-4">
                <div class="relative w-full">
                    <input type="text" id="searchInput" oninput="filterProductsBySearch(this.value)"
                           placeholder="Tìm xe 4, 7, 16, 29, 45 chỗ..."
                           class="w-full pl-3.5 pr-9 py-1.5 text-xs bg-slate-100 border border-slate-200 rounded-full focus:outline-none focus:border-brand focus:bg-white transition">
                    <button type="button" class="absolute right-2.5 top-1/2 -translate-y-1/2 text-slate-400 hover:text-brand text-xs">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </div>
            </div>

            <!-- Thông tin địa chỉ & giờ mở cửa gọn trên máy tính (Không để nút gọi ngay trên header tránh tràn viền) -->
            <div class="hidden md:flex items-center gap-5 text-xs text-slate-600 shrink-0">
                <div class="flex items-center gap-2">
                    <div class="w-7 h-7 rounded-full bg-brand/10 text-brand flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-clock text-xs"></i>
                    </div>
                    <div class="leading-tight">
                        <p class="font-bold text-slate-700 text-[11px]">Phục vụ 24/7</p>
                        <p class="text-[10.5px] text-slate-500">Đặt xe nhanh chóng</p>
                    </div>
                </div>
                <div class="flex items-center gap-2">
                    <div class="w-7 h-7 rounded-full bg-brand/10 text-brand flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-map-location-dot text-xs"></i>
                    </div>
                    <div class="leading-tight">
                        <p class="font-bold text-slate-700 text-[11px]">K78 Nguyễn Xuân Hữu</p>
                        <p class="text-[10.5px] text-slate-500">P. Cẩm Lệ, TP Đà Nẵng</p>
                    </div>
                </div>
            </div>
        </div>

        <!-- THANH MENU DANH MỤC MÁY TÍNH: Chữ nhỏ gọn, viết liền trên 1 hàng hoặc xuống hàng 2, tuyệt đối không gãy dòng tên danh mục -->
        <nav class="hidden lg:block bg-brand text-white border-t border-brand-dark">
            <div class="container-flatsome py-1">
                <ul class="desktop-nav-list">
                    <li class="desktop-nav-item">
                        <a href="#trang-chu" class="text-amber-300"><i class="fa-solid fa-house mr-1"></i>TRANG CHỦ</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#chon-loai-xe">CHỌN LOẠI XE <i class="fa-solid fa-chevron-down text-[9px] ml-0.5"></i></a>
                        <div class="nav-dropdown">
                            <a href="#chon-loai-xe" onclick="filterCategory('all')">Tất cả các dòng xe</a>
                            <a href="#chon-loai-xe" onclick="filterCategory('4-7-cho')">Thuê xe 4 chỗ Đà Nẵng</a>
                            <a href="#chon-loai-xe" onclick="filterCategory('4-7-cho')">Thuê xe 7 chỗ Đà Nẵng</a>
                            <a href="#chon-loai-xe" onclick="filterCategory('16-18-cho')">Thuê xe 16 chỗ Đà Nẵng</a>
                            <a href="#chon-loai-xe" onclick="filterCategory('16-18-cho')">Thuê xe 18 chỗ Đà Nẵng</a>
                            <a href="#chon-loai-xe" onclick="filterCategory('29-45-cho')">Thuê xe 29 chỗ Đà Nẵng</a>
                            <a href="#chon-loai-xe" onclick="filterCategory('29-45-cho')">Thuê xe 35 chỗ Đà Nẵng</a>
                            <a href="#chon-loai-xe" onclick="filterCategory('29-45-cho')">Thuê xe 45 chỗ Đà Nẵng</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#thue-xe-tuyen-duong">THUÊ XE TẠI ĐÀ NẴNG <i class="fa-solid fa-chevron-down text-[9px] ml-0.5"></i></a>
                        <div class="nav-dropdown">
                            <a href="#thue-xe-tuyen-duong">Thuê xe Đà Nẵng đi Hội An</a>
                            <a href="#thue-xe-tuyen-duong">Thuê xe Đà Nẵng đi Bà Nà</a>
                            <a href="#thue-xe-tuyen-duong">Thuê xe Đà Nẵng đi Núi Thần Tài</a>
                            <a href="#thue-xe-tuyen-duong">Thuê xe Đà Nẵng đi Vinpearl Nam Hội An</a>
                            <a href="#thue-xe-tuyen-duong">Thuê xe Đà Nẵng đi Mỹ Sơn</a>
                            <a href="#thue-xe-tuyen-duong">Thuê xe Đà Nẵng đi Huế</a>
                            <a href="#thue-xe-tuyen-duong">Thuê xe Đà Nẵng đi Hòa Phú Thành</a>
                            <a href="#thue-xe-tuyen-duong">Thuê xe Đà Nẵng đi Ngầm Đôi</a>
                            <a href="#thue-xe-tuyen-duong">Thuê xe Đà Nẵng đi Cù Lao Chàm</a>
                            <a href="#thue-xe-tuyen-duong">Thuê xe đưa đón sân bay Đà Nẵng</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#dich-vu-khac">DỊCH VỤ KHÁC <i class="fa-solid fa-chevron-down text-[9px] ml-0.5"></i></a>
                        <div class="nav-dropdown">
                            <a href="#chon-loai-xe" onclick="filterCategory('vip-limousine')">Thuê xe cưới Đà Nẵng</a>
                            <a href="#chon-loai-xe" onclick="filterCategory('vip-limousine')">Thuê xe VIP Đà Nẵng</a>
                            <a href="#chon-loai-xe" onclick="filterCategory('vip-limousine')">Thuê xe Limousine Đà Nẵng</a>
                            <a href="#chon-loai-xe" onclick="filterCategory('vip-limousine')">Thuê xe Sedona / Carnival Đà Nẵng</a>
                            <a href="#chon-loai-xe">Thuê xe dự án Đà Nẵng</a>
                            <a href="#chon-loai-xe">Thuê xe đưa đón công nhân Đà Nẵng</a>
                            <a href="#chon-loai-xe">Thuê xe đưa đón học sinh Đà Nẵng</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#hinh-anh-nha-xe">HÌNH ẢNH NHÀ XE</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#bang-gia">BẢNG GIÁ THUÊ XE</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#bao-gia-nhanh">YÊU CẦU BÁO GIÁ</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#tin-tuc">TIN TỨC <i class="fa-solid fa-chevron-down text-[9px] ml-0.5"></i></a>
                        <div class="nav-dropdown">
                            <a href="#tin-tuc">Cẩm nang thuê xe</a>
                            <a href="#tin-tuc">Cẩm nang du lịch Đà Nẵng</a>
                            <a href="#tin-tuc">Cẩm nang du lịch Hội An</a>
                            <a href="#tin-tuc">Cẩm nang du lịch Huế</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#doi-tac">ĐỐI TÁC</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#gioi-thieu">GIỚI THIỆU</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#lien-he-map">LIÊN HỆ & BẢN ĐỒ</a>
                    </li>
                </ul>
            </div>
        </nav>

        <!-- Thanh danh mục cuộn ngang gọn đẹp trên Điện Thoại -->
        <div class="lg:hidden bg-brand text-white border-t border-brand-dark overflow-x-auto no-scrollbar">
            <div class="flex items-center gap-3 px-3 py-2 text-[11.5px] font-bold whitespace-nowrap">
                <a href="#trang-chu" class="text-amber-300">TRANG CHỦ</a>
                <span class="text-white/30">•</span>
                <a href="#chon-loai-xe">CHỌN LOẠI XE</a>
                <span class="text-white/30">•</span>
                <a href="#thue-xe-tuyen-duong">TUYẾN ĐÀ NẴNG</a>
                <span class="text-white/30">•</span>
                <a href="#hinh-anh-nha-xe">ẢNH NHÀ XE</a>
                <span class="text-white/30">•</span>
                <a href="#bang-gia">BẢNG GIÁ</a>
                <span class="text-white/30">•</span>
                <a href="#bao-gia-nhanh">BÁO GIÁ</a>
                <span class="text-white/30">•</span>
                <a href="#tin-tuc">TIN TỨC</a>
                <span class="text-white/30">•</span>
                <a href="#lien-he-map">BẢN ĐỒ</a>
            </div>
        </div>
    </header>

    <!-- ================= MENU TRƯỢT TRÊN ĐIỆN THOẠI (OFF-CANVAS FLATSOME) ================= -->
    <div id="mobileMenuOverlay" onclick="toggleMobileMenu()" class="fixed inset-0 bg-black/60 z-50 hidden transition-opacity"></div>
    <aside id="mobileMenuDrawer" class="fixed top-0 left-0 bottom-0 w-[280px] max-w-[82vw] bg-white z-50 -translate-x-full transition-transform duration-300 shadow-2xl flex flex-col">
        <div class="p-3.5 bg-brand text-white flex items-center justify-between">
            <span class="font-heading font-bold text-sm">DANH MỤC THUẬN DUYÊN TRAVEL</span>
            <button onclick="toggleMobileMenu()" class="w-7 h-7 rounded-full bg-white/10 flex items-center justify-center text-white">
                <i class="fa-solid fa-xmark"></i>
            </button>
        </div>
        <div class="p-3 border-b border-slate-100">
            <input type="text" oninput="filterProductsBySearch(this.value)" placeholder="Tìm loại xe cần thuê..."
                   class="w-full px-3 py-2 text-xs bg-slate-100 rounded-lg border border-slate-200 focus:outline-none focus:border-brand">
        </div>
        <div class="flex-1 overflow-y-auto divide-y divide-slate-100 text-xs font-semibold text-slate-700">
            <a href="#trang-chu" onclick="toggleMobileMenu()" class="block px-4 py-3 text-brand font-bold"><i class="fa-solid fa-house mr-2"></i>TRANG CHỦ</a>
            <div class="px-4 py-2.5 bg-slate-50 text-[11px] font-bold text-slate-500 uppercase">Chọn Loại Xe Đà Nẵng</div>
            <a href="#chon-loai-xe" onclick="filterCategory('4-7-cho'); toggleMobileMenu()" class="block px-5 py-2.5 hover:bg-slate-50">• Thuê xe 4 chỗ Đà Nẵng</a>
            <a href="#chon-loai-xe" onclick="filterCategory('4-7-cho'); toggleMobileMenu()" class="block px-5 py-2.5 hover:bg-slate-50">• Thuê xe 7 chỗ Đà Nẵng</a>
            <a href="#chon-loai-xe" onclick="filterCategory('16-18-cho'); toggleMobileMenu()" class="block px-5 py-2.5 hover:bg-slate-50">• Thuê xe 16 chỗ & 18 chỗ Đà Nẵng</a>
            <a href="#chon-loai-xe" onclick="filterCategory('29-45-cho'); toggleMobileMenu()" class="block px-5 py-2.5 hover:bg-slate-50">• Thuê xe 29 chỗ Đà Nẵng</a>
            <a href="#chon-loai-xe" onclick="filterCategory('29-45-cho'); toggleMobileMenu()" class="block px-5 py-2.5 hover:bg-slate-50">• Thuê xe 35 chỗ & 45 chỗ Đà Nẵng</a>
            <a href="#chon-loai-xe" onclick="filterCategory('vip-limousine'); toggleMobileMenu()" class="block px-5 py-2.5 hover:bg-slate-50">• Thuê xe Limousine / Carnival / Cưới</a>
            <div class="px-4 py-2.5 bg-slate-50 text-[11px] font-bold text-slate-500 uppercase">Tuyến Thuê Xe Tại Đà Nẵng</div>
            <a href="#thue-xe-tuyen-duong" onclick="toggleMobileMenu()" class="block px-5 py-2.5 hover:bg-slate-50">• Thuê xe Đà Nẵng đi Hội An / Bà Nà</a>
            <a href="#thue-xe-tuyen-duong" onclick="toggleMobileMenu()" class="block px-5 py-2.5 hover:bg-slate-50">• Thuê xe Đà Nẵng đi Huế / Núi Thần Tài</a>
            <a href="#thue-xe-tuyen-duong" onclick="toggleMobileMenu()" class="block px-5 py-2.5 hover:bg-slate-50">• Thuê xe Đưa đón Sân bay Đà Nẵng</a>
            <a href="#hinh-anh-nha-xe" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50"><i class="fa-solid fa-images mr-2 text-brand"></i>HÌNH ẢNH THỰC TẾ NHÀ XE</a>
            <a href="#bang-gia" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50"><i class="fa-solid fa-table-list mr-2 text-brand"></i>BẢNG GIÁ THUÊ XE</a>
            <a href="#bao-gia-nhanh" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50"><i class="fa-solid fa-paper-plane mr-2 text-brand"></i>YÊU CẦU BÁO GIÁ</a>
            <a href="#tin-tuc" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50"><i class="fa-solid fa-newspaper mr-2 text-brand"></i>TIN TỨC & CẨM NANG</a>
            <a href="#doi-tac" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50"><i class="fa-solid fa-handshake mr-2 text-brand"></i>ĐỐI TÁC</a>
            <a href="#lien-he-map" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50"><i class="fa-solid fa-map-pin mr-2 text-brand"></i>LIÊN HỆ & GOOGLE MAPS</a>
        </div>
        <div class="p-3 bg-slate-100 text-[11px] text-slate-600">
            <p class="font-bold text-brand">CÔNG TY TNHH THUẬN DUYÊN TRAVEL</p>
            <p>Đ/c: H12/4 K78 Nguyễn Xuân Hữu, P. Cẩm Lệ, TP Đà Nẵng</p>
            <p class="font-bold text-rose-600 mt-1">Hotline/Zalo: 0988.399.855</p>
        </div>
    </aside>

    <!-- ================= HERO BANNER SLIDER (2 ẢNH BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU, RIÊNG BIỆT CHO MÁY TÍNH & ĐIỆN THOẠI) ================= -->
    <section id="trang-chu" class="py-3">
        <div class="container-flatsome">
            <div class="relative rounded-xl overflow-hidden shadow-md bg-brand-dark">

                <!-- ====== BANNER DÀNH RIÊNG CHO MÁY TÍNH (hidden md:block) - 2 SLIDE KÍCH THƯỚC BẰNG NHAU (h-[370px] lg:h-[410px]) ====== -->
                <div class="hidden md:block relative w-full h-[370px] lg:h-[410px]">
                    <!-- Desktop Slide 1 -->
                    <div class="banner-slide-desktop absolute inset-0 transition-opacity duration-700 opacity-100 z-10">
                        <div class="w-full h-full bg-gradient-to-r from-[#072f5f] via-[#0B4F94] to-[#103f79] grid grid-cols-12 items-center px-8 lg:px-14 py-6">
                            <!-- Cột chữ thu gọn nằm trọn bên trong ảnh banner -->
                            <div class="col-span-7 text-white pr-6 space-y-2.5">
                                <p class="text-amber-300 font-bold text-xs uppercase tracking-wider">
                                    CÔNG TY TNHH THUẬN DUYÊN TRAVEL • THUANDUYENTRAVEL.COM
                                </p>
                                <h1 class="font-heading font-extrabold text-xl lg:text-2xl xl:text-3xl leading-snug text-white">
                                    DỊCH VỤ CHO THUÊ XE DU LỊCH ĐÀ NẴNG UY TÍN – GIÁ TỐT
                                </h1>
                                <p class="text-xs lg:text-sm text-slate-100 leading-relaxed max-w-xl">
                                    Chuyên cho thuê xe 4 chỗ, 7 chỗ, 16 chỗ, 18 chỗ, 29 chỗ, 35 chỗ, 45 chỗ & Limousine đời mới tại Đà Nẵng đi Hội An, Bà Nà Hills, Núi Thần Tài, Huế.
                                </p>
                                <div class="grid grid-cols-4 gap-2 pt-1 max-w-lg text-center">
                                    <div class="bg-white/10 border border-white/15 rounded-lg p-2">
                                        <p class="font-bold text-amber-300 text-xs lg:text-sm">Thủ Tục</p>
                                        <p class="text-[11px] text-white">Nhanh Chóng</p>
                                    </div>
                                    <div class="bg-white/10 border border-white/15 rounded-lg p-2">
                                        <p class="font-bold text-amber-300 text-xs lg:text-sm">Giá Cả</p>
                                        <p class="text-[11px] text-white">Minh Bạch</p>
                                    </div>
                                    <div class="bg-white/10 border border-white/15 rounded-lg p-2">
                                        <p class="font-bold text-amber-300 text-xs lg:text-sm">20+ Dòng Xe</p>
                                        <p class="text-[11px] text-white">Đời Mới Nhất</p>
                                    </div>
                                    <div class="bg-white/10 border border-white/15 rounded-lg p-2">
                                        <p class="font-bold text-amber-300 text-xs lg:text-sm">Tài Xế</p>
                                        <p class="text-[11px] text-white">Chuyên Nghiệp</p>
                                    </div>
                                </div>
                                <div class="pt-2 flex items-center gap-3 text-xs">
                                    <a href="#bao-gia-nhanh" class="bg-amber-400 hover:bg-amber-300 text-slate-900 font-extrabold px-4 py-2 rounded-lg shadow transition">
                                        <i class="fa-solid fa-calendar-check mr-1.5"></i>ĐẶT XE & BÁO GIÁ NGAY
                                    </a>
                                    <span class="text-slate-200 font-semibold">
                                        <i class="fa-solid fa-phone-volume text-amber-300 mr-1"></i>Hotline: 0988.399.855 | K78 Nguyễn Xuân Hữu, Cẩm Lệ, Đà Nẵng
                                    </span>
                                </div>
                            </div>
                            <!-- Cột ảnh thực tế nhà xe -->
                            <div class="col-span-5 grid grid-cols-2 gap-2.5">
                                <div class="rounded-lg overflow-hidden border-2 border-white/30 shadow-lg h-36 lg:h-40 bg-slate-800">
                                    <img src="https://lh3.googleusercontent.com/d/1saiQE-yMBg9d0-LYzZGfiO62N6JLZ0Hv"
                                         onerror="handleDriveImageError(this, '1saiQE-yMBg9d0-LYzZGfiO62N6JLZ0Hv', 'https://images.unsplash.com/photo-1544620347-c4fd4a3d5957?auto=format&fit=crop&w=600&q=80')"
                                         alt="Đội xe Thuận Duyên Travel 1" class="w-full h-full object-cover">
                                </div>
                                <div class="rounded-lg overflow-hidden border-2 border-white/30 shadow-lg h-36 lg:h-40 bg-slate-800">
                                    <img src="https://lh3.googleusercontent.com/d/1Z67s5BnvlVsAC_ZO3g4iaDPG6Te6Pt-D"
                                         onerror="handleDriveImageError(this, '1Z67s5BnvlVsAC_ZO3g4iaDPG6Te6Pt-D', 'https://images.unsplash.com/photo-1570125909232-eb263c188f7e?auto=format&fit=crop&w=600&q=80')"
                                         alt="Đội xe Thuận Duyên Travel 2" class="w-full h-full object-cover">
                                </div>
                                <div class="rounded-lg overflow-hidden border-2 border-white/30 shadow-lg h-36 lg:h-40 bg-slate-800 col-span-2">
                                    <img src="https://lh3.googleusercontent.com/d/1PL0m9Mv4SPeZS6ETTm-389fj6xXcTyPu"
                                         onerror="handleDriveImageError(this, '1PL0m9Mv4SPeZS6ETTm-389fj6xXcTyPu', 'https://images.unsplash.com/photo-1549317661-bd32c8ce0db2?auto=format&fit=crop&w=900&q=80')"
                                         alt="Đội xe Thuận Duyên Travel 3" class="w-full h-full object-cover">
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Desktop Slide 2 (Kích thước bằng nhau tuyệt đối) -->
                    <div class="banner-slide-desktop absolute inset-0 transition-opacity duration-700 opacity-0 z-0">
                        <div class="w-full h-full bg-gradient-to-r from-[#08386e] via-[#0e57a4] to-[#062c56] grid grid-cols-12 items-center px-8 lg:px-14 py-6">
                            <div class="col-span-7 text-white pr-6 space-y-2.5">
                                <p class="text-amber-300 font-bold text-xs uppercase tracking-wider">
                                    ĐỘI XE DU LỊCH ĐỜI MỚI 4 – 7 – 16 – 29 – 35 – 45 CHỖ
                                </p>
                                <h2 class="font-heading font-extrabold text-xl lg:text-2xl xl:text-3xl leading-snug text-white">
                                    CHUYÊN TOUR ĐÀ NẴNG – HỘI AN – BÀ NÀ – HUẾ – SÂN BAY
                                </h2>
                                <p class="text-xs lg:text-sm text-slate-100 leading-relaxed max-w-xl">
                                    Cam kết xe sạch đẹp, máy lạnh mát sâu, đón đúng giờ tại Sân bay Đà Nẵng, khách sạn và các điểm tham quan miền Trung. Hỗ trợ hợp đồng VAT đầy đủ.
                                </p>
                                <div class="grid grid-cols-3 gap-2.5 pt-1 max-w-lg">
                                    <div class="bg-white/10 border border-white/15 rounded-lg p-2">
                                        <p class="font-bold text-amber-300 text-xs">Đưa Đón Sân Bay</p>
                                        <p class="text-[11px] text-white">Chỉ từ 150.000đ</p>
                                    </div>
                                    <div class="bg-white/10 border border-white/15 rounded-lg p-2">
                                        <p class="font-bold text-amber-300 text-xs">Đà Nẵng - Hội An</p>
                                        <p class="text-[11px] text-white">Trọn gói 1 & 2 chiều</p>
                                    </div>
                                    <div class="bg-white/10 border border-white/15 rounded-lg p-2">
                                        <p class="font-bold text-amber-300 text-xs">Đà Nẵng - Bà Nà</p>
                                        <p class="text-[11px] text-white">Đợi đoàn miễn phí</p>
                                    </div>
                                </div>
                                <div class="pt-2 flex items-center gap-3 text-xs">
                                    <a href="#bang-gia" class="bg-amber-400 hover:bg-amber-300 text-slate-900 font-extrabold px-4 py-2 rounded-lg shadow transition">
                                        <i class="fa-solid fa-tags mr-1.5"></i>XEM BẢNG GIÁ ƯU ĐÃI
                                    </a>
                                    <span class="text-slate-200 font-semibold">
                                        <i class="fa-solid fa-location-dot text-amber-300 mr-1"></i>Đ/c: H12/4 K78 Nguyễn Xuân Hữu, P. Cẩm Lệ, TP Đà Nẵng
                                    </span>
                                </div>
                            </div>
                            <div class="col-span-5 grid grid-cols-2 gap-2.5">
                                <div class="rounded-lg overflow-hidden border-2 border-white/30 shadow-lg h-36 lg:h-40 bg-slate-800">
                                    <img src="https://lh3.googleusercontent.com/d/1pkghUWyit5gUrTpXvEMLYRX-Wo8EfBzq"
                                         onerror="handleDriveImageError(this, '1pkghUWyit5gUrTpXvEMLYRX-Wo8EfBzq', 'https://images.unsplash.com/photo-1533473359331-0135ef1b58bf?auto=format&fit=crop&w=600&q=80')"
                                         alt="Xe du lịch Thuận Duyên 4" class="w-full h-full object-cover">
                                </div>
                                <div class="rounded-lg overflow-hidden border-2 border-white/30 shadow-lg h-36 lg:h-40 bg-slate-800">
                                    <img src="https://lh3.googleusercontent.com/d/1gOl4x1tden6n28j2AgM86ByrOAuWZIcU"
                                         onerror="handleDriveImageError(this, '1gOl4x1tden6n28j2AgM86ByrOAuWZIcU', 'https://images.unsplash.com/photo-1552519507-da3b142c6e3d?auto=format&fit=crop&w=600&q=80')"
                                         alt="Xe du lịch Thuận Duyên 5" class="w-full h-full object-cover">
                                </div>
                                <div class="rounded-lg overflow-hidden border-2 border-white/30 shadow-lg h-36 lg:h-40 bg-slate-800 col-span-2">
                                    <img src="https://lh3.googleusercontent.com/d/16UTPnS62O8lWmuPyjZWvg5-gWuLGfkDT"
                                         onerror="handleDriveImageError(this, '16UTPnS62O8lWmuPyjZWvg5-gWuLGfkDT', 'https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=900&q=80')"
                                         alt="Xe du lịch Thuận Duyên 6" class="w-full h-full object-cover">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- ====== BANNER THIẾT KẾ RIÊNG CHO ĐIỆN THOẠI (block md:hidden) - TỐI ƯU CHỮ NHỎ GỌN NẰM TRỌN TRONG KHUNG, KHÔNG TRÀN VIỀN ====== -->
                <div class="block md:hidden relative w-full h-[320px] sm:h-[340px]">
                    <!-- Mobile Slide 1 -->
                    <div class="banner-slide-mobile absolute inset-0 transition-opacity duration-700 opacity-100 z-10">
                        <div class="w-full h-full bg-gradient-to-b from-[#072f5f] via-[#0B4F94] to-[#073666] p-3.5 flex flex-col justify-between text-white">
                            <div class="space-y-1">
                                <p class="text-[10px] font-bold text-amber-300 uppercase tracking-wide">
                                    CÔNG TY TNHH THUẬN DUYÊN TRAVEL
                                </p>
                                <h2 class="font-heading font-extrabold text-[15px] leading-snug text-white">
                                    THUÊ XE DU LỊCH ĐÀ NẴNG UY TÍN – GIÁ RẺ
                                </h2>
                                <p class="text-[11px] text-slate-100 leading-snug">
                                    Chuyên xe 4 - 7 - 16 - 29 - 35 - 45 chỗ đời mới. Đưa đón Sân bay, Hội An, Bà Nà, Huế.
                                </p>
                            </div>
                            <div class="grid grid-cols-2 gap-2 my-1.5">
                                <div class="h-24 rounded-lg overflow-hidden border border-white/25 bg-slate-800">
                                    <img src="https://lh3.googleusercontent.com/d/1saiQE-yMBg9d0-LYzZGfiO62N6JLZ0Hv"
                                         onerror="handleDriveImageError(this, '1saiQE-yMBg9d0-LYzZGfiO62N6JLZ0Hv', 'https://images.unsplash.com/photo-1544620347-c4fd4a3d5957?auto=format&fit=crop&w=500&q=80')"
                                         alt="Ảnh nhà xe mobile 1" class="w-full h-full object-cover">
                                </div>
                                <div class="h-24 rounded-lg overflow-hidden border border-white/25 bg-slate-800">
                                    <img src="https://lh3.googleusercontent.com/d/1Z67s5BnvlVsAC_ZO3g4iaDPG6Te6Pt-D"
                                         onerror="handleDriveImageError(this, '1Z67s5BnvlVsAC_ZO3g4iaDPG6Te6Pt-D', 'https://images.unsplash.com/photo-1570125909232-eb263c188f7e?auto=format&fit=crop&w=500&q=80')"
                                         alt="Ảnh nhà xe mobile 2" class="w-full h-full object-cover">
                                </div>
                            </div>
                            <div class="bg-white/10 rounded-lg px-2.5 py-1.5 text-[10.5px] leading-tight space-y-0.5">
                                <p class="font-bold text-amber-300">Hotline/Zalo: 0988.399.855 • thuanduyentravel.com</p>
                                <p class="text-slate-100">Đ/c: H12/4 K78 Nguyễn Xuân Hữu, P. Cẩm Lệ, Đà Nẵng</p>
                            </div>
                        </div>
                    </div>

                    <!-- Mobile Slide 2 (Kích thước bằng nhau) -->
                    <div class="banner-slide-mobile absolute inset-0 transition-opacity duration-700 opacity-0 z-0">
                        <div class="w-full h-full bg-gradient-to-b from-[#08386e] via-[#0e57a4] to-[#062c56] p-3.5 flex flex-col justify-between text-white">
                            <div class="space-y-1">
                                <p class="text-[10px] font-bold text-amber-300 uppercase tracking-wide">
                                    ĐỘI XE ĐỜI MỚI – TÀI XẾ RÀNH ĐƯỜNG
                                </p>
                                <h2 class="font-heading font-extrabold text-[15px] leading-snug text-white">
                                    THUÊ XE ĐÀ NẴNG ĐI HỘI AN – BÀ NÀ – HUẾ
                                </h2>
                                <p class="text-[11px] text-slate-100 leading-snug">
                                    Thủ tục nhanh gọn trong 1 phút, giá minh bạch trọn gói, phục vụ 24/7.
                                </p>
                            </div>
                            <div class="grid grid-cols-2 gap-2 my-1.5">
                                <div class="h-24 rounded-lg overflow-hidden border border-white/25 bg-slate-800">
                                    <img src="https://lh3.googleusercontent.com/d/1PL0m9Mv4SPeZS6ETTm-389fj6xXcTyPu"
                                         onerror="handleDriveImageError(this, '1PL0m9Mv4SPeZS6ETTm-389fj6xXcTyPu', 'https://images.unsplash.com/photo-1549317661-bd32c8ce0db2?auto=format&fit=crop&w=500&q=80')"
                                         alt="Ảnh nhà xe mobile 3" class="w-full h-full object-cover">
                                </div>
                                <div class="h-24 rounded-lg overflow-hidden border border-white/25 bg-slate-800">
                                    <img src="https://lh3.googleusercontent.com/d/1pkghUWyit5gUrTpXvEMLYRX-Wo8EfBzq"
                                         onerror="handleDriveImageError(this, '1pkghUWyit5gUrTpXvEMLYRX-Wo8EfBzq', 'https://images.unsplash.com/photo-1533473359331-0135ef1b58bf?auto=format&fit=crop&w=500&q=80')"
                                         alt="Ảnh nhà xe mobile 4" class="w-full h-full object-cover">
                                </div>
                            </div>
                            <div class="bg-white/10 rounded-lg px-2.5 py-1.5 text-[10.5px] leading-tight space-y-0.5">
                                <p class="font-bold text-amber-300">Ưu Đãi Giảm Đến 20% Khi Đặt Trước</p>
                                <p class="text-slate-100">Gọi ngay: 0988.399.855 • H12/4 K78 Nguyễn Xuân Hữu</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng & chấm tròn chuyển Slide -->
                <button onclick="prevBannerSlide()" aria-label="Slide trước" class="absolute left-2 top-1/2 -translate-y-1/2 z-20 w-8 h-8 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button onclick="nextBannerSlide()" aria-label="Slide tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 z-20 w-8 h-8 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button onclick="goToBannerSlide(0)" id="bannerDot0" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
                    <button onclick="goToBannerSlide(1)" id="bannerDot1" class="w-2.5 h-2 rounded-full bg-white/50 transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= GIỚI THIỆU NGẮN GỌN (CHUẨN MẪU THUEXEHANA) ================= -->
    <section id="gioi-thieu" class="py-4">
        <div class="container-flatsome">
            <div class="bg-white rounded-xl p-4 md:p-6 shadow-sm border border-slate-200">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-center">
                    <div class="lg:col-span-7 space-y-2.5">
                        <span class="text-xs font-bold text-brand uppercase tracking-wider">GIỚI THIỆU VỀ CHÚNG TÔI</span>
                        <h2 class="font-heading font-bold text-lg md:text-xl text-slate-800">
                            Dịch Vụ Thuê Xe Thuận Duyên Travel – Thuê Xe 4 Chỗ, 7 Chỗ, 16 Chỗ, 29 Chỗ, 45 Chỗ Đà Nẵng
                        </h2>
                        <p class="text-xs md:text-sm text-slate-600 leading-relaxed">
                            <strong>CÔNG TY TNHH THUẬN DUYÊN TRAVEL</strong> (<a href="https://thuanduyentravel.com" class="text-brand font-semibold">thuanduyentravel.com</a>) là đơn vị chuyên cung cấp dịch vụ cho thuê xe du lịch chất lượng cao tại thành phố Đà Nẵng. Chúng tôi chuyên phục vụ thuê xe 4 chỗ, 7 chỗ, 16 chỗ, 18 chỗ, 29 chỗ, 35 chỗ, 45 chỗ, xe Limousine, xe cưới và hợp đồng đưa đón sân bay, tham quan Đà Nẵng – Hội An – Bà Nà Hills – Huế.
                        </p>
                        <p class="text-xs md:text-sm text-slate-600 leading-relaxed">
                            Quý khách có nhu cầu thuê xe du lịch tại Đà Nẵng xin liên hệ trực tiếp tại địa chỉ <strong>H12/4 K78 Nguyễn Xuân Hữu, Phường Cẩm Lệ, TP Đà Nẵng</strong> hoặc qua <strong>Hotline / Zalo: 0988.399.855</strong> để nhận báo giá ưu đãi nhất!
                        </p>
                        <div class="grid grid-cols-2 sm:grid-cols-4 gap-2.5 pt-2">
                            <div class="bg-slate-50 border border-slate-200 rounded-lg p-2.5 text-center">
                                <p class="font-heading font-extrabold text-brand text-sm md:text-base">100%</p>
                                <p class="text-[11px] text-slate-600">Xe Đời Mới Sạch Đẹp</p>
                            </div>
                            <div class="bg-slate-50 border border-slate-200 rounded-lg p-2.5 text-center">
                                <p class="font-heading font-extrabold text-brand text-sm md:text-base">Đúng Giờ</p>
                                <p class="text-[11px] text-slate-600">Đưa Đón Tận Nơi</p>
                            </div>
                            <div class="bg-slate-50 border border-slate-200 rounded-lg p-2.5 text-center">
                                <p class="font-heading font-extrabold text-brand text-sm md:text-base">Trọn Gói</p>
                                <p class="text-[11px] text-slate-600">Không Phí Ẩn</p>
                            </div>
                            <div class="bg-slate-50 border border-slate-200 rounded-lg p-2.5 text-center">
                                <p class="font-heading font-extrabold text-brand text-sm md:text-base">Hỗ Trợ 24/7</p>
                                <p class="text-[11px] text-slate-600">Tư Vấn Lịch Trình</p>
                            </div>
                        </div>
                    </div>
                    <div class="lg:col-span-5 grid grid-cols-2 gap-2.5">
                        <div class="rounded-lg overflow-hidden border border-slate-200 h-36 sm:h-44 bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/14BiC3_Hviw8ghdw02QBqbddXaPBXcSec"
                                 onerror="handleDriveImageError(this, '14BiC3_Hviw8ghdw02QBqbddXaPBXcSec', 'https://images.unsplash.com/photo-1544620347-c4fd4a3d5957?auto=format&fit=crop&w=600&q=80')"
                                 alt="Hình ảnh thực tế Thuận Duyên Travel" class="w-full h-full object-cover">
                        </div>
                        <div class="rounded-lg overflow-hidden border border-slate-200 h-36 sm:h-44 bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1U_qWMBHU4O2qFraO-tGs6qa6Den5WMXe"
                                 onerror="handleDriveImageError(this, '1U_qWMBHU4O2qFraO-tGs6qa6Den5WMXe', 'https://images.unsplash.com/photo-1570125909232-eb263c188f7e?auto=format&fit=crop&w=600&q=80')"
                                 alt="Hình ảnh đội xe Thuận Duyên Travel" class="w-full h-full object-cover">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= DANH MỤC SẢN PHẨM TRANG CHỦ 1: DỊCH VỤ ĐƯỢC CHỌN DÙNG NHIỀU NHẤT (CHỌN LOẠI XE) ================= -->
    <section id="chon-loai-xe" class="py-5">
        <div class="container-flatsome">
            <!-- Header Danh mục + Nút lọc danh mục chữ nhỏ gọn -->
            <div class="section-title-container">
                <div class="section-title-main flex-wrap gap-2">
                    <h2 class="font-heading font-extrabold text-base md:text-lg text-brand uppercase">
                        <i class="fa-solid fa-car-side mr-1.5"></i>DỊCH VỤ THUÊ XE ĐƯỢC CHỌN DÙNG NHIỀU NHẤT
                    </h2>
                    <!-- Các danh mục con chữ nhỏ gọn, viết liền không gãy dòng -->
                    <div class="flex flex-wrap items-center gap-1.5">
                        <button onclick="filterCategory('all')" data-cat-btn="all" class="cat-pill-btn bg-brand text-white text-[11.5px] font-semibold px-2.5 py-1 rounded whitespace-nowrap transition">
                            Tất cả loại xe
                        </button>
                        <button onclick="filterCategory('4-7-cho')" data-cat-btn="4-7-cho" class="cat-pill-btn bg-white hover:bg-slate-100 text-slate-700 border border-slate-200 text-[11.5px] font-semibold px-2.5 py-1 rounded whitespace-nowrap transition">
                            Xe 4 - 7 chỗ
                        </button>
                        <button onclick="filterCategory('16-18-cho')" data-cat-btn="16-18-cho" class="cat-pill-btn bg-white hover:bg-slate-100 text-slate-700 border border-slate-200 text-[11.5px] font-semibold px-2.5 py-1 rounded whitespace-nowrap transition">
                            Xe 16 - 18 chỗ
                        </button>
                        <button onclick="filterCategory('29-45-cho')" data-cat-btn="29-45-cho" class="cat-pill-btn bg-white hover:bg-slate-100 text-slate-700 border border-slate-200 text-[11.5px] font-semibold px-2.5 py-1 rounded whitespace-nowrap transition">
                            Xe 29 - 35 - 45 chỗ
                        </button>
                        <button onclick="filterCategory('vip-limousine')" data-cat-btn="vip-limousine" class="cat-pill-btn bg-white hover:bg-slate-100 text-slate-700 border border-slate-200 text-[11.5px] font-semibold px-2.5 py-1 rounded whitespace-nowrap transition">
                            Xe VIP / Limousine / Cưới
                        </button>
                    </div>
                </div>
            </div>

            <!-- LƯỚI SẢN PHẨM: 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4) -->
            <!-- Có % giảm giá góc trên bên trái chuẩn Flatsome, tên sản phẩm đầy đủ không tràn không mất chữ -->
            <div id="vehicleProductGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">

                <!-- Sản phẩm 1 (Ảnh thực tế 1) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="4-7-cho">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-17%</span>
                        <img src="https://lh3.googleusercontent.com/d/1pTucDZnY7hLh7G-zsPEJ_2yg2CaH_Kwt"
                             onerror="handleDriveImageError(this, '1pTucDZnY7hLh7G-zsPEJ_2yg2CaH_Kwt', 'https://images.unsplash.com/photo-1549317661-bd32c8ce0db2?auto=format&fit=crop&w=600&q=80')"
                             alt="Thuê xe 4 chỗ Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-400 font-medium uppercase">Chọn loại xe</p>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800 hover:text-brand mt-0.5">
                                Thuê xe 4 chỗ Đà Nẵng (Mazda 3, Vios, Accent đời mới)
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">300.000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-rose-600">250.000₫</span>
                            </div>
                            <button onclick="selectVehicleForQuote('Thuê xe 4 chỗ Đà Nẵng')" class="mt-2 w-full bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded-lg transition">
                                Đặt Xe Ngay
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 2 (Ảnh thực tế 2) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="4-7-cho">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-18%</span>
                        <img src="https://lh3.googleusercontent.com/d/1bXIu3Hl4TReZQUYAh_5bOWz_1ng4se2z"
                             onerror="handleDriveImageError(this, '1bXIu3Hl4TReZQUYAh_5bOWz_1ng4se2z', 'https://images.unsplash.com/photo-1533473359331-0135ef1b58bf?auto=format&fit=crop&w=600&q=80')"
                             alt="Thuê xe 7 chỗ Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-400 font-medium uppercase">Chọn loại xe</p>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800 hover:text-brand mt-0.5">
                                Thuê xe 7 chỗ Đà Nẵng (Xpander, Innova, Fortuner)
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">360.000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-rose-600">300.000₫</span>
                            </div>
                            <button onclick="selectVehicleForQuote('Thuê xe 7 chỗ Đà Nẵng')" class="mt-2 w-full bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded-lg transition">
                                Đặt Xe Ngay
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 3 (Ảnh thực tế 3) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="16-18-cho">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-20%</span>
                        <img src="https://lh3.googleusercontent.com/d/1d_zqwjXMzmVNcmNRqR7c5aEREzqbRTs0"
                             onerror="handleDriveImageError(this, '1d_zqwjXMzmVNcmNRqR7c5aEREzqbRTs0', 'https://images.unsplash.com/photo-1544620347-c4fd4a3d5957?auto=format&fit=crop&w=600&q=80')"
                             alt="Thuê xe 16 chỗ Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-400 font-medium uppercase">Chọn loại xe</p>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800 hover:text-brand mt-0.5">
                                Thuê xe 16 chỗ Đà Nẵng (Ford Transit, Hyundai Solati)
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">500.000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-rose-600">400.000₫</span>
                            </div>
                            <button onclick="selectVehicleForQuote('Thuê xe 16 chỗ Đà Nẵng')" class="mt-2 w-full bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded-lg transition">
                                Đặt Xe Ngay
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 4 (Ảnh thực tế nhà xe 1) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="16-18-cho">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-15%</span>
                        <img src="https://lh3.googleusercontent.com/d/1saiQE-yMBg9d0-LYzZGfiO62N6JLZ0Hv"
                             onerror="handleDriveImageError(this, '1saiQE-yMBg9d0-LYzZGfiO62N6JLZ0Hv', 'https://images.unsplash.com/photo-1570125909232-eb263c188f7e?auto=format&fit=crop&w=600&q=80')"
                             alt="Thuê xe 18 chỗ Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-400 font-medium uppercase">Chọn loại xe</p>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800 hover:text-brand mt-0.5">
                                Thuê xe 18 chỗ Đà Nẵng Ford Transit New rộng rãi
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">650.000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-rose-600">550.000₫</span>
                            </div>
                            <button onclick="selectVehicleForQuote('Thuê xe 18 chỗ Đà Nẵng')" class="mt-2 w-full bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded-lg transition">
                                Đặt Xe Ngay
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 5 (Ảnh thực tế nhà xe 2) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="29-45-cho">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-20%</span>
                        <img src="https://lh3.googleusercontent.com/d/1Z67s5BnvlVsAC_ZO3g4iaDPG6Te6Pt-D"
                             onerror="handleDriveImageError(this, '1Z67s5BnvlVsAC_ZO3g4iaDPG6Te6Pt-D', 'https://images.unsplash.com/photo-1544620347-c4fd4a3d5957?auto=format&fit=crop&w=600&q=80')"
                             alt="Thuê xe 29 chỗ Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-400 font-medium uppercase">Chọn loại xe</p>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800 hover:text-brand mt-0.5">
                                Thuê xe 29 chỗ Đà Nẵng (Thaco Town, Hyundai County)
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">1.500.000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-rose-600">1.200.000₫</span>
                            </div>
                            <button onclick="selectVehicleForQuote('Thuê xe 29 chỗ Đà Nẵng')" class="mt-2 w-full bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded-lg transition">
                                Đặt Xe Ngay
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 6 (Ảnh thực tế nhà xe 3) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="29-45-cho">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-16%</span>
                        <img src="https://lh3.googleusercontent.com/d/1PL0m9Mv4SPeZS6ETTm-389fj6xXcTyPu"
                             onerror="handleDriveImageError(this, '1PL0m9Mv4SPeZS6ETTm-389fj6xXcTyPu', 'https://images.unsplash.com/photo-1570125909232-eb263c188f7e?auto=format&fit=crop&w=600&q=80')"
                             alt="Thuê xe 35 chỗ Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-400 font-medium uppercase">Chọn loại xe</p>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800 hover:text-brand mt-0.5">
                                Thuê xe 35 chỗ Đà Nẵng (Thaco Meadow, Samco Felix)
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">1.800.000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-rose-600">1.500.000₫</span>
                            </div>
                            <button onclick="selectVehicleForQuote('Thuê xe 35 chỗ Đà Nẵng')" class="mt-2 w-full bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded-lg transition">
                                Đặt Xe Ngay
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 7 (Ảnh thực tế nhà xe 4) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="29-45-cho">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-18%</span>
                        <img src="https://lh3.googleusercontent.com/d/1pkghUWyit5gUrTpXvEMLYRX-Wo8EfBzq"
                             onerror="handleDriveImageError(this, '1pkghUWyit5gUrTpXvEMLYRX-Wo8EfBzq', 'https://images.unsplash.com/photo-1544620347-c4fd4a3d5957?auto=format&fit=crop&w=600&q=80')"
                             alt="Thuê xe 45 chỗ Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-400 font-medium uppercase">Chọn loại xe</p>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800 hover:text-brand mt-0.5">
                                Thuê xe 45 chỗ Đà Nẵng Hyundai Universe cao cấp
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">2.200.000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-rose-600">1.800.000₫</span>
                            </div>
                            <button onclick="selectVehicleForQuote('Thuê xe 45 chỗ Đà Nẵng')" class="mt-2 w-full bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded-lg transition">
                                Đặt Xe Ngay
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 8 (Ảnh thực tế nhà xe 5) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="vip-limousine">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-15%</span>
                        <img src="https://lh3.googleusercontent.com/d/1gOl4x1tden6n28j2AgM86ByrOAuWZIcU"
                             onerror="handleDriveImageError(this, '1gOl4x1tden6n28j2AgM86ByrOAuWZIcU', 'https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=600&q=80')"
                             alt="Thuê xe Limousine Carnival Sedona Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-400 font-medium uppercase">Dịch vụ VIP</p>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800 hover:text-brand mt-0.5">
                                Thuê xe Limousine 9 chỗ, Kia Carnival & Sedona Đà Nẵng
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">1.400.000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-rose-600">1.200.000₫</span>
                            </div>
                            <button onclick="selectVehicleForQuote('Thuê xe Limousine / Carnival Đà Nẵng')" class="mt-2 w-full bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded-lg transition">
                                Đặt Xe Ngay
                            </button>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ================= DANH MỤC SẢN PHẨM TRANG CHỦ 2: THUÊ XE DU LỊCH TẠI ĐÀ NẴNG (THEO TUYẾN ĐIỂM) ================= -->
    <section id="thue-xe-tuyen-duong" class="py-5">
        <div class="container-flatsome">
            <div class="section-title-container">
                <div class="section-title-main flex-wrap gap-2">
                    <h2 class="font-heading font-extrabold text-base md:text-lg text-brand uppercase">
                        <i class="fa-solid fa-route mr-1.5"></i>THUÊ XE DU LỊCH TẠI ĐÀ NẴNG ĐI CÁC ĐIỂM NỔI TIẾNG
                    </h2>
                    <span class="text-xs text-slate-500 font-medium">Giá trọn gói 1 chiều & khứ hồi • Đưa đón tận nơi</span>
                </div>
            </div>

            <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">

                <!-- Tuyến 1 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-20%</span>
                        <img src="https://lh3.googleusercontent.com/d/16UTPnS62O8lWmuPyjZWvg5-gWuLGfkDT"
                             onerror="handleDriveImageError(this, '16UTPnS62O8lWmuPyjZWvg5-gWuLGfkDT', 'https://images.unsplash.com/photo-1559592413-7cec4d0cae2b?auto=format&fit=crop&w=600&q=80')"
                             alt="Thuê xe Đà Nẵng đi Hội An" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-400 font-medium uppercase">Tuyến Đà Nẵng</p>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800 hover:text-brand mt-0.5">
                                Thuê xe Đà Nẵng đi Hội An (1 chiều & 2 chiều khứ hồi)
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">350.000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-rose-600">280.000₫</span>
                            </div>
                            <button onclick="selectVehicleForQuote('Thuê xe Đà Nẵng đi Hội An')" class="mt-2 w-full bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded-lg transition">
                                Nhận Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Tuyến 2 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-18%</span>
                        <img src="https://lh3.googleusercontent.com/d/14BiC3_Hviw8ghdw02QBqbddXaPBXcSec"
                             onerror="handleDriveImageError(this, '14BiC3_Hviw8ghdw02QBqbddXaPBXcSec', 'https://images.unsplash.com/photo-1583417319070-4a69db38a482?auto=format&fit=crop&w=600&q=80')"
                             alt="Thuê xe Đà Nẵng đi Bà Nà Hills" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-400 font-medium uppercase">Tuyến Đà Nẵng</p>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800 hover:text-brand mt-0.5">
                                Thuê xe Đà Nẵng đi Bà Nà Hills trọn gói đưa đón tận nơi
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">420.000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-rose-600">350.000₫</span>
                            </div>
                            <button onclick="selectVehicleForQuote('Thuê xe Đà Nẵng đi Bà Nà Hills')" class="mt-2 w-full bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded-lg transition">
                                Nhận Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Tuyến 3 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-15%</span>
                        <img src="https://lh3.googleusercontent.com/d/1U_qWMBHU4O2qFraO-tGs6qa6Den5WMXe"
                             onerror="handleDriveImageError(this, '1U_qWMBHU4O2qFraO-tGs6qa6Den5WMXe', 'https://images.unsplash.com/photo-1555921015-5532091f6026?auto=format&fit=crop&w=600&q=80')"
                             alt="Thuê xe Đà Nẵng đi Núi Thần Tài" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-400 font-medium uppercase">Tuyến Đà Nẵng</p>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800 hover:text-brand mt-0.5">
                                Thuê xe Đà Nẵng đi Núi Thần Tài – Hòa Phú Thành – Ngầm Đôi
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">750.000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-rose-600">650.000₫</span>
                            </div>
                            <button onclick="selectVehicleForQuote('Thuê xe Đà Nẵng đi Núi Thần Tài')" class="mt-2 w-full bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded-lg transition">
                                Nhận Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Tuyến 4 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-20%</span>
                        <img src="https://lh3.googleusercontent.com/d/1Setz60zZwRn3108dhggT6O927qYHhej5"
                             onerror="handleDriveImageError(this, '1Setz60zZwRn3108dhggT6O927qYHhej5', 'https://images.unsplash.com/photo-1509023464722-18d996393ca8?auto=format&fit=crop&w=600&q=80')"
                             alt="Thuê xe Đà Nẵng đi Huế" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-400 font-medium uppercase">Tuyến Đà Nẵng</p>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800 hover:text-brand mt-0.5">
                                Thuê xe Đà Nẵng đi Cố Đô Huế – Lăng Cô – Đèo Hải Vân
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">1.250.000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-rose-600">1.000.000₫</span>
                            </div>
                            <button onclick="selectVehicleForQuote('Thuê xe Đà Nẵng đi Huế')" class="mt-2 w-full bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded-lg transition">
                                Nhận Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Tuyến 5 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-16%</span>
                        <img src="https://lh3.googleusercontent.com/d/1pTucDZnY7hLh7G-zsPEJ_2yg2CaH_Kwt"
                             onerror="handleDriveImageError(this, '1pTucDZnY7hLh7G-zsPEJ_2yg2CaH_Kwt', 'https://images.unsplash.com/photo-1549317661-bd32c8ce0db2?auto=format&fit=crop&w=600&q=80')"
                             alt="Thuê xe Đà Nẵng đi Vinpearl Nam Hội An" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-400 font-medium uppercase">Tuyến Đà Nẵng</p>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800 hover:text-brand mt-0.5">
                                Thuê xe Đà Nẵng đi Vinpearl Nam Hội An (VinWonders)
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">600.000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-rose-600">500.000₫</span>
                            </div>
                            <button onclick="selectVehicleForQuote('Thuê xe Đà Nẵng đi Vinpearl Nam Hội An')" class="mt-2 w-full bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded-lg transition">
                                Nhận Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Tuyến 6 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-17%</span>
                        <img src="https://lh3.googleusercontent.com/d/1bXIu3Hl4TReZQUYAh_5bOWz_1ng4se2z"
                             onerror="handleDriveImageError(this, '1bXIu3Hl4TReZQUYAh_5bOWz_1ng4se2z', 'https://images.unsplash.com/photo-1533473359331-0135ef1b58bf?auto=format&fit=crop&w=600&q=80')"
                             alt="Thuê xe Đà Nẵng đi Thánh Địa Mỹ Sơn" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-400 font-medium uppercase">Tuyến Đà Nẵng</p>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800 hover:text-brand mt-0.5">
                                Thuê xe Đà Nẵng đi Thánh Địa Mỹ Sơn kết hợp Hội An
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">850.000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-rose-600">700.000₫</span>
                            </div>
                            <button onclick="selectVehicleForQuote('Thuê xe Đà Nẵng đi Mỹ Sơn')" class="mt-2 w-full bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded-lg transition">
                                Nhận Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Tuyến 7 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-18%</span>
                        <img src="https://lh3.googleusercontent.com/d/1d_zqwjXMzmVNcmNRqR7c5aEREzqbRTs0"
                             onerror="handleDriveImageError(this, '1d_zqwjXMzmVNcmNRqR7c5aEREzqbRTs0', 'https://images.unsplash.com/photo-1544620347-c4fd4a3d5957?auto=format&fit=crop&w=600&q=80')"
                             alt="Thuê xe Đà Nẵng đi Cù Lao Chàm" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-400 font-medium uppercase">Tuyến Đà Nẵng</p>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800 hover:text-brand mt-0.5">
                                Thuê xe Đà Nẵng đi Cảng Cửa Đại – Cù Lao Chàm
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">680.000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-rose-600">550.000₫</span>
                            </div>
                            <button onclick="selectVehicleForQuote('Thuê xe Đà Nẵng đi Cù Lao Chàm')" class="mt-2 w-full bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded-lg transition">
                                Nhận Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Tuyến 8 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-25%</span>
                        <img src="https://lh3.googleusercontent.com/d/1saiQE-yMBg9d0-LYzZGfiO62N6JLZ0Hv"
                             onerror="handleDriveImageError(this, '1saiQE-yMBg9d0-LYzZGfiO62N6JLZ0Hv', 'https://images.unsplash.com/photo-1570125909232-eb263c188f7e?auto=format&fit=crop&w=600&q=80')"
                             alt="Thuê xe đưa đón sân bay Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-400 font-medium uppercase">Đưa đón sân bay</p>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800 hover:text-brand mt-0.5">
                                Thuê xe đưa đón Sân Bay Đà Nẵng về Khách Sạn & Resort
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">200.000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-rose-600">150.000₫</span>
                            </div>
                            <button onclick="selectVehicleForQuote('Thuê xe đưa đón Sân Bay Đà Nẵng')" class="mt-2 w-full bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded-lg transition">
                                Nhận Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ================= HÌNH ẢNH THỰC TẾ ĐỘI XE NHÀ XE THUẬN DUYÊN TRAVEL (TRỌN BỘ 8 ẢNH NHÀ XE + 4 ẢNH SẢN PHẨM) ================= -->
    <section id="hinh-anh-nha-xe" class="py-5">
        <div class="container-flatsome">
            <div class="section-title-container">
                <div class="section-title-main flex-wrap gap-2">
                    <h2 class="font-heading font-extrabold text-base md:text-lg text-brand uppercase">
                        <i class="fa-solid fa-camera-retro mr-1.5"></i>HÌNH ẢNH THỰC TẾ ĐỘI XE NHÀ XE THUẬN DUYÊN TRAVEL
                    </h2>
                    <span class="text-xs text-slate-500 font-medium">Cam kết 100% hình ảnh xe thực tế của công ty phục vụ quý khách</span>
                </div>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
                <!-- Ảnh nhà xe 1 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm">
                    <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1saiQE-yMBg9d0-LYzZGfiO62N6JLZ0Hv"
                             onerror="handleDriveImageError(this, '1saiQE-yMBg9d0-LYzZGfiO62N6JLZ0Hv', 'https://images.unsplash.com/photo-1544620347-c4fd4a3d5957?auto=format&fit=crop&w=600&q=80')"
                             alt="Ảnh thực tế nhà xe Thuận Duyên 1" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="product-title-full text-xs font-bold text-slate-700">Đội xe du lịch Thuận Duyên Travel phục vụ đoàn</p>
                    </div>
                </div>

                <!-- Ảnh nhà xe 2 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm">
                    <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1Z67s5BnvlVsAC_ZO3g4iaDPG6Te6Pt-D"
                             onerror="handleDriveImageError(this, '1Z67s5BnvlVsAC_ZO3g4iaDPG6Te6Pt-D', 'https://images.unsplash.com/photo-1570125909232-eb263c188f7e?auto=format&fit=crop&w=600&q=80')"
                             alt="Ảnh thực tế nhà xe Thuận Duyên 2" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="product-title-full text-xs font-bold text-slate-700">Xe du lịch đời mới đón khách tại Đà Nẵng</p>
                    </div>
                </div>

                <!-- Ảnh nhà xe 3 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm">
                    <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1PL0m9Mv4SPeZS6ETTm-389fj6xXcTyPu"
                             onerror="handleDriveImageError(this, '1PL0m9Mv4SPeZS6ETTm-389fj6xXcTyPu', 'https://images.unsplash.com/photo-1549317661-bd32c8ce0db2?auto=format&fit=crop&w=600&q=80')"
                             alt="Ảnh thực tế nhà xe Thuận Duyên 3" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="product-title-full text-xs font-bold text-slate-700">Xe hợp đồng tham quan Bà Nà Hills – Hội An</p>
                    </div>
                </div>

                <!-- Ảnh nhà xe 4 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm">
                    <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1pkghUWyit5gUrTpXvEMLYRX-Wo8EfBzq"
                             onerror="handleDriveImageError(this, '1pkghUWyit5gUrTpXvEMLYRX-Wo8EfBzq', 'https://images.unsplash.com/photo-1533473359331-0135ef1b58bf?auto=format&fit=crop&w=600&q=80')"
                             alt="Ảnh thực tế nhà xe Thuận Duyên 4" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="product-title-full text-xs font-bold text-slate-700">Dòng xe 16 - 29 - 45 chỗ chất lượng cao</p>
                    </div>
                </div>

                <!-- Ảnh nhà xe 5 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm">
                    <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1gOl4x1tden6n28j2AgM86ByrOAuWZIcU"
                             onerror="handleDriveImageError(this, '1gOl4x1tden6n28j2AgM86ByrOAuWZIcU', 'https://images.unsplash.com/photo-1552519507-da3b142c6e3d?auto=format&fit=crop&w=600&q=80')"
                             alt="Ảnh thực tế nhà xe Thuận Duyên 5" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="product-title-full text-xs font-bold text-slate-700">Nội thất & ngoại thất xe luôn vệ sinh sạch mới</p>
                    </div>
                </div>

                <!-- Ảnh nhà xe 6 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm">
                    <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/16UTPnS62O8lWmuPyjZWvg5-gWuLGfkDT"
                             onerror="handleDriveImageError(this, '16UTPnS62O8lWmuPyjZWvg5-gWuLGfkDT', 'https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=600&q=80')"
                             alt="Ảnh thực tế nhà xe Thuận Duyên 6" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="product-title-full text-xs font-bold text-slate-700">Đội xe đưa đón sân bay Đà Nẵng chuyên nghiệp</p>
                    </div>
                </div>

                <!-- Ảnh nhà xe 7 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm">
                    <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/14BiC3_Hviw8ghdw02QBqbddXaPBXcSec"
                             onerror="handleDriveImageError(this, '14BiC3_Hviw8ghdw02QBqbddXaPBXcSec', 'https://images.unsplash.com/photo-1544620347-c4fd4a3d5957?auto=format&fit=crop&w=600&q=80')"
                             alt="Ảnh thực tế nhà xe Thuận Duyên 7" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="product-title-full text-xs font-bold text-slate-700">Xe du lịch Thuận Duyên phục vụ tour miền Trung</p>
                    </div>
                </div>

                <!-- Ảnh nhà xe 8 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm">
                    <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1U_qWMBHU4O2qFraO-tGs6qa6Den5WMXe"
                             onerror="handleDriveImageError(this, '1U_qWMBHU4O2qFraO-tGs6qa6Den5WMXe', 'https://images.unsplash.com/photo-1570125909232-eb263c188f7e?auto=format&fit=crop&w=600&q=80')"
                             alt="Ảnh thực tế nhà xe Thuận Duyên 8" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="product-title-full text-xs font-bold text-slate-700">Đội ngũ lái xe nhiệt tình, giàu kinh nghiệm</p>
                    </div>
                </div>

                <!-- Ảnh sản phẩm thực tế 9 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm">
                    <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1pTucDZnY7hLh7G-zsPEJ_2yg2CaH_Kwt"
                             onerror="handleDriveImageError(this, '1pTucDZnY7hLh7G-zsPEJ_2yg2CaH_Kwt', 'https://images.unsplash.com/photo-1549317661-bd32c8ce0db2?auto=format&fit=crop&w=600&q=80')"
                             alt="Ảnh sản phẩm thực tế 1" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="product-title-full text-xs font-bold text-slate-700">Xe 4 - 7 chỗ gia đình đời mới tại Đà Nẵng</p>
                    </div>
                </div>

                <!-- Ảnh sản phẩm thực tế 10 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm">
                    <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1bXIu3Hl4TReZQUYAh_5bOWz_1ng4se2z"
                             onerror="handleDriveImageError(this, '1bXIu3Hl4TReZQUYAh_5bOWz_1ng4se2z', 'https://images.unsplash.com/photo-1533473359331-0135ef1b58bf?auto=format&fit=crop&w=600&q=80')"
                             alt="Ảnh sản phẩm thực tế 2" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="product-title-full text-xs font-bold text-slate-700">Xe hợp đồng công tác, hội nghị Đà Nẵng</p>
                    </div>
                </div>

                <!-- Ảnh sản phẩm thực tế 11 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm">
                    <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1d_zqwjXMzmVNcmNRqR7c5aEREzqbRTs0"
                             onerror="handleDriveImageError(this, '1d_zqwjXMzmVNcmNRqR7c5aEREzqbRTs0', 'https://images.unsplash.com/photo-1544620347-c4fd4a3d5957?auto=format&fit=crop&w=600&q=80')"
                             alt="Ảnh sản phẩm thực tế 3" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="product-title-full text-xs font-bold text-slate-700">Xe 16 chỗ Ford Transit & Hyundai Solati</p>
                    </div>
                </div>

                <!-- Ảnh thương hiệu 12 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm">
                    <div class="aspect-[4/3] bg-white overflow-hidden flex items-center justify-center p-3">
                        <img src="https://lh3.googleusercontent.com/d/1Setz60zZwRn3108dhggT6O927qYHhej5"
                             onerror="handleDriveImageError(this, '1Setz60zZwRn3108dhggT6O927qYHhej5', 'https://placehold.co/400x300/0B4F94/FFFFFF?text=THUAN+DUYEN+TRAVEL')"
                             alt="Logo Công Ty TNHH Thuận Duyên Travel" class="w-full h-full object-contain">
                    </div>
                    <div class="p-2.5 text-center bg-slate-50">
                        <p class="product-title-full text-xs font-bold text-brand">Thương hiệu Thuận Duyên Travel Uy Tín</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= DANH MỤC SẢN PHẨM 3: DỊCH VỤ THUÊ XE KHÁC TẠI ĐÀ NẴNG (CHUẨN WEB MẪU THUEXEHANA) ================= -->
    <section id="dich-vu-khac" class="py-5">
        <div class="container-flatsome">
            <div class="section-title-container">
                <div class="section-title-main flex-wrap gap-2">
                    <h2 class="font-heading font-extrabold text-base md:text-lg text-brand uppercase">
                        <i class="fa-solid fa-star mr-1.5"></i>DỊCH VỤ THUÊ XE HỢP ĐỒNG – XE CƯỚI – XE VIP TẠI ĐÀ NẴNG
                    </h2>
                    <span class="text-xs text-slate-500 font-medium">Hợp đồng linh hoạt theo ngày, theo tháng, xuất hóa đơn VAT</span>
                </div>
            </div>

            <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-15%</span>
                        <img src="https://lh3.googleusercontent.com/d/1gOl4x1tden6n28j2AgM86ByrOAuWZIcU"
                             onerror="handleDriveImageError(this, '1gOl4x1tden6n28j2AgM86ByrOAuWZIcU', 'https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=600&q=80')"
                             alt="Thuê xe cưới Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800">
                            Thuê xe cưới hỏi Đà Nẵng – Xe hoa sang trọng đời mới
                        </h3>
                        <div class="mt-2 pt-2 border-t border-slate-100">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">1.200.000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-rose-600">1.000.000₫</span>
                            </div>
                            <button onclick="selectVehicleForQuote('Thuê xe cưới Đà Nẵng')" class="mt-2 w-full bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded-lg transition">
                                Tư Vấn Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-20%</span>
                        <img src="https://lh3.googleusercontent.com/d/16UTPnS62O8lWmuPyjZWvg5-gWuLGfkDT"
                             onerror="handleDriveImageError(this, '16UTPnS62O8lWmuPyjZWvg5-gWuLGfkDT', 'https://images.unsplash.com/photo-1549317661-bd32c8ce0db2?auto=format&fit=crop&w=600&q=80')"
                             alt="Thuê xe dự án Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800">
                            Thuê xe dự án Đà Nẵng – Hợp đồng dài hạn theo tháng
                        </h3>
                        <div class="mt-2 pt-2 border-t border-slate-100">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">1.100.000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-rose-600">880.000₫</span>
                            </div>
                            <button onclick="selectVehicleForQuote('Thuê xe dự án Đà Nẵng')" class="mt-2 w-full bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded-lg transition">
                                Tư Vấn Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-18%</span>
                        <img src="https://lh3.googleusercontent.com/d/1Z67s5BnvlVsAC_ZO3g4iaDPG6Te6Pt-D"
                             onerror="handleDriveImageError(this, '1Z67s5BnvlVsAC_ZO3g4iaDPG6Te6Pt-D', 'https://images.unsplash.com/photo-1544620347-c4fd4a3d5957?auto=format&fit=crop&w=600&q=80')"
                             alt="Thuê xe đưa đón công nhân Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800">
                            Thuê xe đưa đón công nhân, chuyên gia khu công nghiệp
                        </h3>
                        <div class="mt-2 pt-2 border-t border-slate-100">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">950.000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-rose-600">780.000₫</span>
                            </div>
                            <button onclick="selectVehicleForQuote('Thuê xe đưa đón công nhân Đà Nẵng')" class="mt-2 w-full bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded-lg transition">
                                Tư Vấn Báo Giá
                            </button>
                        </div>
                    </div>
                </div>

                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-18%</span>
                        <img src="https://lh3.googleusercontent.com/d/1PL0m9Mv4SPeZS6ETTm-389fj6xXcTyPu"
                             onerror="handleDriveImageError(this, '1PL0m9Mv4SPeZS6ETTm-389fj6xXcTyPu', 'https://images.unsplash.com/photo-1570125909232-eb263c188f7e?auto=format&fit=crop&w=600&q=80')"
                             alt="Thuê xe đưa đón học sinh Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800">
                            Thuê xe đưa đón học sinh & tham quan dã ngoại trường học
                        </h3>
                        <div class="mt-2 pt-2 border-t border-slate-100">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <span class="text-[11px] text-slate-400 line-through">850.000₫</span>
                                <span class="text-xs sm:text-sm font-extrabold text-rose-600">700.000₫</span>
                            </div>
                            <button onclick="selectVehicleForQuote('Thuê xe đưa đón học sinh Đà Nẵng')" class="mt-2 w-full bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded-lg transition">
                                Tư Vấn Báo Giá
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= BẢNG GIÁ THUÊ XE DU LỊCH TẠI ĐÀ NẴNG ================= -->
    <section id="bang-gia" class="py-5">
        <div class="container-flatsome">
            <div class="section-title-container">
                <div class="section-title-main flex-wrap gap-2">
                    <h2 class="font-heading font-extrabold text-base md:text-lg text-brand uppercase">
                        <i class="fa-solid fa-table-list mr-1.5"></i>BẢNG GIÁ THUÊ XE DU LỊCH ĐÀ NẴNG THAM KHẢO
                    </h2>
                    <span class="text-xs text-slate-500 font-medium">Đã bao gồm lương tài xế, xăng dầu, phí cầu đường</span>
                </div>
            </div>

            <div class="bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden">
                <div class="overflow-x-auto">
                    <table class="w-full text-left border-collapse text-xs sm:text-sm">
                        <thead>
                            <tr class="bg-brand text-white">
                                <th class="py-3 px-3 font-bold">Lịch Trình Tuyến Đường Phổ Biến</th>
                                <th class="py-3 px-2.5 font-bold text-center whitespace-nowrap">Xe 4 Chỗ</th>
                                <th class="py-3 px-2.5 font-bold text-center whitespace-nowrap">Xe 7 Chỗ</th>
                                <th class="py-3 px-2.5 font-bold text-center whitespace-nowrap">Xe 16 Chỗ</th>
                                <th class="py-3 px-2.5 font-bold text-center whitespace-nowrap">Xe 29 - 45 Chỗ</th>
                            </tr>
                        </thead>
                        <tbody class="divide-y divide-slate-200 text-slate-700">
                            <tr class="hover:bg-slate-50">
                                <td class="py-2.5 px-3 font-semibold">Đón / Tiễn Sân bay Đà Nẵng về Khách sạn nội thành</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-rose-600">150.000₫</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-rose-600">200.000₫</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-rose-600">350.000₫</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-brand">700.000₫</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="py-2.5 px-3 font-semibold">Đà Nẵng – Phố cổ Hội An (1 chiều)</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-rose-600">250.000₫</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-rose-600">300.000₫</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-rose-600">400.000₫</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-brand">900.000₫</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="py-2.5 px-3 font-semibold">Đà Nẵng – Ngũ Hành Sơn – Hội An (Khứ hồi 2 chiều)</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-rose-600">550.000₫</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-rose-600">650.000₫</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-rose-600">850.000₫</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-brand">1.500.000₫</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="py-2.5 px-3 font-semibold">Đà Nẵng – Bà Nà Hills (Khứ hồi 2 chiều trong ngày)</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-rose-600">600.000₫</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-rose-600">700.000₫</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-rose-600">950.000₫</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-brand">1.700.000₫</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="py-2.5 px-3 font-semibold">Đà Nẵng – Suối khoáng nóng Núi Thần Tài (Khứ hồi)</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-rose-600">650.000₫</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-rose-600">750.000₫</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-rose-600">1.000.000₫</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-brand">1.800.000₫</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="py-2.5 px-3 font-semibold">Đà Nẵng – Vinpearl Nam Hội An / Thánh địa Mỹ Sơn (Khứ hồi)</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-rose-600">700.000₫</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-rose-600">800.000₫</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-rose-600">1.100.000₫</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-brand">1.900.000₫</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="py-2.5 px-3 font-semibold">Đà Nẵng – Cố đô Huế tham quan 1 ngày (Khứ hồi)</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-rose-600">1.300.000₫</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-rose-600">1.450.000₫</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-rose-600">1.900.000₫</td>
                                <td class="py-2.5 px-2.5 text-center font-bold text-brand">3.200.000₫</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ + KẾT NỐI FACEBOOK & GOOGLE MAPS NGOÀI TRANG CHỦ ================= -->
    <section id="bao-gia-nhanh" class="py-5">
        <div class="container-flatsome">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5">

                <!-- Cột Form Yêu Cầu & Báo Giá Nhanh -->
                <div class="lg:col-span-6 bg-white rounded-xl border border-slate-200 p-4 sm:p-6 shadow-sm">
                    <div class="section-title-container mb-4">
                        <div class="section-title-main">
                            <h2 class="font-heading font-extrabold text-base md:text-lg text-brand uppercase">
                                <i class="fa-solid fa-file-signature mr-1.5"></i>ĐĂNG KÝ YÊU CẦU & NHẬN BÁO GIÁ THUÊ XE
                            </h2>
                        </div>
                    </div>
                    <p class="text-xs text-slate-600 mb-4">
                        Quý khách vui lòng điền thông tin lịch trình dưới đây. Bộ phận điều hành <strong>CÔNG TY TNHH THUẬN DUYÊN TRAVEL</strong> sẽ liên hệ báo giá tốt nhất ngay lập tức!
                    </p>

                    <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="space-y-3 text-xs sm:text-sm">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block font-bold text-slate-700 mb-1">Họ và tên quý khách *</label>
                                <input type="text" id="custName" required placeholder="Nhập họ và tên..."
                                       class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:outline-none focus:border-brand">
                            </div>
                            <div>
                                <label class="block font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                <input type="tel" id="custPhone" required placeholder="Ví dụ: 0988399855"
                                       class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:outline-none focus:border-brand">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block font-bold text-slate-700 mb-1">Chọn loại xe cần thuê *</label>
                                <select id="custVehicle" class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:outline-none focus:border-brand bg-white">
                                    <option value="Thuê xe 4 chỗ Đà Nẵng">Thuê xe 4 chỗ Đà Nẵng</option>
                                    <option value="Thuê xe 7 chỗ Đà Nẵng">Thuê xe 7 chỗ Đà Nẵng</option>
                                    <option value="Thuê xe 16 chỗ Đà Nẵng">Thuê xe 16 chỗ Đà Nẵng</option>
                                    <option value="Thuê xe 18 chỗ Đà Nẵng">Thuê xe 18 chỗ Đà Nẵng</option>
                                    <option value="Thuê xe 29 chỗ Đà Nẵng">Thuê xe 29 chỗ Đà Nẵng</option>
                                    <option value="Thuê xe 35 chỗ Đà Nẵng">Thuê xe 35 chỗ Đà Nẵng</option>
                                    <option value="Thuê xe 45 chỗ Đà Nẵng">Thuê xe 45 chỗ Đà Nẵng</option>
                                    <option value="Thuê xe Limousine / Carnival Đà Nẵng">Thuê xe Limousine / Carnival Đà Nẵng</option>
                                    <option value="Thuê xe cưới Đà Nẵng">Thuê xe cưới Đà Nẵng</option>
                                </select>
                            </div>
                            <div>
                                <label class="block font-bold text-slate-700 mb-1">Ngày khởi hành dự kiến</label>
                                <input type="date" id="custDate"
                                       class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:outline-none focus:border-brand">
                            </div>
                        </div>

                        <div>
                            <label class="block font-bold text-slate-700 mb-1">Điểm đón & Lịch trình chi tiết *</label>
                            <textarea id="custRoute" rows="3" required placeholder="Ví dụ: Đón tại Sân bay Đà Nẵng đi Hội An - Bà Nà Hills 3 ngày 2 đêm..."
                                      class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:outline-none focus:border-brand"></textarea>
                        </div>

                        <div id="quoteSuccessBox" class="hidden p-3 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs font-medium"></div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 pt-1">
                            <button type="submit" class="w-full bg-brand hover:bg-brand-dark text-white font-extrabold py-2.5 px-4 rounded-lg shadow transition">
                                <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU BÁO GIÁ
                            </button>
                            <a href="https://zalo.me/0988399855" target="_blank" rel="noopener" class="w-full bg-sky-600 hover:bg-sky-700 text-white font-extrabold py-2.5 px-4 rounded-lg shadow text-center transition">
                                <i class="fa-solid fa-comment-dots mr-1.5"></i>NHẬN BÁO GIÁ QUA ZALO
                            </a>
                        </div>
                    </form>
                </div>

                <!-- Cột Đưa Facebook & Bản Đồ Google Map Ra Ngoài Trang Chủ -->
                <div id="lien-he-map" class="lg:col-span-6 space-y-4">
                    <!-- Khung Facebook Chính Thức Ngoài Trang Chủ -->
                    <div class="bg-white rounded-xl border border-slate-200 p-4 shadow-sm">
                        <div class="flex flex-wrap items-center justify-between gap-3">
                            <div class="flex items-center gap-3">
                                <div class="w-11 h-11 rounded-full bg-blue-600 text-white flex items-center justify-center text-xl shrink-0">
                                    <i class="fa-brands fa-facebook-f"></i>
                                </div>
                                <div>
                                    <h3 class="font-heading font-bold text-sm sm:text-base text-slate-800">
                                        Facebook Chính Thức – Thuận Duyên Travel
                                    </h3>
                                    <p class="text-xs text-slate-500">
                                        Kết nối trực tiếp qua Facebook để xem lịch xe & ưu đãi mới nhất
                                    </p>
                                </div>
                            </div>
                            <a href="https://www.facebook.com/thuong.huynh.892119/" target="_blank" rel="noopener"
                               class="bg-blue-600 hover:bg-blue-700 text-white text-xs font-bold px-3.5 py-2 rounded-lg transition shrink-0">
                                <i class="fa-brands fa-facebook mr-1"></i>Mở Trang Facebook
                            </a>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-slate-100 text-xs text-slate-600 flex flex-wrap items-center justify-between gap-2">
                            <span><i class="fa-solid fa-link text-brand mr-1"></i>Link Facebook: <a href="https://www.facebook.com/thuong.huynh.892119/" target="_blank" rel="noopener" class="text-blue-600 font-semibold hover:underline break-all">facebook.com/thuong.huynh.892119</a></span>
                            <span class="font-bold text-rose-600"><i class="fa-solid fa-phone mr-1"></i>0988.399.855</span>
                        </div>
                    </div>

                    <!-- Khung Bản Đồ Google Map Ngoài Trang Chủ -->
                    <div class="bg-white rounded-xl border border-slate-200 p-4 shadow-sm">
                        <div class="flex flex-wrap items-center justify-between gap-2 mb-2.5">
                            <div>
                                <h3 class="font-heading font-bold text-sm sm:text-base text-brand uppercase">
                                    <i class="fa-solid fa-map-location-dot mr-1.5"></i>BẢN ĐỒ GOOGLE MAPS – ĐỊA CHỈ NHÀ XE
                                </h3>
                                <p class="text-xs text-slate-600 mt-0.5">
                                    <strong>Địa chỉ:</strong> H12/4 K78 Nguyễn Xuân Hữu, Phường Cẩm Lệ, TP Đà Nẵng
                                </p>
                            </div>
                            <a href="https://www.google.com/maps/search/?api=1&query=H12%2F4+K78+Nguy%E1%BB%85n+Xu%C3%A2n+H%E1%BB%AFu%2C+Ph%C6%B0%E1%BB%9Dng+C%E1%BA%A9m+L%E1%BB%87%2C+TP+%C4%90%C3%A0+N%E1%BA%B5ng"
                               target="_blank" rel="noopener"
                               class="bg-slate-100 hover:bg-brand hover:text-white text-brand text-xs font-bold px-3 py-1.5 rounded-lg border border-slate-200 transition">
                                <i class="fa-solid fa-diamond-turn-right mr-1"></i>Chỉ Đường Google Maps
                            </a>
                        </div>
                        <div class="w-full h-56 sm:h-64 rounded-lg overflow-hidden border border-slate-200 bg-slate-100">
                            <iframe
                                title="Bản đồ Công Ty TNHH Thuận Duyên Travel - H12/4 K78 Nguyễn Xuân Hữu, Phường Cẩm Lệ, TP Đà Nẵng"
                                src="https://maps.google.com/maps?q=K78%20Nguy%E1%BB%85n%20Xu%C3%A2n%20H%E1%BB%AFu,%20C%E1%BA%A9m%20L%E1%BB%87,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                class="w-full h-full border-0"
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ================= DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & CẨM NANG DU LỊCH) ================= -->
    <section id="tin-tuc" class="py-5">
        <div class="container-flatsome">
            <div class="section-title-container">
                <div class="section-title-main flex-wrap gap-2">
                    <h2 class="font-heading font-extrabold text-base md:text-lg text-brand uppercase">
                        <i class="fa-solid fa-newspaper mr-1.5"></i>TIN TỨC & CẨM NANG THUÊ XE DU LỊCH ĐÀ NẴNG
                    </h2>
                    <span class="text-xs text-slate-500 font-medium">Cẩm nang thuê xe • Kinh nghiệm du lịch Đà Nẵng – Hội An – Huế</span>
                </div>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 md:grid-cols-4 gap-2.5 sm:gap-4">
                <!-- Bài viết 1 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1saiQE-yMBg9d0-LYzZGfiO62N6JLZ0Hv"
                             onerror="handleDriveImageError(this, '1saiQE-yMBg9d0-LYzZGfiO62N6JLZ0Hv', 'https://images.unsplash.com/photo-1544620347-c4fd4a3d5957?auto=format&fit=crop&w=600&q=80')"
                             alt="Kinh nghiệm thuê xe du lịch Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10.5px] font-bold text-brand uppercase">Cẩm nang thuê xe</span>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800 mt-1">
                                Kinh nghiệm thuê xe du lịch 4 – 7 – 16 – 29 – 45 chỗ tại Đà Nẵng giá rẻ, uy tín
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1.5 line-clamp-2">
                                Hướng dẫn lựa chọn dòng xe phù hợp cho gia đình và đoàn khách khi tham quan Đà Nẵng, Hội An, Bà Nà Hills tiết kiệm chi phí.
                            </p>
                        </div>
                        <a href="#bao-gia-nhanh" class="text-[11px] font-bold text-brand hover:underline mt-2 inline-block">
                            Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/14BiC3_Hviw8ghdw02QBqbddXaPBXcSec"
                             onerror="handleDriveImageError(this, '14BiC3_Hviw8ghdw02QBqbddXaPBXcSec', 'https://images.unsplash.com/photo-1583417319070-4a69db38a482?auto=format&fit=crop&w=600&q=80')"
                             alt="Cẩm nang du lịch Bà Nà Hills" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10.5px] font-bold text-brand uppercase">Du lịch Đà Nẵng</span>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800 mt-1">
                                Lịch trình thuê xe Đà Nẵng đi Bà Nà Hills – Cầu Vàng trọn gói 1 ngày tự túc
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1.5 line-clamp-2">
                                Bảng giá xe đưa đón tận nơi từ khách sạn Đà Nẵng đi khu du lịch Sun World Bà Nà Hills kèm thời gian cáp treo mới nhất.
                            </p>
                        </div>
                        <a href="#bao-gia-nhanh" class="text-[11px] font-bold text-brand hover:underline mt-2 inline-block">
                            Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/16UTPnS62O8lWmuPyjZWvg5-gWuLGfkDT"
                             onerror="handleDriveImageError(this, '16UTPnS62O8lWmuPyjZWvg5-gWuLGfkDT', 'https://images.unsplash.com/photo-1559592413-7cec4d0cae2b?auto=format&fit=crop&w=600&q=80')"
                             alt="Cẩm nang du lịch Hội An" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10.5px] font-bold text-brand uppercase">Du lịch Hội An</span>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800 mt-1">
                                Gợi ý lịch trình thuê xe Đà Nẵng đi Ngũ Hành Sơn – Rừng Dừa Bảy Mẫu – Phố Cổ Hội An
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1.5 line-clamp-2">
                                Khám phá trọn vẹn vẻ đẹp phố cổ Hội An về đêm và trải nghiệm thuyền thúng Rừng Dừa Bảy Mẫu cùng đội xe Thuận Duyên Travel.
                            </p>
                        </div>
                        <a href="#bao-gia-nhanh" class="text-[11px] font-bold text-brand hover:underline mt-2 inline-block">
                            Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1U_qWMBHU4O2qFraO-tGs6qa6Den5WMXe"
                             onerror="handleDriveImageError(this, '1U_qWMBHU4O2qFraO-tGs6qa6Den5WMXe', 'https://images.unsplash.com/photo-1509023464722-18d996393ca8?auto=format&fit=crop&w=600&q=80')"
                             alt="Cẩm nang du lịch Huế" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10.5px] font-bold text-brand uppercase">Du lịch Cố đô Huế</span>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-800 mt-1">
                                Kinh nghiệm thuê xe Đà Nẵng đi Huế qua Đèo Hải Vân – Vịnh Lăng Cô – Đại Nội
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1.5 line-clamp-2">
                                Hành trình khám phá di sản miền Trung: Đèo Hải Vân, Lăng Cô, Đại Nội Huế, Chùa Thiên Mụ và Lăng Khải Định trong ngày.
                            </p>
                        </div>
                        <a href="#bao-gia-nhanh" class="text-[11px] font-bold text-brand hover:underline mt-2 inline-block">
                            Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ================= DANH MỤC CÁC ĐỐI TÁC ĐỒNG HÀNH ================= -->
    <section id="doi-tac" class="py-5">
        <div class="container-flatsome">
            <div class="section-title-container">
                <div class="section-title-main flex-wrap gap-2">
                    <h2 class="font-heading font-extrabold text-base md:text-lg text-brand uppercase">
                        <i class="fa-solid fa-handshake mr-1.5"></i>ĐỐI TÁC KHÁCH SẠN – LỮ HÀNH – DOANH NGHIỆP TIÊU BIỂU
                    </h2>
                    <span class="text-xs text-slate-500 font-medium">Hợp tác vận chuyển du lịch uy tín tại Đà Nẵng & miền Trung</span>
                </div>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5 sm:gap-3">
                <div class="bg-white rounded-xl border border-slate-200 p-3 text-center shadow-sm hover:border-brand transition">
                    <div class="w-10 h-10 mx-auto rounded-full bg-brand/10 text-brand flex items-center justify-center mb-1.5">
                        <i class="fa-solid fa-mountain-sun"></i>
                    </div>
                    <p class="font-heading font-bold text-xs text-slate-800">SUN WORLD BÀ NÀ</p>
                    <p class="text-[10.5px] text-slate-500">Đối tác điểm đến</p>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-3 text-center shadow-sm hover:border-brand transition">
                    <div class="w-10 h-10 mx-auto rounded-full bg-brand/10 text-brand flex items-center justify-center mb-1.5">
                        <i class="fa-solid fa-hotel"></i>
                    </div>
                    <p class="font-heading font-bold text-xs text-slate-800">VINWONDERS NAM HỘI AN</p>
                    <p class="text-[10.5px] text-slate-500">Đối tác du lịch</p>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-3 text-center shadow-sm hover:border-brand transition">
                    <div class="w-10 h-10 mx-auto rounded-full bg-brand/10 text-brand flex items-center justify-center mb-1.5">
                        <i class="fa-solid fa-hot-tub-person"></i>
                    </div>
                    <p class="font-heading font-bold text-xs text-slate-800">NÚI THẦN TÀI</p>
                    <p class="text-[10.5px] text-slate-500">Khu du lịch sinh thái</p>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-3 text-center shadow-sm hover:border-brand transition">
                    <div class="w-10 h-10 mx-auto rounded-full bg-brand/10 text-brand flex items-center justify-center mb-1.5">
                        <i class="fa-solid fa-plane-arrival"></i>
                    </div>
                    <p class="font-heading font-bold text-xs text-slate-800">SÂN BAY ĐÀ NẴNG</p>
                    <p class="text-[10.5px] text-slate-500">Đưa đón hành khách 24/7</p>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-3 text-center shadow-sm hover:border-brand transition">
                    <div class="w-10 h-10 mx-auto rounded-full bg-brand/10 text-brand flex items-center justify-center mb-1.5">
                        <i class="fa-solid fa-earth-asia"></i>
                    </div>
                    <p class="font-heading font-bold text-xs text-slate-800">LỮ HÀNH MIỀN TRUNG</p>
                    <p class="text-[10.5px] text-slate-500">Hợp đồng xe đoàn</p>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-3 text-center shadow-sm hover:border-brand transition">
                    <div class="w-10 h-10 mx-auto rounded-full bg-brand/10 text-brand flex items-center justify-center mb-1.5">
                        <i class="fa-solid fa-building"></i>
                    </div>
                    <p class="font-heading font-bold text-xs text-slate-800">RESORT & KHÁCH SẠN</p>
                    <p class="text-[10.5px] text-slate-500">Đà Nẵng – Hội An – Huế</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= FOOTER CHUẨN FLATSOME ================= -->
    <footer class="bg-brand-dark text-slate-200 pt-8 pb-20 md:pb-8 mt-4 border-t-4 border-amber-400">
        <div class="container-flatsome">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-white/10 text-xs">
                <!-- Cột 1: Thông tin công ty -->
                <div class="lg:col-span-5 space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <div class="w-10 h-10 rounded-lg bg-white p-0.5 shrink-0 flex items-center justify-center">
                            <img src="https://lh3.googleusercontent.com/d/1Setz60zZwRn3108dhggT6O927qYHhej5"
                                 onerror="handleDriveImageError(this, '1Setz60zZwRn3108dhggT6O927qYHhej5', 'https://placehold.co/100x100/0B4F94/FFFFFF?text=TD')"
                                 alt="Logo Thuận Duyên Travel" class="w-full h-full object-contain">
                        </div>
                        <div>
                            <h3 class="font-heading font-extrabold text-sm sm:text-base text-white">
                                CÔNG TY TNHH THUẬN DUYÊN TRAVEL
                            </h3>
                            <p class="text-amber-300 text-[11px] font-semibold">Website: thuanduyentravel.com</p>
                        </div>
                    </div>
                    <p class="text-slate-300 leading-relaxed">
                        Chuyên cung cấp dịch vụ cho thuê xe du lịch 4 chỗ, 7 chỗ, 16 chỗ, 18 chỗ, 29 chỗ, 35 chỗ, 45 chỗ, Limousine tại Đà Nẵng đi Hội An, Bà Nà Hills, Núi Thần Tài, Huế và đưa đón Sân bay Đà Nẵng uy tín, chuyên nghiệp.
                    </p>
                    <ul class="space-y-1.5 text-slate-200">
                        <li><i class="fa-solid fa-location-dot text-amber-400 mr-2"></i><strong>Địa chỉ:</strong> H12/4 K78 Nguyễn Xuân Hữu, Phường Cẩm Lệ, TP Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone-volume text-amber-400 mr-2"></i><strong>Hotline / Zalo:</strong> <a href="tel:0988399855" class="text-amber-300 font-bold">0988.399.855</a></li>
                        <li><i class="fa-solid fa-globe text-amber-400 mr-2"></i><strong>Website:</strong> <a href="https://thuanduyentravel.com" class="hover:text-amber-300">https://thuanduyentravel.com</a></li>
                        <li><i class="fa-brands fa-facebook text-amber-400 mr-2"></i><strong>Facebook:</strong> <a href="https://www.facebook.com/thuong.huynh.892119/" target="_blank" rel="noopener" class="hover:text-amber-300">facebook.com/thuong.huynh.892119</a></li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục loại xe -->
                <div class="lg:col-span-3 space-y-2">
                    <h4 class="font-heading font-bold text-white text-sm uppercase border-b border-white/15 pb-1.5">
                        DỊCH VỤ CHO THUÊ XE
                    </h4>
                    <ul class="space-y-1.5 text-slate-300">
                        <li><a href="#chon-loai-xe" class="hover:text-amber-300">• Thuê xe 4 chỗ Đà Nẵng</a></li>
                        <li><a href="#chon-loai-xe" class="hover:text-amber-300">• Thuê xe 7 chỗ Đà Nẵng</a></li>
                        <li><a href="#chon-loai-xe" class="hover:text-amber-300">• Thuê xe 16 chỗ & 18 chỗ Đà Nẵng</a></li>
                        <li><a href="#chon-loai-xe" class="hover:text-amber-300">• Thuê xe 29 chỗ Đà Nẵng</a></li>
                        <li><a href="#chon-loai-xe" class="hover:text-amber-300">• Thuê xe 35 chỗ & 45 chỗ Đà Nẵng</a></li>
                        <li><a href="#chon-loai-xe" class="hover:text-amber-300">• Thuê xe Limousine / Carnival / Xe cưới</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Tuyến thuê xe phổ biến -->
                <div class="lg:col-span-4 space-y-2">
                    <h4 class="font-heading font-bold text-white text-sm uppercase border-b border-white/15 pb-1.5">
                        TUYẾN DU LỊCH TẠI ĐÀ NẴNG
                    </h4>
                    <ul class="space-y-1.5 text-slate-300">
                        <li><a href="#thue-xe-tuyen-duong" class="hover:text-amber-300">• Thuê xe đưa đón Sân bay Đà Nẵng</a></li>
                        <li><a href="#thue-xe-tuyen-duong" class="hover:text-amber-300">• Thuê xe Đà Nẵng đi Phố cổ Hội An</a></li>
                        <li><a href="#thue-xe-tuyen-duong" class="hover:text-amber-300">• Thuê xe Đà Nẵng đi Sun World Bà Nà Hills</a></li>
                        <li><a href="#thue-xe-tuyen-duong" class="hover:text-amber-300">• Thuê xe Đà Nẵng đi Suối khoáng Núi Thần Tài</a></li>
                        <li><a href="#thue-xe-tuyen-duong" class="hover:text-amber-300">• Thuê xe Đà Nẵng đi Vinpearl Nam Hội An & Mỹ Sơn</a></li>
                        <li><a href="#thue-xe-tuyen-duong" class="hover:text-amber-300">• Thuê xe Đà Nẵng đi Cố đô Huế – Lăng Cô</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between gap-2 text-[11px] text-slate-400 text-center sm:text-left">
                <p>© Bản quyền thuộc về <strong>CÔNG TY TNHH THUẬN DUYÊN TRAVEL (thuanduyentravel.com)</strong>.</p>
                <p>Địa chỉ: H12/4 K78 Nguyễn Xuân Hữu, Phường Cẩm Lệ, TP Đà Nẵng • Hotline: 0988.399.855</p>
            </div>
        </div>
    </footer>

    <!-- ================= CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI ================= -->
    <!-- Cụm nút tròn nổi bên phải (Hiển thị trên cả máy tính và điện thoại) -->
    <div class="fixed right-3 bottom-16 md:bottom-6 z-40 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook -->
        <a href="https://www.facebook.com/thuong.huynh.892119/" target="_blank" rel="noopener"
           title="Facebook Thuận Duyên Travel"
           class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition">
            <i class="fa-brands fa-facebook-f text-sm w-4 text-center"></i>
            <span class="hidden sm:inline text-xs font-bold">Facebook</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a href="https://zalo.me/0988399855" target="_blank" rel="noopener"
           title="Chat Zalo 0988.399.855"
           class="flex items-center gap-2 bg-[#0068FF] hover:bg-sky-700 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="font-extrabold text-xs px-1 bg-white text-[#0068FF] rounded">Zalo</span>
            <span class="hidden sm:inline text-xs font-bold">0988.399.855</span>
        </a>

        <!-- Nút Gọi Hotline -->
        <a href="tel:0988399855"
           title="Gọi ngay 0988.399.855"
           class="floating-pulse flex items-center gap-2 bg-rose-600 hover:bg-rose-700 text-white px-3.5 py-2.5 rounded-full shadow-xl transition">
            <i class="fa-solid fa-phone-volume text-sm"></i>
            <span class="text-xs font-extrabold">0988.399.855</span>
        </a>
    </div>

    <!-- Thanh liên hệ nhanh cố định dưới đáy màn hình Điện Thoại -->
    <div class="md:hidden fixed bottom-0 left-0 right-0 z-40 bg-white border-t border-slate-200 grid grid-cols-3 text-center shadow-2xl">
        <a href="tel:0988399855" class="py-2 px-1 flex flex-col items-center justify-center text-rose-600 font-bold text-[11px] border-r border-slate-100">
            <i class="fa-solid fa-phone-volume text-sm mb-0.5"></i>
            <span>Gọi 0988.399.855</span>
        </a>
        <a href="https://zalo.me/0988399855" target="_blank" rel="noopener" class="py-2 px-1 flex flex-col items-center justify-center text-sky-600 font-bold text-[11px] border-r border-slate-100">
            <i class="fa-solid fa-comment-dots text-sm mb-0.5"></i>
            <span>Chat Zalo</span>
        </a>
        <a href="https://www.facebook.com/thuong.huynh.892119/" target="_blank" rel="noopener" class="py-2 px-1 flex flex-col items-center justify-center text-blue-600 font-bold text-[11px]">
            <i class="fa-brands fa-facebook text-sm mb-0.5"></i>
            <span>Facebook</span>
        </a>
    </div>

    <!-- ================= JAVASCRIPT ĐIỀU KHIỂN SLIDER, LỌC DANH MỤC & FORM BÁO GIÁ ================= -->
    <script>
        // 1. Điều khiển 2 Slide Banner tự trượt cho cả Máy tính & Điện thoại
        let currentBannerIndex = 0;
        const totalBannerSlides = 2;
        let bannerInterval = null;

        function updateBannerDisplay(index) {
            currentBannerIndex = index;
            const desktopSlides = document.querySelectorAll('.banner-slide-desktop');
            const mobileSlides = document.querySelectorAll('.banner-slide-mobile');
            const dot0 = document.getElementById('bannerDot0');
            const dot1 = document.getElementById('bannerDot1');

            desktopSlides.forEach((slide, idx) => {
                if (idx === index) {
                    slide.classList.remove('opacity-0', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0');
                }
            });

            mobileSlides.forEach((slide, idx) => {
                if (idx === index) {
                    slide.classList.remove('opacity-0', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0');
                }
            });

            if (dot0 && dot1) {
                if (index === 0) {
                    dot0.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
                    dot1.className = 'w-2.5 h-2 rounded-full bg-white/50 transition-all';
                } else {
                    dot0.className = 'w-2.5 h-2 rounded-full bg-white/50 transition-all';
                    dot1.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
                }
            }
        }

        function nextBannerSlide() {
            const nextIndex = (currentBannerIndex + 1) % totalBannerSlides;
            updateBannerDisplay(nextIndex);
        }

        function prevBannerSlide() {
            const prevIndex = (currentBannerIndex - 1 + totalBannerSlides) % totalBannerSlides;
            updateBannerDisplay(prevIndex);
        }

        function goToBannerSlide(index) {
            updateBannerDisplay(index);
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(nextBannerSlide, 5500);
        }

        // 2. Đóng/Mở Menu trên điện thoại
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            const overlay = document.getElementById('mobileMenuOverlay');
            if (!drawer || !overlay) return;

            const isClosed = drawer.classList.contains('-translate-x-full');
            if (isClosed) {
                drawer.classList.remove('-translate-x-full');
                overlay.classList.remove('hidden');
            } else {
                drawer.classList.add('-translate-x-full');
                overlay.classList.add('hidden');
            }
        }

        // 3. Lọc sản phẩm theo danh mục loại xe
        function filterCategory(catKey) {
            const cards = document.querySelectorAll('#vehicleProductGrid .product-card');
            const buttons = document.querySelectorAll('.cat-pill-btn');

            buttons.forEach(btn => {
                if (btn.getAttribute('data-cat-btn') === catKey) {
                    btn.className = 'cat-pill-btn bg-brand text-white text-[11.5px] font-semibold px-2.5 py-1 rounded whitespace-nowrap transition';
                } else {
                    btn.className = 'cat-pill-btn bg-white hover:bg-slate-100 text-slate-700 border border-slate-200 text-[11.5px] font-semibold px-2.5 py-1 rounded whitespace-nowrap transition';
                }
            });

            cards.forEach(card => {
                const cardCat = card.getAttribute('data-category');
                if (catKey === 'all' || cardCat === catKey) {
                    card.classList.remove('hidden');
                } else {
                    card.classList.add('hidden');
                }
            });
        }

        // 4. Tìm kiếm nhanh loại xe
        function filterProductsBySearch(keyword) {
            const query = (keyword || '').toLowerCase().trim();
            const cards = document.querySelectorAll('#vehicleProductGrid .product-card');
            cards.forEach(card => {
                const text = card.innerText.toLowerCase();
                if (!query || text.includes(query)) {
                    card.classList.remove('hidden');
                } else {
                    card.classList.add('hidden');
                }
            });
        }

        // 5. Chọn loại xe và cuộn xuống Form Báo Giá
        function selectVehicleForQuote(vehicleName) {
            const selectEl = document.getElementById('custVehicle');
            const routeEl = document.getElementById('custRoute');
            if (selectEl) {
                for (let i = 0; i < selectEl.options.length; i++) {
                    if (selectEl.options[i].value === vehicleName) {
                        selectEl.selectedIndex = i;
                        break;
                    }
                }
            }
            if (routeEl && !routeEl.value) {
                routeEl.value = 'Yêu cầu báo giá: ' + vehicleName;
            }
            const formSection = document.getElementById('bao-gia-nhanh');
            if (formSection) {
                formSection.scrollIntoView({ behavior: 'smooth' });
            }
        }

        // 6. Xử lý gửi Form Báo Giá
        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById('custName').value.trim();
            const phone = document.getElementById('custPhone').value.trim();
            const vehicle = document.getElementById('custVehicle').value;
            const date = document.getElementById('custDate').value || 'Chưa chọn ngày';
            const route = document.getElementById('custRoute').value.trim();
            const box = document.getElementById('quoteSuccessBox');

            if (box) {
                box.classList.remove('hidden');
                box.innerHTML = '<i class="fa-solid fa-circle-check mr-1.5"></i>Đã ghi nhận yêu cầu báo giá của <strong>' + name + ' (' + phone + ')</strong> cho dịch vụ <strong>' + vehicle + '</strong> (Ngày đi: ' + date + '). Quý khách có thể bấm nút <strong>Nhận Báo Giá Qua Zalo 0988.399.855</strong> để kết nối ngay!';
            }
        }

        window.addEventListener('DOMContentLoaded', function () {
            resetBannerTimer();
        });
    </script>
</body>
</html>
