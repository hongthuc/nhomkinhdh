<html lang="vi">
<head>
  <!-- Cấu hình hiển thị & tương thích mọi thiết bị -->
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
  <title>Nhôm Kính ĐH - Cửa Nhôm Xingfa &amp; Kính Cường Lực Đà Nẵng | nhomkinhdh.com</title>
  <meta name="description" content="Nhôm Kính ĐH Đà Nẵng chuyên thiết kế, gia công và thi công lắp đặt cửa nhôm Xingfa chính hãng, cửa kính cường lực, cầu thang kính, kính ốp bếp, phòng tắm kính. Hotline: 0905.680.903.">

  <!-- Meta Open Graph & Thumbnail chia sẻ liên kết sử dụng Logo website -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://nhomkinhdh.com/">
  <meta property="og:site_name" content="Nhôm Kính ĐH">
  <meta property="og:title" content="Nhôm Kính ĐH - Cửa Nhôm Xingfa &amp; Kính Cường Lực Đà Nẵng">
  <meta property="og:description" content="Chuyên thi công Cửa nhôm Xingfa, Cửa kính cường lực, Cửa nhựa lõi thép, Cầu thang kính, Kính ốp bếp, Phòng tắm kính tại Đà Nẵng. Hotline: 0905.680.903.">
  <meta property="og:image" content="https://drive.google.com/thumbnail?id=1BHGuSfC-yCgdoOCoY2mCLQh8vD33HabN&amp;sz=w1000">
  <meta property="og:image:alt" content="Logo Nhôm Kính ĐH - nhomkinhdh.com">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="Nhôm Kính ĐH - Cửa Nhôm Xingfa &amp; Kính Cường Lực Đà Nẵng">
  <meta name="twitter:description" content="Thi công nhôm kính uy tín tại Đà Nẵng - Hotline: 0905.680.903.">
  <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1BHGuSfC-yCgdoOCoY2mCLQh8vD33HabN&amp;sz=w1000">
  <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=1BHGuSfC-yCgdoOCoY2mCLQh8vD33HabN&amp;sz=w256">

  <!-- Phông chữ Inter & Icon Font Awesome -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&amp;display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
          },
          colors: {
            brand: {
              50: '#eff6ff',
              100: '#dbeafe',
              500: '#1565c0',
              600: '#0d4f9b',
              700: '#0a3d7a',
              800: '#072d5c',
              900: '#051f40',
            },
            accent: {
              500: '#e67e22',
              600: '#d35400',
            },
            sale: '#d32f2f',
          }
        }
      }
    }
  </script>

  <!-- Kiểu tùy chỉnh chuẩn Flatsome, chống tràn viền & cấu trúc khung 95% trên máy tính -->
  <style>
    *, *::before, *::after {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
      font-size: 16px;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
    }

    body {
      font-family: 'Inter', system-ui, -apple-system, sans-serif;
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      background-color: #f8fafc;
      color: #1e293b;
      -webkit-font-smoothing: antialiased;
    }

    /* Khung giao diện chuẩn: 100% có lề gọn trên di động, đúng 95% màn hình trên máy tính */
    .ux-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    @media (min-width: 640px) {
      .ux-container {
        padding-left: 16px;
        padding-right: 16px;
      }
    }

    @media (min-width: 1024px) {
      .ux-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Tiêu đề từng khối kiểu Flatsome Section Title */
    .flatsome-heading {
      position: relative;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 12px;
      margin-bottom: 1.5rem;
    }
    .flatsome-heading::before,
    .flatsome-heading::after {
      content: "";
      flex: 1;
      height: 2px;
      background-color: #e2e8f0;
      max-width: 120px;
    }

    /* Menu dropdown mượt mà trên máy tính */
    .nav-dropdown-parent {
      position: relative;
    }
    .nav-dropdown-menu {
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
      pointer-events: none;
    }
    .nav-dropdown-parent:hover .nav-dropdown-menu,
    .nav-dropdown-parent:focus-within .nav-dropdown-menu {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
      pointer-events: auto;
    }

    /* Banner tự trượt: hai slide có kích thước hoàn toàn bằng nhau */
    .hero-track {
      display: flex;
      transition: transform 0.6s cubic-bezier(0.4, 0, 0.2, 1);
      will-change: transform;
    }
    .hero-slide {
      flex: 0 0 100%;
      width: 100%;
      min-width: 100%;
    }

    /* Hiệu ứng gợn sóng nhẹ cho nút liên hệ nổi */
    @keyframes pulseRing {
      0% {
        transform: scale(1);
        opacity: 0.7;
      }
      100% {
        transform: scale(1.45);
        opacity: 0;
      }
    }
    .fab-pulse::before {
      content: "";
      position: absolute;
      inset: 0;
      border-radius: 9999px;
      background: inherit;
      z-index: -1;
      animation: pulseRing 2s cubic-bezier(0.215, 0.61, 0.355, 1) infinite;
    }

    /* Đảm bảo ảnh không bao giờ gây tràn khung */
    img {
      max-width: 100%;
    }
  </style>
</head>
<body class="pb-16 md:pb-0">

  <!-- ===================================================================== -->
  <!-- KHỐI 1: TOPBAR THÔNG TIN + HEADER & MENU DANH MỤC (KHÔNG CÓ NÚT GỌI) -->
  <!-- ===================================================================== -->
  <header class="w-full bg-white shadow-sm sticky top-0 z-40 border-b border-slate-200">
    <!-- Dòng thông tin mỏng phía trên (Flatsome Top Bar) -->
    <div class="w-full bg-brand-700 text-white text-xs py-1.5">
      <div class="ux-container flex flex-wrap items-center justify-between gap-2">
        <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
          <span class="inline-flex items-center gap-1.5">
            <i class="fa-solid fa-location-dot text-amber-300"></i>
            <span>Tổ xuân phố Xuân Phú, Phường Hòa Khánh, TP. Đà Nẵng</span>
          </span>
          <span class="hidden sm:inline-flex items-center gap-1.5 text-brand-100">
            <i class="fa-regular fa-clock text-amber-300"></i>
            <span>Làm việc: 24/7</span>
          </span>
        </div>
        <div class="hidden md:flex items-center gap-4 text-brand-100">
          <a href="tel:0905680903" class="inline-flex items-center gap-1.5 hover:text-white transition">
            <i class="fa-solid fa-phone text-amber-300"></i>
            <span>0905.680.903</span>
          </a>
          <span class="opacity-50">|</span>
          <span class="inline-flex items-center gap-1.5">
            <i class="fa-solid fa-globe text-amber-300"></i>
            <span>nhomkinhdh.com</span>
          </span>
        </div>
      </div>
    </div>

    <!-- Thanh Header chính: Logo thu gọn + Danh mục viết liền trên 1 hàng -->
    <div class="w-full bg-white">
      <div class="ux-container flex items-center justify-between gap-2 lg:gap-4 py-2">
        <!-- Logo Nhôm Kính ĐH chỉnh gọn nhỏ -->
        <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group">
          <img
            src="https://drive.google.com/thumbnail?id=1BHGuSfC-yCgdoOCoY2mCLQh8vD33HabN&amp;sz=w400"
            alt="Logo Nhôm Kính ĐH"
            data-drive-id="1BHGuSfC-yCgdoOCoY2mCLQh8vD33HabN"
            onerror="handleDriveImgError(this, 'Nhôm Kính ĐH')"
            class="h-10 sm:h-11 lg:h-12 w-auto max-w-[125px] object-contain rounded"
          >
          <div class="leading-tight hidden sm:block lg:hidden xl:block">
            <div class="text-sm font-extrabold text-brand-700 tracking-tight whitespace-nowrap">NHÔM KÍNH ĐH</div>
            <div class="text-[10px] font-medium text-slate-500 whitespace-nowrap">nhomkinhdh.com</div>
          </div>
        </a>

        <!-- Menu Danh Mục Máy Tính: Chữ nhỏ gọn, viết liền không gãy chữ, nằm đẹp trên 1 hàng -->
        <nav aria-label="Danh mục chính" class="hidden lg:flex flex-wrap items-center justify-end gap-x-0.5 xl:gap-x-1.5 gap-y-1 flex-1 min-w-0">
          <a href="#trang-chu" class="px-2 xl:px-2.5 py-2 rounded-md text-[12px] xl:text-[13px] font-semibold uppercase text-brand-700 hover:bg-brand-50 transition whitespace-nowrap">
            Trang chủ
          </a>
          <a href="#gioi-thieu" class="px-2 xl:px-2.5 py-2 rounded-md text-[12px] xl:text-[13px] font-semibold uppercase text-slate-700 hover:text-brand-700 hover:bg-brand-50 transition whitespace-nowrap">
            Giới thiệu
          </a>

          <!-- Dropdown: Cửa nhôm xingfa -->
          <div class="nav-dropdown-parent">
            <a href="#san-pham" onclick="filterProductsByCategory('xingfa')" class="inline-flex items-center gap-1 px-2 xl:px-2.5 py-2 rounded-md text-[12px] xl:text-[13px] font-semibold uppercase text-slate-700 hover:text-brand-700 hover:bg-brand-50 transition whitespace-nowrap">
              <span>Cửa nhôm xingfa</span>
              <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
            </a>
            <div class="nav-dropdown-menu absolute left-0 top-full pt-1 w-56 z-50">
              <div class="bg-white rounded-lg shadow-lg border border-slate-200 py-1.5">
                <a href="#san-pham" onclick="filterProductsByTag('1-canh')" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-50 hover:text-brand-700 whitespace-nowrap">Cửa nhôm xingfa 1 cánh</a>
                <a href="#san-pham" onclick="filterProductsByTag('2-canh')" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-50 hover:text-brand-700 whitespace-nowrap">Cửa nhôm xingfa 2 cánh</a>
                <a href="#san-pham" onclick="filterProductsByTag('3-canh')" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-50 hover:text-brand-700 whitespace-nowrap">Cửa nhôm xingfa 3 cánh</a>
                <a href="#san-pham" onclick="filterProductsByTag('4-canh')" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-50 hover:text-brand-700 whitespace-nowrap">Cửa nhôm xingfa 4 cánh</a>
                <a href="#san-pham" onclick="filterProductsByTag('5-canh')" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-50 hover:text-brand-700 whitespace-nowrap">Cửa nhôm xingfa 5 cánh</a>
              </div>
            </div>
          </div>

          <a href="#san-pham" onclick="filterProductsByCategory('kinh-cuong-luc')" class="px-2 xl:px-2.5 py-2 rounded-md text-[12px] xl:text-[13px] font-semibold uppercase text-slate-700 hover:text-brand-700 hover:bg-brand-50 transition whitespace-nowrap">
            Cửa kính cường lực
          </a>

          <!-- Dropdown: Sản phẩm -->
          <div class="nav-dropdown-parent">
            <a href="#danh-muc-san-pham" class="inline-flex items-center gap-1 px-2 xl:px-2.5 py-2 rounded-md text-[12px] xl:text-[13px] font-semibold uppercase text-slate-700 hover:text-brand-700 hover:bg-brand-50 transition whitespace-nowrap">
              <span>Sản phẩm</span>
              <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
            </a>
            <div class="nav-dropdown-menu absolute left-0 top-full pt-1 w-52 z-50">
              <div class="bg-white rounded-lg shadow-lg border border-slate-200 py-1.5">
                <a href="#san-pham" onclick="filterProductsByCategory('xingfa')" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-50 hover:text-brand-700 whitespace-nowrap">Cửa nhôm xingfa</a>
                <a href="#san-pham" onclick="filterProductsByCategory('cua-nhua')" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-50 hover:text-brand-700 whitespace-nowrap">Cửa nhựa lõi thép</a>
                <a href="#san-pham" onclick="filterProductsByCategory('tu-dong')" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-50 hover:text-brand-700 whitespace-nowrap">Cửa kính tự động</a>
                <a href="#san-pham" onclick="filterProductsByCategory('cau-thang')" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-50 hover:text-brand-700 whitespace-nowrap">Cầu thang kính</a>
                <a href="#san-pham" onclick="filterProductsByCategory('kinh-bep')" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-50 hover:text-brand-700 whitespace-nowrap">Kính ốp bếp</a>
                <a href="#san-pham" onclick="filterProductsByCategory('phong-tam')" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-50 hover:text-brand-700 whitespace-nowrap">Phòng tắm kính</a>
              </div>
            </div>
          </div>

          <a href="#cong-trinh" class="px-2 xl:px-2.5 py-2 rounded-md text-[12px] xl:text-[13px] font-semibold uppercase text-slate-700 hover:text-brand-700 hover:bg-brand-50 transition whitespace-nowrap">
            Công trình
          </a>
          <a href="#bao-gia" class="px-2 xl:px-2.5 py-2 rounded-md text-[12px] xl:text-[13px] font-semibold uppercase text-slate-700 hover:text-brand-700 hover:bg-brand-50 transition whitespace-nowrap">
            Báo giá
          </a>
          <a href="#tin-tuc" class="px-2 xl:px-2.5 py-2 rounded-md text-[12px] xl:text-[13px] font-semibold uppercase text-slate-700 hover:text-brand-700 hover:bg-brand-50 transition whitespace-nowrap">
            Tin tức
          </a>
          <a href="#lien-he" class="px-2 xl:px-2.5 py-2 rounded-md text-[12px] xl:text-[13px] font-semibold uppercase text-slate-700 hover:text-brand-700 hover:bg-brand-50 transition whitespace-nowrap">
            Liên hệ
          </a>
        </nav>

        <!-- Nút mở menu di động (chỉ hiển thị trên điện thoại / máy tính bảng) -->
        <button
          id="mobileMenuBtn"
          type="button"
          aria-label="Mở danh mục trang web"
          class="lg:hidden inline-flex items-center justify-center gap-2 px-3 py-2 rounded-lg border border-slate-200 text-brand-700 hover:bg-brand-50 transition"
        >
          <i class="fa-solid fa-bars text-lg"></i>
          <span class="text-xs font-bold uppercase">Danh mục</span>
        </button>
      </div>
    </div>
  </header>

  <!-- Ngăn kéo Menu Di Động (Mobile Off-Canvas Menu kiểu Flatsome) -->
  <div id="mobileMenuOverlay" class="fixed inset-0 bg-slate-900/50 z-50 hidden transition-opacity"></div>
  <aside id="mobileMenuDrawer" class="fixed top-0 left-0 h-full w-[82%] max-w-[320px] bg-white z-50 shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
    <div class="flex items-center justify-between px-4 py-3 border-b border-slate-200 bg-brand-700 text-white">
      <div class="flex items-center gap-2">
        <img
          src="https://drive.google.com/thumbnail?id=1BHGuSfC-yCgdoOCoY2mCLQh8vD33HabN&amp;sz=w256"
          alt="Nhôm Kính ĐH"
          data-drive-id="1BHGuSfC-yCgdoOCoY2mCLQh8vD33HabN"
          onerror="handleDriveImgError(this, 'ĐH')"
          class="h-8 w-auto bg-white rounded p-0.5 object-contain"
        >
        <span class="font-bold text-sm tracking-wide">NHÔM KÍNH ĐH</span>
      </div>
      <button id="closeMobileMenuBtn" type="button" aria-label="Đóng menu" class="p-2 rounded-lg hover:bg-brand-600 transition">
        <i class="fa-solid fa-xmark text-lg"></i>
      </button>
    </div>

    <div class="flex-1 overflow-y-auto py-2 px-3 space-y-1 text-sm">
      <a href="#trang-chu" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg font-semibold text-slate-800 hover:bg-brand-50 hover:text-brand-700">Trang chủ</a>
      <a href="#gioi-thieu" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg font-semibold text-slate-800 hover:bg-brand-50 hover:text-brand-700">Giới thiệu</a>

      <!-- Submenu di động: Cửa nhôm xingfa -->
      <div class="rounded-lg border border-slate-100">
        <button type="button" onclick="toggleMobileSubmenu('sub-xingfa', this)" class="w-full flex items-center justify-between px-3 py-2.5 font-semibold text-slate-800 hover:bg-brand-50 hover:text-brand-700 rounded-lg">
          <span>Cửa nhôm xingfa</span>
          <i class="fa-solid fa-chevron-down text-xs transition-transform"></i>
        </button>
        <div id="sub-xingfa" class="hidden pl-4 pr-2 pb-2 space-y-1">
          <a href="#san-pham" onclick="filterProductsByTag('1-canh'); closeMobileMenu();" class="block py-2 px-3 text-slate-600 rounded hover:bg-brand-50 hover:text-brand-700">Cửa nhôm xingfa 1 cánh</a>
          <a href="#san-pham" onclick="filterProductsByTag('2-canh'); closeMobileMenu();" class="block py-2 px-3 text-slate-600 rounded hover:bg-brand-50 hover:text-brand-700">Cửa nhôm xingfa 2 cánh</a>
          <a href="#san-pham" onclick="filterProductsByTag('3-canh'); closeMobileMenu();" class="block py-2 px-3 text-slate-600 rounded hover:bg-brand-50 hover:text-brand-700">Cửa nhôm xingfa 3 cánh</a>
          <a href="#san-pham" onclick="filterProductsByTag('4-canh'); closeMobileMenu();" class="block py-2 px-3 text-slate-600 rounded hover:bg-brand-50 hover:text-brand-700">Cửa nhôm xingfa 4 cánh</a>
          <a href="#san-pham" onclick="filterProductsByTag('5-canh'); closeMobileMenu();" class="block py-2 px-3 text-slate-600 rounded hover:bg-brand-50 hover:text-brand-700">Cửa nhôm xingfa 5 cánh</a>
        </div>
      </div>

      <a href="#san-pham" onclick="filterProductsByCategory('kinh-cuong-luc'); closeMobileMenu();" class="block px-3 py-2.5 rounded-lg font-semibold text-slate-800 hover:bg-brand-50 hover:text-brand-700">Cửa kính cường lực</a>

      <!-- Submenu di động: Sản phẩm -->
      <div class="rounded-lg border border-slate-100">
        <button type="button" onclick="toggleMobileSubmenu('sub-sanpham', this)" class="w-full flex items-center justify-between px-3 py-2.5 font-semibold text-slate-800 hover:bg-brand-50 hover:text-brand-700 rounded-lg">
          <span>Sản phẩm</span>
          <i class="fa-solid fa-chevron-down text-xs transition-transform"></i>
        </button>
        <div id="sub-sanpham" class="hidden pl-4 pr-2 pb-2 space-y-1">
          <a href="#san-pham" onclick="filterProductsByCategory('xingfa'); closeMobileMenu();" class="block py-2 px-3 text-slate-600 rounded hover:bg-brand-50 hover:text-brand-700">Cửa nhôm xingfa</a>
          <a href="#san-pham" onclick="filterProductsByCategory('cua-nhua'); closeMobileMenu();" class="block py-2 px-3 text-slate-600 rounded hover:bg-brand-50 hover:text-brand-700">Cửa nhựa lõi thép</a>
          <a href="#san-pham" onclick="filterProductsByCategory('tu-dong'); closeMobileMenu();" class="block py-2 px-3 text-slate-600 rounded hover:bg-brand-50 hover:text-brand-700">Cửa kính tự động</a>
          <a href="#san-pham" onclick="filterProductsByCategory('cau-thang'); closeMobileMenu();" class="block py-2 px-3 text-slate-600 rounded hover:bg-brand-50 hover:text-brand-700">Cầu thang kính</a>
          <a href="#san-pham" onclick="filterProductsByCategory('kinh-bep'); closeMobileMenu();" class="block py-2 px-3 text-slate-600 rounded hover:bg-brand-50 hover:text-brand-700">Kính ốp bếp</a>
          <a href="#san-pham" onclick="filterProductsByCategory('phong-tam'); closeMobileMenu();" class="block py-2 px-3 text-slate-600 rounded hover:bg-brand-50 hover:text-brand-700">Phòng tắm kính</a>
        </div>
      </div>

      <a href="#cong-trinh" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg font-semibold text-slate-800 hover:bg-brand-50 hover:text-brand-700">Công trình</a>
      <a href="#bao-gia" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg font-semibold text-slate-800 hover:bg-brand-50 hover:text-brand-700">Báo giá</a>
      <a href="#tin-tuc" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg font-semibold text-slate-800 hover:bg-brand-50 hover:text-brand-700">Tin tức</a>
      <a href="#lien-he" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg font-semibold text-slate-800 hover:bg-brand-50 hover:text-brand-700">Liên hệ</a>
    </div>

    <div class="p-4 border-t border-slate-200 bg-slate-50 text-xs text-slate-600 space-y-1.5">
      <div class="font-semibold text-brand-700">Hotline tư vấn: 0905.680.903</div>
      <div>Tổ xuân phố Xuân Phú, Phường Hòa Khánh, TP. Đà Nẵng</div>
    </div>
  </aside>

  <!-- ===================================================================== -->
  <!-- KHỐI 2: 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP (KÍCH THƯỚC BẰNG NHAU)        -->
  <!-- Chữ & hình nằm trọn trong banner, cách xa viền, không mất chữ         -->
  <!-- ===================================================================== -->
  <section id="trang-chu" class="w-full pt-3 sm:pt-4 pb-6 bg-slate-100">
    <div class="ux-container">
      <div id="heroSlider" class="relative w-full overflow-hidden rounded-xl shadow-md bg-brand-900 select-none">
        <!-- Track chứa 2 Slide kích thước bằng nhau tuyệt đối -->
        <div id="heroTrack" class="hero-track">

          <!-- BANNER 1: CỬA NHÔM XINGFA CHÍNH HÃNG -->
          <div class="hero-slide relative min-h-[270px] sm:min-h-[340px] md:min-h-[410px] lg:min-h-[460px] flex items-center">
            <!-- Ảnh nền kiến trúc nhôm kính -->
            <img
              src="https://drive.google.com/thumbnail?id=1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ&amp;sz=w1600"
              alt="Thi công Cửa nhôm Xingfa Đà Nẵng - Nhôm Kính ĐH"
              data-drive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
              onerror="handleDriveImgError(this, 'Nhôm Kính ĐH Đà Nẵng')"
              class="absolute inset-0 w-full h-full object-cover"
            >
            <!-- Lớp phủ chuyển sắc giúp chữ nổi bật hoàn hảo -->
            <div class="absolute inset-0 bg-gradient-to-r from-brand-900/92 via-brand-800/80 to-brand-900/55"></div>

            <!-- Vùng an toàn nội dung: cách xa hoàn toàn viền banner & nút mũi tên -->
            <div class="relative z-10 w-full px-10 sm:px-14 md:px-20 lg:px-24 py-8 sm:py-10 md:py-12 grid grid-cols-1 md:grid-cols-12 gap-6 items-center">
              <div class="md:col-span-7 lg:col-span-7 text-white space-y-3 sm:space-y-4">
                <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest text-amber-300">
                  NHÔM KÍNH ĐH — ĐÀ NẴNG
                </p>
                <h1 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug tracking-tight">
                  CỬA NHÔM XINGFA CHÍNH HÃNG GIÁ TỐT TẠI ĐÀ NẴNG
                </h1>
                <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-xl">
                  Thiết kế, sản xuất &amp; lắp đặt trọn gói cửa đi mở quay, cửa xếp trượt, cửa sổ mở hất nhôm Xingfa hệ 55, 93 phụ kiện đồng bộ.
                </p>
                <div class="flex flex-wrap items-center gap-2.5 sm:gap-3 pt-1">
                  <a href="#form-bao-gia" class="inline-flex items-center justify-center px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-amber-500 hover:bg-amber-600 text-white text-xs sm:text-sm font-bold shadow transition">
                    Nhận báo giá ngay
                  </a>
                  <a href="#san-pham" class="inline-flex items-center justify-center px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white text-xs sm:text-sm font-semibold transition">
                    Xem sản phẩm
                  </a>
                </div>
              </div>

              <!-- Khung ảnh sản phẩm minh họa nằm gọn trong banner (hiển thị từ tablet trở lên) -->
              <div class="hidden md:flex md:col-span-5 lg:col-span-5 justify-end">
                <div class="w-full max-w-[320px] lg:max-w-[360px] bg-white/10 backdrop-blur-sm p-2.5 rounded-xl border border-white/25 shadow-xl">
                  <img
                    src="https://drive.google.com/thumbnail?id=1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX&amp;sz=w800"
                    alt="Mẫu cửa nhôm Xingfa Nhôm Kính ĐH"
                    data-drive-id="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
                    onerror="handleDriveImgError(this, 'Cửa Nhôm Xingfa')"
                    class="w-full h-44 lg:h-52 object-cover rounded-lg"
                  >
                </div>
              </div>
            </div>
          </div>

          <!-- BANNER 2: KÍNH CƯỜNG LỰC, CẦU THANG KÍNH, PHÒNG TẮM KÍNH -->
          <div class="hero-slide relative min-h-[270px] sm:min-h-[340px] md:min-h-[410px] lg:min-h-[460px] flex items-center">
            <!-- Ảnh nền công trình thực tế tại Đà Nẵng -->
            <img
              src="https://drive.google.com/thumbnail?id=1za_IJpAm850uulT6IuhBsk1THb3LuPuc&amp;sz=w1600"
              alt="Thi công Kính cường lực &amp; Công trình tại Đà Nẵng - Nhôm Kính ĐH"
              data-drive-id="1za_IJpAm850uulT6IuhBsk1THb3LuPuc"
              onerror="handleDriveImgError(this, 'Công Trình Nhôm Kính ĐH')"
              class="absolute inset-0 w-full h-full object-cover"
            >
            <div class="absolute inset-0 bg-gradient-to-r from-slate-900/92 via-brand-900/82 to-brand-800/55"></div>

            <!-- Vùng an toàn nội dung: cách xa viền đồng nhất với Banner 1 -->
            <div class="relative z-10 w-full px-10 sm:px-14 md:px-20 lg:px-24 py-8 sm:py-10 md:py-12 grid grid-cols-1 md:grid-cols-12 gap-6 items-center">
              <div class="md:col-span-7 lg:col-span-7 text-white space-y-3 sm:space-y-4">
                <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest text-amber-300">
                  THI CÔNG CHUYÊN NGHIỆP — NHOMKINHDH.COM
                </p>
                <h2 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug tracking-tight">
                  CỬA KÍNH CƯỜNG LỰC, CẦU THANG &amp; PHÒNG TẮM KÍNH HIỆN ĐẠI
                </h2>
                <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-xl">
                  Khảo sát đo đạc tận nơi miễn phí tại Đà Nẵng. Thi công chuẩn kỹ thuật cho nhà phố, biệt thự, khách sạn và resort cao cấp.
                </p>
                <div class="flex flex-wrap items-center gap-2.5 sm:gap-3 pt-1">
                  <a href="#cong-trinh" class="inline-flex items-center justify-center px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-amber-500 hover:bg-amber-600 text-white text-xs sm:text-sm font-bold shadow transition">
                    Xem dự án thực tế
                  </a>
                  <a href="tel:0905680903" class="inline-flex items-center justify-center px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white text-xs sm:text-sm font-semibold transition">
                    Hotline: 0905.680.903
                  </a>
                </div>
              </div>

              <!-- Khung ảnh sản phẩm minh họa nằm gọn trong banner -->
              <div class="hidden md:flex md:col-span-5 lg:col-span-5 justify-end">
                <div class="w-full max-w-[320px] lg:max-w-[360px] bg-white/10 backdrop-blur-sm p-2.5 rounded-xl border border-white/25 shadow-xl">
                  <img
                    src="https://drive.google.com/thumbnail?id=1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH&amp;sz=w800"
                    alt="Phòng tắm kính &amp; kính cường lực Nhôm Kính ĐH"
                    data-drive-id="1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH"
                    onerror="handleDriveImgError(this, 'Kính Cường Lực ĐH')"
                    class="w-full h-44 lg:h-52 object-cover rounded-lg"
                  >
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- Nút chuyển slide trái / phải đặt sát mép gọn gàng -->
        <button
          id="heroPrev"
          type="button"
          aria-label="Banner trước"
          class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition"
        >
          <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
        </button>
        <button
          id="heroNext"
          type="button"
          aria-label="Banner tiếp theo"
          class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition"
        >
          <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
        </button>

        <!-- Chấm chỉ báo 2 banner -->
        <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
          <button type="button" onclick="goToHeroSlide(0)" aria-label="Chuyển tới banner 1" class="hero-dot w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
          <button type="button" onclick="goToHeroSlide(1)" aria-label="Chuyển tới banner 2" class="hero-dot w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- KHỐI 3: GIỚI THIỆU NHÔM KÍNH ĐH (PHONG CÁCH FLATSOME ĐƠN GIẢN)        -->
  <!-- ===================================================================== -->
  <section id="gioi-thieu" class="w-full py-8 sm:py-12 bg-white">
    <div class="ux-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
        <!-- Cột nội dung giới thiệu -->
        <div class="lg:col-span-7 space-y-4">
          <h2 class="text-lg sm:text-2xl font-extrabold text-brand-700 uppercase leading-snug">
            CÔNG TY NHÔM KÍNH ĐH – CỬA NHÔM XINGFA &amp; KÍNH CƯỜNG LỰC ĐÀ NẴNG
          </h2>
          <div class="w-16 h-1 bg-amber-500 rounded"></div>
          <p class="text-sm sm:text-[15px] text-slate-600 leading-relaxed">
            <strong>Nhôm Kính ĐH (nhomkinhdh.com)</strong> là đơn vị chuyên thiết kế, gia công và thi công lắp đặt các hạng mục nhôm kính cao cấp tại Đà Nẵng và khu vực Miền Trung. Các dòng sản phẩm chủ lực bao gồm: <strong>Cửa nhôm Xingfa nhập khẩu, Cửa kính cường lực, Cửa nhựa lõi thép, Cửa kính tự động, Cầu thang kính, Kính ốp bếp và Phòng tắm kính</strong>.
          </p>
          <p class="text-sm sm:text-[15px] text-slate-600 leading-relaxed">
            Với phương châm đặt chất lượng và thẩm mỹ công trình lên hàng đầu, đội ngũ kỹ thuật lành nghề của Nhôm Kính ĐH cam kết mang đến không gian sống hiện đại, cách âm, cách nhiệt, chống bão gió hiệu quả cùng chính sách bảo hành minh bạch, chu đáo.
          </p>

          <!-- 4 chỉ số nổi bật tối giản -->
          <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 pt-2">
            <div class="p-3 rounded-lg bg-brand-50 border border-brand-100 text-center">
              <div class="text-xl sm:text-2xl font-extrabold text-brand-700">150+</div>
              <div class="text-xs text-slate-600 font-medium mt-0.5">Dự án hoàn thành</div>
            </div>
            <div class="p-3 rounded-lg bg-brand-50 border border-brand-100 text-center">
              <div class="text-xl sm:text-2xl font-extrabold text-brand-700">50+</div>
              <div class="text-xs text-slate-600 font-medium mt-0.5">Thợ kinh nghiệm</div>
            </div>
            <div class="p-3 rounded-lg bg-brand-50 border border-brand-100 text-center">
              <div class="text-xl sm:text-2xl font-extrabold text-brand-700">100+</div>
              <div class="text-xs text-slate-600 font-medium mt-0.5">Mẫu sản phẩm</div>
            </div>
            <div class="p-3 rounded-lg bg-brand-50 border border-brand-100 text-center">
              <div class="text-xl sm:text-2xl font-extrabold text-brand-700">100%</div>
              <div class="text-xs text-slate-600 font-medium mt-0.5">Khách hài lòng</div>
            </div>
          </div>
        </div>

        <!-- Cột hình ảnh công trình & cam kết dịch vụ -->
        <div class="lg:col-span-5">
          <div class="bg-slate-50 border border-slate-200 rounded-xl p-4 sm:p-5 space-y-4">
            <img
              src="https://drive.google.com/thumbnail?id=1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ&amp;sz=w900"
              alt="Công trình thi công nhôm kính Nhôm Kính ĐH Đà Nẵng"
              data-drive-id="1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ"
              onerror="handleDriveImgError(this, 'Nhôm Kính ĐH')"
              class="w-full h-48 sm:h-56 object-cover rounded-lg"
            >
            <ul class="space-y-2 text-xs sm:text-sm text-slate-700">
              <li class="flex items-start gap-2.5">
                <i class="fa-solid fa-circle-check text-brand-600 mt-0.5 shrink-0"></i>
                <span>Khảo sát, tư vấn và đo đạc tận công trình miễn phí tại Đà Nẵng.</span>
              </li>
              <li class="flex items-start gap-2.5">
                <i class="fa-solid fa-circle-check text-brand-600 mt-0.5 shrink-0"></i>
                <span>Thanh nhôm Xingfa nhập khẩu tem đỏ chính hãng, phụ kiện Kinlong đồng bộ.</span>
              </li>
              <li class="flex items-start gap-2.5">
                <i class="fa-solid fa-circle-check text-brand-600 mt-0.5 shrink-0"></i>
                <span>Giá trực tiếp tại xưởng sản xuất, bảo hành dài hạn, hỗ trợ 24/7.</span>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- KHỐI 4: DANH MỤC SẢN PHẨM NỔI BẬT (CHỮ DANH MỤC NHỎ GỌN)             -->
  <!-- ===================================================================== -->
  <section id="danh-muc-san-pham" class="w-full py-8 sm:py-12 bg-slate-50 border-t border-slate-200/70">
    <div class="ux-container">
      <div class="flatsome-heading">
        <h2 class="text-base sm:text-xl font-extrabold text-brand-700 uppercase text-center">
          DANH MỤC SẢN PHẨM NỔI BẬT
        </h2>
      </div>

      <!-- 6 danh mục sản phẩm chuẩn web mẫu -->
      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
        <!-- 1. Cửa nhôm xingfa -->
        <a href="#san-pham" onclick="filterProductsByCategory('xingfa')" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-500 transition flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX&amp;sz=w600"
              alt="Cửa nhôm Xingfa"
              data-drive-id="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
              onerror="handleDriveImgError(this, 'Cửa Nhôm Xingfa')"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
            >
          </div>
          <div class="p-2.5 text-center">
            <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 group-hover:text-brand-700 uppercase leading-tight">
              Cửa nhôm Xingfa
            </h3>
          </div>
        </a>

        <!-- 2. Cửa nhựa lõi thép -->
        <a href="#san-pham" onclick="filterProductsByCategory('cua-nhua')" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-500 transition flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA&amp;sz=w600"
              alt="Cửa nhựa lõi thép"
              data-drive-id="1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA"
              onerror="handleDriveImgError(this, 'Cửa Nhựa Lõi Thép')"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
            >
          </div>
          <div class="p-2.5 text-center">
            <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 group-hover:text-brand-700 uppercase leading-tight">
              Cửa nhựa lõi thép
            </h3>
          </div>
        </a>

        <!-- 3. Cửa kính tự động -->
        <a href="#san-pham" onclick="filterProductsByCategory('tu-dong')" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-500 transition flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ&amp;sz=w600"
              alt="Cửa kính tự động"
              data-drive-id="1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ"
              onerror="handleDriveImgError(this, 'Cửa Tự Động')"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
            >
          </div>
          <div class="p-2.5 text-center">
            <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 group-hover:text-brand-700 uppercase leading-tight">
              Cửa kính tự động
            </h3>
          </div>
        </a>

        <!-- 4. Cầu thang kính -->
        <a href="#san-pham" onclick="filterProductsByCategory('cau-thang')" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-500 transition flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul&amp;sz=w600"
              alt="Cầu thang kính"
              data-drive-id="1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul"
              onerror="handleDriveImgError(this, 'Cầu Thang Kính')"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
            >
          </div>
          <div class="p-2.5 text-center">
            <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 group-hover:text-brand-700 uppercase leading-tight">
              Cầu thang kính
            </h3>
          </div>
        </a>

        <!-- 5. Kính ốp bếp -->
        <a href="#san-pham" onclick="filterProductsByCategory('kinh-bep')" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-500 transition flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb&amp;sz=w600"
              alt="Kính ốp bếp"
              data-drive-id="1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb"
              onerror="handleDriveImgError(this, 'Kính Ốp Bếp')"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
            >
          </div>
          <div class="p-2.5 text-center">
            <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 group-hover:text-brand-700 uppercase leading-tight">
              Kính ốp bếp
            </h3>
          </div>
        </a>

        <!-- 6. Phòng tắm kính -->
        <a href="#san-pham" onclick="filterProductsByCategory('phong-tam')" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-500 transition flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH&amp;sz=w600"
              alt="Phòng tắm kính"
              data-drive-id="1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH"
              onerror="handleDriveImgError(this, 'Phòng Tắm Kính')"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
            >
          </div>
          <div class="p-2.5 text-center">
            <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 group-hover:text-brand-700 uppercase leading-tight">
              Phòng tắm kính
            </h3>
          </div>
        </a>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- KHỐI 5: DANH SÁCH SẢN PHẨM (2 CỘT DI ĐỘNG, GIÁ & GIẢM GIÁ % GÓC TRÁI) -->
  <!-- ===================================================================== -->
  <section id="san-pham" class="w-full py-8 sm:py-12 bg-white border-t border-slate-200/70">
    <div class="ux-container">
      <div class="flatsome-heading">
        <h2 class="text-base sm:text-xl font-extrabold text-brand-700 uppercase text-center">
          SẢN PHẨM CỬA NHÔM XINGFA &amp; NHÔM KÍNH ĐÀ NẴNG
        </h2>
      </div>

      <!-- Bộ lọc danh mục gọn đẹp -->
      <div id="productFilterTabs" class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6">
        <button type="button" data-filter="all" onclick="filterProductsByCategory('all')" class="filter-tab px-3 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-700 text-white transition whitespace-nowrap">
          Tất cả sản phẩm
        </button>
        <button type="button" data-filter="xingfa" onclick="filterProductsByCategory('xingfa')" class="filter-tab px-3 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-slate-100 text-slate-700 hover:bg-brand-50 hover:text-brand-700 transition whitespace-nowrap">
          Cửa nhôm Xingfa
        </button>
        <button type="button" data-filter="kinh-cuong-luc" onclick="filterProductsByCategory('kinh-cuong-luc')" class="filter-tab px-3 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-slate-100 text-slate-700 hover:bg-brand-50 hover:text-brand-700 transition whitespace-nowrap">
          Cửa kính cường lực
        </button>
        <button type="button" data-filter="cua-nhua" onclick="filterProductsByCategory('cua-nhua')" class="filter-tab px-3 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-slate-100 text-slate-700 hover:bg-brand-50 hover:text-brand-700 transition whitespace-nowrap">
          Cửa nhựa lõi thép
        </button>
        <button type="button" data-filter="tu-dong" onclick="filterProductsByCategory('tu-dong')" class="filter-tab px-3 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-slate-100 text-slate-700 hover:bg-brand-50 hover:text-brand-700 transition whitespace-nowrap">
          Cửa kính tự động
        </button>
        <button type="button" data-filter="cau-thang" onclick="filterProductsByCategory('cau-thang')" class="filter-tab px-3 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-slate-100 text-slate-700 hover:bg-brand-50 hover:text-brand-700 transition whitespace-nowrap">
          Cầu thang kính
        </button>
        <button type="button" data-filter="kinh-bep" onclick="filterProductsByCategory('kinh-bep')" class="filter-tab px-3 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-slate-100 text-slate-700 hover:bg-brand-50 hover:text-brand-700 transition whitespace-nowrap">
          Kính ốp bếp
        </button>
        <button type="button" data-filter="phong-tam" onclick="filterProductsByCategory('phong-tam')" class="filter-tab px-3 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-slate-100 text-slate-700 hover:bg-brand-50 hover:text-brand-700 transition whitespace-nowrap">
          Phòng tắm kính
        </button>
      </div>

      <!-- Lưới sản phẩm: 2 cột trên điện thoại, 3 cột máy tính bảng, 4 cột máy tính -->
      <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-4 lg:gap-5">
        <!-- Dữ liệu sản phẩm sẽ được hiển thị động từ JavaScript -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- KHỐI 6: BẢNG BÁO GIÁ THAM KHẢO (FLATSOME PRICING TABLE)               -->
  <!-- ===================================================================== -->
  <section id="bao-gia" class="w-full py-8 sm:py-12 bg-slate-50 border-t border-slate-200/70">
    <div class="ux-container">
      <div class="flatsome-heading">
        <h2 class="text-base sm:text-xl font-extrabold text-brand-700 uppercase text-center">
          BẢNG BÁO GIÁ CỬA NHÔM XINGFA &amp; KÍNH CƯỜNG LỰC ĐÀ NẴNG
        </h2>
      </div>

      <div class="bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden">
        <div class="overflow-x-auto">
          <table class="w-full text-left border-collapse text-xs sm:text-sm">
            <thead>
              <tr class="bg-brand-700 text-white">
                <th class="py-3 px-3 sm:px-4 font-bold">STT</th>
                <th class="py-3 px-3 sm:px-4 font-bold">Hạng mục sản phẩm</th>
                <th class="py-3 px-3 sm:px-4 font-bold hidden sm:table-cell">Thông số kỹ thuật</th>
                <th class="py-3 px-3 sm:px-4 font-bold text-right">Đơn giá (VNĐ/m²)</th>
              </tr>
            </thead>
            <tbody class="divide-y divide-slate-200">
              <tr class="hover:bg-brand-50/50 transition">
                <td class="py-3 px-3 sm:px-4 font-semibold text-slate-500">01</td>
                <td class="py-3 px-3 sm:px-4 font-semibold text-slate-800">Cửa đi mở quay 1 cánh / 2 cánh nhôm Xingfa</td>
                <td class="py-3 px-3 sm:px-4 text-slate-600 hidden sm:table-cell">Hệ 55 dày 2.0mm, kính cường lực 8mm, phụ kiện Kinlong</td>
                <td class="py-3 px-3 sm:px-4 text-right font-bold text-sale whitespace-nowrap">2.050.000 ₫</td>
              </tr>
              <tr class="hover:bg-brand-50/50 transition">
                <td class="py-3 px-3 sm:px-4 font-semibold text-slate-500">02</td>
                <td class="py-3 px-3 sm:px-4 font-semibold text-slate-800">Cửa đi mở quay 3 cánh / 4 cánh nhôm Xingfa</td>
                <td class="py-3 px-3 sm:px-4 text-slate-600 hidden sm:table-cell">Hệ 55 dày 2.0mm, gioăng kép EPDM, kính an toàn</td>
                <td class="py-3 px-3 sm:px-4 text-right font-bold text-sale whitespace-nowrap">2.100.000 ₫</td>
              </tr>
              <tr class="hover:bg-brand-50/50 transition">
                <td class="py-3 px-3 sm:px-4 font-semibold text-slate-500">03</td>
                <td class="py-3 px-3 sm:px-4 font-semibold text-slate-800">Cửa đi xếp trượt nhôm Xingfa (4–6 cánh)</td>
                <td class="py-3 px-3 sm:px-4 text-slate-600 hidden sm:table-cell">Hệ 63 / 93 dày 2.0mm, ray trượt chịu lực đồng bộ</td>
                <td class="py-3 px-3 sm:px-4 text-right font-bold text-sale whitespace-nowrap">2.150.000 ₫</td>
              </tr>
              <tr class="hover:bg-brand-50/50 transition">
                <td class="py-3 px-3 sm:px-4 font-semibold text-slate-500">04</td>
                <td class="py-3 px-3 sm:px-4 font-semibold text-slate-800">Cửa sổ mở hất / mở quay / mở trượt Xingfa</td>
                <td class="py-3 px-3 sm:px-4 text-slate-600 hidden sm:table-cell">Hệ 55 / 93 dày 1.4mm, chống gió giật &amp; nước mưa</td>
                <td class="py-3 px-3 sm:px-4 text-right font-bold text-sale whitespace-nowrap">1.850.000 ₫</td>
              </tr>
              <tr class="hover:bg-brand-50/50 transition">
                <td class="py-3 px-3 sm:px-4 font-semibold text-slate-500">05</td>
                <td class="py-3 px-3 sm:px-4 font-semibold text-slate-800">Cửa kính cường lực mở quay / lùa (10mm – 12mm)</td>
                <td class="py-3 px-3 sm:px-4 text-slate-600 hidden sm:table-cell">Kính tôi nhiệt an toàn, bản lề sàn VVP / Hafele</td>
                <td class="py-3 px-3 sm:px-4 text-right font-bold text-sale whitespace-nowrap">850.000 ₫</td>
              </tr>
              <tr class="hover:bg-brand-50/50 transition">
                <td class="py-3 px-3 sm:px-4 font-semibold text-slate-500">06</td>
                <td class="py-3 px-3 sm:px-4 font-semibold text-slate-800">Phòng tắm kính, Cầu thang kính, Kính ốp bếp</td>
                <td class="py-3 px-3 sm:px-4 text-slate-600 hidden sm:table-cell">Kính cường lực 8mm–12mm, phụ kiện Inox 304 chống gỉ</td>
                <td class="py-3 px-3 sm:px-4 text-right font-bold text-sale whitespace-nowrap">950.000 ₫</td>
              </tr>
            </tbody>
          </table>
        </div>
        <div class="px-4 py-3 bg-slate-50 border-t border-slate-200 flex flex-col sm:flex-row sm:items-center justify-between gap-2 text-xs text-slate-600">
          <span>* Đơn giá tham khảo, có chiết khấu ưu đãi cho công trình diện tích lớn tại Đà Nẵng.</span>
          <a href="#form-bao-gia" class="font-bold text-brand-700 hover:underline whitespace-nowrap">
            Yêu cầu báo giá chi tiết theo bản vẽ &rarr;
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- KHỐI 7: CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (6 CÔNG TRÌNH THỰC TẾ)        -->
  <!-- ===================================================================== -->
  <section id="cong-trinh" class="w-full py-8 sm:py-12 bg-white border-t border-slate-200/70">
    <div class="ux-container">
      <div class="flatsome-heading">
        <h2 class="text-base sm:text-xl font-extrabold text-brand-700 uppercase text-center">
          CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
        </h2>
      </div>

      <div id="projectGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
        <!-- Render 6 dự án Đà Nẵng từ JavaScript -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- KHỐI 8: FORM ĐĂNG KÝ YÊU CẦU & BÁO GIÁ TẠI TRANG CHỦ                  -->
  <!-- ===================================================================== -->
  <section id="form-bao-gia" class="w-full py-8 sm:py-12 bg-brand-700 text-white">
    <div class="ux-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
        <!-- Cột thông tin hỗ trợ -->
        <div class="lg:col-span-5 space-y-4">
          <h2 class="text-xl sm:text-2xl font-extrabold uppercase leading-snug">
            ĐĂNG KÝ NHẬN BÁO GIÁ &amp; TƯ VẤN MIỄN PHÍ
          </h2>
          <div class="w-16 h-1 bg-amber-400 rounded"></div>
          <p class="text-sm text-brand-100 leading-relaxed">
            Để lại thông tin hạng mục công trình cần thi công. Kỹ thuật viên <strong>Nhôm Kính ĐH</strong> sẽ liên hệ tư vấn mẫu mã phù hợp và gửi bảng dự toán chi tiết trong vòng 15 phút.
          </p>
          <div class="space-y-2.5 text-sm pt-1">
            <div class="flex items-center gap-3">
              <span class="w-8 h-8 rounded-full bg-white/15 flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone text-amber-300 text-xs"></i>
              </span>
              <span>Hotline / Zalo: <strong class="text-white">0905.680.903</strong></span>
            </div>
            <div class="flex items-center gap-3">
              <span class="w-8 h-8 rounded-full bg-white/15 flex items-center justify-center shrink-0">
                <i class="fa-solid fa-location-dot text-amber-300 text-xs"></i>
              </span>
              <span>Tổ xuân phố Xuân Phú, Phường Hòa Khánh, TP. Đà Nẵng</span>
            </div>
            <div class="flex items-center gap-3">
              <span class="w-8 h-8 rounded-full bg-white/15 flex items-center justify-center shrink-0">
                <i class="fa-solid fa-shield-halved text-amber-300 text-xs"></i>
              </span>
              <span>Khảo sát thực tế miễn phí — Bảo hành chính hãng dài hạn</span>
            </div>
          </div>
        </div>

        <!-- Cột biểu mẫu báo giá Flatsome -->
        <div class="lg:col-span-7">
          <form id="quoteForm" class="bg-white text-slate-800 rounded-xl p-5 sm:p-6 shadow-lg space-y-4">
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <label for="customerName" class="block text-xs font-bold uppercase text-slate-600 mb-1.5">Họ và tên *</label>
                <input id="customerName" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-600 focus:ring-2 focus:ring-brand-100 outline-none">
              </div>
              <div>
                <label for="customerPhone" class="block text-xs font-bold uppercase text-slate-600 mb-1.5">Số điện thoại / Zalo *</label>
                <input id="customerPhone" type="tel" required placeholder="Ví dụ: 0905 680 903" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-600 focus:ring-2 focus:ring-brand-100 outline-none">
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <label for="customerService" class="block text-xs font-bold uppercase text-slate-600 mb-1.5">Hạng mục quan tâm</label>
                <select id="customerService" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:border-brand-600 focus:ring-2 focus:ring-brand-100 outline-none">
                  <option value="Cửa nhôm Xingfa">Cửa nhôm Xingfa (1, 2, 3, 4, 5 cánh)</option>
                  <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                  <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                  <option value="Cửa kính tự động">Cửa kính tự động</option>
                  <option value="Cầu thang kính">Cầu thang kính</option>
                  <option value="Kính ốp bếp">Kính ốp bếp</option>
                  <option value="Phòng tắm kính">Phòng tắm kính</option>
                </select>
              </div>
              <div>
                <label for="customerAddress" class="block text-xs font-bold uppercase text-slate-600 mb-1.5">Khu vực thi công</label>
                <input id="customerAddress" type="text" placeholder="Quận/Huyện tại Đà Nẵng..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-600 focus:ring-2 focus:ring-brand-100 outline-none">
              </div>
            </div>

            <div>
              <label for="customerNote" class="block text-xs font-bold uppercase text-slate-600 mb-1.5">Yêu cầu kích thước / Ghi chú</label>
              <textarea id="customerNote" rows="3" placeholder="Ví dụ: Cần báo giá bộ cửa đi 4 cánh nhôm Xingfa màu xám ghi, kích thước ngang 3m x cao 2.4m..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-600 focus:ring-2 focus:ring-brand-100 outline-none"></textarea>
            </div>

            <button type="submit" class="w-full py-3 px-6 rounded-lg bg-amber-500 hover:bg-amber-600 text-white font-bold text-sm uppercase tracking-wide shadow transition flex items-center justify-center gap-2">
              <i class="fa-solid fa-paper-plane"></i>
              <span>Gửi yêu cầu báo giá ngay</span>
            </button>

            <!-- Hộp thông báo phản hồi ngay trên form (không dùng alert) -->
            <div id="quoteFeedback" class="hidden rounded-lg p-3 text-xs sm:text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200"></div>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- KHỐI 9: DANH MỤC CÁC BÀI VIẾT & TIN TỨC NỔI BẬT TRANG CHỦ             -->
  <!-- ===================================================================== -->
  <section id="tin-tuc" class="w-full py-8 sm:py-12 bg-slate-50 border-t border-slate-200/70">
    <div class="ux-container">
      <div class="flatsome-heading">
        <h2 class="text-base sm:text-xl font-extrabold text-brand-700 uppercase text-center">
          TIN TỨC &amp; KIẾN THỨC NHÔM KÍNH
        </h2>
      </div>

      <!-- Danh mục nhóm bài viết nhỏ gọn -->
      <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6">
        <button type="button" onclick="filterArticles('all')" data-art-filter="all" class="art-tab px-3 py-1.5 rounded-lg text-xs font-semibold bg-brand-700 text-white transition whitespace-nowrap">
          Tất cả bài viết
        </button>
        <button type="button" onclick="filterArticles('tu-van')" data-art-filter="tu-van" class="art-tab px-3 py-1.5 rounded-lg text-xs font-semibold bg-white border border-slate-200 text-slate-700 hover:border-brand-500 transition whitespace-nowrap">
          Tư vấn chọn cửa
        </button>
        <button type="button" onclick="filterArticles('kinh-nghiem')" data-art-filter="kinh-nghiem" class="art-tab px-3 py-1.5 rounded-lg text-xs font-semibold bg-white border border-slate-200 text-slate-700 hover:border-brand-500 transition whitespace-nowrap">
          Kinh nghiệm thi công
        </button>
        <button type="button" onclick="filterArticles('bao-gia')" data-art-filter="bao-gia" class="art-tab px-3 py-1.5 rounded-lg text-xs font-semibold bg-white border border-slate-200 text-slate-700 hover:border-brand-500 transition whitespace-nowrap">
          Cẩm nang báo giá
        </button>
      </div>

      <div id="articleGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
        <!-- Render danh sách bài viết từ JavaScript -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- KHỐI 10: ĐỐI TÁC CỦA CHÚNG TÔI (6 LOGO ĐỐI TÁC)                       -->
  <!-- ===================================================================== -->
  <section class="w-full py-8 sm:py-10 bg-white border-t border-slate-200/70">
    <div class="ux-container">
      <div class="flatsome-heading">
        <h2 class="text-base sm:text-xl font-extrabold text-brand-700 uppercase text-center">
          ĐỐI TÁC CỦA CHÚNG TÔI
        </h2>
      </div>

      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4 items-center">
        <div class="bg-white border border-slate-200 rounded-xl p-3 h-20 sm:h-24 flex items-center justify-center hover:shadow-sm transition">
          <img src="https://drive.google.com/thumbnail?id=13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk&amp;sz=w400" alt="Đối tác Nhôm Kính ĐH 1" data-drive-id="13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk" onerror="handleDriveImgError(this, 'Đối tác 1')" class="max-h-full max-w-full object-contain">
        </div>
        <div class="bg-white border border-slate-200 rounded-xl p-3 h-20 sm:h-24 flex items-center justify-center hover:shadow-sm transition">
          <img src="https://drive.google.com/thumbnail?id=1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq&amp;sz=w400" alt="Đối tác Nhôm Kính ĐH 2" data-drive-id="1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq" onerror="handleDriveImgError(this, 'Đối tác 2')" class="max-h-full max-w-full object-contain">
        </div>
        <div class="bg-white border border-slate-200 rounded-xl p-3 h-20 sm:h-24 flex items-center justify-center hover:shadow-sm transition">
          <img src="https://drive.google.com/thumbnail?id=1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn&amp;sz=w400" alt="Đối tác Nhôm Kính ĐH 3" data-drive-id="1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn" onerror="handleDriveImgError(this, 'Đối tác 3')" class="max-h-full max-w-full object-contain">
        </div>
        <div class="bg-white border border-slate-200 rounded-xl p-3 h-20 sm:h-24 flex items-center justify-center hover:shadow-sm transition">
          <img src="https://drive.google.com/thumbnail?id=1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT&amp;sz=w400" alt="Đối tác Nhôm Kính ĐH 4" data-drive-id="1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT" onerror="handleDriveImgError(this, 'Đối tác 4')" class="max-h-full max-w-full object-contain">
        </div>
        <div class="bg-white border border-slate-200 rounded-xl p-3 h-20 sm:h-24 flex items-center justify-center hover:shadow-sm transition">
          <img src="https://drive.google.com/thumbnail?id=1SDcarhnX0yypmqdbawICjYBRtFnKngn-&amp;sz=w400" alt="Đối tác Nhôm Kính ĐH 5" data-drive-id="1SDcarhnX0yypmqdbawICjYBRtFnKngn-" onerror="handleDriveImgError(this, 'Đối tác 5')" class="max-h-full max-w-full object-contain">
        </div>
        <div class="bg-white border border-slate-200 rounded-xl p-3 h-20 sm:h-24 flex items-center justify-center hover:shadow-sm transition">
          <img src="https://drive.google.com/thumbnail?id=1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg&amp;sz=w400" alt="Đối tác Nhôm Kính ĐH 6" data-drive-id="1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg" onerror="handleDriveImgError(this, 'Đối tác 6')" class="max-h-full max-w-full object-contain">
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- KHỐI 11: BẢN ĐỒ GOOGLE MAPS & FANPAGE FACEBOOK NGAY TRÊN TRANG CHỦ    -->
  <!-- ===================================================================== -->
  <section id="lien-he" class="w-full py-8 sm:py-12 bg-slate-100 border-t border-slate-200">
    <div class="ux-container">
      <div class="flatsome-heading">
        <h2 class="text-base sm:text-xl font-extrabold text-brand-700 uppercase text-center">
          BẢN ĐỒ CHỈ ĐƯỜNG &amp; FANPAGE NHÔM KÍNH ĐH
        </h2>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 sm:gap-6">
        <!-- Cột trái: Bản đồ Google Map -->
        <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
          <div class="px-4 py-3 bg-brand-700 text-white flex items-center justify-between gap-2">
            <div class="flex items-center gap-2 text-xs sm:text-sm font-bold">
              <i class="fa-solid fa-map-location-dot text-amber-300"></i>
              <span>Bản đồ Google Maps – Nhôm Kính ĐH</span>
            </div>
            <a
              href="https://www.google.com/maps/search/?api=1&amp;query=Xu%C3%A2n+Ph%C3%BA,+H%C3%B2a+Kh%C3%A1nh,+%C4%90%C3%A0+N%E1%BA%B5ng"
              target="_blank"
              rel="noopener noreferrer"
              class="text-xs text-amber-300 hover:underline whitespace-nowrap"
            >
              Mở Google Maps &rarr;
            </a>
          </div>
          <div class="w-full h-[300px] sm:h-[360px] bg-slate-200 relative">
            <iframe
              title="Bản đồ vị trí Nhôm Kính ĐH - Tổ xuân phố Xuân Phú, Phường Hòa Khánh, TP. Đà Nẵng"
              src="https://maps.google.com/maps?q=Xu%C3%A2n%20Ph%C3%BA,%20H%C3%B2a%20Kh%C3%A1nh,%20%C4%90%C3%A0%20N%E1%BA%B5ng&amp;t=&amp;z=15&amp;ie=UTF8&amp;iwloc=&amp;output=embed"
              class="w-full h-full border-0"
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"
              allowfullscreen
            ></iframe>
          </div>
          <div class="px-4 py-3 text-xs sm:text-sm text-slate-600 bg-slate-50 border-t border-slate-200">
            <strong class="text-slate-800">Địa chỉ:</strong> Tổ xuân phố Xuân Phú, Phường Hòa Khánh, TP. Đà Nẵng
          </div>
        </div>

        <!-- Cột phải: Fanpage Facebook Nhôm Kính ĐH ngay ngoài trang chủ -->
        <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
          <div class="px-4 py-3 bg-[#1877F2] text-white flex items-center justify-between gap-2">
            <div class="flex items-center gap-2 text-xs sm:text-sm font-bold">
              <i class="fa-brands fa-facebook"></i>
              <span>Fanpage Facebook Nhôm Kính ĐH</span>
            </div>
            <a
              href="https://www.facebook.com/profile.php?id=100094026249967&amp;locale=ca_ES"
              target="_blank"
              rel="noopener noreferrer"
              class="text-xs bg-white/20 hover:bg-white/30 px-2.5 py-1 rounded font-semibold transition whitespace-nowrap"
            >
              Theo dõi trang
            </a>
          </div>

          <!-- Khung nhúng Fanpage + thẻ kết nối trực tiếp đề phòng trình duyệt chặn cookie bên thứ ba -->
          <div class="p-4 flex-1 flex flex-col justify-between gap-4">
            <!-- Thẻ thương hiệu Fanpage trực quan -->
            <div class="rounded-lg border border-slate-200 overflow-hidden bg-slate-50">
              <div class="relative h-28 bg-gradient-to-r from-brand-800 to-brand-600 flex items-center px-4">
                <img
                  src="https://drive.google.com/thumbnail?id=1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ&amp;sz=w800"
                  alt="Ảnh bìa Fanpage Nhôm Kính ĐH"
                  data-drive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
                  onerror="handleDriveImgError(this, 'Nhôm Kính ĐH')"
                  class="absolute inset-0 w-full h-full object-cover opacity-35"
                >
                <div class="relative z-10 flex items-center gap-3">
                  <img
                    src="https://drive.google.com/thumbnail?id=1BHGuSfC-yCgdoOCoY2mCLQh8vD33HabN&amp;sz=w256"
                    alt="Avatar Fanpage Nhôm Kính ĐH"
                    data-drive-id="1BHGuSfC-yCgdoOCoY2mCLQh8vD33HabN"
                    onerror="handleDriveImgError(this, 'ĐH')"
                    class="w-14 h-14 rounded-lg bg-white p-1 object-contain shadow border border-white"
                  >
                  <div class="text-white">
                    <div class="font-extrabold text-sm sm:text-base leading-tight">Nhôm Kính ĐH – Đà Nẵng</div>
                    <div class="text-xs text-slate-200 mt-0.5">Thi công Cửa nhôm Xingfa &amp; Kính cường lực</div>
                  </div>
                </div>
              </div>
              <div class="p-3 flex flex-wrap items-center justify-between gap-2 bg-white">
                <span class="text-xs text-slate-600"><i class="fa-solid fa-phone text-brand-600 mr-1"></i>0905.680.903</span>
                <a
                  href="https://www.facebook.com/profile.php?id=100094026249967&amp;locale=ca_ES"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-lg bg-[#1877F2] hover:bg-[#1665d1] text-white text-xs font-bold transition"
                >
                  <i class="fa-brands fa-facebook-f"></i>
                  <span>Truy cập Fanpage</span>
                </a>
              </div>
            </div>

            <!-- Plugin nhúng chính thức từ Facebook -->
            <div class="w-full overflow-hidden rounded-lg border border-slate-200 bg-white">
              <iframe
                title="Facebook Page Plugin Nhôm Kính ĐH"
                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D100094026249967&amp;tabs=timeline&amp;width=500&amp;height=180&amp;small_header=true&amp;adapt_container_width=true&amp;hide_cover=false&amp;show_facepile=true"
                class="w-full h-[180px] border-0"
                scrolling="no"
                frameborder="0"
                allowfullscreen="true"
                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
              ></iframe>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- KHỐI 12: FOOTER (CHÂN TRANG PHONG CÁCH FLATSOME 4 CỘT)                -->
  <!-- ===================================================================== -->
  <footer class="w-full bg-brand-900 text-slate-300 pt-10 pb-6">
    <div class="ux-container">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-white/15">
        <!-- Cột 1: Thông tin liên hệ -->
        <div class="space-y-3">
          <div class="flex items-center gap-2.5">
            <img
              src="https://drive.google.com/thumbnail?id=1BHGuSfC-yCgdoOCoY2mCLQh8vD33HabN&amp;sz=w256"
              alt="Logo Nhôm Kính ĐH"
              data-drive-id="1BHGuSfC-yCgdoOCoY2mCLQh8vD33HabN"
              onerror="handleDriveImgError(this, 'Nhôm Kính ĐH')"
              class="h-10 w-auto bg-white rounded p-1 object-contain"
            >
            <div class="text-white font-extrabold text-base">NHÔM KÍNH ĐH</div>
          </div>
          <p class="text-xs sm:text-sm text-slate-300 leading-relaxed">
            Chuyên thiết kế, sản xuất và thi công cửa nhôm Xingfa, cửa kính cường lực, cầu thang kính, kính ốp bếp, phòng tắm kính uy tín tại Đà Nẵng.
          </p>
          <ul class="space-y-1.5 text-xs sm:text-sm">
            <li><i class="fa-solid fa-location-dot text-amber-400 w-5"></i>Tổ xuân phố Xuân Phú, Phường Hòa Khánh, TP. Đà Nẵng</li>
            <li><i class="fa-solid fa-phone text-amber-400 w-5"></i><a href="tel:0905680903" class="hover:text-white">0905.680.903</a></li>
            <li><i class="fa-solid fa-globe text-amber-400 w-5"></i>nhomkinhdh.com</li>
          </ul>
        </div>

        <!-- Cột 2: Cửa nhôm Xingfa -->
        <div>
          <h3 class="text-white font-bold text-sm uppercase tracking-wide mb-3 pb-2 border-b border-white/15">
            Cửa nhôm Xingfa
          </h3>
          <ul class="space-y-2 text-xs sm:text-sm">
            <li><a href="#san-pham" onclick="filterProductsByTag('1-canh')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 1 cánh</a></li>
            <li><a href="#san-pham" onclick="filterProductsByTag('2-canh')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 2 cánh</a></li>
            <li><a href="#san-pham" onclick="filterProductsByTag('3-canh')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 3 cánh</a></li>
            <li><a href="#san-pham" onclick="filterProductsByTag('4-canh')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 4 cánh</a></li>
            <li><a href="#san-pham" onclick="filterProductsByTag('5-canh')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 5 cánh</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục sản phẩm -->
        <div>
          <h3 class="text-white font-bold text-sm uppercase tracking-wide mb-3 pb-2 border-b border-white/15">
            Danh mục dịch vụ
          </h3>
          <ul class="space-y-2 text-xs sm:text-sm">
            <li><a href="#san-pham" onclick="filterProductsByCategory('kinh-cuong-luc')" class="hover:text-amber-300 transition">Cửa kính cường lực</a></li>
            <li><a href="#san-pham" onclick="filterProductsByCategory('cua-nhua')" class="hover:text-amber-300 transition">Cửa nhựa lõi thép</a></li>
            <li><a href="#san-pham" onclick="filterProductsByCategory('tu-dong')" class="hover:text-amber-300 transition">Cửa kính tự động</a></li>
            <li><a href="#san-pham" onclick="filterProductsByCategory('cau-thang')" class="hover:text-amber-300 transition">Cầu thang kính</a></li>
            <li><a href="#san-pham" onclick="filterProductsByCategory('kinh-bep')" class="hover:text-amber-300 transition">Kính ốp bếp</a></li>
            <li><a href="#san-pham" onclick="filterProductsByCategory('phong-tam')" class="hover:text-amber-300 transition">Phòng tắm kính</a></li>
          </ul>
        </div>

        <!-- Cột 4: Liên kết nhanh -->
        <div>
          <h3 class="text-white font-bold text-sm uppercase tracking-wide mb-3 pb-2 border-b border-white/15">
            Hỗ trợ khách hàng
          </h3>
          <ul class="space-y-2 text-xs sm:text-sm">
            <li><a href="#gioi-thieu" class="hover:text-amber-300 transition">Giới thiệu Nhôm Kính ĐH</a></li>
            <li><a href="#cong-trinh" class="hover:text-amber-300 transition">Công trình tiêu biểu Đà Nẵng</a></li>
            <li><a href="#bao-gia" class="hover:text-amber-300 transition">Bảng báo giá mới nhất</a></li>
            <li><a href="#tin-tuc" class="hover:text-amber-300 transition">Tin tức &amp; Tư vấn</a></li>
            <li><a href="#form-bao-gia" class="hover:text-amber-300 transition">Đăng ký khảo sát miễn phí</a></li>
            <li>
              <a href="https://www.facebook.com/profile.php?id=100094026249967&amp;locale=ca_ES" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 text-amber-300 hover:underline">
                <i class="fa-brands fa-facebook"></i>
                <span>Fanpage Facebook chính thức</span>
              </a>
            </li>
          </ul>
        </div>
      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
        <div>Copyright © 2026 <strong>Nhôm Kính ĐH</strong> (nhomkinhdh.com). Bảo lưu mọi quyền.</div>
        <div>Thi công Nhôm Kính &amp; Cửa Nhôm Xingfa chuyên nghiệp tại TP. Đà Nẵng</div>
      </div>
    </div>
  </footer>

  <!-- ===================================================================== -->
  <!-- CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE                      -->
  <!-- Tương thích riêng biệt cho Máy tính (góc phải) & Điện thoại (đáy)     -->
  <!-- ===================================================================== -->

  <!-- Nút nổi cho Máy tính & Máy tính bảng (từ md trở lên) -->
  <div class="hidden md:flex fixed bottom-6 right-5 z-40 flex-col items-end gap-3">
    <!-- Zalo -->
    <a
      href="https://zalo.me/0905680903"
      target="_blank"
      rel="noopener noreferrer"
      title="Chat Zalo Nhôm Kính ĐH"
      class="group relative flex items-center gap-2 bg-[#0068FF] hover:bg-[#0054cc] text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition-all"
    >
      <span class="w-7 h-7 rounded-full bg-white text-[#0068FF] font-extrabold text-[11px] flex items-center justify-center shrink-0">Zalo</span>
      <span class="text-xs font-bold whitespace-nowrap">Chat Zalo</span>
    </a>

    <!-- Facebook -->
    <a
      href="https://www.facebook.com/profile.php?id=100094026249967&amp;locale=ca_ES"
      target="_blank"
      rel="noopener noreferrer"
      title="Fanpage Facebook Nhôm Kính ĐH"
      class="group relative flex items-center gap-2 bg-[#1877F2] hover:bg-[#145dbf] text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition-all"
    >
      <span class="w-7 h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
        <i class="fa-brands fa-facebook-f text-sm"></i>
      </span>
      <span class="text-xs font-bold whitespace-nowrap">Facebook</span>
    </a>

    <!-- Hotline có hiệu ứng nhịp nổi bật -->
    <a
      href="tel:0905680903"
      title="Gọi Hotline 0905.680.903"
      class="relative fab-pulse flex items-center gap-2 bg-sale hover:bg-red-700 text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-xl transition-all"
    >
      <span class="w-7 h-7 rounded-full bg-white text-sale flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone-volume text-xs"></i>
      </span>
      <span class="text-xs font-extrabold whitespace-nowrap">0905.680.903</span>
    </a>
  </div>

  <!-- Thanh liên hệ cố định dưới cùng dành riêng cho Điện thoại (không tràn viền) -->
  <div class="md:hidden fixed bottom-0 left-0 right-0 z-40 bg-white border-t border-slate-200 shadow-[0_-4px_12px_rgba(0,0,0,0.08)] grid grid-cols-3 divide-x divide-slate-200">
    <a
      href="tel:0905680903"
      class="flex items-center justify-center gap-1.5 py-3 bg-sale text-white font-bold text-xs active:bg-red-700"
    >
      <i class="fa-solid fa-phone-volume"></i>
      <span>Hotline</span>
    </a>
    <a
      href="https://zalo.me/0905680903"
      target="_blank"
      rel="noopener noreferrer"
      class="flex items-center justify-center gap-1.5 py-3 bg-[#0068FF] text-white font-bold text-xs active:bg-blue-700"
    >
      <span class="px-1 py-0.5 rounded bg-white text-[#0068FF] text-[10px] font-extrabold leading-none">Z</span>
      <span>Chat Zalo</span>
    </a>
    <a
      href="https://www.facebook.com/profile.php?id=100094026249967&amp;locale=ca_ES"
      target="_blank"
      rel="noopener noreferrer"
      class="flex items-center justify-center gap-1.5 py-3 bg-[#1877F2] text-white font-bold text-xs active:bg-blue-800"
    >
      <i class="fa-brands fa-facebook-f"></i>
      <span>Facebook</span>
    </a>
  </div>

  <!-- ===================================================================== -->
  <!-- HỘP THOẠI XEM NHANH SẢN PHẨM / DỰ ÁN / BÀI VIẾT (FLATSOME LIGHTBOX)  -->
  <!-- ===================================================================== -->
  <div id="detailModal" class="fixed inset-0 z-50 hidden items-center justify-center p-3 sm:p-4 bg-slate-900/65 backdrop-blur-[1px]">
    <div class="bg-white rounded-xl shadow-2xl w-full max-w-2xl max-h-[90vh] overflow-y-auto relative">
      <button
        type="button"
        onclick="closeDetailModal()"
        aria-label="Đóng cửa sổ"
        class="sticky top-3 float-right mr-3 mt-3 z-10 w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-700 flex items-center justify-center transition"
      >
        <i class="fa-solid fa-xmark"></i>
      </button>
      <div id="detailModalContent" class="p-4 sm:p-6"></div>
    </div>
  </div>

  <!-- ===================================================================== -->
  <!-- JAVASCRIPT: DỮ LIỆU SẢN PHẨM, DỰ ÁN, TIN TỨC, SLIDER & TƯƠNG TÁC      -->
  <!-- ===================================================================== -->
  <script>
    /**
     * Xử lý dự phòng khi tải ảnh Google Drive:
     * Bước 1: Thử đường dẫn lh3.googleusercontent.com nếu thumbnail lỗi.
     * Bước 2: Dùng ảnh placeholder có tên hạng mục nếu vẫn không tải được.
     */
    function handleDriveImgError(imgEl, labelText) {
      try {
        const driveId = imgEl.getAttribute('data-drive-id');
        const attempt = parseInt(imgEl.getAttribute('data-attempt') || '0', 10);

        if (driveId && attempt === 0) {
          imgEl.setAttribute('data-attempt', '1');
          imgEl.src = 'https://lh3.googleusercontent.com/d/' + driveId + '=w1000';
          return;
        }
        imgEl.onerror = null;
        const safeText = encodeURIComponent(labelText || 'Nhôm Kính ĐH');
        imgEl.src = 'https://placehold.co/600x450/0d4f9b/ffffff?text=' + safeText;
      } catch (err) {
        imgEl.onerror = null;
      }
    }

    /**
     * Hàm tạo đường dẫn ảnh Google Drive chuẩn
     */
    function driveImg(id, size) {
      return 'https://drive.google.com/thumbnail?id=' + id + '&sz=w' + (size || 800);
    }

    /**
     * Định dạng tiền tệ VNĐ
     */
    function formatVND(amount) {
      return amount.toString().replace(/\B(?=(\d{3})+(?!\d))/g, '.') + ' ₫';
    }

    /* =================================================================== */
    /* DỮ LIỆU SẢN PHẨM (ĐẦY ĐỦ ẢNH CUNG CẤP + DANH MỤC WEB MẪU)           */
    /* =================================================================== */
    const PRODUCTS = [
      {
        id: 'sp-1',
        name: 'Cửa đi quay mở 1 cánh nhôm Xingfa',
        category: 'xingfa',
        tags: ['xingfa', '1-canh'],
        driveId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
        oldPrice: 2400000,
        price: 2100000,
        discount: 13,
        unit: 'm²',
        specs: [
          'Thanh nhôm Profile Xingfa hệ 55 nhập khẩu, độ dày 2.0mm',
          'Kính cường lực 8mm hoặc kính dán an toàn 6.38mm',
          'Phụ kiện Kinlong chính hãng đồng bộ, gioăng kép EPDM kín khít',
          'Màu sắc: Xám ghi, Nâu cafe, Trắng sứ, Đen tuyền, Vân gỗ',
          'Bảo hành thanh nhôm 5 năm, phụ kiện 2 năm'
        ]
      },
      {
        id: 'sp-2',
        name: 'Cửa đi quay mở 2 cánh nhôm Xingfa',
        category: 'xingfa',
        tags: ['xingfa', '2-canh'],
        driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
        oldPrice: 2450000,
        price: 2100000,
        discount: 14,
        unit: 'm²',
        specs: [
          'Thanh nhôm Xingfa hệ 55 dày 2.0mm kết cấu khoang rỗng tăng cứng',
          'Phù hợp cửa chính nhà phố, cửa ban công, cửa phòng khách',
          'Khóa đa điểm an toàn cao, chống cạy phá, cách âm vượt trội',
          'Keo ép góc đặc chủng & keo Silicone trung tính chịu mưa nắng Đà Nẵng'
        ]
      },
      {
        id: 'sp-3',
        name: 'Cửa đi quay mở 3 cánh nhôm Xingfa',
        category: 'xingfa',
        tags: ['xingfa', '3-canh'],
        driveId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
        oldPrice: 2500000,
        price: 2100000,
        discount: 16,
        unit: 'm²',
        specs: [
          'Nhôm Xingfa nhập khẩu tem đỏ hệ 55 dày 2.0mm',
          'Thiết kế 3 cánh linh hoạt, mở rộng tối đa không gian đi lại',
          'Chịu áp lực gió lên đến 1600 Pascal, an toàn mùa mưa bão',
          'Phụ kiện Kinlong đồng bộ, vận hành êm ái không xệ cánh'
        ]
      },
      {
        id: 'sp-4',
        name: 'Cửa đi quay mở 4 cánh nhôm Xingfa',
        category: 'xingfa',
        tags: ['xingfa', '4-canh'],
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        oldPrice: 2500000,
        price: 2100000,
        discount: 16,
        unit: 'm²',
        specs: [
          'Nhôm Xingfa hệ 55 dày 2.0mm dành cho mặt tiền rộng rãi',
          'Mở quay 4 cánh sang trọng, lấy sáng tối đa cho phòng khách',
          'Sơn tĩnh điện cao cấp ngoài trời bền màu trước khí hậu ven biển',
          'Lắp đặt trọn gói kèm đo đạc miễn phí tại TP. Đà Nẵng'
        ]
      },
      {
        id: 'sp-5',
        name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
        category: 'xingfa',
        tags: ['xingfa', '5-canh'],
        driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        oldPrice: 2550000,
        price: 2150000,
        discount: 15,
        unit: 'm²',
        specs: [
          'Nhôm Xingfa hệ 63 / 93 nhập khẩu độ dày 1.8mm – 2.5mm',
          'Thiết kế xếp gấp gọn về một bên (từ 3, 4, 5 đến 8 cánh)',
          'Hệ ray treo, bánh xe chịu lực chống nhấc, đóng mở nhẹ nhàng',
          'Lý tưởng cho biệt thự, resort, nhà hàng, không gian sân vườn'
        ]
      },
      {
        id: 'sp-6',
        name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
        category: 'xingfa',
        tags: ['xingfa', '2-canh'],
        driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
        oldPrice: 2250000,
        price: 1900000,
        discount: 15,
        unit: 'm²',
        specs: [
          'Thanh nhôm Xingfa hệ 55 chuyên dụng cho cửa sổ, dày 1.4mm',
          'Mở hất góc 45 độ giúp thông gió kể cả khi trời mưa nhỏ',
          'Thanh định vị chống gió dập, bản lề chữ A inox 304 cao cấp',
          'Cách âm, cách nhiệt tốt, tiết kiệm điện điều hòa'
        ]
      },
      {
        id: 'sp-7',
        name: 'Cửa kính cường lực bản lề sàn 10mm – 12mm',
        category: 'kinh-cuong-luc',
        tags: ['kinh-cuong-luc'],
        driveId: '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ',
        oldPrice: 1050000,
        price: 890000,
        discount: 15,
        unit: 'm²',
        specs: [
          'Kính cường lực tôi nhiệt chuẩn 10mm hoặc 12mm chịu lực cao',
          'Phụ kiện bản lề sàn, kẹp kính, tay nắm inox VVP / Hafele chính hãng',
          'Thiết kế không khung sang trọng cho cửa hàng, văn phòng, nhà phố',
          'Thi công nhanh gọn, an toàn tuyệt đối'
        ]
      },
      {
        id: 'sp-8',
        name: 'Cửa nhựa lõi thép uPVC cách âm cao cấp',
        category: 'cua-nhua',
        tags: ['cua-nhua'],
        driveId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
        oldPrice: 1850000,
        price: 1590000,
        discount: 14,
        unit: 'm²',
        specs: [
          'Thanh nhựa uPVC Sparlee có lõi thép mạ kẽm gia cường bên trong',
          'Cách âm, cách nhiệt hiệu quả, không cong vênh mối mọt',
          'Phù hợp cửa phòng ngủ, cửa nhà vệ sinh, cửa sổ căn hộ',
          'Giá thành tiết kiệm, độ bền sử dụng lâu dài'
        ]
      },
      {
        id: 'sp-9',
        name: 'Cửa kính tự động cảm biến mắt thần',
        category: 'tu-dong',
        tags: ['tu-dong', 'kinh-cuong-luc'],
        driveId: '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ',
        oldPrice: 28500000,
        price: 24900000,
        discount: 13,
        unit: 'bộ',
        specs: [
          'Motor tự động nhập khẩu Hàn Quốc / Nhật Bản vận hành êm ái',
          'Cảm biến mắt thần đóng mở nhạy bén, tự đảo chiều khi gặp vật cản',
          'Kết hợp kính cường lực 10mm–12mm sang trọng hiện đại',
          'Phù hợp khách sạn, showroom, siêu thị, văn phòng'
        ]
      },
      {
        id: 'sp-10',
        name: 'Cầu thang kính cường lực tay vịn gỗ',
        category: 'cau-thang',
        tags: ['cau-thang', 'kinh-cuong-luc'],
        driveId: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul',
        oldPrice: 1550000,
        price: 1350000,
        discount: 13,
        unit: 'md',
        specs: [
          'Kính cường lực 10mm – 12mm trong suốt mở rộng không gian nhà',
          'Trụ inox 304 chống gỉ kết hợp tay vịn gỗ tự nhiên hoặc inox',
          'Dễ vệ sinh lau chùi, chịu va đập mạnh, đảm bảo an toàn',
          'Đo đạc CNC chuẩn xác từng bậc cầu thang'
        ]
      },
      {
        id: 'sp-11',
        name: 'Kính ốp bếp cường lực sơn màu chịu nhiệt',
        category: 'kinh-bep',
        tags: ['kinh-bep'],
        driveId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
        oldPrice: 980000,
        price: 820000,
        discount: 16,
        unit: 'md',
        specs: [
          'Kính cường lực 8mm phun sơn nhiệt bền màu không bong tróc',
          'Chịu nhiệt độ cao khu vực bếp nấu, chống bám dầu mỡ dễ lau chùi',
          'Bảng màu phong phú: xanh ngọc, vàng chanh, trắng sữa, kim sa...',
          'Lắp đặt liền mạch không mạch vữa, hoàn thiện trong ngày'
        ]
      },
      {
        id: 'sp-12',
        name: 'Phòng tắm kính cường lực vách ngăn hiện đại',
        category: 'phong-tam',
        tags: ['phong-tam', 'kinh-cuong-luc'],
        driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
        oldPrice: 1650000,
        price: 1390000,
        discount: 16,
        unit: 'm²',
        specs: [
          'Kính cường lực 10mm an toàn, thiết kế góc 90°, 135° hoặc cửa lùa',
          'Phụ kiện kẹp kính, bản lề, gioăng chắn nước inox 304 không gỉ',
          'Giữ khu vực vệ sinh luôn khô ráo, sạch sẽ, đẳng cấp như khách sạn',
          'Thi công gọn gàng, bảo hành chống thấm nước'
        ]
      }
    ];

    /* =================================================================== */
    /* DỮ LIỆU 6 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG                               */
    /* =================================================================== */
    const PROJECTS = [
      {
        title: 'DỰ ÁN KHÁCH SẠN RUBY LIGHT',
        location: 'TP. Đà Nẵng',
        category: 'Khách sạn',
        driveId: '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ',
        summary: 'Thi công toàn bộ hệ thống cửa nhôm Xingfa cách âm, cửa đi ban công, vách kính mặt dựng và phòng tắm kính cường lực đạt chuẩn khách sạn.'
      },
      {
        title: 'DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT & SPA”',
        location: 'Quảng Nam – Đà Nẵng',
        category: 'Resort 4 sao',
        driveId: '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ',
        summary: 'Cung cấp và lắp đặt hạng mục cửa nhôm Xingfa xếp trượt không gian mở, vách kính lớn đón ánh sáng tự nhiên và kính phòng tắm cao cấp.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE',
        location: 'TP. Đà Nẵng',
        category: 'Khách sạn',
        driveId: '1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy',
        summary: 'Gia công và lắp đặt trọn gói cửa sổ nhôm Xingfa chống gió bão ven biển, cửa kính tự động sảnh chính và vách kính cường lực.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA',
        location: 'TP. Đà Nẵng',
        category: 'Khách sạn & Căn hộ',
        driveId: '1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64',
        summary: 'Hoàn thiện hệ cửa nhôm kính Xingfa nhập khẩu đồng bộ phụ kiện Kinlong, đảm bảo độ kín khít, cách âm tối đa cho khối phòng lưu trú.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN SOHO',
        location: 'TP. Đà Nẵng',
        category: 'Boutique Hotel',
        driveId: '1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt',
        summary: 'Thi công hạng mục mặt dựng nhôm kính, cửa kính cường lực sảnh đón tiếp, cầu thang kính và cabin phòng tắm kính sang trọng.'
      },
      {
        title: 'THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL',
        location: 'Biển Mỹ Khê, Đà Nẵng',
        category: 'Khách sạn ven biển',
        driveId: '1za_IJpAm850uulT6IuhBsk1THb3LuPuc',
        summary: 'Lắp đặt hệ nhôm kính cao cấp sơn tĩnh điện chống ăn mòn muối biển, cửa lùa ban công tầm nhìn biển rộng mở và phòng tắm kính hiện đại.'
      }
    ];

    /* =================================================================== */
    /* DỮ LIỆU DANH MỤC BÀI VIẾT & TIN TỨC NỔI BẬT TRANG CHỦ               */
    /* =================================================================== */
    const ARTICLES = [
      {
        id: 'bv-1',
        cat: 'tu-van',
        catLabel: 'Tư vấn chọn cửa',
        date: '18/11/2026',
        driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
        title: 'Cửa nhôm Xingfa có phù hợp với khí hậu ven biển Đà Nẵng không?',
        excerpt: 'Đà Nẵng có khí hậu nắng nóng, mưa bão và hơi muối biển. Cửa nhôm Xingfa sơn tĩnh điện cao cấp kết hợp gioăng EPDM giúp chống ăn mòn và chắn gió vượt trội.',
        content: 'Với đặc thù khí hậu miền Trung thường xuyên chịu ảnh hưởng của gió bão và độ ẩm cao vùng ven biển, việc lựa chọn hệ cửa bền bỉ là ưu tiên hàng đầu. Thanh nhôm Xingfa chính hãng có kết cấu khoang rỗng kèm 2 đường gân gia cường, bề mặt phủ sơn tĩnh điện ngoài trời chống oxy hóa hiệu quả. Khi kết hợp phụ kiện Kinlong đồng bộ và hệ gioăng cao su kép EPDM, cửa đạt độ kín khít cao, chống hắt nước mưa và chịu áp lực gió lên đến 1600 Pascal.'
      },
      {
        id: 'bv-2',
        cat: 'tu-van',
        catLabel: 'Tư vấn chọn cửa',
        date: '15/11/2026',
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        title: 'Cửa nhôm Xingfa có tiết kiệm năng lượng và cách âm tốt không?',
        excerpt: 'Nhờ cấu trúc khoang rỗng và kính an toàn hoặc kính hộp, cửa nhôm Xingfa hạn chế thất thoát nhiệt điều hòa và giảm tiếng ồn đô thị hiệu quả.',
        content: 'Một trong những ưu điểm khiến cửa nhôm Xingfa được nhiều gia đình và khách sạn tại Đà Nẵng lựa chọn là khả năng cách âm, cách nhiệt vượt trội. Khung nhôm ép góc kín khít bằng công nghệ máy hiện đại giúp giữ hơi lạnh điều hòa trong phòng, giảm đáng kể hóa đơn tiền điện mùa nắng nóng đồng thời mang lại không gian nghỉ ngơi yên tĩnh.'
      },
      {
        id: 'bv-3',
        cat: 'kinh-nghiem',
        catLabel: 'Kinh nghiệm thi công',
        date: '10/11/2026',
        driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
        title: 'So sánh cửa nhôm Xingfa và cửa nhựa lõi thép: Nên chọn loại nào?',
        excerpt: 'Phân tích chi tiết độ bền, tính thẩm mỹ, khả năng chịu lực và chi phí đầu tư giữa cửa nhôm Xingfa và cửa nhựa lõi thép uPVC.',
        content: 'Cửa nhôm Xingfa nổi bật với độ cứng vững cao, chịu lực tốt, viền khung thanh mảnh sang trọng và nhiều lựa chọn màu sắc như xám ghi, đen, nâu cafe, vân gỗ — rất lý tưởng cho cửa mặt tiền và công trình cao tầng. Trong khi đó, cửa nhựa lõi thép uPVC có ưu thế chi phí hợp lý và khả năng cách âm tốt, thích hợp làm cửa phòng ngủ hoặc căn hộ tối ưu ngân sách.'
      },
      {
        id: 'bv-4',
        cat: 'kinh-nghiem',
        catLabel: 'Kinh nghiệm thi công',
        date: '05/11/2026',
        driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
        title: 'Kinh nghiệm lắp đặt phòng tắm kính & kính ốp bếp bền đẹp theo thời gian',
        excerpt: 'Cách chọn độ dày kính cường lực chuẩn, phụ kiện inox 304 chống rỉ sét và quy trình bắn keo chống thấm cho phòng tắm, khu bếp.',
        content: 'Đối với phòng tắm kính, nên sử dụng kính cường lực dày 10mm đi kèm phụ kiện kẹp, bản lề bằng Inox 304 chống gỉ tuyệt đối trong môi trường ẩm ướt. Đối với kính ốp bếp, kính cường lực 8mm sơn chịu nhiệt giúp bề mặt sáng bóng, dễ lau sạch dầu mỡ và mang lại cảm giác rộng thoáng cho không gian nấu nướng.'
      },
      {
        id: 'bv-5',
        cat: 'bao-gia',
        catLabel: 'Cẩm nang báo giá',
        date: '01/11/2026',
        driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        title: 'Cách tính diện tích và dự toán báo giá cửa nhôm Xingfa chính xác',
        excerpt: 'Hướng dẫn công thức tính giá trọn gói cửa nhôm kính = (Diện tích cửa x Đơn giá/m²) + Bộ phụ kiện đi kèm giúp chủ nhà chủ động ngân sách.',
        content: 'Để dự toán chi phí làm cửa nhôm Xingfa chính xác, bạn chỉ cần nhân diện tích thông thủy (chiều rộng x chiều cao) với đơn giá từng hệ cửa (mở quay, mở trượt, xếp trượt, mở hất), sau đó cộng thêm giá bộ phụ kiện Kinlong tương ứng số cánh. Tại Nhôm Kính ĐH, chúng tôi luôn khảo sát thực tế và gửi bảng báo giá bóc tách minh bạch trước khi thi công.'
      },
      {
        id: 'bv-6',
        cat: 'bao-gia',
        catLabel: 'Cẩm nang báo giá',
        date: '26/10/2026',
        driveId: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul',
        title: 'Các mẫu cầu thang kính và cửa kính cường lực đẹp cho nhà phố Đà Nẵng',
        excerpt: 'Tổng hợp những mẫu cầu thang kính tay vịn gỗ và cửa kính bản lề sàn giúp tối ưu ánh sáng tự nhiên cho nhà ống hiện đại.',
        content: 'Nhà phố hiện đại thường có chiều ngang vừa phải nên giải pháp sử dụng cầu thang kính cường lực và cửa kính trong suốt giúp không gian trở nên thoáng đãng, sang trọng hơn hẳn so với lan can xây tường truyền thống. Nhôm Kính ĐH nhận thiết kế và thi công trọn gói theo kích thước thực tế từng ngôi nhà.'
      }
    ];

    /* =================================================================== */
    /* RENDER SẢN PHẨM (CHIA 2 CỘT DI ĐỘNG, TÊN KHÔNG TRÀN, GIẢM GIÁ %)    */
    /* =================================================================== */
    function renderProducts(list) {
      const grid = document.getElementById('productGrid');
      if (!grid) return;

      if (!list || list.length === 0) {
        grid.innerHTML = '<div class="col-span-full text-center py-8 text-sm text-slate-500">Không tìm thấy sản phẩm trong danh mục này.</div>';
        return;
      }

      grid.innerHTML = list.map(function (p) {
        return (
          '<article class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-500 transition flex flex-col">' +
            '<div class="relative aspect-[4/3] w-full overflow-hidden bg-slate-100">' +
              /* Huy hiệu giảm giá % góc trên bên trái đúng phong cách Flatsome */
              '<span class="absolute top-2 left-2 z-10 inline-flex items-center justify-center px-2 py-1 rounded-md bg-sale text-white text-[11px] sm:text-xs font-extrabold leading-none shadow">-' + p.discount + '%</span>' +
              '<img ' +
                'src="' + driveImg(p.driveId, 700) + '" ' +
                'alt="' + p.name + '" ' +
                'data-drive-id="' + p.driveId + '" ' +
                'onerror="handleDriveImgError(this, \'' + p.name.replace(/'/g, '') + '\')" ' +
                'class="w-full h-full object-cover group-hover:scale-105 transition duration-300 cursor-pointer" ' +
                'onclick="openProductModal(\'' + p.id + '\')"' +
              '>' +
            '</div>' +
            '<div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between gap-2">' +
              /* Tên sản phẩm hiển thị đầy đủ, không bị cắt thiếu chữ hay tràn viền */
              '<h3 onclick="openProductModal(\'' + p.id + '\')" class="text-[12.5px] sm:text-[14px] font-bold text-slate-800 group-hover:text-brand-700 leading-snug break-words cursor-pointer">' +
                p.name +
              '</h3>' +
              '<div class="space-y-2 pt-1">' +
                '<div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">' +
                  '<span class="text-[13px] sm:text-[15px] font-extrabold text-sale">' + formatVND(p.price) + '<span class="text-[11px] font-medium text-slate-500">/' + p.unit + '</span></span>' +
                  '<span class="text-[11px] sm:text-xs text-slate-400 line-through">' + formatVND(p.oldPrice) + '</span>' +
                '</div>' +
                '<div class="grid grid-cols-2 gap-1.5">' +
                  '<button type="button" onclick="openProductModal(\'' + p.id + '\')" class="px-2 py-1.5 rounded-lg border border-brand-600 text-brand-700 hover:bg-brand-50 text-[11px] sm:text-xs font-semibold transition text-center">Xem nhanh</button>' +
                  '<button type="button" onclick="requestProductQuote(\'' + p.name.replace(/'/g, '') + '\')" class="px-2 py-1.5 rounded-lg bg-brand-700 hover:bg-brand-800 text-white text-[11px] sm:text-xs font-semibold transition text-center">Báo giá</button>' +
                '</div>' +
              '</div>' +
            '</div>' +
          '</article>'
        );
      }).join('');
    }

    function updateActiveFilterTab(filterKey) {
      document.querySelectorAll('.filter-tab').forEach(function (btn) {
        const isMatch = btn.getAttribute('data-filter') === filterKey;
        btn.className = 'filter-tab px-3 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold transition whitespace-nowrap ' +
          (isMatch ? 'bg-brand-700 text-white' : 'bg-slate-100 text-slate-700 hover:bg-brand-50 hover:text-brand-700');
      });
    }

    function filterProductsByCategory(category) {
      updateActiveFilterTab(category);
      if (category === 'all') {
        renderProducts(PRODUCTS);
        return;
      }
      const filtered = PRODUCTS.filter(function (p) {
        return p.category === category || (p.tags && p.tags.indexOf(category) !== -1);
      });
      renderProducts(filtered);
    }

    function filterProductsByTag(tag) {
      updateActiveFilterTab('xingfa');
      const filtered = PRODUCTS.filter(function (p) {
        return p.tags && p.tags.indexOf(tag) !== -1;
      });
      renderProducts(filtered.length > 0 ? filtered : PRODUCTS.filter(function (p) { return p.category === 'xingfa'; }));
    }

    /* =================================================================== */
    /* RENDER 6 DỰ ÁN ĐÀ NẴNG                                              */
    /* =================================================================== */
    function renderProjects() {
      const grid = document.getElementById('projectGrid');
      if (!grid) return;

      grid.innerHTML = PROJECTS.map(function (proj, idx) {
        return (
          '<article onclick="openProjectModal(' + idx + ')" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-500 transition cursor-pointer flex flex-col">' +
            '<div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">' +
              '<img ' +
                'src="' + driveImg(proj.driveId, 800) + '" ' +
                'alt="' + proj.title + '" ' +
                'data-drive-id="' + proj.driveId + '" ' +
                'onerror="handleDriveImgError(this, \'' + proj.title.replace(/'/g, '') + '\')" ' +
                'class="w-full h-full object-cover group-hover:scale-105 transition duration-300"' +
              '>' +
            '</div>' +
            '<div class="p-4 flex-1 flex flex-col justify-between gap-2">' +
              '<div>' +
                '<div class="text-[11px] font-semibold text-amber-600 uppercase mb-1">' + proj.category + ' • ' + proj.location + '</div>' +
                '<h3 class="text-sm font-bold text-slate-800 group-hover:text-brand-700 leading-snug">' + proj.title + '</h3>' +
                '<p class="text-xs text-slate-600 mt-1.5 leading-relaxed">' + proj.summary + '</p>' +
              '</div>' +
              '<div class="text-xs font-bold text-brand-700 pt-1">Xem chi tiết công trình &rarr;</div>' +
            '</div>' +
          '</article>'
        );
      }).join('');
    }

    /* =================================================================== */
    /* RENDER DANH MỤC BÀI VIẾT TRANG CHỦ                                  */
    /* =================================================================== */
    function renderArticles(list) {
      const grid = document.getElementById('articleGrid');
      if (!grid) return;

      grid.innerHTML = list.map(function (art) {
        return (
          '<article onclick="openArticleModal(\'' + art.id + '\')" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-500 transition cursor-pointer flex flex-col">' +
            '<div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">' +
              '<img ' +
                'src="' + driveImg(art.driveId, 700) + '" ' +
                'alt="' + art.title + '" ' +
                'data-drive-id="' + art.driveId + '" ' +
                'onerror="handleDriveImgError(this, \'Tin Tức Nhôm Kính\')" ' +
                'class="w-full h-full object-cover group-hover:scale-105 transition duration-300"' +
              '>' +
            '</div>' +
            '<div class="p-4 flex-1 flex flex-col justify-between gap-2">' +
              '<div>' +
                '<div class="flex items-center justify-between text-[11px] text-slate-500 mb-1.5">' +
                  '<span class="font-semibold text-brand-700">' + art.catLabel + '</span>' +
                  '<span>' + art.date + '</span>' +
                '</div>' +
                '<h3 class="text-sm font-bold text-slate-800 group-hover:text-brand-700 leading-snug">' + art.title + '</h3>' +
                '<p class="text-xs text-slate-600 mt-1.5 leading-relaxed">' + art.excerpt + '</p>' +
              '</div>' +
              '<div class="text-xs font-bold text-brand-700 pt-1">Đọc bài viết &rarr;</div>' +
            '</div>' +
          '</article>'
        );
      }).join('');
    }

    function filterArticles(cat) {
      document.querySelectorAll('.art-tab').forEach(function (btn) {
        const active = btn.getAttribute('data-art-filter') === cat;
        btn.className = 'art-tab px-3 py-1.5 rounded-lg text-xs font-semibold transition whitespace-nowrap ' +
          (active ? 'bg-brand-700 text-white' : 'bg-white border border-slate-200 text-slate-700 hover:border-brand-500');
      });
      if (cat === 'all') {
        renderArticles(ARTICLES);
      } else {
        renderArticles(ARTICLES.filter(function (a) { return a.cat === cat; }));
      }
    }

    /* =================================================================== */
    /* HỘP THOẠI XEM NHANH (SẢN PHẨM / DỰ ÁN / BÀI VIẾT)                   */
    /* =================================================================== */
    function openDetailModal(html) {
      const modal = document.getElementById('detailModal');
      const content = document.getElementById('detailModalContent');
      content.innerHTML = html;
      modal.classList.remove('hidden');
      modal.classList.add('flex');
      document.body.style.overflow = 'hidden';
    }

    function closeDetailModal() {
      const modal = document.getElementById('detailModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
      document.body.style.overflow = '';
    }

    function openProductModal(productId) {
      const p = PRODUCTS.find(function (item) { return item.id === productId; });
      if (!p) return;

      const specsHtml = p.specs.map(function (s) {
        return '<li class="flex items-start gap-2 text-xs sm:text-sm text-slate-700"><i class="fa-solid fa-check text-brand-600 mt-1 shrink-0"></i><span>' + s + '</span></li>';
      }).join('');

      openDetailModal(
        '<div class="grid grid-cols-1 sm:grid-cols-2 gap-5 items-start">' +
          '<div class="relative rounded-xl overflow-hidden bg-slate-100 border border-slate-200">' +
            '<span class="absolute top-2.5 left-2.5 z-10 px-2.5 py-1 rounded-md bg-sale text-white text-xs font-extrabold">-' + p.discount + '%</span>' +
            '<img src="' + driveImg(p.driveId, 900) + '" alt="' + p.name + '" data-drive-id="' + p.driveId + '" onerror="handleDriveImgError(this, \'' + p.name.replace(/'/g, '') + '\')" class="w-full h-56 sm:h-64 object-cover">' +
          '</div>' +
          '<div class="space-y-3">' +
            '<h3 class="text-base sm:text-lg font-extrabold text-brand-700 leading-snug">' + p.name + '</h3>' +
            '<div class="flex items-baseline gap-2.5">' +
              '<span class="text-xl font-extrabold text-sale">' + formatVND(p.price) + ' / ' + p.unit + '</span>' +
              '<span class="text-xs text-slate-400 line-through">' + formatVND(p.oldPrice) + '</span>' +
            '</div>' +
            '<ul class="space-y-1.5 pt-1">' + specsHtml + '</ul>' +
            '<div class="flex flex-wrap gap-2 pt-3">' +
              '<button type="button" onclick="closeDetailModal(); requestProductQuote(\'' + p.name.replace(/'/g, '') + '\');" class="flex-1 py-2.5 px-4 rounded-lg bg-amber-500 hover:bg-amber-600 text-white text-xs sm:text-sm font-bold transition">Nhận báo giá mẫu này</button>' +
              '<a href="tel:0905680903" class="py-2.5 px-4 rounded-lg bg-brand-700 hover:bg-brand-800 text-white text-xs sm:text-sm font-bold transition">Gọi 0905.680.903</a>' +
            '</div>' +
          '</div>' +
        '</div>'
      );
    }

    function openProjectModal(index) {
      const proj = PROJECTS[index];
      if (!proj) return;
      openDetailModal(
        '<div class="space-y-4">' +
          '<img src="' + driveImg(proj.driveId, 1000) + '" alt="' + proj.title + '" data-drive-id="' + proj.driveId + '" onerror="handleDriveImgError(this, \'Dự Án Đà Nẵng\')" class="w-full max-h-80 object-cover rounded-xl">' +
          '<div class="text-xs font-bold uppercase text-amber-600">' + proj.category + ' • ' + proj.location + '</div>' +
          '<h3 class="text-lg font-extrabold text-brand-700">' + proj.title + '</h3>' +
          '<p class="text-sm text-slate-600 leading-relaxed">' + proj.summary + '</p>' +
          '<div class="pt-2 flex flex-wrap gap-2">' +
            '<button type="button" onclick="closeDetailModal(); requestProductQuote(\'Tư vấn hạng mục tương tự ' + proj.title.replace(/'/g, '') + '\');" class="px-5 py-2.5 rounded-lg bg-brand-700 hover:bg-brand-800 text-white text-xs sm:text-sm font-bold transition">Yêu cầu tư vấn công trình</button>' +
          '</div>' +
        '</div>'
      );
    }

    function openArticleModal(articleId) {
      const art = ARTICLES.find(function (a) { return a.id === articleId; });
      if (!art) return;
      openDetailModal(
        '<div class="space-y-4">' +
          '<div class="text-xs text-slate-500 font-semibold">' + art.catLabel + ' • ' + art.date + '</div>' +
          '<h3 class="text-lg sm:text-xl font-extrabold text-brand-700 leading-snug">' + art.title + '</h3>' +
          '<img src="' + driveImg(art.driveId, 900) + '" alt="' + art.title + '" data-drive-id="' + art.driveId + '" onerror="handleDriveImgError(this, \'Nhôm Kính ĐH\')" class="w-full max-h-72 object-cover rounded-xl">' +
          '<p class="text-sm text-slate-700 leading-relaxed">' + art.content + '</p>' +
          '<div class="p-3.5 rounded-lg bg-brand-50 border border-brand-100 text-xs sm:text-sm text-brand-800">' +
            'Quý khách cần tư vấn chi tiết &amp; đo đạc miễn phí tại Đà Nẵng vui lòng liên hệ <strong>Nhôm Kính ĐH – Hotline/Zalo: 0905.680.903</strong>.' +
          '</div>' +
        '</div>'
      );
    }

    /**
     * Điền sẵn tên sản phẩm vào form báo giá và cuộn mượt tới form
     */
    function requestProductQuote(productName) {
      const noteEl = document.getElementById('customerNote');
      const formSec = document.getElementById('form-bao-gia');
      if (noteEl) {
        noteEl.value = 'Tôi cần tư vấn và báo giá chi tiết cho: ' + productName;
      }
      if (formSec) {
        formSec.scrollIntoView({ behavior: 'smooth' });
      }
      setTimeout(function () {
        const nameInput = document.getElementById('customerName');
        if (nameInput) nameInput.focus();
      }, 500);
    }

    /* =================================================================== */
    /* ĐIỀU KHIỂN 2 BANNER TỰ TRƯỢT + HỖ TRỢ VUỐT CẢM ỨNG TRÊN ĐIỆN THOẠI  */
    /* =================================================================== */
    let currentHeroSlide = 0;
    const totalHeroSlides = 2;
    let heroAutoTimer = null;

    function updateHeroSlider() {
      const track = document.getElementById('heroTrack');
      const dots = document.querySelectorAll('.hero-dot');
      if (track) {
        track.style.transform = 'translateX(-' + (currentHeroSlide * 100) + '%)';
      }
      dots.forEach(function (dot, idx) {
        if (idx === currentHeroSlide) {
          dot.classList.remove('w-2.5', 'bg-white/60');
          dot.classList.add('w-6', 'bg-amber-400');
        } else {
          dot.classList.remove('w-6', 'bg-amber-400');
          dot.classList.add('w-2.5', 'bg-white/60');
        }
      });
    }

    function goToHeroSlide(index) {
      currentHeroSlide = (index + totalHeroSlides) % totalHeroSlides;
      updateHeroSlider();
      resetHeroTimer();
    }

    function resetHeroTimer() {
      if (heroAutoTimer) clearInterval(heroAutoTimer);
      heroAutoTimer = setInterval(function () {
        currentHeroSlide = (currentHeroSlide + 1) % totalHeroSlides;
        updateHeroSlider();
      }, 5000);
    }

    /* =================================================================== */
    /* MENU DI ĐỘNG (MOBILE DRAWER & SUBMENU ACCORDION)                    */
    /* =================================================================== */
    function openMobileMenu() {
      document.getElementById('mobileMenuOverlay').classList.remove('hidden');
      document.getElementById('mobileMenuDrawer').classList.remove('-translate-x-full');
      document.body.style.overflow = 'hidden';
    }

    function closeMobileMenu() {
      document.getElementById('mobileMenuOverlay').classList.add('hidden');
      document.getElementById('mobileMenuDrawer').classList.add('-translate-x-full');
      document.body.style.overflow = '';
    }

    function toggleMobileSubmenu(id, btn) {
      const sub = document.getElementById(id);
      if (!sub) return;
      sub.classList.toggle('hidden');
      const icon = btn.querySelector('i');
      if (icon) icon.classList.toggle('rotate-180');
    }

    /* =================================================================== */
    /* KHỞI TẠO TOÀN BỘ SỰ KIỆN KHI TRANG TẢI XONG                         */
    /* =================================================================== */
    window.addEventListener('DOMContentLoaded', function () {
      // Hiển thị toàn bộ danh sách ban đầu
      renderProducts(PRODUCTS);
      renderProjects();
      renderArticles(ARTICLES);

      // Gắn sự kiện nút trượt banner
      const prevBtn = document.getElementById('heroPrev');
      const nextBtn = document.getElementById('heroNext');
      if (prevBtn) prevBtn.addEventListener('click', function () { goToHeroSlide(currentHeroSlide - 1); });
      if (nextBtn) nextBtn.addEventListener('click', function () { goToHeroSlide(currentHeroSlide + 1); });

      // Hỗ trợ vuốt ngang banner trên điện thoại
      const sliderEl = document.getElementById('heroSlider');
      let touchStartX = 0;
      if (sliderEl) {
        sliderEl.addEventListener('touchstart', function (e) {
          touchStartX = e.changedTouches[0].screenX;
        }, { passive: true });
        sliderEl.addEventListener('touchend', function (e) {
          const diff = e.changedTouches[0].screenX - touchStartX;
          if (Math.abs(diff) > 40) {
            if (diff < 0) goToHeroSlide(currentHeroSlide + 1);
            else goToHeroSlide(currentHeroSlide - 1);
          }
        }, { passive: true });
      }
      resetHeroTimer();

      // Sự kiện menu di động
      const mobileBtn = document.getElementById('mobileMenuBtn');
      const closeBtn = document.getElementById('closeMobileMenuBtn');
      const overlay = document.getElementById('mobileMenuOverlay');
      if (mobileBtn) mobileBtn.addEventListener('click', openMobileMenu);
      if (closeBtn) closeBtn.addEventListener('click', closeMobileMenu);
      if (overlay) overlay.addEventListener('click', closeMobileMenu);

      // Đóng modal khi bấm ra ngoài hoặc nhấn phím ESC
      const detailModal = document.getElementById('detailModal');
      if (detailModal) {
        detailModal.addEventListener('click', function (e) {
          if (e.target === detailModal) closeDetailModal();
        });
      }
      document.addEventListener('keydown', function (e) {
        if (e.key === 'Escape') {
          closeDetailModal();
          closeMobileMenu();
        }
      });

      // Xử lý gửi form đăng ký báo giá (thông báo trực tiếp, không dùng alert)
      const quoteForm = document.getElementById('quoteForm');
      const quoteFeedback = document.getElementById('quoteFeedback');
      if (quoteForm && quoteFeedback) {
        quoteForm.addEventListener('submit', function (e) {
          e.preventDefault();
          const name = document.getElementById('customerName').value.trim();
          const phone = document.getElementById('customerPhone').value.trim();
          const service = document.getElementById('customerService').value;

          if (!name || !phone) {
            quoteFeedback.className = 'rounded-lg p-3 text-xs sm:text-sm font-medium bg-red-50 text-red-700 border border-red-200';
            quoteFeedback.textContent = 'Vui lòng nhập đầy đủ Họ tên và Số điện thoại để Nhôm Kính ĐH liên hệ báo giá.';
            quoteFeedback.classList.remove('hidden');
            return;
          }

          quoteFeedback.className = 'rounded-lg p-3 text-xs sm:text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200';
          quoteFeedback.innerHTML =
            '<i class="fa-solid fa-circle-check mr-1.5"></i>Cảm ơn anh/chị <strong>' + name + '</strong>! Yêu cầu báo giá hạng mục <strong>' + service + '</strong> đã được ghi nhận. Nhôm Kính ĐH sẽ liên hệ qua số <strong>' + phone + '</strong> trong thời gian sớm nhất (Hotline hỗ trợ nhanh: 0905.680.903).';
          quoteFeedback.classList.remove('hidden');
          quoteForm.reset();
        });
      }
    });
  </script>
</body>
</html>
