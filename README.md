# 🌐 Portofolio 3D Interaktif — Giska Aura

Website portofolio pribadi dengan efek **3D real-time** menggunakan **Three.js**, desain modern, serta animasi halus. Proyek ini dibuat untuk menampilkan profil, keahlian, dan proyek dalam tampilan web profesional dan responsif.

![Preview](assets/foto.jpg)

---

## ✨ Fitur Utama

- 🎨 **Desain Modern & Responsif** — Menggunakan CSS grid & flexbox, mendukung mode terang dan gelap.  
- 🧭 **Navigasi Smooth Scroll** — Transisi halaman yang lembut saat klik menu.  
- 🌙 **Dark Mode Toggle** — Tersimpan otomatis di `localStorage`.  
- 🧍‍♂️ **Animasi Profil 3D** — Efek tilt & floating halus.  
- 💫 **Efek 3D Real-Time** — Menggunakan Three.js + GLTF model untuk canvas hero section.  
- 🖱️ **Cursor Interaktif** — Lingkaran dan jejak mengikuti gerakan pointer.  
- 🧱 **Reveal on Scroll** — Elemen muncul dengan animasi saat discroll.  
- 📄 **Download CV** — Tautan langsung ke file PDF.

---

## 🧰 Teknologi yang Digunakan

- **HTML5**, **CSS3**, **JavaScript (ES6+)**  
- [Three.js](https://threejs.org/) (GLTFLoader, UnrealBloomPass, dll)  
- [Lottie](https://airbnb.io/lottie/#/) untuk animasi logo  
- Intersection Observer API  
- Responsive Web Design Principles

---

## 📁 Struktur Proyek

```
.
├── index.html               # Halaman utama
├── assets/
│   ├── foto.jpg            # Foto profil
│   ├── cv.pdf              # CV untuk tombol unduh
│   ├── lottie/logo.json    # File animasi logo
│   ├── env_small.hdr       # Environment HDR untuk Three.js
│   └── model/
│       └── hero.glb        # Model 3D GLTF
└── README.md
```

---

## 🚀 Cara Menjalankan

1. **Clone Repository**  
   ```bash
   git clone https://github.com/username/portofolio-3d.git
   cd portofolio-3d
   ```

2. **Buka Secara Lokal**  
   Kamu dapat membuka file `index.html` langsung di browser.  
   Atau, gunakan server lokal agar fitur `import` module Three.js berjalan optimal:

   ```bash
   # Menggunakan Python
   python -m http.server 8000
   # Akses: http://localhost:8000
   ```

   atau dengan Node.js:
   ```bash
   npx serve .
   ```

3. Pastikan semua file `assets/` sudah tersedia dan path benar.

---

## 🧠 Tips & Modifikasi

- Ganti `assets/model/hero.glb` dengan model GLTF kamu sendiri untuk tampilan unik.  
- Sesuaikan palet warna pada `:root` dan `[data-theme='dark']`.  
- Tambahkan proyek baru dengan menyalin struktur `.card` di bagian `#projects`.

---

## 📜 Lisensi

Proyek ini dibuat untuk keperluan pribadi dan pembelajaran. Kamu bebas melakukan modifikasi untuk portofolio sendiri, tetapi harap berikan atribusi jika menggunakan ulang desain dan struktur ini.

---

## 👩‍💻 Tentang

**Giska Aura Muhamad Prasetyo**  
Web Developer • UI/UX Enthusiast  
[🌐 Website](https://giskaaura.dev) • [GitHub](https://github.com/giskaaura) • [LinkedIn](https://www.linkedin.com/in/giskaaura)

---

> Dibuat dengan ❤️, JavaScript, dan sedikit sentuhan anime.
