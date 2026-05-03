<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Geri Setiawan | IT Support Specialist Portfolio</title>
    
    <!-- Tailwind CSS via CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- AOS Library for Scroll Animations -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;600;800&display=swap');
        
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: #0f0f0f;
            color: #e2e8f0;
            overflow-x: hidden;
        }

        .text-maroon { color: #b91c1c; }
        .bg-maroon { background-color: #800000; }
        
        .hero-gradient {
            background: linear-gradient(135deg, #1a1a1a 0%, #4c0505 100%);
        }

        .glass-card {
            background: rgba(255, 255, 255, 0.03);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.08);
        }

        /* Fix untuk GitHub Pages agar image tetap proporsional */
        .profile-img-container {
            width: 100%;
            max-width: 400px;
            aspect-ratio: 3/4;
            border: 8px solid rgba(255, 255, 255, 0.05);
            border-radius: 1.5rem;
            overflow: hidden;
            position: relative;
        }
    </style>
</head>
<body>

    <!-- Navigasi -->
    <nav class="fixed w-full z-50 bg-black/90 backdrop-blur-md border-b border-white/5">
        <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
            <span class="text-xl font-extrabold tracking-tighter text-white">GERI<span class="text-maroon">.</span></span>
            <div class="hidden md:flex space-x-8 text-sm font-medium uppercase tracking-widest">
                <a href="#profil" class="hover:text-maroon transition-colors">Profil</a>
                <a href="#pengalaman" class="hover:text-maroon transition-colors">Pengalaman</a>
                <a href="#kontak" class="bg-maroon px-6 py-2 rounded-full text-white hover:bg-red-700 transition-all shadow-lg shadow-red-900/20">Hubungi Saya</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header id="profil" class="hero-gradient min-h-screen flex items-center pt-24 pb-12">
        <div class="max-w-6xl mx-auto px-6 grid md:grid-cols-2 gap-16 items-center">
            <div data-aos="fade-right" data-aos-duration="1000">
                <div class="inline-block px-4 py-1 border border-maroon text-maroon text-xs font-bold tracking-[0.2em] uppercase rounded-full mb-6">
                    IT Support Specialist
                </div>
                <h1 class="text-5xl md:text-7xl font-extrabold text-white mb-6 leading-tight">
                    Geri Setiawan
                </h1>
                <p class="text-lg text-slate-400 mb-10 leading-relaxed max-w-xl">
                    Berpengalaman selama 4 tahun dalam mengelola sistem komputerisasi, administrasi jaringan, dan pengembangan web. Fokus pada efisiensi operasional dan solusi infrastruktur IT[cite: 1].
                </p>
                <div class="flex flex-wrap gap-4">
                    <a href="#kontak" class="bg-maroon text-white px-8 py-4 rounded-xl font-bold hover:scale-105 transition-transform">Mulai Kolaborasi</a>
                    <a href="https://github.com/geri02042" target="_blank" class="border border-white/20 px-8 py-4 rounded-xl font-bold hover:bg-white/5 transition-all">Lihat GitHub</a>
                </div>
            </div>
            
            <div class="flex justify-center" data-aos="zoom-in" data-aos-duration="1200">
                <div class="profile-img-container shadow-2xl">
                    <!-- Image Link Updated for your GitHub Repo[cite: 1] -->
                    <img src="https://raw.githubusercontent.com/geri02042/Profil-Geri-Setiawan/main/WhatsApp%20Image%202026-01-08%20at%2014.19.50.jpeg" 
                         alt="Geri Setiawan Profile" 
                         class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-700">
                    <div class="absolute inset-0 bg-maroon/10 mix-blend-overlay"></div>
                </div>
            </div>
        </div>
    </header>

    <!-- Skills & Certificates -->
    <section class="py-24 bg-[#0a0a0a]">
        <div class="max-w-6xl mx-auto px-6">
            <h3 class="text-center text-slate-500 uppercase tracking-[0.3em] text-xs font-bold mb-12">Sertifikasi & Keahlian[cite: 1]</h3>
            <div class="grid grid-cols-2 md:grid-cols-3 gap-6">
                <div class="glass-card p-8 rounded-2xl" data-aos="fade-up">
                    <h4 class="text-white font-bold mb-2">Network Admin</h4>
                    <p class="text-slate-500 text-xs uppercase">Kominfo Cert. 2023[cite: 1]</p>
                </div>
                <div class="glass-card p-8 rounded-2xl" data-aos="fade-up" data-aos-delay="100">
                    <h4 class="text-white font-bold mb-2">Mobile Programming</h4>
                    <p class="text-slate-500 text-xs uppercase">Kominfo Cert. 2019[cite: 1]</p>
                </div>
                <div class="glass-card p-8 rounded-2xl" data-aos="fade-up" data-aos-delay="200">
                    <h4 class="text-white font-bold mb-2">Web Development</h4>
                    <p class="text-slate-500 text-xs uppercase">4 Years Experience[cite: 1]</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Experience Timeline -->
    <section id="pengalaman" class="py-24 px-6">
        <div class="max-w-4xl mx-auto">
            <h2 class="text-3xl font-bold mb-16 text-center" data-aos="fade-up">Pengalaman Kerja[cite: 1]</h2>
            
            <div class="space-y-12 border-l-2 border-maroon/30 ml-4 md:ml-0 pl-8">
                <!-- Job 1 -->
                <div class="relative" data-aos="fade-up">
                    <div class="absolute -left-[41px] top-1 w-5 h-5 bg-maroon rounded-full border-4 border-[#0f0f0f]"></div>
                    <span class="text-maroon font-bold text-sm uppercase">2024 - Sekarang[cite: 1]</span>
                    <h4 class="text-xl font-bold text-white mt-1">Teknisi Project Pengeboran Pertamina</h4>
                    <p class="text-slate-500 text-sm mb-4">PT. Aplikanusa Lintasarta[cite: 1]</p>
                    <p class="text-slate-400 text-sm max-w-2xl leading-relaxed">
                        Fokus pada instalasi perangkat Starlink, troubleshooting sistem kompleks, dan administrasi jaringan untuk operasional drilling[cite: 1].
                    </p>
                </div>

                <!-- Job 2 -->
                <div class="relative" data-aos="fade-up">
                    <div class="absolute -left-[41px] top-1 w-5 h-5 bg-slate-700 rounded-full border-4 border-[#0f0f0f]"></div>
                    <span class="text-slate-500 font-bold text-sm uppercase">2022[cite: 1]</span>
                    <h4 class="text-xl font-bold text-white mt-1">Admin Verifikator</h4>
                    <p class="text-slate-500 text-sm mb-4">PT. ASP[cite: 1]</p>
                    <p class="text-slate-400 text-sm max-w-2xl leading-relaxed">
                        Mengelola data jaringan fiber optic SUTET PLN dan supervisi teknisi lapangan[cite: 1].
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer id="kontak" class="py-20 bg-black border-t border-white/5">
        <div class="max-w-6xl mx-auto px-6 text-center">
            <h2 class="text-3xl font-bold text-white mb-8">Hubungi Saya</h2>
            <div class="flex flex-col md:flex-row justify-center gap-8 mb-12">
                <a href="mailto:geri02042@gmail.com" class="text-slate-400 hover:text-maroon transition">geri02042@gmail.com[cite: 1]</a>
                <a href="https://wa.me/62895605100951" class="text-slate-400 hover:text-maroon transition">0895-6051-00951[cite: 1]</a>
                <span class="text-slate-400">Palembang, Indonesia[cite: 1]</span>
            </div>
            <p class="text-slate-600 text-xs tracking-widest uppercase">© 2026 Geri Setiawan Portfolio</p>
        </div>
    </footer>

    <!-- Scripts -->
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        AOS.init({ 
            once: true,
            duration: 800
        });
    </script>
</body>
</html>
