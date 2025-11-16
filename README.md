
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang Chính Thức - Ghi Chú Siêu Tốc (Chúng tôi)</title>
    <!-- Tải Tailwind CSS để design nhanh và đẹp -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap" rel="stylesheet">
    <style>
        /* Thiết lập font Inter cho toàn bộ trang */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0d1117; /* Nền tối của dân Code/Tech */
            color: #e6edf3;
            animation: fadeIn 1s ease-in-out;
        }

        /* Animation cho hiệu ứng tải trang mượt mà */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        /* Hiệu ứng nổi bật cho nút Download */
        .download-btn {
            background-image: linear-gradient(45deg, #38bdf8, #818cf8); /* Gradient Xanh Neon/Tím */
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            box-shadow: 0 0 10px rgba(56, 189, 248, 0.5), 0 0 20px rgba(129, 140, 248, 0.4);
        }

        .download-btn:hover {
            transform: translateY(-3px) scale(1.02);
            box-shadow: 0 5px 15px rgba(56, 189, 248, 0.7), 0 5px 25px rgba(129, 140, 248, 0.6);
            filter: brightness(1.1);
        }

        .feature-card {
            border: 1px solid #30363d;
            background-color: #161b22;
            transition: transform 0.3s ease;
        }
        .feature-card:hover {
            border-color: #38bdf8;
            transform: translateY(-5px);
        }
    </style>
</head>
<body class="min-h-screen flex flex-col justify-between">

    <!-- HEADER (Trang chính thức Chúng tôi) -->
    <header class="py-4 border-b border-gray-700">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h1 class="text-xl font-bold text-gray-400">
                <span class="text-blue-400">Chúng tôi</span> / Trang Chính Thức
            </h1>
        </div>
    </header>

    <!-- MAIN CONTENT - HERO SECTION -->
    <main class="flex-grow flex items-center justify-center">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center py-12">
            
            <!-- TÊN SẢN PHẨM & SLOGAN -->
            <h2 class="text-6xl sm:text-7xl font-extrabold tracking-tight mb-4 text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-indigo-500">
                GHI CHÚ SIÊU TỐC
            </h2>
            <p class="text-2xl text-gray-400 mb-10">
                (beta_1.1_made_in_vietnam)
            </p>

            <!-- MÔ TẢ MỞ RỘNG -->
            <p class="text-xl sm:text-2xl text-gray-300 max-w-3xl mx-auto mb-8">
                "Ghi Chú Siêu Tốc" không chỉ là một ứng dụng ghi chú đơn thuần, nó là công cụ được **chúng tôi** thiết kế dành riêng cho những ai cần tốc độ và sự rõ ràng tuyệt đối trong luồng thông tin. Được xây dựng trên nền tảng Python gọn nhẹ, ứng dụng này giúp bro xử lý, tổ chức và tìm kiếm các **tín hiệu** quan trọng mà không cần phải thoát ra khỏi môi trường làm việc của mình. Tải ngay để trải nghiệm tốc độ của Markdown và sự yên tâm của Autosave 2s, bản này đã sửa đổi một chút nên chúng tôi xin thông cảm quý khách!
            </p>

            <!-- NÚT DOWNLOAD CHÍNH -->
            <a href="https://drive.google.com/file/d/1ApBWgBdsIj06MiSoZt-8NkF3bv3tX4Rp/view?usp=sharing" target="_blank" 
               class="download-btn inline-block px-12 py-4 text-2xl font-bold text-white rounded-xl uppercase shadow-lg transition duration-300 ease-in-out">
                TẢI VỀ NGAY (FILE .PY)
            </a>

            <!-- HƯỚNG DẪN NGẮN -->
            <p class="mt-4 text-sm text-gray-500">
                (Link Drive đã được chúng tôi xác nhận. Yêu cầu: Đã cài Python 3.x)
            </p>

        </div>
    </main>
    
    <!-- FEATURE SECTION -->
    <section class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16">
        <h3 class="text-3xl font-bold text-center mb-10 text-blue-400">
            Cái Chất Lượng Cao Nằm Ở Đâu?
        </h3>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            
            <!-- FEATURE 1: AUTOSAVE 2S -->
            <div class="feature-card p-6 rounded-xl shadow-2xl">
                <div class="text-4xl mb-3 text-indigo-400">
                    ⚡
                </div>
                <h4 class="text-xl font-semibold mb-2">Autosave Siêu Tốc (2s)</h4>
                <p class="text-gray-400">Không sợ mất dữ liệu. Sau mỗi 2 giây, hệ thống tự động ghi lại note của bạn. Tốc độ là tất cả!</p>
            </div>
            
            <!-- FEATURE 2: MARKDOWN NỘI BỘ -->
            <div class="feature-card p-6 rounded-xl shadow-2xl">
                <div class="text-4xl mb-3 text-green-400">
                    📝
                </div>
                <h4 class="text-xl font-semibold mb-2">Định Dạng Chuẩn Markdown</h4>
                <p class="text-gray-400">Hỗ trợ các định dạng Bold, Italic, Link, Header ngay trong Tkinter. Ghi chú phải chuyên nghiệp như dân code!</p>
            </div>

            <!-- FEATURE 3: TAGGING & SEARCHING -->
            <div class="feature-card p-6 rounded-xl shadow-2xl">
                <div class="text-4xl mb-3 text-yellow-400">
                    🔍
                </div>
                <h4 class="text-xl font-semibold mb-2">Hệ Thống Tags & Tìm Kiếm Đa Năng</h4>
                <p class="text-gray-400">Quản lý các tín hiệu và thông tin nhiễu loạn bằng #tags. Tìm kiếm xuyên suốt tiêu đề, nội dung và tag.</p>
            </div>
        </div>
    </section>

    <!-- CHANGELOG SECTION -->
    <section class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 py-16 border-t border-gray-800">
        <h3 class="text-3xl font-bold text-center mb-8 text-indigo-400">
            Nhật Ký Tín Hiệu (Changelog)
        </h3>
        <div class="space-y-6 text-left">
            <!-- Phiên bản Beta 1.0 -->
            <div class="p-6 bg-[#1f2937]/50 rounded-lg shadow-xl border border-[#374151]">
                <div class="flex items-center mb-3">
                    <span class="bg-blue-600 text-white text-xs font-semibold px-3 py-1 rounded-full mr-3">BETA 1.0</span>
                    <span class="text-sm text-gray-400 font-mono">2025-11-16</span>
                </div>
                <h4 class="text-xl font-bold text-gray-200 mb-2">Ra mắt công cụ Ghi Chú Siêu Tốc</h4>
                <ul class="list-disc list-inside text-gray-400 space-y-2 pl-4">
                    <li>Kích hoạt hệ thống lưu trữ note cục bộ (local storage) dựa trên file JSON.</li>
                    <li>Triển khai tính năng Autosave tự động sau 2 giây.</li>
                    <li>Thêm hỗ trợ định dạng Markdown cơ bản (Bold, Italic) cho nội dung note.</li>
                    <li>Tích hợp cơ chế #tag và thanh tìm kiếm đa năng (Search).</li>
                    <li>Sử dụng giao diện đồ họa Tkinter (Python GUI) tối giản và dễ dùng.</li>
                </ul>
            </div>
            <!-- Future Placeholder -->
            <div class="p-4 bg-gray-800/30 rounded-lg text-center text-gray-500 italic border-dashed border-2 border-gray-700">
                Trong tương lai, có thể sẽ có một phiên bản là 2.0 do chúng tôi tạo ra.
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="py-6 border-t border-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center text-gray-500">
            Tác giả: Duong Minh Long, © 2025 Powered by Duong Minh Long
        </div>
    </footer>

</body>
</html>
