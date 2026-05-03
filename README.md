<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Geri Setiawan | IT Support Specialist</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;600;800&display=swap');
        
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: #0f0f0f; /* Hitam Deep */
            color: #e2e8f0;
        }

        .bg-maroon-dark { background-color: #4c0505; }
        .bg-maroon { background-color: #800000; }
        .text-maroon { color: #b91c1c; }
        .border-maroon { border-color: #800000; }

        .hero-gradient {
            background: linear-gradient(135deg, #1a1a1a 0%, #4c0505 100%);
        }

        .glass-card {
            background: rgba(255, 255, 255, 0.03);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.05);
        }

        /* Custom scrollbar ala profesional */
        ::-webkit-scrollbar { width: 6px; }
        ::-webkit-scrollbar-track { background: #0f0f0f; }
        ::-webkit-scrollbar-thumb { background: #800000; border-radius: 10px; }
    </style>
</head>
<body>

    <!-- Navigasi -->
    <nav class="fixed w-full z-50 bg-black/80 backdrop-blur-md border-b border-white/5">
        <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
            <span class="text-xl font-extrabold tracking-tighter text-white">GERI<span class="text-maroon">.</span></span>
            <div class="hidden md:flex space-x-8 text-sm font-medium uppercase tracking-widest">
                <a href="#profil" class="hover:text-maroon transition">Profil</a>
                <a href="#pengalaman" class="hover:text-maroon transition">Pengalaman</a>
                <a href="#kontak" class="bg-maroon px-5 py-2 rounded-full text-white hover:bg-red-700 transition">Hubungi Saya</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-gradient min-h-screen flex items-center pt-20">
        <div class="max-w-6xl mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">
            <div data-aos="fade-right" data-aos-duration="1000">
                <h2 class="text-maroon font-bold tracking-widest mb-4 uppercase">IT Support Specialist</h2>
                <h1 class="text-5xl md:text-7xl font-extrabold text-white mb-6 leading-tight">
                    Geri Setiawan
                </h1>
                <p class="text-lg text-slate-400 mb-8 leading-relaxed">
                    Profesional IT dengan 4 tahun pengalaman dalam sistem komputerisasi, administrasi jaringan, dan pengembangan website. Fokus pada optimasi operasional perusahaan melalui solusi teknologi yang andal.
                </p>
                <div class="flex gap-4">
                    <a href="#kontak" class="bg-maroon text-white px-8 py-4 rounded-xl font-bold shadow-lg shadow-red-900/20 hover:scale-105 transition">Kontak Saya</a>
                    <a href="#" class="border border-white/20 px-8 py-4 rounded-xl font-bold hover:bg-white/5 transition">Download CV</a>
                </div>
            </div>
            
            <div class="relative flex justify-center" data-aos="zoom-in" data-aos-duration="1200">
                <div class="relative w-80 h-[450px] md:w-[400px] md:h-[550px] border-[12px] border-white/5 rounded-3xl overflow-hidden shadow-2xl">
                    <!-- Gunakan Foto Dari CV Anda -->
                    <img src="https://raw.githubusercontent.com/geri02042/Profil-Geri-Setiawan/main/WhatsApp%20Image%202026-01-08%20at%2014.19.50.jpeg" alt="Geri Setiawan" class="w-full h-full object-cover grayscale hover:grayscale-0 transition duration-700">
                    <div class="absolute inset-0 bg-maroon/20 mix-blend-multiply"></div>
                </div>
                <!-- Dekorasi -->
                <div class="absolute -bottom-10 -right-10 w-40 h-40 bg-maroon blur-[100px] opacity-50"></div>
            </div>
        </div>
    </section>

    <!-- Skill Section (Cards) -->
    <section class="py-24 bg-[#0a0a0a]">
        <div class="max-w-6xl mx-auto px-6">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
                <div class="glass-card p-6 rounded-2xl text-center" data-aos="fade-up">
                    <h3 class="text-maroon font-bold text-xl mb-1">4+</h3>
                    <p class="text-slate-500 text-sm">Tahun Pengalaman</p>
                </div>
                <div class="glass-card p-6 rounded-2xl text-center" data-aos="fade-up" data-aos-delay="100">
                    <h3 class="text-maroon font-bold text-xl mb-1">Network</h3>
                    <p class="text-slate-500 text-sm">Administration</p>
                </div>
                <div class="glass-card p-6 rounded-2xl text-center" data-aos="fade-up" data-aos-delay="200">
                    <h3 class="text-maroon font-bold text-xl mb-1">Website</h3>
                    <p class="text-slate-500 text-sm">Development</p>
                </div>
                <div class="glass-card p-6 rounded-2xl text-center" data-aos="fade-up" data-aos-delay="300">
                    <h3 class="text-maroon font-bold text-xl mb-1">Starlink</h3>
                    <p class="text-slate-500 text-sm">Installation Expert</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Work Experience -->
    <section id="pengalaman" class="py-24">
        <div class="max-w-4xl mx-auto px-6">
            <h2 class="text-3xl font-bold mb-16 text-center border-b border-maroon inline-block pb-2 mx-auto" data-aos="fade-up">Riwayat Pekerjaan</h2>
            
            <div class="space-y-12">
                <!-- Job 1 -->
                <div class="flex flex-col md:flex-row gap-6" data-aos="fade-up">
                    <div class="md:w-1/3">
                        <p class="text-maroon font-bold">2024 - Sekarang</p>
                        <p class="text-sm text-slate-500 italic">PT. Aplikanusa Lintasarta</p>
                    </div>
                    <div class="md:w-2/3 border-l border-white/10 pl-8 relative">
                        <div class="absolute w-3 h-3 bg-maroon rounded-full -left-[6.5px] top-1"></div>
                        <h4 class="text-xl font-bold text-white mb-2">Teknisi Project Pengeboran Pertamina</h4>
                        <ul class="text-slate-400 text-sm space-y-2">
                            <li>• Instalasi dan konfigurasi perangkat satelit Starlink di area remote.</li>
                            <li>• Troubleshooting hardware, software, dan konektivitas jaringan kompleks.</li>
                            <li>• Maintenance infrastruktur jaringan untuk performa maksimal.</li>
                        </ul>
                    </div>
                </div>

                <!-- Job 2 -->
                <div class="flex flex-col md:flex-row gap-6" data-aos="fade-up">
                    <div class="md:w-1/3">
                        <p class="text-maroon font-bold">Feb 2022 - Juli 2022</p>
                        <p class="text-sm text-slate-500 italic">PT. ASP</p>
                    </div>
                    <div class="md:w-2/3 border-l border-white/10 pl-8 relative">
                        <div class="absolute w-3 h-3 bg-white/20 rounded-full -left-[6.5px] top-1"></div>
                        <h4 class="text-xl font-bold text-white mb-2">Admin Verifikator</h4>
                        <ul class="text-slate-400 text-sm space-y-2">
                            <li>• Pengelolaan input data jaringan fiber optic untuk SUTET PLN.</li>
                            <li>• Manajemen personil, rekrutmen, dan supervisi teknisi lapangan.</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer / Kontak -->
    <footer id="kontak" class="py-24 bg-[#050505] border-t border-white/5">
        <div class="max-w-6xl mx-auto px-6 grid md:grid-cols-2 gap-12">
            <div data-aos="fade-right">
                <h2 class="text-4xl font-extrabold mb-6">Mari Terhubung.</h2>
                <p class="text-slate-500 mb-8 max-w-sm">
                    Tersedia untuk peluang kerja sama profesional di bidang IT Support, Networking, dan Web Development.
                </p>
                <div class="space-y-4 text-slate-300">
                    <p class="flex items-center gap-3"><span class="text-maroon font-bold">📍</span> Palembang, Sumatera Selatan</p>
                    <p class="flex items-center gap-3"><span class="text-maroon font-bold">📧</span> geri02042@gmail.com</p>
                    <p class="flex items-center gap-3"><span class="text-maroon font-bold">📞</span> 0895-6051-00951</p>
                </div>
            </div>
            
            <div class="glass-card p-8 rounded-3xl" data-aos="fade-left">
                <form class="space-y-4">
                    <input type="text" placeholder="Nama Anda" class="w-full bg-white/5 border border-white/10 p-4 rounded-xl focus:outline-none focus:border-maroon transition">
                    <textarea placeholder="Pesan Anda" rows="4" class="w-full bg-white/5 border border-white/10 p-4 rounded-xl focus:outline-none focus:border-maroon transition"></textarea>
                    <button class="w-full bg-maroon p-4 rounded-xl font-bold hover:bg-red-700 transition">Kirim Pesan</button>
                </form>
            </div>
        </div>
        <div class="text-center mt-20 text-slate-600 text-xs tracking-[0.2em] uppercase">
            © 2026 GERI SETIAWAN — PORTFOLIO EDITION
        </div>
    </footer>

    <!-- AOS Script -->
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        AOS.init({ once: true });
    </script>
</body>
</html>
