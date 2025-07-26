<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Cá Nhân</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 font-sans">
    <!-- Navigation -->
    <nav class="bg-blue-600 text-white p-4 sticky top-0 shadow-md">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-2xl font-bold">Portfolio Cá Nhân</h1>
            <div class="space-x-4">
                <a href="#home" class="hover:underline">Trang chủ</a>
                <a href="#about" class="hover:underline">Giới thiệu</a>
                <a href="#skills" class="hover:underline">Kỹ năng</a>
                <a href="#projects" class="hover:underline">Dự án</a>
                <a href="#contact" class="hover:underline">Liên hệ</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="bg-blue-100 py-20 text-center">
        <div class="container mx-auto">
            <h2 class="text-4xl font-bold mb-4">Chào mừng đến với Website của tôi!</h2>
            <p class="text-lg mb-6">Tôi là [Tên của bạn], một [nghề nghiệp/vai trò].</p>
            <a href="#contact" class="bg-blue-600 text-white px-6 py-2 rounded-full hover:bg-blue-700">Liên hệ với tôi</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-8">Giới thiệu</h2>
            <p class="text-lg text-gray-700 leading-relaxed">
                Xin chào! Tôi là Nguyễn Trung Thông, làm nghềtự do. 
                Tôi đam mê đọc truyện và rivew truyện. Với hơn 10 năm kinh nghiệm trong rivew truyện, 
                tôi luôn nỗ lực tạo ra những sản phẩm chất lượng cao và mang lại giá trị cho cộng đồng.
            </p>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="bg-gray-200 py-16">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-8">Kỹ năng</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="bg-white p-6 rounded-lg shadow-md text-center">
                    <h3 class="text-xl font-semibold mb-2">Kỹ năng 1</h3>
                    <p class="text-gray-600">[Mô tả kỹ năng, ví dụ: Lập trình Python]</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md text-center">
                    <h3 class="text-xl font-semibold mb-2">Kỹ năng 2</h3>
                    <p class="text-gray-600">[Mô tả kỹ năng, ví dụ: Thiết kế giao diện UI/UX]</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md text-center">
                    <h3 class="text-xl font-semibold mb-2">Kỹ năng 3</h3>
                    <p class="text-gray-600">[Mô tả kỹ năng, ví dụ: Quản lý dự án]</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-16">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-8">Dự án</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h3 class="text-xl font-semibold mb-2">Dự án 1</h3>
                    <p class="text-gray-600">[Mô tả ngắn về dự án, ví dụ: Một ứng dụng web bán hàng]</p>
                    <a href="#" class="text-blue-600 hover:underline">Xem chi tiết</a>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h3 class="text-xl font-semibold mb-2">Dự án 2</h3>
                    <p class="text-gray-600">[Mô tả ngắn về dự án, ví dụ: Một trò chơi đơn giản]</p>
                    <a href="#" class="text-blue-600 hover:underline">Xem chi tiết</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-gray-200 py-16">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-8">Liên hệ</h2>
            <div class="max-w-lg mx-auto">
                <div class="mb-4">
                    <label class="block text-gray-700 font-semibold mb-2" for="name">Họ tên</label>
                    <input type="text" id="name" class="w-full p-3 border rounded-lg" placeholder="Nhập họ tên">
                </div>
                <div class="mb-4">
                    <label class="block text-gray-700 font-semibold mb-2" for="email">Email</label>
                    <input type="email" id="email" class="w-full p-3 border rounded-lg" placeholder="Nhập email">
                </div>
                <div class="mb-4">
                    <label class="block text-gray-700 font-semibold mb-2" for="message">Tin nhắn</label>
                    <textarea id="message" class="w-full p-3 border rounded-lg" rows="5" placeholder="Nhập tin nhắn"></textarea>
                </div>
                <button onclick="alert('Tin nhắn đã được gửi!')" class="bg-blue-600 text-white px-6 py-3 rounded-lg hover:bg-blue-700">Gửi</button>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-blue-600 text-white text-center py-4">
        <p>&copy; 2025 [Tên của bạn]. All rights reserved.</p>
    </footer>

    <!-- Smooth Scroll Script -->
    <script>
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
