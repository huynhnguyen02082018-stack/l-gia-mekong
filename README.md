# l-gia-mekong
https://legiamekonggarment99.com
<!DOCTYPE html>
<html lang="vi" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Công Ty TNHH May Mặc Lê Gia - Mekong Garment | Đầm Cùng, Cà Mau</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        brand: {
                            blue: '#0047AB',
                            darkblue: '#002D62',
                            red: '#E31B23',
                            accent: '#2563EB'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        .custom-scrollbar::-webkit-scrollbar {
            width: 6px;
        }
        .custom-scrollbar::-webkit-scrollbar-track {
            background: #f1f1f1;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb {
            background: #cbd5e1;
            border-radius: 4px;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb:hover {
            background: #94a3b8;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800 dark:bg-gray-900 dark:text-gray-100 font-sans transition-colors duration-300">

    <!-- SVG LOGO COMPONENT DEFINITION (Reused across header, hero, footer) -->
    <svg style="display: none;">
        <symbol id="legia-logo" viewBox="0 0 500 500">
            <!-- Background Outer Fill -->
            <circle cx="250" cy="250" r="240" fill="#ffffff" />
            <!-- Outer Double Ring -->
            <circle cx="250" cy="250" r="230" fill="none" stroke="#0047AB" stroke-width="12" />
            <circle cx="250" cy="250" r="212" fill="none" stroke="#0047AB" stroke-width="4" />
            
            <!-- Monogram LG with Sewing Machine -->
            <g transform="translate(100, 50)">
                <!-- Letter L in Blue -->
                <path d="M 20 20 L 80 20 L 80 140 L 160 140 L 160 185 L 20 185 Z" fill="#0047AB" />
                <!-- Red Swoosh Curve (Part of G) -->
                <path d="M 120 70 C 80 90, 70 160, 110 200 C 140 225, 230 220, 260 180 C 230 180, 180 180, 160 150 C 130 110, 150 80, 120 70 Z" fill="#E31B23" />
                <!-- Blue G Outer Frame -->
                <path d="M 180 20 C 260 20, 300 70, 300 130 L 260 130 C 260 90, 230 55, 180 55 C 130 55, 130 100, 130 100 L 180 100 L 180 130 L 80 130 Z" fill="#0047AB" />
                <!-- Sewing Machine Silhouette inside Monogram -->
                <g transform="translate(140, 55) scale(0.65)" fill="#0047AB">
                    <!-- Base -->
                    <rect x="10" y="110" width="160" height="20" rx="3" />
                    <!-- Body -->
                    <path d="M 30 110 L 30 30 Q 30 10 50 10 L 130 10 Q 150 10 150 30 L 150 60 Q 150 70 140 70 L 100 70 L 100 85 L 115 85 L 115 100 L 85 100 L 85 85 L 90 85 L 90 70 L 70 70 L 70 110 Z" />
                    <!-- Needle mechanism -->
                    <rect x="42" y="70" width="6" height="30" />
                    <polygon points="45,100 42,108 48,108" />
                    <!-- Wheel -->
                    <circle cx="135" cy="40" r="14" fill="#ffffff" stroke="#0047AB" stroke-width="4" />
                    <circle cx="135" cy="40" r="5" />
                </g>
            </g>

            <!-- Water Waves graphic -->
            <path d="M 90 235 Q 200 190 300 220 T 410 200 Q 330 250 240 230 T 90 235 Z" fill="#0047AB" />
            <path d="M 120 250 Q 220 215 310 235 T 390 220 Q 310 260 220 245 T 120 250 Z" fill="#0047AB" />

            <!-- Text: CTY TNHH MAY MẶC -->
            <text x="250" y="280" text-anchor="middle" font-family="'Inter', Arial, sans-serif" font-weight="900" font-size="28" fill="#0047AB" letter-spacing="1">CTY TNHH MAY MẶC</text>

            <!-- Text: LÊ GIA (Red Accent) -->
            <text x="250" y="355" text-anchor="middle" font-family="'Inter', Arial, sans-serif" font-weight="900" font-size="78" fill="#E31B23" letter-spacing="2">LÊ GIA</text>

            <!-- Text: MEKONG GARMENT -->
            <text x="250" y="398" text-anchor="middle" font-family="'Inter', Arial, sans-serif" font-weight="900" font-size="30" fill="#0047AB" letter-spacing="1.5">MEKONG GARMENT</text>

            <!-- Underline separator -->
            <line x1="80" y1="410" x2="420" y2="410" stroke="#0047AB" stroke-width="3" />

            <!-- Location Pill Container -->
            <g transform="translate(105, 420)">
                <rect x="0" y="0" width="290" height="52" rx="26" fill="#0047AB" />
                <!-- Pin Icon -->
                <path d="M 32 14 C 23.7 14 17 20.7 17 29 C 17 39.5 32 48 32 48 C 32 48 47 39.5 47 29 C 47 20.7 40.3 14 32 14 Z M 32 33 C 29.8 33 28 31.2 28 29 C 28 26.8 29.8 25 32 25 C 34.2 25 36 26.8 36 29 C 36 31.2 34.2 33 32 33 Z" fill="#ffffff" />
                <!-- Address Text -->
                <text x="60" y="25" font-family="'Inter', Arial, sans-serif" font-weight="700" font-size="16" fill="#ffffff">Ấp Đầm Cùng,</text>
                <text x="60" y="42" font-family="'Inter', Arial, sans-serif" font-weight="700" font-size="16" fill="#ffffff">Cái Nước, Cà Mau</text>
            </g>
        </symbol>
    </svg>

    <!-- TOP HEADER / NAVBAR -->
    <header class="sticky top-0 z-40 bg-white/95 dark:bg-gray-900/95 backdrop-blur-md border-b border-gray-200 dark:border-gray-800 shadow-sm transition-all">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                
                <!-- Logo & Brand Name -->
                <a href="#" class="flex items-center gap-3 group">
                    <svg class="w-14 h-14 transition-transform duration-300 group-hover:scale-105">
                        <use href="#legia-logo"></use>
                    </svg>
                    <div>
                        <span class="text-xs uppercase tracking-wider font-bold text-brand-blue dark:text-blue-400 block">Cty TNHH May Mặc</span>
                        <span class="text-xl font-black text-brand-red tracking-tight leading-none block">LÊ GIA</span>
                        <span class="text-xs font-extrabold text-brand-blue dark:text-blue-300 tracking-wider block">MEKONG GARMENT</span>
                    </div>
                </a>

                <!-- Desktop Navigation Links -->
                <nav class="hidden md:flex items-center gap-8 font-medium text-sm">
                    <a href="#about" class="hover:text-brand-blue dark:hover:text-blue-400 transition-colors">Giới Thiệu</a>
                    <a href="#products" class="hover:text-brand-blue dark:hover:text-blue-400 transition-colors">Sản Phẩm</a>
                    <a href="#quote-calculator" class="hover:text-brand-blue dark:hover:text-blue-400 transition-colors flex items-center gap-1">
                        <i class="fa-solid fa-calculator text-brand-red"></i> Tính Báo Giá
                    </a>
                    <a href="#services" class="hover:text-brand-blue dark:hover:text-blue-400 transition-colors">Dịch Vụ</a>
                    <a href="#contact" class="hover:text-brand-blue dark:hover:text-blue-400 transition-colors">Liên Hệ</a>
                </nav>

                <!-- Action Controls (Cart, Theme, Quote Modal Button) -->
                <div class="flex items-center gap-3">
                    
                    <!-- Dark Mode Toggle -->
                    <button id="theme-toggle" class="p-2.5 rounded-full text-gray-500 dark:text-gray-400 hover:bg-gray-100 dark:hover:bg-gray-800 transition-colors" title="Chuyển chế độ sáng/tối">
                        <i class="fa-solid fa-moon text-lg dark:hidden"></i>
                        <i class="fa-solid fa-sun text-lg hidden dark:block text-amber-400"></i>
                    </button>

                    <!-- Cart Trigger Button -->
                    <button id="open-cart-btn" class="relative p-2.5 rounded-full text-gray-700 dark:text-gray-200 hover:bg-gray-100 dark:hover:bg-gray-800 transition-colors">
                        <i class="fa-solid fa-cart-shopping text-xl"></i>
                        <span id="cart-badge" class="absolute -top-1 -right-1 bg-brand-red text-white text-xs font-bold w-5 h-5 rounded-full flex items-center justify-center border-2 border-white dark:border-gray-900 hidden">0</span>
                    </button>

                    <!-- Quick Quote Button -->
                    <button onclick="toggleModal('quote-modal')" class="hidden sm:inline-flex items-center justify-center px-4 py-2.5 text-sm font-semibold rounded-xl text-white bg-brand-blue hover:bg-brand-darkblue transition-all shadow-md hover:shadow-lg transform active:scale-95">
                        <i class="fa-solid fa-paper-plane mr-2"></i> Báo Giá Nhanh
                    </button>

                    <!-- Mobile Menu Button -->
                    <button id="mobile-menu-btn" class="md:hidden p-2 rounded-lg text-gray-600 dark:text-gray-300 hover:bg-gray-100 dark:hover:bg-gray-800">
                        <i class="fa-solid fa-bars text-xl"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile Menu Dropdown -->
        <div id="mobile-menu" class="hidden md:hidden bg-white dark:bg-gray-900 border-b border-gray-200 dark:border-gray-800 px-4 pt-2 pb-4 space-y-3">
            <a href="#about" class="block py-2 text-base font-medium hover:text-brand-blue">Giới Thiệu</a>
            <a href="#products" class="block py-2 text-base font-medium hover:text-brand-blue">Sản Phẩm</a>
            <a href="#quote-calculator" class="block py-2 text-base font-medium hover:text-brand-blue">Tính Báo Giá Tự Động</a>
            <a href="#services" class="block py-2 text-base font-medium hover:text-brand-blue">Dịch Vụ</a>
            <a href="#contact" class="block py-2 text-base font-medium hover:text-brand-blue">Liên Hệ</a>
            <button onclick="toggleModal('quote-modal')" class="w-full mt-2 py-2.5 text-center font-bold text-white bg-brand-blue rounded-xl">
                Yêu Cầu Báo Giá
            </button>
        </div>
    </header>

    <!-- HERO SECTION -->
    <section class="relative bg-gradient-to-br from-blue-900 via-brand-darkblue to-gray-900 text-white overflow-hidden py-16 md:py-24">
        <div class="absolute inset-0 opacity-10 bg-[radial-gradient(#fff_1px,transparent_1px)] [background-size:16px_16px]"></div>
        
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                
                <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                    <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-white/10 text-blue-200 backdrop-blur-md text-xs font-semibold border border-white/10">
                        <i class="fa-solid fa-location-dot text-brand-red"></i> Xưởng May Uy Tín Tại Ấp Đầm Cùng, Cái Nước, Cà Mau
                    </div>
                    
                    <h1 class="text-3xl sm:text-5xl lg:text-6xl font-black tracking-tight leading-tight">
                        Chuyên May Mặc <span class="text-transparent bg-clip-text bg-gradient-to-r from-red-500 to-amber-400">Đồng Phục & Thời Trang</span> Chất Lượng Cao
                    </h1>
                    
                    <p class="text-base sm:text-lg text-gray-300 max-w-2xl mx-auto lg:mx-0 font-normal">
                        Công ty TNHH May Mặc <strong class="text-white">Lê Gia Mekong Garment</strong> đáp ứng trọn gói nhu cầu thiết kế, in ấn và may đo đồng phục doanh nghiệp, trường học, bảo hộ lao động cho khu vực Cà Mau và toàn quốc.
                    </p>

                    <div class="flex flex-col sm:flex-row gap-4 justify-center lg:justify-start pt-4">
                        <a href="#quote-calculator" class="px-7 py-3.5 bg-brand-red hover:bg-red-700 text-white font-bold rounded-xl shadow-lg hover:shadow-red-500/30 transition-all flex items-center justify-center gap-2 transform hover:-translate-y-0.5">
                            <i class="fa-solid fa-calculator"></i> Tính Giá May Tự Động
                        </a>
                        <a href="#products" class="px-7 py-3.5 bg-white/10 hover:bg-white/20 text-white font-semibold rounded-xl backdrop-blur-md border border-white/20 transition-all flex items-center justify-center gap-2">
                            Xem Bộ Sưu Tập <i class="fa-solid fa-arrow-right text-xs"></i>
                        </a>
                    </div>

                    <!-- Highlights Badge Grid -->
                    <div class="grid grid-cols-3 gap-4 pt-8 border-t border-white/10 max-w-lg mx-auto lg:mx-0">
                        <div>
                            <div class="text-2xl font-black text-amber-400">100%</div>
                            <div class="text-xs text-gray-300">Vải Chuẩn Chất Lượng</div>
                        </div>
                        <div>
                            <div class="text-2xl font-black text-amber-400">5.000+</div>
                            <div class="text-xs text-gray-300">Sản Phẩm / Ngày</div>
                        </div>
                        <div>
                            <div class="text-2xl font-black text-amber-400">Giao Nhanh</div>
                            <div class="text-xs text-gray-300">Toàn Quốc</div>
                        </div>
                    </div>
                </div>

                <!-- Right Banner Logo Presentation Card -->
                <div class="lg:col-span-5 flex justify-center">
                    <div class="relative w-full max-w-md bg-white/10 backdrop-blur-xl p-8 rounded-3xl border border-white/20 shadow-2xl text-center group hover:border-brand-red/50 transition-all">
                        <div class="absolute -top-4 -right-4 bg-brand-red text-white text-xs font-black uppercase px-3 py-1 rounded-full shadow-md tracking-wider">
                            May Mặc Lê Gia
                        </div>
                        <div class="p-6 bg-white rounded-2xl shadow-inner flex justify-center items-center">
                            <svg class="w-64 h-64 sm:w-72 sm:h-72 transform group-hover:scale-105 transition-transform duration-500 drop-shadow-md">
                                <use href="#legia-logo"></use>
                            </svg>
                        </div>
                        <div class="mt-6">
                            <h3 class="text-xl font-bold text-white">Xưởng May Lê Gia Cà Mau</h3>
                            <p class="text-sm text-gray-300 mt-1">Sản xuất trực tiếp - Không qua trung gian - Giá gốc tại xưởng</p>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ABOUT SECTION -->
    <section id="about" class="py-16 bg-white dark:bg-gray-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
                
                <div class="relative">
                    <div class="aspect-video sm:aspect-square rounded-2xl overflow-hidden shadow-2xl bg-gray-100 dark:bg-gray-800 relative group">
                        <img src="https://images.unsplash.com/photo-1558769132-cb1aea458c5e?auto=format&fit=crop&w=1000&q=80" alt="Xưởng may Lê Gia Mekong Garment" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" onerror="this.src='https://placehold.co/800x800/0047AB/FFFFFF?text=Xuong+May+Le+Gia'">
                        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent flex items-end p-6">
                            <div class="text-white">
                                <p class="text-sm font-semibold text-amber-400">Trụ sở xưởng sản xuất</p>
                                <p class="text-lg font-bold">Ấp Đầm Cùng, Huyện Cái Nước, Tỉnh Cà Mau</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="space-y-6">
                    <div class="inline-block px-3 py-1 bg-blue-100 dark:bg-blue-900/50 text-brand-blue dark:text-blue-300 rounded-lg text-sm font-bold">
                        Về Chúng Tôi
                    </div>
                    <h2 class="text-3xl sm:text-4xl font-extrabold tracking-tight">
                        Công Ty TNHH May Mặc <span class="text-brand-red">Lê Gia</span> (Mekong Garment)
                    </h2>
                    <p class="text-gray-600 dark:text-gray-300 leading-relaxed">
                        Đặt dây chuyền sản xuất cốt lõi tại <strong>Ấp Đầm Cùng, Huyện Cái Nước, Tỉnh Cà Mau</strong>, May Mặc Lê Gia tự hào là một trong những xưởng may công nghiệp hàng đầu khu vực Đồng bằng Sông Cửu Long.
                    </p>
                    <p class="text-gray-600 dark:text-gray-300 leading-relaxed">
                        Chúng tôi trang bị hệ thống máy cắt, máy may tự động, dây chuyền in thêu công nghệ cao. Lê Gia cung cấp các giải pháp toàn diện từ tư vấn mẫu vải, thiết kế kiểu dáng đến sản xuất may đo đồng phục số lượng lớn.
                    </p>

                    <div class="grid grid-cols-2 gap-4 pt-2">
                        <div class="p-4 rounded-xl bg-gray-50 dark:bg-gray-800 border border-gray-100 dark:border-gray-700">
                            <i class="fa-solid fa-shirt text-brand-blue text-2xl mb-2"></i>
                            <h4 class="font-bold text-base">Mẫu Mã Đa Dạng</h4>
                            <p class="text-xs text-gray-500 dark:text-gray-400 mt-1">Đồng phục áo phông, bảo hộ, học sinh, công sở...</p>
                        </div>
                        <div class="p-4 rounded-xl bg-gray-50 dark:bg-gray-800 border border-gray-100 dark:border-gray-700">
                            <i class="fa-solid fa-scissors text-brand-red text-2xl mb-2"></i>
                            <h4 class="font-bold text-base">In Thêu Sắc Nét</h4>
                            <p class="text-xs text-gray-500 dark:text-gray-400 mt-1">Công nghệ in thêu vi tính độ bền cao, không phai màu.</p>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- PRODUCTS SECTION WITH FILTER -->
    <section id="products" class="py-16 bg-gray-100 dark:bg-gray-800/50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <div class="text-center max-w-3xl mx-auto mb-10">
                <h2 class="text-3xl font-extrabold">Sản Phẩm Nổi Bật</h2>
                <p class="text-gray-600 dark:text-gray-400 mt-2">Các mẫu sản phẩm chất lượng cao được may trực tiếp từ xưởng Lê Gia</p>
            </div>

            <!-- Filter Buttons -->
            <div class="flex flex-wrap justify-center gap-2 mb-10">
                <button onclick="filterProducts('all')" class="filter-btn active px-5 py-2 rounded-full font-medium text-sm transition-all bg-brand-blue text-white shadow-sm">Tất Cả</button>
                <button onclick="filterProducts('polo')" class="filter-btn px-5 py-2 rounded-full font-medium text-sm transition-all bg-white dark:bg-gray-800 text-gray-700 dark:text-gray-300 hover:bg-gray-200 dark:hover:bg-gray-700">Áo Polo Đồng Phục</button>
                <button onclick="filterProducts('tshirt')" class="filter-btn px-5 py-2 rounded-full font-medium text-sm transition-all bg-white dark:bg-gray-800 text-gray-700 dark:text-gray-300 hover:bg-gray-200 dark:hover:bg-gray-700">Áo Thun Cổ Tròn</button>
                <button onclick="filterProducts('workwear')" class="filter-btn px-5 py-2 rounded-full font-medium text-sm transition-all bg-white dark:bg-gray-800 text-gray-700 dark:text-gray-300 hover:bg-gray-200 dark:hover:bg-gray-700">Đồ Bảo Hộ Lao Động</button>
                <button onclick="filterProducts('school')" class="filter-btn px-5 py-2 rounded-full font-medium text-sm transition-all bg-white dark:bg-gray-800 text-gray-700 dark:text-gray-300 hover:bg-gray-200 dark:hover:bg-gray-700">Đồng Phục Học Sinh</button>
            </div>

            <!-- Product Cards Grid -->
            <div id="product-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- Dynamic Javascript Insertion or static fallback -->
            </div>

        </div>
    </section>

    <!-- QUOTE CALCULATOR SECTION -->
    <section id="quote-calculator" class="py-16 bg-white dark:bg-gray-900 border-y border-gray-200 dark:border-gray-800">
        <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <div class="bg-gradient-to-br from-brand-darkblue to-blue-900 text-white p-8 sm:p-10 rounded-3xl shadow-2xl relative overflow-hidden">
                <div class="absolute -right-10 -bottom-10 opacity-10">
                    <svg class="w-96 h-96"><use href="#legia-logo"></use></svg>
                </div>

                <div class="relative z-10">
                    <div class="text-center max-w-2xl mx-auto mb-8">
                        <span class="inline-block px-3 py-1 bg-red-600/80 text-white rounded-full text-xs font-bold uppercase tracking-wider mb-2">Công Cụ Độc Quyền</span>
                        <h2 class="text-3xl sm:text-4xl font-extrabold">Tính Báo Giá May Dự Kiến</h2>
                        <p class="text-blue-200 text-sm mt-2">Nhập số lượng & quy cách để xem ước tính chi phí ngay lập tức</p>
                    </div>

                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6 bg-white/10 backdrop-blur-md p-6 rounded-2xl border border-white/10">
                        
                        <!-- Left Inputs -->
                        <div class="space-y-4">
                            <div>
                                <label class="block text-xs font-semibold text-blue-200 uppercase mb-1">Loại Sản Phẩm</label>
                                <select id="calc-type" onchange="calculateQuote()" class="w-full bg-white dark:bg-gray-800 text-gray-900 dark:text-white rounded-xl px-4 py-2.5 font-medium border-0 focus:ring-2 focus:ring-brand-red outline-none">
                                    <option value="110000">Áo Polo Đồng Phục (Cổ Trụ)</option>
                                    <option value="75000">Áo Thun Cổ Tròn</option>
                                    <option value="180000">Áo Sơ Mi Công Sở</option>
                                    <option value="220000">Đồ Bảo Hộ Lao Động</option>
                                    <option value="130000">Áo Khoác Gió Đồng Phục</option>
                                </select>
                            </div>

                            <div>
                                <label class="block text-xs font-semibold text-blue-200 uppercase mb-1">Chất Liệu Vải</label>
                                <select id="calc-fabric" onchange="calculateQuote()" class="w-full bg-white dark:bg-gray-800 text-gray-900 dark:text-white rounded-xl px-4 py-2.5 font-medium border-0 focus:ring-2 focus:ring-brand-red outline-none">
                                    <option value="1">Vải TC / PE Tiêu Chuẩn</option>
                                    <option value="1.2">Vải Cotton 65/35 Co Giãn 4 Chiều (+20%)</option>
                                    <option value="1.4">Vải Cotton 100% Cao Cấp (+40%)</option>
                                    <option value="1.3">Vải Cà Phê / Coolmax Thoáng Nhiệt (+30%)</option>
                                </select>
                            </div>

                            <div>
                                <label class="block text-xs font-semibold text-blue-200 uppercase mb-1">Số Lượng May (Càng nhiều càng rẻ)</label>
                                <input type="number" id="calc-qty" value="50" min="10" oninput="calculateQuote()" class="w-full bg-white dark:bg-gray-800 text-gray-900 dark:text-white rounded-xl px-4 py-2.5 font-bold border-0 focus:ring-2 focus:ring-brand-red outline-none">
                            </div>

                            <div>
                                <label class="block text-xs font-semibold text-blue-200 uppercase mb-1">In / Thêu Logo</label>
                                <select id="calc-logo" onchange="calculateQuote()" class="w-full bg-white dark:bg-gray-800 text-gray-900 dark:text-white rounded-xl px-4 py-2.5 font-medium border-0 focus:ring-2 focus:ring-brand-red outline-none">
                                    <option value="0">Không in / thêu logo</option>
                                    <option value="15000">In Lụa / In Chuyển Nhiệt (+15.000đ/áo)</option>
                                    <option value="25000">Thêu Vi Tính Logo Ngực (+25.000đ/áo)</option>
                                </select>
                            </div>
                        </div>

                        <!-- Right Estimate Result Card -->
                        <div class="bg-white text-gray-900 rounded-2xl p-6 flex flex-col justify-between shadow-xl">
                            <div>
                                <h3 class="text-sm font-bold text-gray-500 uppercase tracking-wider">Dự Toán Chi Phí</h3>
                                <div class="mt-4">
                                    <div class="text-xs text-gray-500">Đơn giá ước tính / áo:</div>
                                    <div id="unit-price-display" class="text-2xl font-bold text-brand-blue">110.000 VNĐ</div>
                                </div>
                                <div class="mt-4 pt-4 border-t border-gray-100">
                                    <div class="text-xs text-gray-500">Tổng giá trị đơn hàng (Chưa VAT):</div>
                                    <div id="total-price-display" class="text-3xl sm:text-4xl font-black text-brand-red mt-1">5.500.000 VNĐ</div>
                                </div>
                                <p class="text-xs text-gray-400 mt-4 leading-relaxed">* Giá chính xác có thể thay đổi tùy thuộc vào vị trí thêu, độ chi tiết của logo và yêu cầu đóng gói đặc biệt.</p>
                            </div>

                            <button onclick="requestCalcQuote()" class="w-full mt-6 py-3 bg-brand-red hover:bg-red-700 text-white font-bold rounded-xl transition-all shadow-md text-center">
                                <i class="fa-solid fa-paper-plane mr-2"></i> Đặt Hàng Theo Đơn Giá Này
                            </button>
                        </div>

                    </div>
                </div>
            </div>

        </div>
    </section>

    <!-- SERVICES SECTION -->
    <section id="services" class="py-16 bg-gray-50 dark:bg-gray-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-12">
                <h2 class="text-3xl font-extrabold">Dịch Vụ Tại Lê Gia Mekong Garment</h2>
                <p class="text-gray-600 dark:text-gray-400 mt-2">Quy trình sản xuất khép kín mang lại sản phẩm hoàn hảo nhất</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="bg-white dark:bg-gray-800 p-8 rounded-2xl shadow-sm border border-gray-100 dark:border-gray-700 hover:shadow-xl transition-all">
                    <div class="w-14 h-14 bg-blue-100 dark:bg-blue-900/40 text-brand-blue rounded-2xl flex items-center justify-center text-2xl font-bold mb-6">
                        <i class="fa-solid fa-compass-drafting"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Tư Vấn & Thiết Kế Miễn Phí</h3>
                    <p class="text-gray-600 dark:text-gray-400 text-sm leading-relaxed">Đội ngũ hỗ trợ phác thảo mẫu đồng phục 2D/3D theo đúng bộ nhận diện thương hiệu của bạn hoàn toàn miễn phí.</p>
                </div>

                <!-- Service 2 -->
                <div class="bg-white dark:bg-gray-800 p-8 rounded-2xl shadow-sm border border-gray-100 dark:border-gray-700 hover:shadow-xl transition-all">
                    <div class="w-14 h-14 bg-red-100 dark:bg-red-900/40 text-brand-red rounded-2xl flex items-center justify-center text-2xl font-bold mb-6">
                        <i class="fa-solid fa-print"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">In & Thêu Logo Hiện Đại</h3>
                    <p class="text-gray-600 dark:text-gray-400 text-sm leading-relaxed">Sử dụng công nghệ thêu vi tính 12 kim và in lụa, in cao su nổi, in DTG sắc nét, bền đẹp qua nhiều lần giặt.</p>
                </div>

                <!-- Service 3 -->
                <div class="bg-white dark:bg-gray-800 p-8 rounded-2xl shadow-sm border border-gray-100 dark:border-gray-700 hover:shadow-xl transition-all">
                    <div class="w-14 h-14 bg-amber-100 dark:bg-amber-900/40 text-amber-600 rounded-2xl flex items-center justify-center text-2xl font-bold mb-6">
                        <i class="fa-solid fa-truck-fast"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Giao Hàng Tận Nơi</h3>
                    <p class="text-gray-600 dark:text-gray-400 text-sm leading-relaxed">Vận chuyển tận tay khách hàng tại Cà Mau, Miền Tây và giao hàng toàn quốc nhanh chóng, đúng tiến độ cam kết.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer id="contact" class="bg-gray-900 text-gray-300 pt-16 pb-12 border-t border-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-10 pb-12 border-b border-gray-800">
                
                <!-- Col 1: Brand -->
                <div class="space-y-4">
                    <div class="flex items-center gap-3">
                        <svg class="w-16 h-16 bg-white p-1 rounded-full">
                            <use href="#legia-logo"></use>
                        </svg>
                        <div>
                            <span class="text-xs uppercase text-gray-400 font-bold block">May Mặc Lê Gia</span>
                            <span class="text-lg font-black text-brand-red block">MEKONG GARMENT</span>
                        </div>
                    </div>
                    <p class="text-xs text-gray-400 leading-relaxed">
                        Chuyên nghiệp - Chất lượng - Đúng tiến độ. Đồng hành cùng sự phát triển hình ảnh của doanh nghiệp và tổ chức.
                    </p>
                </div>

                <!-- Col 2: Contact Details -->
                <div class="space-y-3">
                    <h4 class="text-white font-bold text-base uppercase tracking-wider">Thông Tin Liên Hệ</h4>
                    <ul class="space-y-2 text-sm">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-brand-red mt-1"></i>
                            <span>Ấp Đầm Cùng, Xã Trần Thới, Huyện Cái Nước, Tỉnh Cà Mau</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-phone text-brand-blue"></i>
                            <a href="tel:0900000000" class="hover:text-white">0847.337.792 - 0987.654.321</a>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-envelope text-amber-400"></i>
                            <span>legia221322@gmail.com</span>
                        </li>
                    </ul>
                </div>

                <!-- Col 3: Quick Links -->
                <div class="space-y-3">
                    <h4 class="text-white font-bold text-base uppercase tracking-wider">Liên Kết Nhanh</h4>
                    <ul class="space-y-2 text-sm">
                        <li><a href="#about" class="hover:text-white transition-colors">Giới thiệu xưởng may</a></li>
                        <li><a href="#products" class="hover:text-white transition-colors">Sản phẩm đồng phục</a></li>
                        <li><a href="#quote-calculator" class="hover:text-white transition-colors">Báo giá tự động</a></li>
                        <li><a href="#services" class="hover:text-white transition-colors">Chính sách bảo hành</a></li>
                    </ul>
                </div>

                <!-- Col 4: Map / Working Hours -->
                <div class="space-y-3">
                    <h4 class="text-white font-bold text-base uppercase tracking-wider">Thời Gian Làm Việc</h4>
                    <p class="text-xs text-gray-400">Thứ 2 - Thứ 7: 07:30 - 16:30</p>
                    <p class="text-xs text-gray-400">Chủ Nhật: Nghỉ (Hỗ trợ Hotline 24/7)</p>
                    <div class="pt-2">
                        <button onclick="toggleModal('quote-modal')" class="w-full py-2.5 bg-brand-blue hover:bg-brand-darkblue text-white font-bold rounded-xl text-xs uppercase tracking-wider">
                            Gửi Yêu Cầu Tư Vấn
                        </button>
                    </div>
                </div>

            </div>

            <div class="pt-8 text-center text-xs text-gray-500">
                <p>&copy; 2026 Công Ty TNHH May Mặc Lê Gia (Mekong Garment). Tất cả quyền được bảo lưu.</p>
            </div>
        </div>
    </footer>

    <!-- SLIDE-OUT CART DRAWER -->
    <div id="cart-drawer" class="fixed inset-0 z-50 overflow-hidden hidden" aria-labelledby="slide-over-title" role="dialog" aria-modal="true">
        <div class="absolute inset-0 bg-gray-900/60 backdrop-blur-sm transition-opacity" onclick="toggleCart()"></div>

        <div class="fixed inset-y-0 right-0 max-w-full flex pl-10">
            <div class="w-screen max-w-md bg-white dark:bg-gray-900 shadow-2xl flex flex-col">
                
                <!-- Drawer Header -->
                <div class="p-6 bg-brand-blue text-white flex items-center justify-between">
                    <h2 class="text-lg font-bold flex items-center gap-2">
                        <i class="fa-solid fa-cart-shopping"></i> Giỏ Mẫu Đặt May
                    </h2>
                    <button onclick="toggleCart()" class="text-white hover:text-gray-200">
                        <i class="fa-solid fa-xmark text-2xl"></i>
                    </button>
                </div>

                <!-- Cart Items List -->
                <div id="cart-items" class="flex-1 overflow-y-auto p-6 space-y-4 custom-scrollbar">
                    <!-- Populated via Javascript -->
                </div>

                <!-- Cart Footer / Checkout -->
                <div class="p-6 border-t border-gray-200 dark:border-gray-800 bg-gray-50 dark:bg-gray-800">
                    <div class="flex justify-between text-base font-bold text-gray-900 dark:text-white mb-4">
                        <span>Tổng tạm tính:</span>
                        <span id="cart-total" class="text-brand-red">0 VNĐ</span>
                    </div>
                    <button onclick="checkoutCart()" class="w-full py-3 bg-brand-red hover:bg-red-700 text-white font-bold rounded-xl transition-all shadow-md">
                        Tiến Hành Gửi Đơn Đặt May
                    </button>
                </div>

            </div>
        </div>
    </div>

    <!-- MODAL POPUP: QUICK QUOTE FORM -->
    <div id="quote-modal" class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-gray-900/70 backdrop-blur-sm hidden">
        <div class="bg-white dark:bg-gray-900 rounded-3xl max-w-lg w-full p-6 sm:p-8 shadow-2xl relative border border-gray-100 dark:border-gray-800">
            
            <button onclick="toggleModal('quote-modal')" class="absolute top-5 right-5 text-gray-400 hover:text-gray-600 dark:hover:text-white">
                <i class="fa-solid fa-xmark text-2xl"></i>
            </button>

            <div class="text-center mb-6">
                <svg class="w-16 h-16 mx-auto mb-2"><use href="#legia-logo"></use></svg>
                <h3 class="text-2xl font-bold">Yêu Cầu Báo Giá Nhanh</h3>
                <p class="text-xs text-gray-500 dark:text-gray-400 mt-1">Lê Gia Mekong Garment sẽ phản hồi trong vòng 15 phút</p>
            </div>

            <form id="quote-form" onsubmit="handleFormSubmit(event)" class="space-y-4">
                <div>
                    <label class="block text-xs font-bold uppercase text-gray-600 dark:text-gray-300 mb-1">Họ và Tên *</label>
                    <input type="text" required placeholder="Nguyễn Văn A" class="w-full px-4 py-2.5 rounded-xl border border-gray-300 dark:border-gray-700 bg-white dark:bg-gray-800 focus:ring-2 focus:ring-brand-blue outline-none text-sm">
                </div>
                <div>
                    <label class="block text-xs font-bold uppercase text-gray-600 dark:text-gray-300 mb-1">Số Điện Thoại / Zalo *</label>
                    <input type="tel" required placeholder="0847 337 792" class="w-full px-4 py-2.5 rounded-xl border border-gray-300 dark:border-gray-700 bg-white dark:bg-gray-800 focus:ring-2 focus:ring-brand-blue outline-none text-sm">
                </div>
                <div>
                    <label class="block text-xs font-bold uppercase text-gray-600 dark:text-gray-300 mb-1">Yêu Cầu Chi Tiết (Loại áo, số lượng, màu sắc...)</label>
                    <textarea id="quote-message-input" rows="3" placeholder="Ví dụ: Cần may 100 áo polo màu xanh dương in logo ở ngực cho công ty..." class="w-full px-4 py-2.5 rounded-xl border border-gray-300 dark:border-gray-700 bg-white dark:bg-gray-800 focus:ring-2 focus:ring-brand-blue outline-none text-sm"></textarea>
                </div>
                <button type="submit" class="w-full py-3 bg-brand-blue hover:bg-brand-darkblue text-white font-bold rounded-xl shadow-lg transition-all">
                    Gửi Yêu Cầu Báo Giá
                </button>
            </form>
        </div>
    </div>

    <!-- JAVASCRIPT LOGIC -->
    <script>
        // Sample Product Data
        const products = [
            {
                id: 1,
                name: "Áo Polo Đồng Phục Công Ty",
                category: "polo",
                price: 120000,
                image: "https://images.unsplash.com/photo-1581655353564-df123a1eb820?auto=format&fit=crop&w=600&q=80",
                desc: "Vải cá sấu 4 chiều thoáng mát, cổ bo dệt cao cấp"
            },
            {
                id: 2,
                name: "Áo Thun Cổ Tròn Sự Kiện",
                category: "tshirt",
                price: 75000,
                image: "https://images.unsplash.com/photo-1521572267360-ee0c2909d518?auto=format&fit=crop&w=600&q=80",
                desc: "Chất liệu Cotton 100% co giãn, phù hợp team building"
            },
            {
                id: 3,
                name: "Bộ Đồ Bảo Hộ Kỹ Thuật Viện",
                category: "workwear",
                price: 240000,
                image: "https://images.unsplash.com/photo-1617137984095-74e4e5e3613f?auto=format&fit=crop&w=600&q=80",
                desc: "Vải Kaki Păng Rim dày dặn, chống bám bụi & độ bền cao"
            },
            {
                id: 4,
                name: "Đồng Phục Học Sinh Tiểu Học / THCS",
                category: "school",
                price: 135000,
                image: "https://images.unsplash.com/photo-1622290291468-a28f7a7dc6a8?auto=format&fit=crop&w=600&q=80",
                desc: "Áo sơ mi trắng phối váy/quần tây vải Kate Ý thấm hút mồ hôi"
            }
        ];

        let cart = [];

        // Dark Mode Logic
        const themeToggleBtn = document.getElementById('theme-toggle');
        themeToggleBtn.addEventListener('click', () => {
            document.documentElement.classList.toggle('dark');
        });

        // Mobile Menu Toggle
        document.getElementById('mobile-menu-btn').addEventListener('click', () => {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        });

        // Render Product Catalog
        function renderProducts(items) {
            const grid = document.getElementById('product-grid');
            grid.innerHTML = items.map(p => `
                <div class="bg-white dark:bg-gray-900 rounded-2xl overflow-hidden shadow-sm hover:shadow-xl transition-all border border-gray-100 dark:border-gray-800 flex flex-col">
                    <div class="h-48 overflow-hidden relative">
                        <img src="${p.image}" alt="${p.name}" class="w-full h-full object-cover hover:scale-105 transition-transform duration-300" onerror="this.src='https://placehold.co/600x400/0047AB/FFFFFF?text=May+Mac+Le+Gia'">
                        <span class="absolute top-3 right-3 bg-brand-blue text-white text-[10px] font-bold uppercase px-2.5 py-1 rounded-full">Lê Gia</span>
                    </div>
                    <div class="p-5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-base mb-1 text-gray-900 dark:text-white">${p.name}</h3>
                            <p class="text-xs text-gray-500 dark:text-gray-400 mb-3">${p.desc}</p>
                        </div>
                        <div>
                            <div class="text-brand-red font-black text-lg mb-3">${p.price.toLocaleString('vi-VN')} VNĐ <span class="text-xs text-gray-400 font-normal">/ áo</span></div>
                            <button onclick="addToCart(${p.id})" class="w-full py-2 bg-gray-100 dark:bg-gray-800 hover:bg-brand-blue hover:text-white dark:hover:bg-brand-blue font-semibold rounded-xl text-xs transition-colors">
                                <i class="fa-solid fa-cart-plus mr-1"></i> Thêm Vào Mẫu Đặt
                            </button>
                        </div>
                    </div>
                </div>
            `).join('');
        }

        // Filter Products
        function filterProducts(category) {
            document.querySelectorAll('.filter-btn').forEach(btn => {
                btn.classList.remove('bg-brand-blue', 'text-white');
                btn.classList.add('bg-white', 'dark:bg-gray-800', 'text-gray-700', 'dark:text-gray-300');
            });
            event.target.classList.remove('bg-white', 'dark:bg-gray-800', 'text-gray-700', 'dark:text-gray-300');
            event.target.classList.add('bg-brand-blue', 'text-white');

            if (category === 'all') {
                renderProducts(products);
            } else {
                renderProducts(products.filter(p => p.category === category));
            }
        }

        // Calculator Logic
        function calculateQuote() {
            const basePrice = parseInt(document.getElementById('calc-type').value);
            const fabricMultiplier = parseFloat(document.getElementById('calc-fabric').value);
            const logoPrice = parseInt(document.getElementById('calc-logo').value);
            const qty = parseInt(document.getElementById('calc-qty').value) || 1;

            let discount = 1;
            if (qty >= 100) discount = 0.9;
            if (qty >= 300) discount = 0.82;
            if (qty >= 500) discount = 0.75;

            const unitPrice = Math.round(((basePrice * fabricMultiplier) + logoPrice) * discount);
            const totalPrice = unitPrice * qty;

            document.getElementById('unit-price-display').innerText = unitPrice.toLocaleString('vi-VN') + ' VNĐ';
            document.getElementById('total-price-display').innerText = totalPrice.toLocaleString('vi-VN') + ' VNĐ';
        }

        function requestCalcQuote() {
            const typeText = document.getElementById('calc-type').options[document.getElementById('calc-type').selectedIndex].text;
            const qty = document.getElementById('calc-qty').value;
            const total = document.getElementById('total-price-display').innerText;
            
            document.getElementById('quote-message-input').value = `Tôi muốn đặt may ${qty} ${typeText}. Tổng dự toán: ${total}. Nhờ xưởng Lê Gia liên hệ tư vấn mẫu vải và thiết kế!`;
            toggleModal('quote-modal');
        }

        // Cart Actions
        function addToCart(productId) {
            const item = products.find(p => p.id === productId);
            const existing = cart.find(c => c.id === productId);

            if (existing) {
                existing.qty++;
            } else {
                cart.push({ ...item, qty: 1 });
            }

            updateCartUI();
            toggleCart(true);
        }

        function updateCartUI() {
            const badge = document.getElementById('cart-badge');
            const totalQty = cart.reduce((acc, item) => acc + item.qty, 0);

            if (totalQty > 0) {
                badge.innerText = totalQty;
                badge.classList.remove('hidden');
            } else {
                badge.classList.add('hidden');
            }

            const cartContainer = document.getElementById('cart-items');
            if (cart.length === 0) {
                cartContainer.innerHTML = '<p class="text-center text-gray-400 py-8 text-sm">Chưa có mẫu sản phẩm nào trong giỏ.</p>';
            } else {
                cartContainer.innerHTML = cart.map(item => `
                    <div class="flex items-center gap-3 p-3 bg-gray-50 dark:bg-gray-800 rounded-xl border border-gray-100 dark:border-gray-700">
                        <img src="${item.image}" class="w-14 h-14 object-cover rounded-lg">
                        <div class="flex-1">
                            <h4 class="font-bold text-xs text-gray-900 dark:text-white">${item.name}</h4>
                            <div class="text-brand-red font-bold text-xs mt-1">${item.price.toLocaleString('vi-VN')} VNĐ</div>
                            <div class="flex items-center gap-2 mt-2">
                                <button onclick="changeQty(${item.id}, -1)" class="w-5 h-5 bg-gray-200 dark:bg-gray-700 rounded text-xs">-</button>
                                <span class="text-xs font-bold">${item.qty}</span>
                                <button onclick="changeQty(${item.id}, 1)" class="w-5 h-5 bg-gray-200 dark:bg-gray-700 rounded text-xs">+</button>
                            </div>
                        </div>
                    </div>
                `).join('');
            }

            const grandTotal = cart.reduce((acc, item) => acc + (item.price * item.qty), 0);
            document.getElementById('cart-total').innerText = grandTotal.toLocaleString('vi-VN') + ' VNĐ';
        }

        function changeQty(id, delta) {
            const item = cart.find(c => c.id === id);
            if (item) {
                item.qty += delta;
                if (item.qty <= 0) {
                    cart = cart.filter(c => c.id !== id);
                }
            }
            updateCartUI();
        }

        function toggleCart(forceOpen = false) {
            const drawer = document.getElementById('cart-drawer');
            if (forceOpen) {
                drawer.classList.remove('hidden');
            } else {
                drawer.classList.toggle('hidden');
            }
        }

        function checkoutCart() {
            if (cart.length === 0) return alert('Giỏ hàng trống!');
            toggleCart();
            document.getElementById('quote-message-input').value = `Thông tin giỏ hàng mẫu:\n` + cart.map(i => `- ${i.name} (x${i.qty})`).join('\n');
            toggleModal('quote-modal');
        }

        // Modal Toggle Helper
        function toggleModal(modalId) {
            const modal = document.getElementById(modalId);
            modal.classList.toggle('hidden');
        }

        // Form Submit Handler
        function handleFormSubmit(e) {
            e.preventDefault();
            alert('Cảm ơn bạn đã gửi yêu cầu! Xưởng May Lê Gia Mekong Garment (Ấp Đầm Cùng, Cái Nước, Cà Mau) sẽ liên hệ sớm nhất.');
            toggleModal('quote-modal');
        }

        // Init App
        window.onload = function() {
            renderProducts(products);
            calculateQuote();
        }
    </script>
</body>
</html>
