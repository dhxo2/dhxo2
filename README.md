<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DHX.O2 - Solusi Digital Inovatif</title>
    
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    
    <!-- Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest/dist/lucide.min.js"></script>


    <style>
        /* Menggunakan font Inter sebagai default */
        body {
            font-family: 'Inter', sans-serif;
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;
        }
        /* Efek gradien untuk teks */
        .text-gradient {
            background: linear-gradient(to right, #ffffff, #a7a7a7);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        /* Efek glow halus di hero section */
        .hero-glow {
            background-image: radial-gradient(ellipse 50% 50% at 50% 50%, rgba(128, 90, 213, 0.2), transparent 70%);
        }
    </style>
</head>
<body class="bg-gray-900 text-gray-300">

    <!-- ===== Header Section ===== -->
    <header class="fixed top-0 left-0 right-0 z-50 bg-gray-900/80 backdrop-blur-sm border-b border-gray-800">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <!-- Logo dan Nama Website -->
            <a href="#" class="flex items-center gap-3">
                <!-- SVG Logo .O2 (Diperbarui) -->
                <svg width="35" height="35" viewBox="0 0 120 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <circle cx="15" cy="50" r="8" fill="white"/>
                    <circle cx="58" cy="50" r="25" stroke="white" stroke-width="8"/>
                    <path d="M88,42 C88,32 108,32 108,42 C108,57 88,57 88,72 L113,72" stroke="white" stroke-width="8" fill="none" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
                <span class="text-2xl font-bold text-white">DHX.O2</span>
            </a>
            
            <!-- Navigasi Desktop -->
            <nav class="hidden md:flex items-center space-x-8">
                <a href="#fitur" class="hover:text-white transition-colors duration-300">Fitur</a>
                <a href="#proyek" class="hover:text-white transition-colors duration-300">Proyek</a>
                <a href="#tentang" class="hover:text-white transition-colors duration-300">Tentang</a>
                <a href="#kontak" class="bg-white text-gray-900 px-4 py-2 rounded-md font-semibold hover:bg-gray-200 transition-colors duration-300">Hubungi Kami</a>
            </nav>

            <!-- Tombol Menu Mobile -->
            <button id="mobile-menu-button" class="md:hidden text-white">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-menu"><line x1="4" x2="20" y1="12" y2="12"/><line x1="4" x2="20" y1="6" y2="6"/><line x1="4" x2="20" y1="18" y2="18"/></svg>
            </button>
        </div>

        <!-- Menu Mobile (muncul saat di-klik) -->
        <div id="mobile-menu" class="hidden md:hidden bg-gray-900/95">
            <a href="#fitur" class="block py-3 px-6 text-center hover:bg-gray-800">Fitur</a>
            <a href="#proyek" class="block py-3 px-6 text-center hover:bg-gray-800">Proyek</a>
            <a href="#tentang" class="block py-3 px-6 text-center hover:bg-gray-800">Tentang</a>
            <a href="#kontak" class="block py-4 px-6 text-center bg-white text-gray-900 font-semibold mt-2">Hubungi Kami</a>
        </div>
    </header>

    <main>
        <!-- ===== Hero Section ===== -->
        <section class="relative pt-32 pb-20 md:pt-48 md:pb-32 text-center overflow-hidden">
            <div class="absolute inset-0 hero-glow"></div>
            <div class="container mx-auto px-6 relative z-10">
                <h1 class="text-4xl md:text-6xl lg:text-7xl font-extrabold mb-4">
                    <span class="text-gradient">Mewujudkan Ide Digital Anda</span>
                </h1>
                <p class="text-lg md:text-xl max-w-3xl mx-auto mb-8 text-gray-400">
                    Kami adalah partner inovatif Anda dalam membangun produk digital yang luar biasa, dari website modern hingga aplikasi canggih.
                </p>
                <a href="#proyek" class="bg-gradient-to-r from-purple-600 to-blue-600 text-white font-bold py-3 px-8 rounded-lg text-lg hover:from-purple-700 hover:to-blue-700 transition-all duration-300 transform hover:scale-105">
                    Lihat Portofolio
                </a>
            </div>
        </section>

        <!-- ===== Fitur Section ===== -->
        <section id="fitur" class="py-20 bg-black/20">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-white">Layanan Unggulan Kami</h2>
                    <p class="text-gray-400 mt-2">Solusi lengkap untuk kebutuhan digital Anda.</p>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Kartu Fitur 1 -->
                    <div class="bg-gray-800/50 backdrop-blur-sm border border-gray-700 p-8 rounded-xl text-center hover:border-purple-500 transition-colors duration-300">
                        <div class="flex justify-center mb-4">
                            <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-layout-template text-purple-400"><rect width="18" height="7" x="3" y="3" rx="1"/><rect width="9" height="7" x="3" y="14" rx="1"/><rect width="5" height="7" x="16" y="14" rx="1"/></svg>
                        </div>
                        <h3 class="text-xl font-bold text-white mb-2">Desain Web Modern</h3>
                        <p class="text-gray-400">Tampilan website yang responsif, menarik, dan ramah pengguna untuk meningkatkan citra brand Anda.</p>
                    </div>
                    <!-- Kartu Fitur 2 -->
                    <div class="bg-gray-800/50 backdrop-blur-sm border border-gray-700 p-8 rounded-xl text-center hover:border-blue-500 transition-colors duration-300">
                        <div class="flex justify-center mb-4">
                            <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-smartphone-cog text-blue-400"><path d="M12 18a2 2 0 1 0 4 0 2 2 0 0 0-4 0Z"/><path d="M12 12a2 2 0 1 0 4 0 2 2 0 0 0-4 0Z"/><path d="M12 6a2 2 0 1 0 4 0 2 2 0 0 0-4 0Z"/><rect width="14" height="20" x="5" y="2" rx="2"/><path d="M12 18v-2"/><path d="M12 12V6"/></svg>
                        </div>
                        <h3 class="text-xl font-bold text-white mb-2">Pengembangan Aplikasi</h3>
                        <p class="text-gray-400">Membangun aplikasi mobile atau web-based yang fungsional dan sesuai dengan proses bisnis Anda.</p>
                    </div>
                    <!-- Kartu Fitur 3 -->
                    <div class="bg-gray-800/50 backdrop-blur-sm border border-gray-700 p-8 rounded-xl text-center hover:border-green-500 transition-colors duration-300">
                        <div class="flex justify-center mb-4">
                            <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-megaphone text-green-400"><path d="m3 11 18-5v12L3 14v-3z"/><path d="M11.6 16.8a3 3 0 1 1-5.8-1.6"/></svg>
                        </div>
                        <h3 class="text-xl font-bold text-white mb-2">Digital Marketing</h3>
                        <p class="text-gray-400">Strategi pemasaran digital yang efektif untuk menjangkau audiens yang lebih luas dan meningkatkan penjualan.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===== Proyek/Portofolio Section ===== -->
        <section id="proyek" class="py-20">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-white">Proyek Terbaru Kami</h2>
                    <p class="text-gray-400 mt-2">Beberapa karya yang telah kami selesaikan dengan bangga.</p>
                </div>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Proyek 1 -->
                    <div class="group relative overflow-hidden rounded-lg">
                        <img src="https://placehold.co/600x400/1a202c/ffffff?text=Proyek+A" alt="Gambar Proyek A" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110">
                        <div class="absolute inset-0 bg-black/70 flex flex-col justify-end p-6 opacity-0 group-hover:opacity-100 transition-opacity duration-500">
                            <h3 class="text-xl font-bold text-white">Platform E-commerce</h3>
                            <p class="text-gray-300">Website jual beli online dengan fitur lengkap.</p>
                        </div>
                    </div>
                    <!-- Proyek 2 -->
                    <div class="group relative overflow-hidden rounded-lg">
                        <img src="https://placehold.co/600x400/1a202c/ffffff?text=Proyek+B" alt="Gambar Proyek B" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110">
                        <div class="absolute inset-0 bg-black/70 flex flex-col justify-end p-6 opacity-0 group-hover:opacity-100 transition-opacity duration-500">
                            <h3 class="text-xl font-bold text-white">Aplikasi Manajemen Tugas</h3>
                            <p class="text-gray-300">Aplikasi untuk meningkatkan produktivitas tim.</p>
                        </div>
                    </div>
                    <!-- Proyek 3 -->
                    <div class="group relative overflow-hidden rounded-lg">
                        <img src="https://placehold.co/600x400/1a202c/ffffff?text=Proyek+C" alt="Gambar Proyek C" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110">
                        <div class="absolute inset-0 bg-black/70 flex flex-col justify-end p-6 opacity-0 group-hover:opacity-100 transition-opacity duration-500">
                            <h3 class="text-xl font-bold text-white">Company Profile</h3>
                            <p class="text-gray-300">Website profesional untuk perusahaan.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===== Tentang Kami Section ===== -->
        <section id="tentang" class="py-20 bg-black/20">
            <div class="container mx-auto px-6 flex flex-col md:flex-row items-center gap-12">
                <div class="md:w-1/2">
                    <img src="https://placehold.co/600x450/111827/ffffff?text=Tim+DHX.O2" alt="Tim DHX.O2" class="rounded-xl shadow-2xl">
                </div>
                <div class="md:w-1/2">
                    <h2 class="text-3xl md:text-4xl font-bold text-white mb-4">Tentang DHX.O2</h2>
                    <p class="text-gray-400 mb-4">
                        DHX.O2 lahir dari semangat untuk berinovasi dan memberikan solusi digital terbaik. Kami adalah tim yang terdiri dari para profesional kreatif dan teknis yang berdedikasi untuk membantu klien kami sukses di dunia digital.
                    </p>
                    <p class="text-gray-400">
                        Dengan fokus pada kualitas, kecepatan, dan kepuasan klien, kami berkomitmen untuk menjadi mitra terpercaya dalam setiap langkah transformasi digital Anda.
                    </p>
                </div>
            </div>
        </section>
    </main>

    <!-- ===== Footer Section ===== -->
    <footer id="kontak" class="bg-gray-900 border-t border-gray-800 pt-16 pb-8">
        <div class="container mx-auto px-6">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-center md:text-left">
                <!-- Kolom 1: Tentang -->
                <div>
                    <a href="#" class="flex items-center justify-center md:justify-start gap-3 mb-4">
                         <svg width="30" height="30" viewBox="0 0 120 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <circle cx="15" cy="50" r="8" fill="white"/>
                            <circle cx="58" cy="50" r="25" stroke="white" stroke-width="8"/>
                            <path d="M88,42 C88,32 108,32 108,42 C108,57 88,57 88,72 L113,72" stroke="white" stroke-width="8" fill="none" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                        <span class="text-xl font-bold text-white">DHX.O2</span>
                    </a>
                    <p class="text-gray-400">Partner inovatif untuk solusi digital Anda.</p>
                </div>
                
                <!-- Kolom 2: Kontak -->
                <div>
                    <h3 class="text-lg font-semibold text-white mb-4">Hubungi Kami</h3>
                    <ul class="space-y-2">
                        <li><a href="mailto:kontak@dhxo2.com" class="text-gray-400 hover:text-white">kontak@dhxo2.com</a></li>
                        <li><a href="tel:+6281234567890" class="text-gray-400 hover:text-white">+62 812-3456-7890</a></li>
                    </ul>
                </div>

                <!-- Kolom 3: Media Sosial -->
                <div>
                    <h3 class="text-lg font-semibold text-white mb-4">Ikuti Kami</h3>
                    <div class="flex justify-center md:justify-start space-x-4">
                        <a href="https://www.instagram.com/dhx.o2?igsh=djBwa2Q4M2lxNjV6" target="_blank" rel="noopener noreferrer" class="text-gray-400 hover:text-white"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-instagram"><rect width="20" height="20" x="2" y="2" rx="5" ry="5"/><path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"/><line x1="17.5" x2="17.51" y1="6.5" y2="6.5"/></svg></a>
                        <a href="#" class="text-gray-400 hover:text-white"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-facebook"><path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"/></svg></a>
                        <a href="#" class="text-gray-400 hover:text-white"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-twitter"><path d="M22 4s-.7 2.1-2 3.4c1.6 1.4 3.3 4.4 3.3 4.4s-1.4-.5-2.8-.8c0 0-4.1 2.8-7.3 2.8c-3.3 0-6.3-2.1-6.3-2.1s-1.4.6-2.8.8c0 0 1.7-3 3.3-4.4C2.8 6.5 2 4.4 2 4.4s2.1.8 3.6 1.1c0 0 2.1-3.3 6.3-3.3s6.3 3.3 6.3 3.3z"/></svg></a>
                        <a href="#" class="text-gray-400 hover:text-white"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-linkedin"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"/><rect width="4" height="12" x="2" y="9"/><circle cx="4" cy="4" r="2"/></svg></a>
                        <a href="#" class="text-gray-400 hover:text-white"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-youtube"><path d="M2.5 17a24.12 24.12 0 0 1 0-10C2.5 6 7.5 4 12 4s9.5 2 9.5 3a24.12 24.12 0 0 1 0 10c0 1-5 3-9.5 3s-9.5-2-9.5-3Z"/><path d="m10 15 5-3-5-3z"/></svg></a>
                    </div>
                </div>
            </div>

            <div class="border-t border-gray-800 mt-12 pt-6 text-center text-gray-500">
                <p>&copy; 2024 DHX.O2. Semua Hak Cipta Dilindungi.</p>
            </div>
        </div>
    </footer>

    <script>
        // Script untuk toggle menu mobile
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
    </script>
</body>
</html>
