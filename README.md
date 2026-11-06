<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>Hồn Trầm Hương - Shop Trầm Hương Uy Tín Tại Đà Nẵng | hontramhuong.com</title>
  <meta name="description" content="Hồn Trầm Hương (hontramhuong.com) chuyên cung cấp Chuỗi trầm hương 108 hạt, Vòng tay phong thủy, Trầm chìm VIP, Nhang trầm, Thác lư xông, Trầm miếng xông nhà tự nhiên 100% tại 79 Nguyễn Xí, Phường Hòa Khánh, TP. Đà Nẵng. Hotline: 0855.655.555">

  <!-- Open Graph Thumbnail là ảnh Logo khi gửi link trang web -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://hontramhuong.com/">
  <meta property="og:site_name" content="hontramhuong.com">
  <meta property="og:title" content="Hồn Trầm Hương - Tinh Hoa Trầm Hương Tự Nhiên Đà Nẵng">
  <meta property="og:description" content="Chuyên chuỗi trầm hương, vòng tay phong thủy, nhang trầm, trầm miếng xông nhà thiên nhiên 100%. Địa chỉ: 79 Nguyễn Xí, Phường Hòa Khánh, Tp. Đà Nẵng - SĐT: 0855.655.555">
  <meta property="og:image" content="https://drive.google.com/thumbnail?id=1-L1skYj1KMQJBqxAngxJJn1xi09XjthK&sz=w1200">
  <meta property="og:image:alt" content="Logo Hồn Trầm Hương - hontramhuong.com">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1-L1skYj1KMQJBqxAngxJJn1xi09XjthK&sz=w1200">
  <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=1-L1skYj1KMQJBqxAngxJJn1xi09XjthK&sz=w200">

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Google Fonts: Roboto & Playfair Display chuẩn phong cách Flatsome Trầm Hương -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,600;0,700;1,600&family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            tram: {
              dark: '#4a2508',     /* Màu nâu trầm đậm chủ đạo giống tramhuongdanang.vn */
              primary: '#5c2e0c',  /* Màu thanh điều hướng & tiêu đề Flatsome */
              medium: '#7a4116',   /* Màu nâu gỗ trầm trung gian */
              gold: '#d4a037',     /* Màu vàng kim điểm nhấn */
              goldlight: '#f5d27b',/* Màu vàng sáng trên nền tối */
              bg: '#fdfbf7',       /* Màu nền kem ấm đặc trưng web mẫu */
              card: '#ffffff',
              sale: '#b20000'      /* Màu đỏ giảm giá chuẩn Flatsome */
            }
          },
          fontFamily: {
            sans: ['Roboto', 'sans-serif'],
            serif: ['Playfair Display', 'serif']
          }
        }
      }
    }
  </script>

  <style>
    /* Đảm bảo toàn bộ trang không tràn viền ngang và không lệch phải */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      width: 100%;
      max-width: 100vw;
      overflow-x: hidden;
      margin: 0;
      padding: 0;
      background-color: #fdfbf7;
      color: #2d1e12;
      font-family: 'Roboto', sans-serif;
      scroll-behavior: smooth;
    }

    /* Chiều ngang giao diện chuẩn 1500px trên máy tính */
    .container-1500 {
      width: 100%;
      max-width: 1500px;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }
    @media (min-width: 768px) {
      .container-1500 {
        padding-left: 20px;
        padding-right: 20px;
      }
    }

    /* Tiêu đề Section chuẩn Flatsome UX Builder (Line - Title - Line) */
    .flatsome-section-title {
      display: flex;
      align-items: center;
      justify-content: center;
      width: 100%;
      margin-bottom: 1.25rem;
    }
    .flatsome-section-title b {
      display: block;
      flex: 1;
      height: 2px;
      background-color: #d8c7b2;
    }
    .flatsome-section-title span {
      margin: 0 14px;
      font-weight: 700;
      text-transform: uppercase;
      color: #4a2508;
      text-align: center;
      letter-spacing: 0.03em;
    }

    /* Nút giảm giá góc trên bên trái chuẩn Flatsome */
    .flatsome-badge-sale {
      position: absolute;
      top: 8px;
      left: 8px;
      z-index: 10;
      background-color: #b20000;
      color: #ffffff;
      font-weight: 700;
      font-size: 11.5px;
      line-height: 1;
      padding: 6px 7px;
      border-radius: 9999px;
      min-width: 38px;
      min-height: 38px;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
    }

    /* Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ (...) và không tràn khung */
    .product-title-full {
      word-break: break-word;
      overflow-wrap: break-word;
      white-space: normal;
      line-height: 1.38;
    }

    /* Tên danh mục viết liền trên 1 hàng, không xuống dòng bên trong tên */
    .cat-nowrap {
      white-space: nowrap;
      display: inline-flex;
      align-items: center;
    }

    /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
    @keyframes pulseRing {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(178, 0, 0, 0.7); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(178, 0, 0, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(178, 0, 0, 0); }
    }
    .pulse-contact {
      animation: pulseRing 2s infinite;
    }
  </style>
</head>
<body class="bg-tram-bg text-stone-800 antialiased selection:bg-tram-primary selection:text-white">

  <!-- =====================================================================
       TOP BAR (Thanh thông tin phía trên chuẩn web mẫu tramhuongdanang.vn)
       ===================================================================== -->
  <div class="bg-tram-dark text-amber-100/90 text-xs py-1.5 border-b border-amber-900/40">
    <div class="container-1500 flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-3 sm:gap-5 overflow-hidden">
        <span class="inline-flex items-center gap-1.5 truncate">
          <i class="fa-solid fa-location-dot text-tram-gold"></i>
          <span>79 Nguyễn Xí, Phường Hòa Khánh, Tp.Đà Nẵng</span>
        </span>
        <span class="hidden md:inline-flex items-center gap-1.5">
          <i class="fa-solid fa-globe text-tram-gold"></i>
          <span>hontramhuong.com</span>
        </span>
      </div>
      <div class="hidden sm:flex items-center gap-4 text-[11.5px]">
        <a href="#form-bao-gia" class="hover:text-tram-gold transition">Chính sách đại lý</a>
        <span class="opacity-40">|</span>
        <a href="#form-bao-gia" class="hover:text-tram-gold transition">Hướng dẫn đặt hàng</a>
        <span class="opacity-40">|</span>
        <a href="https://www.facebook.com/saneespa55" target="_blank" rel="noopener" class="hover:text-tram-gold transition inline-flex items-center gap-1">
          <i class="fa-brands fa-facebook"></i> Fanpage Hồn Trầm Hương
        </a>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       HEADER CHÍNH (Logo chỉnh gọn nhỏ lại, KHÔNG để nút gọi ngay để tránh tràn viền)
       ===================================================================== -->
  <header class="bg-white sticky top-0 z-40 shadow-sm border-b border-stone-200">
    <div class="container-1500 py-2.5 flex items-center justify-between gap-3">
      
      <!-- Nút mở Menu Danh mục trên Điện thoại -->
      <button id="mobileMenuBtn" type="button" aria-label="Mở danh mục" class="lg:hidden p-2 rounded-md text-tram-primary hover:bg-amber-50 border border-stone-200 flex-shrink-0">
        <i class="fa-solid fa-bars text-lg"></i>
      </button>

      <!-- Logo chỉnh gọn nhỏ lại + Tên thương hiệu -->
      <a href="#" class="flex items-center gap-2.5 flex-shrink-0 group">
        <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-full overflow-hidden border border-amber-700/30 bg-stone-50 flex items-center justify-center flex-shrink-0 p-0.5">
          <img 
            src="https://drive.google.com/thumbnail?id=1-L1skYj1KMQJBqxAngxJJn1xi09XjthK&sz=w300" 
            data-drive-id="1-L1skYj1KMQJBqxAngxJJn1xi09XjthK"
            alt="Logo Hồn Trầm Hương" 
            class="w-full h-full object-contain rounded-full"
            onerror="handleDriveImgError(this, 'Hồn Trầm Hương')"
          >
        </div>
        <div class="flex flex-col">
          <span class="font-serif font-bold text-base sm:text-lg md:text-xl text-tram-primary tracking-tight leading-none">
            HỒN TRẦM HƯƠNG
          </span>
          <span class="text-[10px] sm:text-[11px] text-stone-500 font-medium tracking-wider uppercase mt-0.5">
            hontramhuong.com
          </span>
        </div>
      </a>

      <!-- Thanh tìm kiếm sản phẩm chuẩn Flatsome -->
      <div class="hidden md:flex flex-1 max-w-xl mx-4">
        <div class="relative flex w-full">
          <input 
            id="desktopSearchInput"
            type="text" 
            placeholder="Tìm chuỗi trầm 108 hạt, vòng tay phong thủy, nhang trầm..." 
            class="w-full pl-3.5 pr-10 py-2 text-sm bg-stone-50 border border-stone-300 rounded-l-md focus:outline-none focus:border-tram-primary"
          >
          <button 
            id="desktopSearchBtn"
            type="button" 
            class="bg-tram-primary hover:bg-tram-dark text-white px-4 py-2 rounded-r-md text-sm font-medium transition flex items-center justify-center"
          >
            <i class="fa-solid fa-magnifying-glass"></i>
          </button>
        </div>
      </div>

      <!-- Liên kết nhanh & Giỏ hàng (Không để nút gọi ngay trên Header theo yêu cầu) -->
      <div class="flex items-center gap-2 sm:gap-4 flex-shrink-0">
        <nav class="hidden xl:flex items-center gap-4 text-[13px] font-medium text-stone-700">
          <a href="#" class="text-tram-primary font-bold">Trang chủ</a>
          <a href="#gioi-thieu-cua-hang" class="hover:text-tram-primary transition">Giới thiệu</a>
          <a href="#danh-muc-trang-chu" class="hover:text-tram-primary transition">Sản phẩm</a>
          <a href="#kien-thuc-tram-huong" class="hover:text-tram-primary transition">Kiến thức</a>
          <a href="#form-bao-gia" class="hover:text-tram-primary transition">Báo giá</a>
          <a href="#ban-do-fanpage" class="hover:text-tram-primary transition">Liên hệ</a>
        </nav>

        <!-- Nút Giỏ hàng -->
        <button id="cartToggleBtn" type="button" class="relative inline-flex items-center gap-1.5 px-2.5 py-1.5 rounded-md border border-stone-300 bg-stone-50 hover:bg-amber-50 text-tram-primary text-xs sm:text-sm font-medium transition">
          <i class="fa-solid fa-bag-shopping text-tram-primary text-sm sm:text-base"></i>
          <span class="hidden sm:inline">Giỏ hàng</span>
          <span id="cartCountBadge" class="bg-tram-sale text-white text-[10px] font-bold px-1.5 py-0.5 rounded-full leading-none">0</span>
        </button>
      </div>
    </div>

    <!-- Thanh tìm kiếm trên điện thoại (Gọn gàng, không tràn viền) -->
    <div class="md:hidden px-3 pb-2">
      <div class="relative flex w-full">
        <input 
          id="mobileSearchInput"
          type="text" 
          placeholder="Tìm sản phẩm trầm hương..." 
          class="w-full pl-3 pr-9 py-1.5 text-xs bg-stone-50 border border-stone-300 rounded-md focus:outline-none focus:border-tram-primary"
        >
        <button id="mobileSearchBtn" type="button" class="absolute right-2.5 top-1/2 -translate-y-1/2 text-tram-primary text-xs">
          <i class="fa-solid fa-magnifying-glass"></i>
        </button>
      </div>
    </div>

    <!-- =====================================================================
         THANH DANH MỤC SẢN PHẨM TRÊN MÁY TÍNH (Chữ nhỏ gọn, viết liền 1 hàng từng danh mục, nằm trên 1 hàng hoặc xuống hàng 2, tuyệt đối không gãy chữ)
         ===================================================================== -->
    <div class="hidden lg:block bg-tram-primary text-white border-t border-amber-900/30">
      <div class="container-1500 py-1.5">
        <ul class="flex flex-wrap items-center justify-center gap-x-1.5 gap-y-1">
          <li>
            <button onclick="filterByCategory('all')" class="cat-nowrap px-2.5 py-1 rounded text-[12px] font-medium bg-amber-800/70 text-tram-goldlight hover:bg-amber-700 transition">
              <i class="fa-solid fa-border-all mr-1.5 text-[10px]"></i>Tất cả sản phẩm
            </button>
          </li>
          <li>
            <button onclick="filterByCategory('Chuỗi trầm hương')" class="cat-nowrap px-2.5 py-1 rounded text-[12px] font-medium hover:bg-amber-800/60 hover:text-tram-goldlight transition">
              Chuỗi trầm hương 108 hạt
            </button>
          </li>
          <li>
            <button onclick="filterByCategory('Chuỗi trầm hương')" class="cat-nowrap px-2.5 py-1 rounded text-[12px] font-medium hover:bg-amber-800/60 hover:text-tram-goldlight transition">
              Chuỗi trầm hương mix charm
            </button>
          </li>
          <li>
            <button onclick="filterByCategory('Vòng tay phong thủy')" class="cat-nowrap px-2.5 py-1 rounded text-[12px] font-medium hover:bg-amber-800/60 hover:text-tram-goldlight transition">
              Vòng tay phong thủy
            </button>
          </li>
          <li>
            <button onclick="filterByCategory('Vòng trầm hương bọc vàng')" class="cat-nowrap px-2.5 py-1 rounded text-[12px] font-medium hover:bg-amber-800/60 hover:text-tram-goldlight transition">
              Vòng trầm hương bọc vàng
            </button>
          </li>
          <li>
            <button onclick="filterByCategory('Trầm chìm vip cao cấp')" class="cat-nowrap px-2.5 py-1 rounded text-[12px] font-medium hover:bg-amber-800/60 hover:text-tram-goldlight transition">
              Trầm chìm VIP cao cấp
            </button>
          </li>
          <li>
            <button onclick="filterByCategory('Mặt tượng đeo cổ')" class="cat-nowrap px-2.5 py-1 rounded text-[12px] font-medium hover:bg-amber-800/60 hover:text-tram-goldlight transition">
              Mặt tượng đeo cổ
            </button>
          </li>
          <li>
            <button onclick="filterByCategory('Nhang trầm - Thác lư xông')" class="cat-nowrap px-2.5 py-1 rounded text-[12px] font-medium hover:bg-amber-800/60 hover:text-tram-goldlight transition">
              Nhang trầm - Thác lư xông
            </button>
          </li>
          <li>
            <button onclick="filterByCategory('Trầm hương miếng - giác xông')" class="cat-nowrap px-2.5 py-1 rounded text-[12px] font-medium hover:bg-amber-800/60 hover:text-tram-goldlight transition">
              Trầm hương miếng - Giác xông
            </button>
          </li>
          <li>
            <button onclick="filterByCategory('Tranh - tượng trầm cảnh')" class="cat-nowrap px-2.5 py-1 rounded text-[12px] font-medium hover:bg-amber-800/60 hover:text-tram-goldlight transition">
              Tranh - Tượng trầm cảnh
            </button>
          </li>
          <li>
            <button onclick="filterByCategory('Vòng tay phong thủy')" class="cat-nowrap px-2.5 py-1 rounded text-[12px] font-medium hover:bg-amber-800/60 hover:text-tram-goldlight transition">
              Vòng đeo cổ & Vòng cho bé
            </button>
          </li>
        </ul>
      </div>
    </div>
  </header>

  <!-- MENU TRƯỢT TRÊN ĐIỆN THOẠI -->
  <div id="mobileMenuOverlay" class="fixed inset-0 bg-black/50 z-50 hidden">
    <div class="w-[280px] max-w-[85vw] bg-white h-full overflow-y-auto p-4 flex flex-col justify-between shadow-xl">
      <div>
        <div class="flex items-center justify-between pb-3 border-b border-stone-200">
          <span class="font-serif font-bold text-tram-primary text-base">DANH MỤC SẢN PHẨM</span>
          <button id="closeMobileMenuBtn" type="button" class="p-1.5 text-stone-500 hover:text-stone-800">
            <i class="fa-solid fa-xmark text-lg"></i>
          </button>
        </div>
        <ul class="mt-3 space-y-1 text-[13px] font-medium text-stone-700">
          <li><button onclick="filterByCategory('all'); closeMobileMenu();" class="w-full text-left py-2 px-2.5 rounded hover:bg-amber-50 text-tram-primary font-semibold">Tất cả sản phẩm</button></li>
          <li><button onclick="filterByCategory('Chuỗi trầm hương'); closeMobileMenu();" class="w-full text-left py-2 px-2.5 rounded hover:bg-amber-50">Chuỗi trầm hương 108 & 216 hạt</button></li>
          <li><button onclick="filterByCategory('Vòng tay phong thủy'); closeMobileMenu();" class="w-full text-left py-2 px-2.5 rounded hover:bg-amber-50">Vòng tay phong thủy Nam & Nữ</button></li>
          <li><button onclick="filterByCategory('Vòng trầm hương bọc vàng'); closeMobileMenu();" class="w-full text-left py-2 px-2.5 rounded hover:bg-amber-50">Vòng trầm hương bọc vàng</button></li>
          <li><button onclick="filterByCategory('Trầm chìm vip cao cấp'); closeMobileMenu();" class="w-full text-left py-2 px-2.5 rounded hover:bg-amber-50">Trầm chìm VIP cao cấp</button></li>
          <li><button onclick="filterByCategory('Mặt tượng đeo cổ'); closeMobileMenu();" class="w-full text-left py-2 px-2.5 rounded hover:bg-amber-50">Mặt tượng đeo cổ</button></li>
          <li><button onclick="filterByCategory('Nhang trầm - Thác lư xông'); closeMobileMenu();" class="w-full text-left py-2 px-2.5 rounded hover:bg-amber-50">Nhang trầm - Thác lư xông</button></li>
          <li><button onclick="filterByCategory('Trầm hương miếng - giác xông'); closeMobileMenu();" class="w-full text-left py-2 px-2.5 rounded hover:bg-amber-50">Trầm hương miếng - Giác xông</button></li>
          <li><button onclick="filterByCategory('Tranh - tượng trầm cảnh'); closeMobileMenu();" class="w-full text-left py-2 px-2.5 rounded hover:bg-amber-50">Tranh - Tượng trầm cảnh</button></li>
        </ul>
      </div>
      <div class="pt-4 border-t border-stone-200 text-xs text-stone-600 space-y-1.5">
        <p class="font-bold text-tram-primary">HỒN TRẦM HƯƠNG ĐÀ NẴNG</p>
        <p><i class="fa-solid fa-location-dot text-tram-gold mr-1"></i>79 Nguyễn Xí, P. Hòa Khánh, Đà Nẵng</p>
        <p><i class="fa-solid fa-phone text-tram-gold mr-1"></i>0855.655.555</p>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       SECTION 1: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
       - Tách biệt bản thiết kế Banner Máy Tính (Desktop) và Banner Điện Thoại (Mobile)
       - Chữ trong ảnh banner nhỏ gọn, căn lề an toàn, tuyệt đối không tràn viền
       ===================================================================== -->
  <section class="w-full py-3">
    <div class="container-1500">
      <div class="relative w-full overflow-hidden rounded-lg shadow-md border border-amber-900/20 bg-tram-dark">
        
        <!-- ================= SLIDE 1 ================= -->
        <div class="banner-slide transition-opacity duration-700 opacity-100 block" data-slide="0">
          
          <!-- BANNER MÁY TÍNH SLIDE 1 (Chỉ hiển thị trên máy tính md trở lên, cao cố định 380px) -->
          <div class="hidden md:grid md:grid-cols-12 items-center w-full h-[380px] bg-gradient-to-r from-[#3b1c05] via-[#562b0b] to-[#3b1c05] px-10 lg:px-14 relative overflow-hidden">
            <!-- Hoa văn chìm trang nhã -->
            <div class="absolute inset-0 opacity-10 pointer-events-none" style="background-image: radial-gradient(#f5d27b 1px, transparent 1px); background-size: 24px 24px;"></div>
            
            <!-- Cột chữ bên trong ảnh banner máy tính (chữ nhỏ gọn, nằm gọn trong khung) -->
            <div class="col-span-7 z-10 pr-6 space-y-2.5">
              <div class="inline-block px-3 py-1 rounded bg-amber-500/20 border border-amber-400/40 text-tram-goldlight text-xs font-semibold tracking-wider uppercase">
                TINH HOA TRẦM HƯƠNG VIỆT NAM • HONTRAMHUONG.COM
              </div>
              <h1 class="font-serif font-bold text-2xl lg:text-3xl text-white leading-snug">
                HỒN TRẦM HƯƠNG – TÂM AN VẠN SỰ AN
              </h1>
              <p class="text-amber-100/90 text-xs lg:text-sm leading-relaxed max-w-xl">
                Chuyên chế tác & phân phối Chuỗi Trầm Hương 108 Hạt, Vòng Tay Phong Thủy, Trầm Chìm VIP, Nhang Nụ Trầm & Giác Xông Thiên Nhiên 100%. Hương thơm ngọt dịu, tụ vượng khí, chiêu tài lộc.
              </p>
              <div class="pt-1 flex flex-wrap items-center gap-4 text-xs text-amber-200">
                <span><i class="fa-solid fa-location-dot text-tram-gold mr-1.5"></i>79 Nguyễn Xí, Phường Hòa Khánh, Tp.Đà Nẵng</span>
                <span><i class="fa-solid fa-phone-volume text-tram-gold mr-1.5"></i>Hotline: <strong>0855.655.555</strong></span>
              </div>
              <div class="pt-2 flex items-center gap-3">
                <a href="#san-pham-ban-chay" class="px-4 py-2 rounded bg-tram-gold hover:bg-amber-500 text-stone-900 font-bold text-xs uppercase tracking-wide transition shadow">
                  Khám phá sản phẩm
                </a>
                <a href="#form-bao-gia" class="px-4 py-2 rounded border border-amber-300/60 hover:bg-white/10 text-amber-100 font-medium text-xs uppercase tracking-wide transition">
                  Nhận báo giá ưu đãi
                </a>
              </div>
            </div>

            <!-- Cột hình ảnh thực tế ghép trong Banner Máy Tính 1 -->
            <div class="col-span-5 z-10 flex items-center justify-center gap-3">
              <div class="w-44 h-60 rounded-lg overflow-hidden border-2 border-tram-gold/60 shadow-lg bg-stone-900 flex-shrink-0">
                <img 
                  src="https://drive.google.com/thumbnail?id=1ReytPfRctosCWC1GAWXxZrZ8Y6JNkPOO&sz=w600" 
                  data-drive-id="1ReytPfRctosCWC1GAWXxZrZ8Y6JNkPOO"
                  alt="Vòng Trầm Hương Hồn Trầm Hương" 
                  class="w-full h-full object-cover"
                  onerror="handleDriveImgError(this, 'Vòng Trầm VIP')"
                >
              </div>
              <div class="w-40 h-52 rounded-lg overflow-hidden border-2 border-amber-200/40 shadow-lg bg-stone-900 flex-shrink-0 hidden lg:block">
                <img 
                  src="https://drive.google.com/thumbnail?id=1fBsmeSpo4FOg1g9XgHlC5dTWjlQvlSOH&sz=w600" 
                  data-drive-id="1fBsmeSpo4FOg1g9XgHlC5dTWjlQvlSOH"
                  alt="Chuỗi Trầm Hương 108 Hạt" 
                  class="w-full h-full object-cover"
                  onerror="handleDriveImgError(this, 'Chuỗi Trầm 108 Hạt')"
                >
              </div>
            </div>
          </div>

          <!-- BANNER ĐIỆN THOẠI SLIDE 1 (Thiết kế riêng cho màn hình điện thoại, chữ nhỏ gọn tuyệt đối không tràn viền, cao 230px) -->
          <div class="md:hidden w-full h-[230px] bg-gradient-to-br from-[#3b1c05] via-[#562b0b] to-[#2e1503] px-4 py-3 flex items-center justify-between gap-2.5 relative overflow-hidden">
            <div class="w-[62%] z-10 space-y-1.5 pl-1">
              <span class="inline-block px-2 py-0.5 rounded bg-amber-500/20 border border-amber-400/40 text-tram-goldlight text-[9.5px] font-semibold uppercase">
                hontramhuong.com
              </span>
              <h2 class="font-serif font-bold text-[14px] text-white leading-tight">
                HỒN TRẦM HƯƠNG ĐÀ NẴNG
              </h2>
              <p class="text-amber-100/90 text-[10.5px] leading-snug">
                Chuỗi trầm 108 hạt, Vòng tay phong thủy, Nhang trầm & Giác xông tự nhiên 100%.
              </p>
              <div class="text-[10px] text-amber-200 space-y-0.5 pt-0.5">
                <p class="leading-tight"><i class="fa-solid fa-location-dot text-tram-gold mr-1"></i>79 Nguyễn Xí, Hòa Khánh, Đà Nẵng</p>
                <p class="leading-tight"><i class="fa-solid fa-phone text-tram-gold mr-1"></i>SĐT: <strong>0855.655.555</strong></p>
              </div>
            </div>
            <div class="w-[36%] h-[175px] rounded-md overflow-hidden border border-tram-gold/60 shadow bg-stone-900 flex-shrink-0 z-10">
              <img 
                src="https://drive.google.com/thumbnail?id=1ReytPfRctosCWC1GAWXxZrZ8Y6JNkPOO&sz=w500" 
                data-drive-id="1ReytPfRctosCWC1GAWXxZrZ8Y6JNkPOO"
                alt="Hồn Trầm Hương Mobile Banner 1" 
                class="w-full h-full object-cover"
                onerror="handleDriveImgError(this, 'Hồn Trầm Hương')"
              >
            </div>
          </div>

        </div>

        <!-- ================= SLIDE 2 (Kích thước bằng hệt Slide 1) ================= -->
        <div class="banner-slide transition-opacity duration-700 hidden" data-slide="1">
          
          <!-- BANNER MÁY TÍNH SLIDE 2 (Cao cố định 380px bằng Slide 1) -->
          <div class="hidden md:grid md:grid-cols-12 items-center w-full h-[380px] bg-gradient-to-r from-[#2e1604] via-[#4f2609] to-[#2e1604] px-10 lg:px-14 relative overflow-hidden">
            <div class="absolute inset-0 opacity-10 pointer-events-none" style="background-image: radial-gradient(#f5d27b 1px, transparent 1px); background-size: 24px 24px;"></div>
            
            <div class="col-span-7 z-10 pr-6 space-y-2.5">
              <div class="inline-block px-3 py-1 rounded bg-amber-500/20 border border-amber-400/40 text-tram-goldlight text-xs font-semibold tracking-wider uppercase">
                SHOWROOM TRẦM HƯƠNG UY TÍN TẠI ĐÀ NẴNG
              </div>
              <h2 class="font-serif font-bold text-2xl lg:text-3xl text-white leading-snug">
                QUÀ TẶNG PHONG THỦY ĐẲNG CẤP & Ý NGHĨA
              </h2>
              <p class="text-amber-100/90 text-xs lg:text-sm leading-relaxed max-w-xl">
                Cam kết Trầm Hương chuẩn tự nhiên, mùi hương nguyên bản thanh ngọt bền lâu. Tư vấn tận tâm theo mệnh phong thủy, bảo hành đánh bóng & thay dây trọn đời tại cửa hàng.
              </p>
              <div class="pt-1 flex flex-wrap items-center gap-4 text-xs text-amber-200">
                <span><i class="fa-solid fa-store text-tram-gold mr-1.5"></i>Showroom: 79 Nguyễn Xí, Phường Hòa Khánh, Tp.Đà Nẵng</span>
                <span><i class="fa-solid fa-headset text-tram-gold mr-1.5"></i>Tư vấn 24/7: <strong>0855.655.555</strong></span>
              </div>
              <div class="pt-2 flex items-center gap-3">
                <a href="#gioi-thieu-cua-hang" class="px-4 py-2 rounded bg-tram-gold hover:bg-amber-500 text-stone-900 font-bold text-xs uppercase tracking-wide transition shadow">
                  Xem cửa hàng thực tế
                </a>
                <a href="#ban-do-fanpage" class="px-4 py-2 rounded border border-amber-300/60 hover:bg-white/10 text-amber-100 font-medium text-xs uppercase tracking-wide transition">
                  Chỉ đường Google Map
                </a>
              </div>
            </div>

            <div class="col-span-5 z-10 flex items-center justify-center gap-3">
              <div class="w-44 h-60 rounded-lg overflow-hidden border-2 border-tram-gold/60 shadow-lg bg-stone-900 flex-shrink-0">
                <img 
                  src="https://drive.google.com/thumbnail?id=1QsWaCOmB-08_LLBqZ5-pTnMDHkQGg6i6&sz=w600" 
                  data-drive-id="1QsWaCOmB-08_LLBqZ5-pTnMDHkQGg6i6"
                  alt="Showroom Hồn Trầm Hương 79 Nguyễn Xí" 
                  class="w-full h-full object-cover"
                  onerror="handleDriveImgError(this, 'Cửa Hàng Hồn Trầm Hương')"
                >
              </div>
              <div class="w-40 h-52 rounded-lg overflow-hidden border-2 border-amber-200/40 shadow-lg bg-stone-900 flex-shrink-0 hidden lg:block">
                <img 
                  src="https://drive.google.com/thumbnail?id=1W6oTRgr-AKquOvdlW-WxFpoc12nsq0XL&sz=w600" 
                  data-drive-id="1W6oTRgr-AKquOvdlW-WxFpoc12nsq0XL"
                  alt="Bộ Sưu Tập Trầm Hương Cao Cấp" 
                  class="w-full h-full object-cover"
                  onerror="handleDriveImgError(this, 'Trầm Hương Cao Cấp')"
                >
              </div>
            </div>
          </div>

          <!-- BANNER ĐIỆN THOẠI SLIDE 2 (Cao cố định 230px bằng Slide 1, chữ nhỏ gọn trong khung) -->
          <div class="md:hidden w-full h-[230px] bg-gradient-to-br from-[#2e1604] via-[#4f2609] to-[#241002] px-4 py-3 flex items-center justify-between gap-2.5 relative overflow-hidden">
            <div class="w-[62%] z-10 space-y-1.5 pl-1">
              <span class="inline-block px-2 py-0.5 rounded bg-amber-500/20 border border-amber-400/40 text-tram-goldlight text-[9.5px] font-semibold uppercase">
                Cam kết 100% Tự Nhiên
              </span>
              <h2 class="font-serif font-bold text-[14px] text-white leading-tight">
                SHOWROOM HỒN TRẦM HƯƠNG
              </h2>
              <p class="text-amber-100/90 text-[10.5px] leading-snug">
                Bảo hành uy tín, giao hàng toàn quốc, kiểm tra hàng trước khi thanh toán.
              </p>
              <div class="text-[10px] text-amber-200 space-y-0.5 pt-0.5">
                <p class="leading-tight"><i class="fa-solid fa-location-dot text-tram-gold mr-1"></i>79 Nguyễn Xí, Hòa Khánh, Đà Nẵng</p>
                <p class="leading-tight"><i class="fa-solid fa-phone text-tram-gold mr-1"></i>Hotline: <strong>0855.655.555</strong></p>
              </div>
            </div>
            <div class="w-[36%] h-[175px] rounded-md overflow-hidden border border-tram-gold/60 shadow bg-stone-900 flex-shrink-0 z-10">
              <img 
                src="https://drive.google.com/thumbnail?id=1QsWaCOmB-08_LLBqZ5-pTnMDHkQGg6i6&sz=w500" 
                data-drive-id="1QsWaCOmB-08_LLBqZ5-pTnMDHkQGg6i6"
                alt="Cửa Hàng Hồn Trầm Hương Mobile Banner 2" 
                class="w-full h-full object-cover"
                onerror="handleDriveImgError(this, 'Showroom Hồn Trầm Hương')"
              >
            </div>
          </div>

        </div>

        <!-- Nút điều hướng Slide trái / phải -->
        <button onclick="changeBannerSlide(-1)" aria-label="Slide trước" class="absolute left-2 top-1/2 -translate-y-1/2 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center transition z-20">
          <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
        </button>
        <button onclick="changeBannerSlide(1)" aria-label="Slide tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center transition z-20">
          <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
        </button>

        <!-- Dấu chấm chỉ báo Slide -->
        <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
          <button onclick="goToBannerSlide(0)" class="banner-dot w-2.5 h-2.5 rounded-full bg-tram-gold transition"></button>
          <button onclick="goToBannerSlide(1)" class="banner-dot w-2.5 h-2.5 rounded-full bg-white/50 transition"></button>
        </div>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 2: DANH MỤC SẢN PHẨM TRANG CHỦ (Lấy từ web mẫu tramhuongdanang.vn)
       - Thiết kế đẹp trên cả máy tính và điện thoại
       - Chữ danh mục ở trang chủ nhỏ gọn, viết liền trên 1 hàng (whitespace-nowrap)
       ===================================================================== -->
  <section id="danh-muc-trang-chu" class="py-5">
    <div class="container-1500">
      <div class="flatsome-section-title">
        <b></b>
        <span class="text-base sm:text-lg md:text-xl">DANH MỤC SẢN PHẨM</span>
        <b></b>
      </div>

      <!-- Lưới danh mục hình ảnh + tên nhỏ gọn trên 1 hàng -->
      <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5 sm:gap-3">
        
        <button onclick="filterByCategory('Chuỗi trầm hương')" class="group bg-white border border-stone-200 hover:border-tram-primary rounded-lg p-2 flex flex-col items-center text-center shadow-sm hover:shadow transition">
          <div class="w-16 h-16 sm:w-20 sm:h-20 rounded-full overflow-hidden border border-amber-700/20 mb-2 bg-stone-100">
            <img src="https://drive.google.com/thumbnail?id=1fBsmeSpo4FOg1g9XgHlC5dTWjlQvlSOH&sz=w300" data-drive-id="1fBsmeSpo4FOg1g9XgHlC5dTWjlQvlSOH" alt="Chuỗi trầm hương" class="w-full h-full object-cover group-hover:scale-105 transition" onerror="handleDriveImgError(this, 'Chuỗi trầm')">
          </div>
          <span class="cat-nowrap text-[11px] sm:text-[12px] font-semibold text-stone-800 group-hover:text-tram-primary">Chuỗi trầm hương</span>
        </button>

        <button onclick="filterByCategory('Vòng tay phong thủy')" class="group bg-white border border-stone-200 hover:border-tram-primary rounded-lg p-2 flex flex-col items-center text-center shadow-sm hover:shadow transition">
          <div class="w-16 h-16 sm:w-20 sm:h-20 rounded-full overflow-hidden border border-amber-700/20 mb-2 bg-stone-100">
            <img src="https://drive.google.com/thumbnail?id=1ReytPfRctosCWC1GAWXxZrZ8Y6JNkPOO&sz=w300" data-drive-id="1ReytPfRctosCWC1GAWXxZrZ8Y6JNkPOO" alt="Vòng tay phong thủy" class="w-full h-full object-cover group-hover:scale-105 transition" onerror="handleDriveImgError(this, 'Vòng phong thủy')">
          </div>
          <span class="cat-nowrap text-[11px] sm:text-[12px] font-semibold text-stone-800 group-hover:text-tram-primary">Vòng tay phong thủy</span>
        </button>

        <button onclick="filterByCategory('Vòng trầm hương bọc vàng')" class="group bg-white border border-stone-200 hover:border-tram-primary rounded-lg p-2 flex flex-col items-center text-center shadow-sm hover:shadow transition">
          <div class="w-16 h-16 sm:w-20 sm:h-20 rounded-full overflow-hidden border border-amber-700/20 mb-2 bg-stone-100">
            <img src="https://drive.google.com/thumbnail?id=1W6oTRgr-AKquOvdlW-WxFpoc12nsq0XL&sz=w300" data-drive-id="1W6oTRgr-AKquOvdlW-WxFpoc12nsq0XL" alt="Vòng trầm bọc vàng" class="w-full h-full object-cover group-hover:scale-105 transition" onerror="handleDriveImgError(this, 'Trầm bọc vàng')">
          </div>
          <span class="cat-nowrap text-[11px] sm:text-[12px] font-semibold text-stone-800 group-hover:text-tram-primary">Vòng trầm bọc vàng</span>
        </button>

        <button onclick="filterByCategory('Trầm chìm vip cao cấp')" class="group bg-white border border-stone-200 hover:border-tram-primary rounded-lg p-2 flex flex-col items-center text-center shadow-sm hover:shadow transition">
          <div class="w-16 h-16 sm:w-20 sm:h-20 rounded-full overflow-hidden border border-amber-700/20 mb-2 bg-stone-100">
            <img src="https://drive.google.com/thumbnail?id=1p54no0Jv1jNwTLCDFmFY4ht6dnkFis4-&sz=w300" data-drive-id="1p54no0Jv1jNwTLCDFmFY4ht6dnkFis4-" alt="Trầm chìm VIP" class="w-full h-full object-cover group-hover:scale-105 transition" onerror="handleDriveImgError(this, 'Trầm chìm VIP')">
          </div>
          <span class="cat-nowrap text-[11px] sm:text-[12px] font-semibold text-stone-800 group-hover:text-tram-primary">Trầm chìm VIP</span>
        </button>

        <button onclick="filterByCategory('Mặt tượng đeo cổ')" class="group bg-white border border-stone-200 hover:border-tram-primary rounded-lg p-2 flex flex-col items-center text-center shadow-sm hover:shadow transition">
          <div class="w-16 h-16 sm:w-20 sm:h-20 rounded-full overflow-hidden border border-amber-700/20 mb-2 bg-stone-100">
            <img src="https://drive.google.com/thumbnail?id=1EwaDk1tmboAlMXAYgbcllqVPY-cDeo1d&sz=w300" data-drive-id="1EwaDk1tmboAlMXAYgbcllqVPY-cDeo1d" alt="Mặt tượng đeo cổ" class="w-full h-full object-cover group-hover:scale-105 transition" onerror="handleDriveImgError(this, 'Mặt tượng trầm')">
          </div>
          <span class="cat-nowrap text-[11px] sm:text-[12px] font-semibold text-stone-800 group-hover:text-tram-primary">Mặt tượng đeo cổ</span>
        </button>

        <button onclick="filterByCategory('Nhang trầm - Thác lư xông')" class="group bg-white border border-stone-200 hover:border-tram-primary rounded-lg p-2 flex flex-col items-center text-center shadow-sm hover:shadow transition">
          <div class="w-16 h-16 sm:w-20 sm:h-20 rounded-full overflow-hidden border border-amber-700/20 mb-2 bg-stone-100">
            <img src="https://drive.google.com/thumbnail?id=1R7Yd_hXFqTr5GqUhwZg0XFX4gyQ0Rq_s&sz=w300" data-drive-id="1R7Yd_hXFqTr5GqUhwZg0XFX4gyQ0Rq_s" alt="Nhang trầm - Thác lư" class="w-full h-full object-cover group-hover:scale-105 transition" onerror="handleDriveImgError(this, 'Nhang trầm')">
          </div>
          <span class="cat-nowrap text-[11px] sm:text-[12px] font-semibold text-stone-800 group-hover:text-tram-primary">Nhang - Thác lư xông</span>
        </button>

        <button onclick="filterByCategory('Trầm hương miếng - giác xông')" class="group bg-white border border-stone-200 hover:border-tram-primary rounded-lg p-2 flex flex-col items-center text-center shadow-sm hover:shadow transition">
          <div class="w-16 h-16 sm:w-20 sm:h-20 rounded-full overflow-hidden border border-amber-700/20 mb-2 bg-stone-100">
            <img src="https://drive.google.com/thumbnail?id=12Stw_Q95muFUNLuapH2h6W0fWNxEWdvs&sz=w300" data-drive-id="12Stw_Q95muFUNLuapH2h6W0fWNxEWdvs" alt="Trầm miếng giác xông" class="w-full h-full object-cover group-hover:scale-105 transition" onerror="handleDriveImgError(this, 'Trầm miếng')">
          </div>
          <span class="cat-nowrap text-[11px] sm:text-[12px] font-semibold text-stone-800 group-hover:text-tram-primary">Trầm miếng giác xông</span>
        </button>

        <button onclick="filterByCategory('Tranh - tượng trầm cảnh')" class="group bg-white border border-stone-200 hover:border-tram-primary rounded-lg p-2 flex flex-col items-center text-center shadow-sm hover:shadow transition">
          <div class="w-16 h-16 sm:w-20 sm:h-20 rounded-full overflow-hidden border border-amber-700/20 mb-2 bg-stone-100">
            <img src="https://drive.google.com/thumbnail?id=19-YhHFjXWcbxmCGVHb63HPAjehE13Wqn&sz=w300" data-drive-id="19-YhHFjXWcbxmCGVHb63HPAjehE13Wqn" alt="Tượng trầm cảnh" class="w-full h-full object-cover group-hover:scale-105 transition" onerror="handleDriveImgError(this, 'Tượng trầm cảnh')">
          </div>
          <span class="cat-nowrap text-[11px] sm:text-[12px] font-semibold text-stone-800 group-hover:text-tram-primary">Tranh tượng trầm cảnh</span>
        </button>

      </div>

      <!-- Hàng nút lọc nhanh danh mục phụ chuẩn Flatsome (Chữ nhỏ gọn, viết liền trên 1 hàng) -->
      <div class="mt-3 flex flex-wrap items-center justify-center gap-1.5" id="categoryFilterBar">
        <button onclick="filterByCategory('all')" data-cat="all" class="cat-filter-btn cat-nowrap px-3 py-1 rounded-full text-xs font-medium bg-tram-primary text-white transition">
          Tất cả (14)
        </button>
        <button onclick="filterByCategory('Chuỗi trầm hương')" data-cat="Chuỗi trầm hương" class="cat-filter-btn cat-nowrap px-3 py-1 rounded-full text-xs font-medium bg-white border border-stone-300 text-stone-700 hover:border-tram-primary transition">
          Chuỗi trầm hương 108 hạt
        </button>
        <button onclick="filterByCategory('Vòng tay phong thủy')" data-cat="Vòng tay phong thủy" class="cat-filter-btn cat-nowrap px-3 py-1 rounded-full text-xs font-medium bg-white border border-stone-300 text-stone-700 hover:border-tram-primary transition">
          Vòng tay phong thủy
        </button>
        <button onclick="filterByCategory('Vòng trầm hương bọc vàng')" data-cat="Vòng trầm hương bọc vàng" class="cat-filter-btn cat-nowrap px-3 py-1 rounded-full text-xs font-medium bg-white border border-stone-300 text-stone-700 hover:border-tram-primary transition">
          Vòng trầm hương bọc vàng
        </button>
        <button onclick="filterByCategory('Trầm chìm vip cao cấp')" data-cat="Trầm chìm vip cao cấp" class="cat-filter-btn cat-nowrap px-3 py-1 rounded-full text-xs font-medium bg-white border border-stone-300 text-stone-700 hover:border-tram-primary transition">
          Trầm chìm VIP cao cấp
        </button>
        <button onclick="filterByCategory('Mặt tượng đeo cổ')" data-cat="Mặt tượng đeo cổ" class="cat-filter-btn cat-nowrap px-3 py-1 rounded-full text-xs font-medium bg-white border border-stone-300 text-stone-700 hover:border-tram-primary transition">
          Mặt tượng đeo cổ
        </button>
        <button onclick="filterByCategory('Nhang trầm - Thác lư xông')" data-cat="Nhang trầm - Thác lư xông" class="cat-filter-btn cat-nowrap px-3 py-1 rounded-full text-xs font-medium bg-white border border-stone-300 text-stone-700 hover:border-tram-primary transition">
          Nhang trầm - Thác lư xông
        </button>
        <button onclick="filterByCategory('Trầm hương miếng - giác xông')" data-cat="Trầm hương miếng - giác xông" class="cat-filter-btn cat-nowrap px-3 py-1 rounded-full text-xs font-medium bg-white border border-stone-300 text-stone-700 hover:border-tram-primary transition">
          Trầm hương miếng - Giác xông
        </button>
        <button onclick="filterByCategory('Tranh - tượng trầm cảnh')" data-cat="Tranh - tượng trầm cảnh" class="cat-filter-btn cat-nowrap px-3 py-1 rounded-full text-xs font-medium bg-white border border-stone-300 text-stone-700 hover:border-tram-primary transition">
          Tranh - Tượng trầm cảnh
        </button>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 3: SẢN PHẨM BÁN CHẠY & DANH MỤC SẢN PHẨM TRANG CHỦ
       - Sử dụng toàn bộ 14 ảnh sản phẩm thực tế từ Google Drive
       - Chia 2 cột trên điện thoại (grid-cols-2), 4-5 cột trên máy tính
       - Chỉ hiển thị % giảm giá góc trên bên trái giống Flatsome, KHÔNG để nhãn dán phụ
       - Tên sản phẩm hiển thị đầy đủ, không bị tràn hay thiếu chữ
       ===================================================================== -->
  <section id="san-pham-ban-chay" class="py-4">
    <div class="container-1500">
      <div class="flatsome-section-title">
        <b></b>
        <span id="currentCategoryHeading" class="text-base sm:text-lg md:text-xl">SẢN PHẨM TRẦM HƯƠNG NỔI BẬT</span>
        <b></b>
      </div>

      <!-- Lưới sản phẩm: 2 cột trên điện thoại, 3 cột tablet, 4-5 cột desktop -->
      <div id="mainProductGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 gap-2.5 sm:gap-4">
        <!-- Được render tự động bằng JavaScript từ danh sách 14 ảnh thực tế -->
      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 4: CHUYÊN MỤC VÒNG TAY PHONG THỦY & CHUỖI TRẦM HƯƠNG (Giống bố cục tramhuongdanang.vn)
       ===================================================================== -->
  <section class="py-5">
    <div class="container-1500">
      <!-- Thanh tiêu đề ngang màu nâu trầm đặc trưng Flatsome -->
      <div class="bg-tram-primary text-white rounded-t-lg px-3.5 py-2.5 flex flex-wrap items-center justify-between gap-2">
        <h2 class="font-bold text-sm sm:text-base uppercase tracking-wide flex items-center gap-2">
          <i class="fa-solid fa-gem text-tram-gold"></i>
          <span>VÒNG TAY PHONG THỦY & CHUỖI TRẦM HƯƠNG</span>
        </h2>
        <div class="flex flex-wrap items-center gap-1.5 text-[11px] sm:text-xs">
          <button onclick="filterByCategory('Chuỗi trầm hương')" class="cat-nowrap px-2 py-0.5 rounded bg-amber-900/60 hover:bg-amber-800 text-amber-100">Chuỗi 108 hạt</button>
          <button onclick="filterByCategory('Chuỗi trầm hương')" class="cat-nowrap px-2 py-0.5 rounded bg-amber-900/60 hover:bg-amber-800 text-amber-100">Chuỗi mix charm</button>
          <button onclick="filterByCategory('Vòng trầm hương bọc vàng')" class="cat-nowrap px-2 py-0.5 rounded bg-amber-900/60 hover:bg-amber-800 text-amber-100">Vòng bọc vàng</button>
          <button onclick="filterByCategory('Vòng tay phong thủy')" class="cat-nowrap px-2 py-0.5 rounded bg-amber-900/60 hover:bg-amber-800 text-amber-100">Vòng đơn Nam/Nữ</button>
        </div>
      </div>

      <div id="braceletProductGrid" class="bg-white border border-t-0 border-stone-200 rounded-b-lg p-2.5 sm:p-4 grid grid-cols-2 md:grid-cols-4 gap-2.5 sm:gap-4">
        <!-- Render 8 sản phẩm thuộc nhóm Chuỗi & Vòng tay -->
      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 5: CHUYÊN MỤC VẬT PHẨM PHONG THỦY - NHANG TRẦM - GIÁC XÔNG
       ===================================================================== -->
  <section class="py-4">
    <div class="container-1500">
      <div class="bg-tram-primary text-white rounded-t-lg px-3.5 py-2.5 flex flex-wrap items-center justify-between gap-2">
        <h2 class="font-bold text-sm sm:text-base uppercase tracking-wide flex items-center gap-2">
          <i class="fa-solid fa-fire-flame-simple text-tram-gold"></i>
          <span>VẬT PHẨM PHONG THỦY • NHANG TRẦM • TRẦM MIẾNG XÔNG NHÀ</span>
        </h2>
        <div class="flex flex-wrap items-center gap-1.5 text-[11px] sm:text-xs">
          <button onclick="filterByCategory('Mặt tượng đeo cổ')" class="cat-nowrap px-2 py-0.5 rounded bg-amber-900/60 hover:bg-amber-800 text-amber-100">Mặt tượng đeo cổ</button>
          <button onclick="filterByCategory('Nhang trầm - Thác lư xông')" class="cat-nowrap px-2 py-0.5 rounded bg-amber-900/60 hover:bg-amber-800 text-amber-100">Nhang trầm - Thác lư</button>
          <button onclick="filterByCategory('Trầm hương miếng - giác xông')" class="cat-nowrap px-2 py-0.5 rounded bg-amber-900/60 hover:bg-amber-800 text-amber-100">Trầm miếng giác xông</button>
          <button onclick="filterByCategory('Tranh - tượng trầm cảnh')" class="cat-nowrap px-2 py-0.5 rounded bg-amber-900/60 hover:bg-amber-800 text-amber-100">Tranh - Tượng trầm cảnh</button>
        </div>
      </div>

      <div id="incenseProductGrid" class="bg-white border border-t-0 border-stone-200 rounded-b-lg p-2.5 sm:p-4 grid grid-cols-2 md:grid-cols-3 lg:grid-cols-6 gap-2.5 sm:gap-3.5">
        <!-- Render 6 sản phẩm vật phẩm phong thủy & nhang trầm -->
      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 6: HÌNH ẢNH THỰC TẾ CỬA HÀNG HỒN TRẦM HƯƠNG (2 ảnh thực tế cửa hàng từ Google Drive)
       ===================================================================== -->
  <section id="gioi-thieu-cua-hang" class="py-6">
    <div class="container-1500">
      <div class="flatsome-section-title">
        <b></b>
        <span class="text-base sm:text-lg md:text-xl">GIỚI THIỆU & HÌNH ẢNH THỰC TẾ CỬA HÀNG HỒN TRẦM HƯƠNG</span>
        <b></b>
      </div>

      <div class="bg-white border border-stone-200 rounded-lg p-4 sm:p-6 shadow-sm grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
        <!-- Cột nội dung giới thiệu chuẩn SEO như web mẫu -->
        <div class="lg:col-span-6 space-y-3 text-sm text-stone-700 leading-relaxed">
          <h3 class="font-serif font-bold text-lg sm:text-xl text-tram-primary">
            Hồn Trầm Hương – Địa Chỉ Trầm Hương Thiên Nhiên Uy Tín Tại Đà Nẵng
          </h3>
          <p>
            Tọa lạc tại <strong>79 Nguyễn Xí, Phường Hòa Khánh, Tp.Đà Nẵng</strong>, <strong>Hồn Trầm Hương (hontramhuong.com)</strong> là thương hiệu chuyên chế tác và cung cấp các dòng sản phẩm Trầm Hương thiên nhiên cao cấp: Chuỗi trầm hương 108 hạt, Vòng tay trầm hương phong thủy nam nữ, Trầm chìm VIP, Mặt tượng Phật trầm hương, Nhang trầm sạch không hóa chất và Trầm miếng giác xông.
          </p>
          <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 pt-1">
            <div class="p-3 rounded bg-amber-50/70 border border-amber-200/60">
              <p class="font-bold text-tram-primary text-xs uppercase mb-1"><i class="fa-solid fa-circle-check text-green-700 mr-1.5"></i>Trầm hương thiên nhiên 100%</p>
              <p class="text-xs text-stone-600">Cam kết nguồn gốc trầm tự nhiên rõ ràng, hương thơm thanh ngọt dịu nhẹ, càng đeo càng bóng đẹp.</p>
            </div>
            <div class="p-3 rounded bg-amber-50/70 border border-amber-200/60">
              <p class="font-bold text-tram-primary text-xs uppercase mb-1"><i class="fa-solid fa-circle-check text-green-700 mr-1.5"></i>Đa dạng mẫu mã phong thủy</p>
              <p class="text-xs text-stone-600">Đầy đủ chuỗi hạt 108 hạt, 216 hạt, vòng tay mix charm vàng 24K, đá quý hợp mệnh Kim - Mộc - Thủy - Hỏa - Thổ.</p>
            </div>
            <div class="p-3 rounded bg-amber-50/70 border border-amber-200/60">
              <p class="font-bold text-tram-primary text-xs uppercase mb-1"><i class="fa-solid fa-circle-check text-green-700 mr-1.5"></i>An toàn cho sức khỏe</p>
              <p class="text-xs text-stone-600">Nhang trầm và nụ trầm nguyên chất từ bột trầm sạch, giúp an thần, thanh lọc không khí và tụ vượng khí.</p>
            </div>
            <div class="p-3 rounded bg-amber-50/70 border border-amber-200/60">
              <p class="font-bold text-tram-primary text-xs uppercase mb-1"><i class="fa-solid fa-circle-check text-green-700 mr-1.5"></i>Tư vấn & bảo hành tận tâm</p>
              <p class="text-xs text-stone-600">Hỗ trợ thay dây, đánh bóng hạt trầm miễn phí và giao hàng tận nơi trên toàn quốc.</p>
            </div>
          </div>
        </div>

        <!-- Cột 2 ảnh thực tế cửa hàng từ file Google Drive -->
        <div class="lg:col-span-6 grid grid-cols-1 sm:grid-cols-2 gap-3.5">
          <div class="rounded-lg overflow-hidden border border-stone-200 shadow-sm bg-stone-100 flex flex-col">
            <div class="h-56 sm:h-64 w-full overflow-hidden">
              <img 
                src="https://drive.google.com/thumbnail?id=1QsWaCOmB-08_LLBqZ5-pTnMDHkQGg6i6&sz=w800" 
                data-drive-id="1QsWaCOmB-08_LLBqZ5-pTnMDHkQGg6i6"
                alt="Không gian trưng bày Hồn Trầm Hương 79 Nguyễn Xí" 
                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                onerror="handleDriveImgError(this, 'Ảnh Cửa Hàng 1')"
              >
            </div>
            <div class="p-2.5 bg-stone-50 text-center border-t border-stone-200">
              <p class="text-xs font-semibold text-tram-primary">Không gian trưng bày Hồn Trầm Hương</p>
              <p class="text-[11px] text-stone-500">79 Nguyễn Xí, P. Hòa Khánh, Tp. Đà Nẵng</p>
            </div>
          </div>

          <div class="rounded-lg overflow-hidden border border-stone-200 shadow-sm bg-stone-100 flex flex-col">
            <div class="h-56 sm:h-64 w-full overflow-hidden">
              <img 
                src="https://drive.google.com/thumbnail?id=1AYrLTBRNuj_idwmTf-AuZnCeco6yopBd&sz=w800" 
                data-drive-id="1AYrLTBRNuj_idwmTf-AuZnCeco6yopBd"
                alt="Kệ trưng bày sản phẩm thực tế tại Hồn Trầm Hương" 
                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                onerror="handleDriveImgError(this, 'Ảnh Cửa Hàng 2')"
              >
            </div>
            <div class="p-2.5 bg-stone-50 text-center border-t border-stone-200">
              <p class="text-xs font-semibold text-tram-primary">Sản phẩm trầm hương thực tế tại cửa hàng</p>
              <p class="text-[11px] text-stone-500">Hotline tư vấn: 0855.655.555</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 7: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ
       ===================================================================== -->
  <section id="form-bao-gia" class="py-6">
    <div class="container-1500">
      <div class="bg-gradient-to-r from-[#4a2508] via-[#5c2e0c] to-[#4a2508] rounded-lg p-4 sm:p-7 text-white shadow-md border border-amber-700/40">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
          
          <div class="lg:col-span-5 space-y-2.5">
            <span class="inline-block px-2.5 py-0.5 rounded bg-tram-gold text-stone-900 font-bold text-xs uppercase">
              Hỗ trợ khách hàng 24/7
            </span>
            <h2 class="font-serif font-bold text-xl sm:text-2xl text-white">
              ĐĂNG KÝ YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ SỈ / LẺ
            </h2>
            <p class="text-xs sm:text-sm text-amber-100/90 leading-relaxed">
              Quý khách cần tư vấn chọn vòng trầm hợp mệnh, đặt chế tác riêng hoặc nhận bảng báo giá sỉ/lẻ ưu đãi nhất từ <strong>Hồn Trầm Hương</strong>, vui lòng để lại thông tin bên cạnh.
            </p>
            <div class="pt-2 space-y-1.5 text-xs sm:text-sm text-amber-200">
              <p><i class="fa-solid fa-location-dot text-tram-gold mr-2"></i><strong>Địa chỉ:</strong> 79 Nguyễn Xí, Phường Hòa Khánh, Tp.Đà Nẵng</p>
              <p><i class="fa-solid fa-phone-volume text-tram-gold mr-2"></i><strong>Hotline / Zalo:</strong> 0855.655.555</p>
              <p><i class="fa-solid fa-globe text-tram-gold mr-2"></i><strong>Website:</strong> hontramhuong.com</p>
            </div>
          </div>

          <div class="lg:col-span-7 bg-white text-stone-800 rounded-lg p-4 sm:p-6 shadow">
            <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="space-y-3">
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                <div>
                  <label class="block text-xs font-bold text-stone-700 uppercase mb-1">Họ và tên quý khách *</label>
                  <input id="quoteName" type="text" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 text-sm border border-stone-300 rounded focus:outline-none focus:border-tram-primary">
                </div>
                <div>
                  <label class="block text-xs font-bold text-stone-700 uppercase mb-1">Số điện thoại / Zalo *</label>
                  <input id="quotePhone" type="tel" required placeholder="Ví dụ: 0905xxxxxx" class="w-full px-3 py-2 text-sm border border-stone-300 rounded focus:outline-none focus:border-tram-primary">
                </div>
              </div>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                <div>
                  <label class="block text-xs font-bold text-stone-700 uppercase mb-1">Danh mục quan tâm</label>
                  <select id="quoteCategory" class="w-full px-3 py-2 text-sm border border-stone-300 rounded focus:outline-none focus:border-tram-primary bg-white">
                    <option value="Chuỗi trầm hương 108 hạt">Chuỗi trầm hương 108 hạt / 216 hạt</option>
                    <option value="Vòng tay phong thủy Nam Nữ">Vòng tay phong thủy Nam / Nữ</option>
                    <option value="Vòng trầm hương bọc vàng">Vòng trầm hương bọc vàng</option>
                    <option value="Trầm chìm VIP cao cấp">Trầm chìm VIP cao cấp</option>
                    <option value="Mặt tượng đeo cổ">Mặt tượng Phật trầm hương đeo cổ</option>
                    <option value="Nhang trầm - Thác lư xông">Nhang trầm sạch - Thác lư xông</option>
                    <option value="Trầm hương miếng - Giác xông">Trầm hương miếng - Giác xông nhà</option>
                    <option value="Đăng ký đại lý / Báo giá sỉ">Đăng ký đại lý / Nhận báo giá sỉ</option>
                  </select>
                </div>
                <div>
                  <label class="block text-xs font-bold text-stone-700 uppercase mb-1">Ngân sách dự kiến / Số lượng</label>
                  <input id="quoteBudget" type="text" placeholder="Ví dụ: 1 chiếc làm quà tặng, hoặc lấy sỉ..." class="w-full px-3 py-2 text-sm border border-stone-300 rounded focus:outline-none focus:border-tram-primary">
                </div>
              </div>

              <div>
                <label class="block text-xs font-bold text-stone-700 uppercase mb-1">Nội dung yêu cầu chi tiết</label>
                <textarea id="quoteNote" rows="2" placeholder="Nhập năm sinh để tư vấn hợp mệnh hoặc tên sản phẩm cần báo giá..." class="w-full px-3 py-2 text-sm border border-stone-300 rounded focus:outline-none focus:border-tram-primary"></textarea>
              </div>

              <div class="flex flex-wrap items-center justify-between gap-3 pt-1">
                <span class="text-[11.5px] text-stone-500">
                  <i class="fa-solid fa-shield-halved text-tram-primary mr-1"></i>Cam kết bảo mật thông tin khách hàng 100%
                </span>
                <button type="submit" class="px-6 py-2.5 rounded bg-tram-primary hover:bg-tram-dark text-white font-bold text-xs sm:text-sm uppercase tracking-wide transition shadow">
                  <i class="fa-solid fa-paper-plane mr-1.5"></i>Gửi yêu cầu & Nhận báo giá
                </button>
              </div>
            </form>
          </div>

        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 8: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (KIẾN THỨC PHONG THỦY & TIN TỨC)
       ===================================================================== -->
  <section id="kien-thuc-tram-huong" class="py-6">
    <div class="container-1500">
      <div class="flatsome-section-title">
        <b></b>
        <span class="text-base sm:text-lg md:text-xl">KIẾN THỨC TRẦM HƯƠNG & PHONG THỦY</span>
        <b></b>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
        
        <!-- Bài viết 1 -->
        <article class="bg-white border border-stone-200 rounded-lg overflow-hidden shadow-sm hover:shadow transition flex flex-col">
          <div class="h-44 overflow-hidden bg-stone-100 relative">
            <img src="https://drive.google.com/thumbnail?id=1p54no0Jv1jNwTLCDFmFY4ht6dnkFis4-&sz=w600" data-drive-id="1p54no0Jv1jNwTLCDFmFY4ht6dnkFis4-" alt="Trầm Hương Chìm Nước Là Gì" class="w-full h-full object-cover hover:scale-105 transition duration-500" onerror="handleDriveImgError(this, 'Kiến thức Trầm Hương')">
          </div>
          <div class="p-3.5 flex-1 flex flex-col justify-between space-y-2">
            <div>
              <span class="text-[11px] text-tram-medium font-semibold uppercase">Kiến thức trầm hương</span>
              <h3 class="font-bold text-sm text-stone-800 hover:text-tram-primary transition mt-1 leading-snug">
                Trầm Hương Chìm Nước Là Gì? Vì Sao Giá Trị Cao Hơn Các Loại Trầm Khác?
              </h3>
              <p class="text-xs text-stone-600 mt-1.5 leading-relaxed">
                Tìm hiểu nguyên nhân vì sao lượng tinh dầu kết tinh dày đặc trong thớ gỗ giúp trầm hương chìm hoàn toàn trong nước và mang giá trị sưu tầm cao.
              </p>
            </div>
            <button onclick="openArticleModal(0)" class="text-xs font-bold text-tram-primary hover:underline inline-flex items-center gap-1 pt-1">
              Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
            </button>
          </div>
        </article>

        <!-- Bài viết 2 -->
        <article class="bg-white border border-stone-200 rounded-lg overflow-hidden shadow-sm hover:shadow transition flex flex-col">
          <div class="h-44 overflow-hidden bg-stone-100 relative">
            <img src="https://drive.google.com/thumbnail?id=1KTqlhzv4dCxi9NoTfDhOi8GGjvnJ6MDK&sz=w600" data-drive-id="1KTqlhzv4dCxi9NoTfDhOi8GGjvnJ6MDK" alt="Cách phân biệt trầm hương thật giả" class="w-full h-full object-cover hover:scale-105 transition duration-500" onerror="handleDriveImgError(this, 'Phân biệt Trầm thật giả')">
          </div>
          <div class="p-3.5 flex-1 flex flex-col justify-between space-y-2">
            <div>
              <span class="text-[11px] text-tram-medium font-semibold uppercase">Kinh nghiệm chọn trầm</span>
              <h3 class="font-bold text-sm text-stone-800 hover:text-tram-primary transition mt-1 leading-snug">
                Cách Phân Biệt Trầm Hương Thật Giả Chuẩn Xác Từ Chuyên Gia
              </h3>
              <p class="text-xs text-stone-600 mt-1.5 leading-relaxed">
                Hướng dẫn quan sát vân dầu tự nhiên, cảm nhận mùi hương thanh ngọt dịu nhẹ và kiểm tra độ nặng để nhận biết vòng trầm hương tự nhiên 100%.
              </p>
            </div>
            <button onclick="openArticleModal(1)" class="text-xs font-bold text-tram-primary hover:underline inline-flex items-center gap-1 pt-1">
              Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
            </button>
          </div>
        </article>

        <!-- Bài viết 3 -->
        <article class="bg-white border border-stone-200 rounded-lg overflow-hidden shadow-sm hover:shadow transition flex flex-col">
          <div class="h-44 overflow-hidden bg-stone-100 relative">
            <img src="https://drive.google.com/thumbnail?id=16rsPA9mYKMwxMniZTowZoyrqN2BivGV-&sz=w600" data-drive-id="16rsPA9mYKMwxMniZTowZoyrqN2BivGV-" alt="Đeo vòng tay trầm hương có tác dụng gì" class="w-full h-full object-cover hover:scale-105 transition duration-500" onerror="handleDriveImgError(this, 'Công dụng vòng trầm')">
          </div>
          <div class="p-3.5 flex-1 flex flex-col justify-between space-y-2">
            <div>
              <span class="text-[11px] text-tram-medium font-semibold uppercase">Kiến thức phong thủy</span>
              <h3 class="font-bold text-sm text-stone-800 hover:text-tram-primary transition mt-1 leading-snug">
                Đeo Vòng Tay Trầm Hương Có Tác Dụng Gì? 4 Công Dụng Phong Thủy
              </h3>
              <p class="text-xs text-stone-600 mt-1.5 leading-relaxed">
                Vòng tay trầm hương không chỉ là món trang sức sang trọng mà còn giúp an thần, giảm căng thẳng, thu hút bình an và tài lộc cho chủ nhân.
              </p>
            </div>
            <button onclick="openArticleModal(2)" class="text-xs font-bold text-tram-primary hover:underline inline-flex items-center gap-1 pt-1">
              Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
            </button>
          </div>
        </article>

        <!-- Bài viết 4 -->
        <article class="bg-white border border-stone-200 rounded-lg overflow-hidden shadow-sm hover:shadow transition flex flex-col">
          <div class="h-44 overflow-hidden bg-stone-100 relative">
            <img src="https://drive.google.com/thumbnail?id=12Stw_Q95muFUNLuapH2h6W0fWNxEWdvs&sz=w600" data-drive-id="12Stw_Q95muFUNLuapH2h6W0fWNxEWdvs" alt="Trầm hương xông nhà có tác dụng gì" class="w-full h-full object-cover hover:scale-105 transition duration-500" onerror="handleDriveImgError(this, 'Trầm hương xông nhà')">
          </div>
          <div class="p-3.5 flex-1 flex flex-col justify-between space-y-2">
            <div>
              <span class="text-[11px] text-tram-medium font-semibold uppercase">Thưởng trầm & Đời sống</span>
              <h3 class="font-bold text-sm text-stone-800 hover:text-tram-primary transition mt-1 leading-snug">
                Trầm Hương Xông Nhà Có Tác Dụng Gì? Cách Đốt Nụ & Giác Xông Đúng Chuẩn
              </h3>
              <p class="text-xs text-stone-600 mt-1.5 leading-relaxed">
                Khám phá nghệ thuật xông nhà bằng trầm miếng, bột trầm và nụ trầm hương giúp thanh tẩy uế khí, làm ấm không gian thờ cúng và phòng khách.
              </p>
            </div>
            <button onclick="openArticleModal(3)" class="text-xs font-bold text-tram-primary hover:underline inline-flex items-center gap-1 pt-1">
              Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
            </button>
          </div>
        </article>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 9: ĐƯA ẢNH GOOGLE MAP & FANPAGE RA NGOÀI TRANG CHỦ
       - Địa chỉ: 79 Nguyễn Xí, Phường Hòa Khánh, Tp.Đà Nẵng
       - Link Google Map: https://maps.app.goo.gl/UTxqSSACZCgLfs6J9
       - Link Fanpage: https://www.facebook.com/saneespa55
       ===================================================================== -->
  <section id="ban-do-fanpage" class="py-6">
    <div class="container-1500">
      <div class="flatsome-section-title">
        <b></b>
        <span class="text-base sm:text-lg md:text-xl">BẢN ĐỒ ĐƯỜNG ĐI & FANPAGE HỒN TRẦM HƯƠNG</span>
        <b></b>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-5">
        
        <!-- Cột Bản đồ Google Map ngoài trang chủ (7 phần) -->
        <div class="lg:col-span-7 bg-white border border-stone-200 rounded-lg overflow-hidden shadow-sm flex flex-col">
          <div class="p-3.5 bg-stone-50 border-b border-stone-200 flex flex-wrap items-center justify-between gap-2">
            <div>
              <h3 class="font-bold text-sm text-tram-primary uppercase flex items-center gap-1.5">
                <i class="fa-solid fa-map-location-dot text-tram-sale"></i>
                <span>Bản Đồ Cửa Hàng: 79 Nguyễn Xí, Phường Hòa Khánh, Tp.Đà Nẵng</span>
              </h3>
              <p class="text-xs text-stone-500 mt-0.5">Mở cửa: 08:00 – 21:30 tất cả các ngày trong tuần • Hotline: 0855.655.555</p>
            </div>
            <a 
              href="https://maps.app.goo.gl/UTxqSSACZCgLfs6J9" 
              target="_blank" 
              rel="noopener" 
              class="px-3 py-1.5 rounded bg-tram-primary hover:bg-tram-dark text-white text-xs font-medium inline-flex items-center gap-1.5 transition"
            >
              <i class="fa-solid fa-diamond-turn-right"></i> Mở Google Maps
            </a>
          </div>
          
          <!-- Khung Google Map trực quan ngoài trang chủ -->
          <div class="w-full h-[300px] sm:h-[340px] bg-stone-100 relative">
            <iframe 
              title="Bản đồ Hồn Trầm Hương 79 Nguyễn Xí Đà Nẵng"
              src="https://maps.google.com/maps?q=79%20Nguy%E1%BB%85n%20X%C3%AD,%20H%C3%B2a%20Kh%C3%A1nh,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed" 
              class="w-full h-full border-0" 
              allowfullscreen="" 
              loading="lazy" 
              referrerpolicy="no-referrer-when-downgrade">
            </iframe>
          </div>
        </div>

        <!-- Cột Fanpage Facebook ngoài trang chủ (5 phần) -->
        <div class="lg:col-span-5 bg-white border border-stone-200 rounded-lg overflow-hidden shadow-sm flex flex-col justify-between">
          <div class="p-3.5 bg-stone-50 border-b border-stone-200 flex items-center justify-between">
            <h3 class="font-bold text-sm text-tram-primary uppercase flex items-center gap-1.5">
              <i class="fa-brands fa-facebook text-[#1877F2] text-base"></i>
              <span>Fanpage Chính Thức Hồn Trầm Hương</span>
            </h3>
            <a href="https://www.facebook.com/saneespa55" target="_blank" rel="noopener" class="text-xs font-semibold text-[#1877F2] hover:underline">
              Theo dõi trang
            </a>
          </div>

          <!-- Thẻ Fanpage trực quan kèm Iframe Plugin Facebook -->
          <div class="p-4 space-y-3 flex-1 flex flex-col justify-between">
            <div class="relative rounded-lg overflow-hidden border border-stone-200 bg-gradient-to-r from-[#3b1c05] to-[#5c2e0c] p-3.5 text-white flex items-center gap-3">
              <img 
                src="https://drive.google.com/thumbnail?id=1-L1skYj1KMQJBqxAngxJJn1xi09XjthK&sz=w200" 
                data-drive-id="1-L1skYj1KMQJBqxAngxJJn1xi09XjthK"
                alt="Avatar Fanpage Hồn Trầm Hương" 
                class="w-14 h-14 rounded-full object-contain bg-white p-0.5 border-2 border-tram-gold flex-shrink-0"
                onerror="handleDriveImgError(this, 'Logo')"
              >
              <div class="min-w-0 flex-1">
                <a href="https://www.facebook.com/saneespa55" target="_blank" rel="noopener" class="font-bold text-base text-white hover:underline block truncate">
                  Hồn Trầm Hương - Đà Nẵng
                </a>
                <p class="text-xs text-amber-200 truncate">facebook.com/saneespa55</p>
                <div class="mt-2 flex flex-wrap items-center gap-2">
                  <a href="https://www.facebook.com/saneespa55" target="_blank" rel="noopener" class="px-2.5 py-1 rounded bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-medium inline-flex items-center gap-1">
                    <i class="fa-brands fa-facebook-f"></i> Thích Trang
                  </a>
                  <a href="https://www.facebook.com/saneespa55" target="_blank" rel="noopener" class="px-2.5 py-1 rounded bg-white/15 hover:bg-white/25 text-white text-xs font-medium inline-flex items-center gap-1">
                    <i class="fa-brands fa-facebook-messenger"></i> Nhắn tin
                  </a>
                </div>
              </div>
            </div>

            <!-- Nhúng Facebook Page Plugin chuẩn -->
            <div class="w-full overflow-hidden rounded border border-stone-200 bg-stone-50 flex justify-center">
              <iframe 
                title="Facebook Fanpage Hồn Trầm Hương"
                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fsaneespa55&tabs=timeline&width=380&height=210&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                width="380" 
                height="210" 
                style="border:none;overflow:hidden;max-width:100%;" 
                scrolling="no" 
                frameborder="0" 
                allowfullscreen="true" 
                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
              </iframe>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       FOOTER (Chân trang chuẩn cấu trúc Flatsome tramhuongdanang.vn)
       ===================================================================== -->
  <footer class="bg-tram-dark text-amber-100/90 pt-8 pb-6 border-t-4 border-tram-gold mt-4">
    <div class="container-1500">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-amber-900/50 text-xs sm:text-sm">
        
        <!-- Cột 1: Thông tin liên hệ -->
        <div class="space-y-2.5">
          <div class="flex items-center gap-2.5">
            <img 
              src="https://drive.google.com/thumbnail?id=1-L1skYj1KMQJBqxAngxJJn1xi09XjthK&sz=w200" 
              data-drive-id="1-L1skYj1KMQJBqxAngxJJn1xi09XjthK"
              alt="Logo Hồn Trầm Hương" 
              class="w-10 h-10 rounded-full object-contain bg-white p-0.5"
              onerror="handleDriveImgError(this, 'Logo')"
            >
            <div>
              <h4 class="font-serif font-bold text-base text-tram-goldlight uppercase">HỒN TRẦM HƯƠNG</h4>
              <p class="text-[11px] text-amber-200/80">hontramhuong.com</p>
            </div>
          </div>
          <p class="text-xs leading-relaxed text-amber-100/80">
            Chuyên cung cấp các sản phẩm trầm hương phong thủy thiên nhiên: Chuỗi hạt 108 hạt, vòng tay trầm hương, nhang trầm, thác khói, trầm cảnh, giác xông và quà tặng cao cấp.
          </p>
          <ul class="space-y-1.5 text-xs pt-1">
            <li><i class="fa-solid fa-location-dot text-tram-gold mr-2"></i><strong>Địa chỉ:</strong> 79 Nguyễn Xí, Phường Hòa Khánh, Tp.Đà Nẵng</li>
            <li><i class="fa-solid fa-phone text-tram-gold mr-2"></i><strong>Hotline / Zalo:</strong> <a href="tel:0855655555" class="text-tram-goldlight font-bold hover:underline">0855.655.555</a></li>
            <li><i class="fa-solid fa-globe text-tram-gold mr-2"></i><strong>Website:</strong> <a href="https://hontramhuong.com" class="hover:underline">hontramhuong.com</a></li>
            <li><i class="fa-brands fa-facebook text-tram-gold mr-2"></i><strong>Fanpage:</strong> <a href="https://www.facebook.com/saneespa55" target="_blank" rel="noopener" class="hover:underline">fb.com/saneespa55</a></li>
          </ul>
        </div>

        <!-- Cột 2: Danh mục sản phẩm -->
        <div class="space-y-2">
          <h4 class="font-bold text-sm text-tram-goldlight uppercase tracking-wide pb-1 border-b border-amber-800/60">
            DANH MỤC SẢN PHẨM
          </h4>
          <ul class="space-y-1.5 text-xs">
            <li><button onclick="filterByCategory('Chuỗi trầm hương')" class="hover:text-tram-gold transition">• Chuỗi trầm hương 108 hạt & 216 hạt</button></li>
            <li><button onclick="filterByCategory('Vòng tay phong thủy')" class="hover:text-tram-gold transition">• Vòng tay trầm hương phong thủy</button></li>
            <li><button onclick="filterByCategory('Vòng trầm hương bọc vàng')" class="hover:text-tram-gold transition">• Vòng trầm hương bọc vàng</button></li>
            <li><button onclick="filterByCategory('Trầm chìm vip cao cấp')" class="hover:text-tram-gold transition">• Trầm chìm VIP cao cấp</button></li>
            <li><button onclick="filterByCategory('Mặt tượng đeo cổ')" class="hover:text-tram-gold transition">• Mặt tượng trầm hương đeo cổ</button></li>
            <li><button onclick="filterByCategory('Nhang trầm - Thác lư xông')" class="hover:text-tram-gold transition">• Nhang trầm sạch - Thác lư xông</button></li>
            <li><button onclick="filterByCategory('Trầm hương miếng - giác xông')" class="hover:text-tram-gold transition">• Trầm hương miếng - Giác xông</button></li>
            <li><button onclick="filterByCategory('Tranh - tượng trầm cảnh')" class="hover:text-tram-gold transition">• Tranh - Tượng trầm cảnh</button></li>
          </ul>
        </div>

        <!-- Cột 3: Chính sách khách hàng -->
        <div class="space-y-2">
          <h4 class="font-bold text-sm text-tram-goldlight uppercase tracking-wide pb-1 border-b border-amber-800/60">
            CHÍNH SÁCH & HỖ TRỢ
          </h4>
          <ul class="space-y-1.5 text-xs">
            <li><a href="#form-bao-gia" class="hover:text-tram-gold transition">• Hướng dẫn mua hàng & Đặt hàng</a></li>
            <li><a href="#form-bao-gia" class="hover:text-tram-gold transition">• Chính sách bảo hành trọn đời</a></li>
            <li><a href="#form-bao-gia" class="hover:text-tram-gold transition">• Chính sách đổi trả sản phẩm</a></li>
            <li><a href="#form-bao-gia" class="hover:text-tram-gold transition">• Hình thức vận chuyển & Giao nhận</a></li>
            <li><a href="#form-bao-gia" class="hover:text-tram-gold transition">• Phương thức thanh toán</a></li>
            <li><a href="#form-bao-gia" class="hover:text-tram-gold transition">• Chính sách đại lý & Khách sỉ</a></li>
          </ul>
        </div>

        <!-- Cột 4: Kết nối & Bản đồ nhanh -->
        <div class="space-y-2.5">
          <h4 class="font-bold text-sm text-tram-goldlight uppercase tracking-wide pb-1 border-b border-amber-800/60">
            KẾT NỐI VỚI CHÚNG TÔI
          </h4>
          <p class="text-xs text-amber-100/80">
            Đến trực tiếp cửa hàng Hồn Trầm Hương tại 79 Nguyễn Xí, Phường Hòa Khánh, Tp.Đà Nẵng để thưởng trầm và trải nghiệm thực tế.
          </p>
          <div class="flex flex-wrap gap-2 pt-1">
            <a href="https://maps.app.goo.gl/UTxqSSACZCgLfs6J9" target="_blank" rel="noopener" class="px-3 py-1.5 rounded bg-amber-800/80 hover:bg-amber-700 text-amber-100 text-xs inline-flex items-center gap-1.5 transition">
              <i class="fa-solid fa-map-pin text-tram-gold"></i> Xem Bản Đồ
            </a>
            <a href="https://www.facebook.com/saneespa55" target="_blank" rel="noopener" class="px-3 py-1.5 rounded bg-[#1877F2] hover:bg-blue-700 text-white text-xs inline-flex items-center gap-1.5 transition">
              <i class="fa-brands fa-facebook-f"></i> Fanpage
            </a>
          </div>
        </div>

      </div>

      <div class="pt-4 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-amber-200/70 text-center sm:text-left">
        <p>Copyright 2026 © <strong>hontramhuong.com</strong> - Hồn Trầm Hương Đà Nẵng (79 Nguyễn Xí, P. Hòa Khánh, Tp.Đà Nẵng).</p>
        <p>Hotline tư vấn: <strong>0855.655.555</strong></p>
      </div>
    </div>
  </footer>

  <!-- =====================================================================
       CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI
       ===================================================================== -->
  <div class="fixed bottom-4 right-3 sm:bottom-6 sm:right-5 z-40 flex flex-col items-end gap-2.5">
    
    <!-- Nút Facebook Fanpage -->
    <a 
      href="https://www.facebook.com/saneespa55" 
      target="_blank" 
      rel="noopener" 
      aria-label="Chat Facebook Hồn Trầm Hương"
      class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white rounded-full p-2.5 sm:px-3.5 sm:py-2 shadow-lg transition"
    >
      <i class="fa-brands fa-facebook-messenger text-lg sm:text-base"></i>
      <span class="hidden sm:inline text-xs font-bold">Facebook</span>
    </a>

    <!-- Nút Chat Zalo 0855.655.555 -->
    <a 
      href="https://zalo.me/0855655555" 
      target="_blank" 
      rel="noopener" 
      aria-label="Chat Zalo 0855.655.555"
      class="group flex items-center gap-2 bg-[#0068ff] hover:bg-blue-600 text-white rounded-full p-2.5 sm:px-3.5 sm:py-2 shadow-lg transition"
    >
      <span class="font-extrabold text-xs sm:text-sm leading-none px-0.5">Zalo</span>
      <span class="hidden sm:inline text-xs font-bold">0855.655.555</span>
    </a>

    <!-- Nút Gọi Hotline nổi bật -->
    <a 
      href="tel:0855655555" 
      aria-label="Gọi ngay 0855.655.555"
      class="pulse-contact flex items-center gap-2 bg-tram-sale hover:bg-red-800 text-white rounded-full px-3.5 py-2.5 shadow-xl transition"
    >
      <i class="fa-solid fa-phone-volume text-sm sm:text-base"></i>
      <span class="text-xs sm:text-sm font-bold tracking-wide">0855.655.555</span>
    </a>

  </div>

  <!-- =====================================================================
       MODAL XEM CHI TIẾT SẢN PHẨM & ĐẶT HÀNG NHANH
       ===================================================================== -->
  <div id="productModal" class="fixed inset-0 bg-black/60 z-50 hidden items-center justify-center p-3">
    <div class="bg-white rounded-lg max-w-2xl w-full overflow-hidden shadow-2xl border border-stone-200 max-h-[90vh] overflow-y-auto">
      <div class="flex items-center justify-between px-4 py-3 bg-tram-primary text-white">
        <h3 id="modalProductCategory" class="font-bold text-xs sm:text-sm uppercase tracking-wider">CHI TIẾT SẢN PHẨM</h3>
        <button onclick="closeProductModal()" type="button" class="text-white/80 hover:text-white p-1">
          <i class="fa-solid fa-xmark text-lg"></i>
        </button>
      </div>
      <div class="p-4 sm:p-6 grid grid-cols-1 sm:grid-cols-12 gap-5 items-start">
        <div class="sm:col-span-5 rounded-lg overflow-hidden border border-stone-200 bg-stone-100 relative">
          <span id="modalProductDiscount" class="flatsome-badge-sale">-15%</span>
          <img id="modalProductImg" src="" alt="" class="w-full h-64 sm:h-72 object-cover">
        </div>
        <div class="sm:col-span-7 space-y-3">
          <h4 id="modalProductName" class="font-bold text-base sm:text-lg text-stone-800 leading-snug"></h4>
          <div class="flex items-baseline gap-2.5">
            <span id="modalProductOldPrice" class="text-sm text-stone-400 line-through"></span>
            <span id="modalProductPrice" class="text-xl font-bold text-tram-sale"></span>
          </div>
          <p id="modalProductDesc" class="text-xs sm:text-sm text-stone-600 leading-relaxed"></p>
          <div class="p-3 rounded bg-amber-50 border border-amber-200 text-xs text-stone-700 space-y-1">
            <p><i class="fa-solid fa-check text-green-700 mr-1.5"></i>Cam kết Trầm Hương tự nhiên 100% tại Hồn Trầm Hương</p>
            <p><i class="fa-solid fa-location-dot text-tram-primary mr-1.5"></i>Xem hàng trực tiếp: 79 Nguyễn Xí, P. Hòa Khánh, Tp.Đà Nẵng</p>
            <p><i class="fa-solid fa-phone text-tram-primary mr-1.5"></i>Tư vấn & Đặt hàng nhanh: <strong>0855.655.555</strong></p>
          </div>
          <div class="pt-2 flex flex-wrap items-center gap-2.5">
            <button id="modalAddToCartBtn" type="button" class="flex-1 py-2.5 px-4 rounded bg-tram-primary hover:bg-tram-dark text-white font-bold text-xs uppercase tracking-wide transition">
              <i class="fa-solid fa-cart-plus mr-1.5"></i>Thêm vào giỏ hàng
            </button>
            <a href="https://zalo.me/0855655555" target="_blank" rel="noopener" class="py-2.5 px-4 rounded bg-[#0068ff] hover:bg-blue-700 text-white font-bold text-xs uppercase tracking-wide transition">
              Chat Zalo tư vấn
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- MODAL XEM BÀI VIẾT KIẾN THỨC -->
  <div id="articleModal" class="fixed inset-0 bg-black/60 z-50 hidden items-center justify-center p-3">
    <div class="bg-white rounded-lg max-w-xl w-full overflow-hidden shadow-2xl border border-stone-200 max-h-[88vh] overflow-y-auto">
      <div class="flex items-center justify-between px-4 py-3 bg-tram-primary text-white">
        <h3 class="font-bold text-xs sm:text-sm uppercase">KIẾN THỨC TRẦM HƯƠNG & PHONG THỦY</h3>
        <button onclick="closeArticleModal()" type="button" class="text-white/80 hover:text-white p-1">
          <i class="fa-solid fa-xmark text-lg"></i>
        </button>
      </div>
      <div class="p-4 sm:p-6 space-y-3">
        <h4 id="articleModalTitle" class="font-serif font-bold text-lg text-tram-primary"></h4>
        <div id="articleModalBody" class="text-xs sm:text-sm text-stone-700 space-y-2.5 leading-relaxed"></div>
      </div>
    </div>
  </div>

  <!-- MODAL GIỎ HÀNG -->
  <div id="cartModal" class="fixed inset-0 bg-black/60 z-50 hidden items-center justify-center p-3">
    <div class="bg-white rounded-lg max-w-lg w-full overflow-hidden shadow-2xl border border-stone-200">
      <div class="flex items-center justify-between px-4 py-3 bg-tram-primary text-white">
        <h3 class="font-bold text-sm uppercase"><i class="fa-solid fa-bag-shopping mr-1.5"></i>Giỏ Hàng Của Quý Khách</h3>
        <button onclick="closeCartModal()" type="button" class="text-white/80 hover:text-white p-1">
          <i class="fa-solid fa-xmark text-lg"></i>
        </button>
      </div>
      <div class="p-4 max-h-[60vh] overflow-y-auto" id="cartItemsContainer"></div>
      <div class="p-4 bg-stone-50 border-t border-stone-200 flex items-center justify-between">
        <div>
          <span class="text-xs text-stone-500 block">Tổng tạm tính:</span>
          <strong id="cartTotalAmount" class="text-base text-tram-sale">0₫</strong>
        </div>
        <button onclick="proceedToQuoteFromCart()" type="button" class="px-4 py-2 rounded bg-tram-primary hover:bg-tram-dark text-white text-xs font-bold uppercase transition">
          Gửi đơn đặt hàng
        </button>
      </div>
    </div>
  </div>

  <!-- HỘP THÔNG BÁO TÙY CHỈNH (Thay thế hoàn toàn alert/confirm) -->
  <div id="toastNotification" class="fixed top-16 right-4 z-50 hidden max-w-sm bg-tram-dark text-white px-4 py-3 rounded-lg shadow-xl border-l-4 border-tram-gold text-xs sm:text-sm items-center gap-2.5">
    <i class="fa-solid fa-circle-check text-tram-gold text-base"></i>
    <span id="toastMessage">Đã cập nhật!</span>
  </div>

  <!-- =====================================================================
       JAVASCRIPT XỬ LÝ DỮ LIỆU SẢN PHẨM, SLIDER, BỘ LỌC & FALLBACK ẢNH DRIVE
       ===================================================================== -->
  <script>
    // Hàm tự động chuyển đổi dự phòng nếu link ảnh Google Drive bị chặn hoặc chậm
    function handleDriveImgError(imgEl, fallbackTitle) {
      const fileId = imgEl.getAttribute('data-drive-id');
      const retryStage = parseInt(imgEl.getAttribute('data-retry') || '0', 10);

      if (fileId && retryStage === 0) {
        imgEl.setAttribute('data-retry', '1');
        imgEl.src = 'https://lh3.googleusercontent.com/d/' + fileId + '=w800';
      } else if (fileId && retryStage === 1) {
        imgEl.setAttribute('data-retry', '2');
        imgEl.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
      } else {
        imgEl.onerror = null;
        const encodedText = encodeURIComponent(fallbackTitle || 'Hon Tram Huong');
        imgEl.src = 'https://placehold.co/600x600/4a2508/f5d27b?text=' + encodedText;
      }
    }

    // Danh sách 14 sản phẩm thực tế từ 14 file Google Drive của khách hàng,
    // phân bổ đúng danh mục và tên sản phẩm chuẩn theo web mẫu tramhuongdanang.vn
    const productsData = [
      {
        id: 1,
        driveId: '1ReytPfRctosCWC1GAWXxZrZ8Y6JNkPOO',
        name: 'VÒNG TRẦM VIP GIÀ DẦU BANH ĐỎ 108 HẠT 8MM',
        category: 'Chuỗi trầm hương',
        group: 'bracelet',
        oldPrice: 18000000,
        price: 16000000,
        discount: '-11%',
        desc: 'Chuỗi vòng trầm hương 108 hạt 8mm già dầu banh đỏ tự nhiên, vân dầu rõ nét, hương thơm ngọt sâu chuẩn trầm hương thiên nhiên.'
      },
      {
        id: 2,
        driveId: '1fBsmeSpo4FOg1g9XgHlC5dTWjlQvlSOH',
        name: 'CHUỖI TRẦM HƯƠNG THIÊN NHIÊN 108 HẠT MIX CHARM SEN',
        category: 'Chuỗi trầm hương',
        group: 'bracelet',
        oldPrice: 1200000,
        price: 1000000,
        discount: '-17%',
        desc: 'Chuỗi 108 hạt trầm hương tự nhiên kết hợp charm hoa sen tinh tế, giúp tịnh tâm, an thần và thu hút may mắn bình an.'
      },
      {
        id: 3,
        driveId: '1p54no0Jv1jNwTLCDFmFY4ht6dnkFis4-',
        name: 'VÒNG TRẦM VIP CHÌM RIN TỪNG HẠT CAO CẤP',
        category: 'Trầm chìm vip cao cấp',
        group: 'bracelet',
        oldPrice: 25000000,
        price: 22000000,
        discount: '-12%',
        desc: 'Dòng trầm hương VIP cận chìm và chìm nước tuyển chọn từng hạt, hàm lượng tinh dầu trầm tích tụ lâu năm cực kỳ quý hiếm.'
      },
      {
        id: 4,
        driveId: '1W6oTRgr-AKquOvdlW-WxFpoc12nsq0XL',
        name: 'VÒNG TRẦM HƯƠNG TỐC KIẾN BỌC VÀNG PHONG THỦY',
        category: 'Vòng trầm hương bọc vàng',
        group: 'bracelet',
        oldPrice: 6800000,
        price: 6000000,
        discount: '-12%',
        desc: 'Vòng tay trầm hương tốc kiến tự nhiên phối charm bọc vàng sang trọng, mang lại tài lộc và vượng khí cho người đeo.'
      },
      {
        id: 5,
        driveId: '1KTqlhzv4dCxi9NoTfDhOi8GGjvnJ6MDK',
        name: 'VÒNG TAY TRẦM HƯƠNG ĐƠN NAM SIZE 12-14MM VÂN ĐẸP',
        category: 'Vòng tay phong thủy',
        group: 'bracelet',
        oldPrice: 1850000,
        price: 1500000,
        discount: '-19%',
        desc: 'Vòng trầm hương hạt tròn đơn dành cho nam kích thước 12-14mm mạnh mẽ, lịch lãm, sớ dầu tự nhiên thơm ngọt ấm.'
      },
      {
        id: 6,
        driveId: '16rsPA9mYKMwxMniZTowZoyrqN2BivGV-',
        name: 'VÒNG TRẦM HƯƠNG THIÊN NHIÊN MIX LU THỐNG PHONG THỦY',
        category: 'Vòng tay phong thủy',
        group: 'bracelet',
        oldPrice: 360000,
        price: 225000,
        discount: '-38%',
        desc: 'Vòng tay trầm hương thiên nhiên phối Lu Thống phong thủy giúp mọi việc hanh thông, thuận buồm xuôi gió.'
      },
      {
        id: 7,
        driveId: '1WeRGseSzRT3RIBu9utm6va7ve_W5-aW-',
        name: 'VÒNG TRẦM HƯƠNG SÁNH CHÌM ĐƠN NỮ MIX CHARM ĐÁ QUÝ',
        category: 'Vòng tay phong thủy',
        group: 'bracelet',
        oldPrice: 580000,
        price: 450000,
        discount: '-22%',
        desc: 'Thiết kế thanh lịch dành cho nữ từ trầm hương sánh chìm kết hợp charm đá phong thủy hợp mệnh.'
      },
      {
        id: 8,
        driveId: '18_RALfLafal-LeLKR6AhX1Xk-TjydsDD',
        name: 'COMBO VÒNG TRẦM HƯƠNG ĐEO CỔ VÀ VÒNG ĐEO TAY NAM',
        category: 'Chuỗi trầm hương',
        group: 'bracelet',
        oldPrice: 900000,
        price: 650000,
        discount: '-28%',
        desc: 'Bộ đôi chuỗi vòng trầm đeo cổ và vòng đeo tay đồng bộ, thích hợp làm quà tặng phong thủy cao cấp.'
      },
      {
        id: 9,
        driveId: '1dv2z9dYZ4BDQJo57WjG9p0YraRue-nwX',
        name: 'VÒNG TRẦM RỤC CHÌM DÁNG MIẾNG TỰ NHIÊN VÂN GỖ ĐẬM NÉT',
        category: 'Trầm chìm vip cao cấp',
        group: 'incense',
        oldPrice: 9500000,
        price: 8200000,
        discount: '-14%',
        desc: 'Vòng trầm rục tự nhiên dáng đốt trúc/miếng mộc mạc, vân dầu đen đậm nét, mùi hương sống ngọt sâu.'
      },
      {
        id: 10,
        driveId: '1EwaDk1tmboAlMXAYgbcllqVPY-cDeo1d',
        name: 'MẶT TƯỢNG PHẬT TRẦM SÁNH CHÌM THIÊN THỦ THIÊN NHÃN',
        category: 'Mặt tượng đeo cổ',
        group: 'incense',
        oldPrice: 600000,
        price: 480000,
        discount: '-20%',
        desc: 'Mặt dây chuyền trầm hương chạm khắc Phật Thiên Thủ Thiên Nhãn thủ công sắc nét, hộ mệnh bình an.'
      },
      {
        id: 11,
        driveId: '19-YhHFjXWcbxmCGVHb63HPAjehE13Wqn',
        name: 'TƯỢNG TRẦM TỐC QUAN ÂM ĐỂ Ô TÔ HOẶC TRANG THỜ',
        category: 'Tranh - tượng trầm cảnh',
        group: 'incense',
        oldPrice: 1200000,
        price: 800000,
        discount: '-33%',
        desc: 'Tượng Phật Quan Âm chế tác từ gỗ trầm tốc tự nhiên, đặt trên xe ô tô, bàn làm việc hoặc không gian thờ tự.'
      },
      {
        id: 12,
        driveId: '12Stw_Q95muFUNLuapH2h6W0fWNxEWdvs',
        name: 'TRẦM MIẾNG XÔNG ĐỐT CAO CẤP – TRẦM HƯƠNG TỰ NHIÊN',
        category: 'Trầm hương miếng - giác xông',
        group: 'incense',
        oldPrice: 480000,
        price: 400000,
        discount: '-17%',
        desc: 'Trầm hương miếng giác xông tự nhiên dùng xông nhà, cửa hàng kinh doanh, thanh lọc không khí và khử mùi.'
      },
      {
        id: 13,
        driveId: '1R7Yd_hXFqTr5GqUhwZg0XFX4gyQ0Rq_s',
        name: 'NHANG TRẦM SẠCH HÌNH BÚP SEN & THÁC KHÓI TRẦM HƯƠNG',
        category: 'Nhang trầm - Thác lư xông',
        group: 'incense',
        oldPrice: 120000,
        price: 90000,
        discount: '-25%',
        desc: 'Nụ trầm hương búp sen nguyên chất 100% từ bột trầm thiên nhiên, khói tỏa dịu nhẹ dùng cho lư xông và thác khói.'
      },
      {
        id: 14,
        driveId: '1uOrkCHeb3D0fJOm5whpS8jxO-JKchQwG',
        name: 'NHANG TRẦM KHÔNG TĂM THƯỢNG HẠNG – 100% BỘT TRẦM NGUYÊN CHẤT',
        category: 'Nhang trầm - Thác lư xông',
        group: 'incense',
        oldPrice: 180000,
        price: 150000,
        discount: '-17%',
        desc: 'Ống nhang trầm hương không tăm thượng hạng, hương thơm thanh khiết dùng trong thưởng trà, thiền định và yoga.'
      }
    ];

    function formatCurrencyVND(amount) {
      return amount.toString().replace(/\B(?=(\d{3})+(?!\d))/g, '.') + '₫';
    }

    // Tạo thẻ HTML cho từng sản phẩm chuẩn Flatsome:
    // - Chỉ có duy nhất badge % giảm giá ở góc trên bên trái, KHÔNG có nhãn dán phụ
    // - Tên sản phẩm hiển thị đầy đủ (product-title-full), không bị cắt chữ hay tràn khung
    function createProductCardHTML(product) {
      const imgUrl = 'https://drive.google.com/thumbnail?id=' + product.driveId + '&sz=w600';
      return `
        <div class="bg-white border border-stone-200 hover:border-tram-primary rounded-lg overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between group">
          <div>
            <!-- Khung ảnh vuông chuẩn Flatsome + % Giảm giá góc trên bên trái -->
            <div onclick="openProductModal(${product.id})" class="relative w-full pt-[100%] bg-stone-100 overflow-hidden cursor-pointer">
              <span class="flatsome-badge-sale">${product.discount}</span>
              <img 
                src="${imgUrl}" 
                data-drive-id="${product.driveId}"
                alt="${product.name}" 
                class="absolute inset-0 w-full h-full object-cover group-hover:scale-105 transition duration-500"
                onerror="handleDriveImgError(this, '${product.category}')"
              >
            </div>

            <!-- Thông tin sản phẩm: Tên đầy đủ không bị tràn hay thiếu chữ -->
            <div class="p-2.5 sm:p-3 text-center">
              <p class="text-[10px] sm:text-[11px] text-stone-400 uppercase tracking-wider mb-1">${product.category}</p>
              <h3 onclick="openProductModal(${product.id})" class="product-title-full font-bold text-[12px] sm:text-[13.5px] text-stone-800 hover:text-tram-primary cursor-pointer">
                ${product.name}
              </h3>
            </div>
          </div>

          <!-- Giá gốc gạch ngang + Giá khuyến mãi chuẩn Flatsome -->
          <div class="px-2.5 pb-3 pt-1 text-center border-t border-stone-100">
            <div class="flex flex-wrap items-center justify-center gap-x-2 gap-y-0.5 mb-2">
              <span class="text-[11px] sm:text-xs text-stone-400 line-through">${formatCurrencyVND(product.oldPrice)}</span>
              <span class="text-xs sm:text-sm font-bold text-tram-sale">${formatCurrencyVND(product.price)}</span>
            </div>
            <button 
              onclick="addToCart(${product.id})" 
              type="button" 
              class="w-full py-1.5 px-2 rounded bg-tram-primary hover:bg-tram-dark text-white text-[11px] sm:text-xs font-medium transition"
            >
              Đặt mua nhanh
            </button>
          </div>
        </div>
      `;
    }

    // Render toàn bộ lưới sản phẩm trên trang chủ
    function renderAllProductSections(filterCategory = 'all', searchKeyword = '') {
      const mainGrid = document.getElementById('mainProductGrid');
      const heading = document.getElementById('currentCategoryHeading');

      let filtered = productsData;
      if (filterCategory !== 'all') {
        filtered = productsData.filter(p => p.category.toLowerCase() === filterCategory.toLowerCase());
        heading.textContent = 'DANH MỤC: ' + filterCategory.toUpperCase();
      } else {
        heading.textContent = 'SẢN PHẨM TRẦM HƯƠNG NỔI BẬT';
      }

      if (searchKeyword.trim() !== '') {
        const kw = searchKeyword.trim().toLowerCase();
        filtered = productsData.filter(p => 
          p.name.toLowerCase().includes(kw) || 
          p.category.toLowerCase().includes(kw)
        );
        heading.textContent = 'KẾT QUẢ TÌM KIẾM: "' + searchKeyword.trim().toUpperCase() + '"';
      }

      if (filtered.length === 0) {
        mainGrid.innerHTML = `
          <div class="col-span-full py-8 text-center text-stone-500 text-sm">
            Không tìm thấy sản phẩm phù hợp. <button onclick="filterByCategory('all')" class="text-tram-primary font-bold underline ml-1">Xem tất cả sản phẩm</button>
          </div>
        `;
      } else {
        mainGrid.innerHTML = filtered.map(createProductCardHTML).join('');
      }

      // Render chuyên mục Vòng tay & Chuỗi trầm hương (8 sản phẩm đầu)
      const braceletGrid = document.getElementById('braceletProductGrid');
      if (braceletGrid) {
        const bracelets = productsData.filter(p => p.group === 'bracelet');
        braceletGrid.innerHTML = bracelets.map(createProductCardHTML).join('');
      }

      // Render chuyên mục Vật phẩm phong thủy & Nhang trầm (6 sản phẩm tiếp theo)
      const incenseGrid = document.getElementById('incenseProductGrid');
      if (incenseGrid) {
        const incenses = productsData.filter(p => p.group === 'incense');
        incenseGrid.innerHTML = incenses.map(createProductCardHTML).join('');
      }
    }

    function filterByCategory(categoryName) {
      renderAllProductSections(categoryName, '');
      // Cập nhật trạng thái nút active
      document.querySelectorAll('.cat-filter-btn').forEach(btn => {
        if (btn.getAttribute('data-cat') === categoryName) {
          btn.className = 'cat-filter-btn cat-nowrap px-3 py-1 rounded-full text-xs font-medium bg-tram-primary text-white transition';
        } else {
          btn.className = 'cat-filter-btn cat-nowrap px-3 py-1 rounded-full text-xs font-medium bg-white border border-stone-300 text-stone-700 hover:border-tram-primary transition';
        }
      });
      const sectionEl = document.getElementById('san-pham-ban-chay');
      if (sectionEl) {
        sectionEl.scrollIntoView({ behavior: 'smooth', block: 'start' });
      }
    }

    // =====================================================================
    // SLIDER 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP
    // =====================================================================
    let currentBannerIndex = 0;
    const totalBanners = 2;
    let bannerInterval = null;

    function showBannerSlide(index) {
      const slides = document.querySelectorAll('.banner-slide');
      const dots = document.querySelectorAll('.banner-dot');
      currentBannerIndex = (index + totalBanners) % totalBanners;

      slides.forEach((slide, i) => {
        if (i === currentBannerIndex) {
          slide.classList.remove('hidden');
          slide.classList.add('block');
        } else {
          slide.classList.remove('block');
          slide.classList.add('hidden');
        }
      });

      dots.forEach((dot, i) => {
        if (i === currentBannerIndex) {
          dot.className = 'banner-dot w-2.5 h-2.5 rounded-full bg-tram-gold transition';
        } else {
          dot.className = 'banner-dot w-2.5 h-2.5 rounded-full bg-white/50 transition';
        }
      });
    }

    function changeBannerSlide(step) {
      showBannerSlide(currentBannerIndex + step);
      resetBannerTimer();
    }

    function goToBannerSlide(index) {
      showBannerSlide(index);
      resetBannerTimer();
    }

    function resetBannerTimer() {
      if (bannerInterval) clearInterval(bannerInterval);
      bannerInterval = setInterval(() => {
        showBannerSlide(currentBannerIndex + 1);
      }, 4500);
    }

    // =====================================================================
    // GIỎ HÀNG & MODAL SẢN PHẨM
    // =====================================================================
    let cart = [];

    function showToast(msg) {
      const toast = document.getElementById('toastNotification');
      const text = document.getElementById('toastMessage');
      text.textContent = msg;
      toast.classList.remove('hidden');
      toast.classList.add('flex');
      setTimeout(() => {
        toast.classList.add('hidden');
        toast.classList.remove('flex');
      }, 3200);
    }

    function addToCart(productId) {
      const item = productsData.find(p => p.id === productId);
      if (!item) return;
      const existing = cart.find(c => c.id === productId);
      if (existing) {
        existing.qty += 1;
      } else {
        cart.push({ ...item, qty: 1 });
      }
      updateCartUI();
      showToast('Đã thêm "' + item.name + '" vào giỏ hàng!');
    }

    function updateCartUI() {
      const badge = document.getElementById('cartCountBadge');
      const totalQty = cart.reduce((sum, item) => sum + item.qty, 0);
      badge.textContent = totalQty;
    }

    function openProductModal(productId) {
      const product = productsData.find(p => p.id === productId);
      if (!product) return;
      document.getElementById('modalProductCategory').textContent = product.category;
      document.getElementById('modalProductDiscount').textContent = product.discount;
      const imgEl = document.getElementById('modalProductImg');
      imgEl.setAttribute('data-drive-id', product.driveId);
      imgEl.setAttribute('data-retry', '0');
      imgEl.src = 'https://drive.google.com/thumbnail?id=' + product.driveId + '&sz=w700';
      imgEl.onerror = function() { handleDriveImgError(this, product.name); };

      document.getElementById('modalProductName').textContent = product.name;
      document.getElementById('modalProductOldPrice').textContent = formatCurrencyVND(product.oldPrice);
      document.getElementById('modalProductPrice').textContent = formatCurrencyVND(product.price);
      document.getElementById('modalProductDesc').textContent = product.desc;

      const addBtn = document.getElementById('modalAddToCartBtn');
      addBtn.onclick = function() {
        addToCart(product.id);
        closeProductModal();
      };

      const modal = document.getElementById('productModal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeProductModal() {
      const modal = document.getElementById('productModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    function openCartModal() {
      const container = document.getElementById('cartItemsContainer');
      const totalEl = document.getElementById('cartTotalAmount');

      if (cart.length === 0) {
        container.innerHTML = '<p class="text-center text-stone-500 text-sm py-6">Chưa có sản phẩm nào trong giỏ hàng.</p>';
        totalEl.textContent = '0₫';
      } else {
        let total = 0;
        container.innerHTML = cart.map(item => {
          total += item.price * item.qty;
          return `
            <div class="flex items-center justify-between gap-3 py-2.5 border-b border-stone-200 text-xs">
              <div class="flex-1">
                <p class="font-bold text-stone-800">${item.name}</p>
                <p class="text-stone-500">${formatCurrencyVND(item.price)} x ${item.qty}</p>
              </div>
              <button onclick="removeFromCart(${item.id})" class="text-red-600 hover:underline">Xóa</button>
            </div>
          `;
        }).join('');
        totalEl.textContent = formatCurrencyVND(total);
      }

      const modal = document.getElementById('cartModal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function removeFromCart(id) {
      cart = cart.filter(c => c.id !== id);
      updateCartUI();
      openCartModal();
    }

    function closeCartModal() {
      const modal = document.getElementById('cartModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    function proceedToQuoteFromCart() {
      closeCartModal();
      const noteEl = document.getElementById('quoteNote');
      if (cart.length > 0 && noteEl) {
        const summary = cart.map(c => c.name + ' (SL: ' + c.qty + ')').join(', ');
        noteEl.value = 'Đặt mua: ' + summary;
      }
      document.getElementById('form-bao-gia').scrollIntoView({ behavior: 'smooth' });
    }

    // Xử lý gửi Form Báo Giá
    function submitQuoteForm(e) {
      e.preventDefault();
      const name = document.getElementById('quoteName').value;
      const phone = document.getElementById('quotePhone').value;
      const cat = document.getElementById('quoteCategory').value;
      showToast('Cảm ơn ' + name + ' (' + phone + ')! Hồn Trầm Hương đã nhận yêu cầu "' + cat + '" và sẽ liên hệ ngay.');
      e.target.reset();
    }

    // Dữ liệu chi tiết 4 bài viết kiến thức
    const articlesContent = [
      {
        title: 'Trầm Hương Chìm Nước Là Gì? Vì Sao Giá Trị Cao Hơn Các Loại Trầm Khác?',
        body: `
          <p><strong>Trầm hương chìm nước</strong> là loại trầm hương có hàm lượng tinh dầu kết tinh trong thớ gỗ cực kỳ cao, khiến khối lượng riêng của gỗ lớn hơn nước và chìm hoàn toàn khi thả vào nước.</p>
          <p>Quá trình hình thành trầm chìm tự nhiên từ cây Dó Bầu đòi hỏi hàng chục năm tích tụ tinh hoa đất trời. Chính vì độ quý hiếm, mùi hương ngọt sâu bền bỉ và năng lượng phong thủy mạnh mẽ mà trầm chìm luôn có giá trị cao bậc nhất.</p>
          <p>Tại <strong>Hồn Trầm Hương (79 Nguyễn Xí, Phường Hòa Khánh, Tp.Đà Nẵng)</strong>, quý khách có thể trực tiếp kiểm tra vân dầu và trải nghiệm các dòng vòng trầm VIP cận chìm và chìm nước chuẩn tự nhiên.</p>
        `
      },
      {
        title: 'Cách Phân Biệt Trầm Hương Thật Giả Chuẩn Xác Từ Chuyên Gia',
        body: `
          <p>Để phân biệt vòng trầm hương tự nhiên thật và hàng nấu dầu hóa chất, quý khách cần lưu ý 3 yếu tố cốt lõi:</p>
          <p><strong>1. Quan sát vân trầm:</strong> Trầm thật có các sớ dầu và thớ gỗ xen kẽ tự nhiên, màu nâu trầm ấm áp, không bóng đen bất thường do tẩm keo.</p>
          <p><strong>2. Cảm nhận mùi hương:</strong> Trầm hương tự nhiên có hương thơm thanh ngọt, dịu nhẹ, thoang thoảng bền lâu và không gây hắc hay nồng gắt mũi.</p>
          <p><strong>3. Khi đốt thử:</strong> Trầm hương thật tỏa làn khói trắng nhẹ, mùi thơm ngọt dịu giúp thư giãn tinh thần ngay lập tức.</p>
        `
      },
      {
        title: 'Đeo Vòng Tay Trầm Hương Có Tác Dụng Gì? 4 Công Dụng Phong Thủy',
        body: `
          <p><strong>1. An thần, giảm căng thẳng:</strong> Hương thơm tự nhiên tỏa ra từ hạt trầm giúp xua tan mệt mỏi, mang lại sự tĩnh tâm và cải thiện giấc ngủ.</p>
          <p><strong>2. Thu hút tài lộc & may mắn:</strong> Trong phong thủy, trầm hương mang nguồn dương khí mạnh, giúp hóa giải điềm xấu và chiêu tài lộc cho người kinh doanh.</p>
          <p><strong>3. Thể hiện đẳng cấp tinh tế:</strong> Vòng tay trầm hương 108 hạt hoặc vòng trầm đơn dễ dàng kết hợp cùng mọi trang phục công sở và dự tiệc.</p>
        `
      },
      {
        title: 'Trầm Hương Xông Nhà Có Tác Dụng Gì? Cách Đốt Nụ & Giác Xông Đúng Chuẩn',
        body: `
          <p>Xông nhà bằng trầm hương miếng, bột trầm hoặc nhang nụ trầm hương là nét đẹp văn hóa tâm linh giúp thanh lọc không khí, khử mùi ẩm mốc và làm ấm không gian sống.</p>
          <p>Đặc biệt vào dịp khai trương, nhập trạch, lễ Tết hoặc rằm mùng một, đốt một nụ trầm hương búp sen trên thác khói hay lư đồng giúp gia đạo bình an, tụ khí sinh tài.</p>
        `
      }
    ];

    function openArticleModal(idx) {
      const art = articlesContent[idx];
      if (!art) return;
      document.getElementById('articleModalTitle').textContent = art.title;
      document.getElementById('articleModalBody').innerHTML = art.body;
      const modal = document.getElementById('articleModal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeArticleModal() {
      const modal = document.getElementById('articleModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    function closeMobileMenu() {
      document.getElementById('mobileMenuOverlay').classList.add('hidden');
    }

    // Khởi chạy khi trang tải xong
    window.addEventListener('DOMContentLoaded', () => {
      renderAllProductSections('all', '');
      resetBannerTimer();

      // Sự kiện mở/đóng menu điện thoại
      document.getElementById('mobileMenuBtn').addEventListener('click', () => {
        document.getElementById('mobileMenuOverlay').classList.remove('hidden');
      });
      document.getElementById('closeMobileMenuBtn').addEventListener('click', closeMobileMenu);

      // Sự kiện mở giỏ hàng
      document.getElementById('cartToggleBtn').addEventListener('click', openCartModal);

      // Sự kiện tìm kiếm trên máy tính & điện thoại
      const dInput = document.getElementById('desktopSearchInput');
      const dBtn = document.getElementById('desktopSearchBtn');
      dBtn.addEventListener('click', () => renderAllProductSections('all', dInput.value));
      dInput.addEventListener('keyup', (e) => {
        if (e.key === 'Enter') renderAllProductSections('all', dInput.value);
      });

      const mInput = document.getElementById('mobileSearchInput');
      const mBtn = document.getElementById('mobileSearchBtn');
      mBtn.addEventListener('click', () => renderAllProductSections('all', mInput.value));
      mInput.addEventListener('keyup', (e) => {
        if (e.key === 'Enter') renderAllProductSections('all', mInput.value);
      });
    });
  </script>
</body>
</html>
