# 🌐 PORTO

> Website portofolio 3D interaktif dengan desain modern, animasi halus, dan integrasi Three.js — dibuat untuk menampilkan profil, keahlian, dan proyek secara profesional.

![Preview](assets/foto.jpg)

<p align="center">
  <a href="#-tentang-proyek">Tentang</a> •
  <a href="#-fitur-utama">Fitur</a> •
  <a href="#-teknologi">Teknologi</a> •
  <a href="#-instalasi">Instalasi</a> •
  <a href="#-struktur-proyek">Struktur</a> •
  <a href="#-kontribusi">Kontribusi</a> •
  <a href="#-lisensi">Lisensi</a>
</p>

---

## 🪄 Badge

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

---

## 📖 Tentang Proyek

**PORTO** adalah website portofolio interaktif yang memanfaatkan teknologi **Three.js** untuk efek 3D real-time pada bagian profil, serta dilengkapi dengan dark mode, animasi halus, dan navigasi modern.  
Proyek ini cocok untuk personal branding, web developer, desainer UI/UX, atau siapa pun yang ingin tampil profesional secara online.

---

## ✨ Fitur Utama

- 🌗 **Mode Gelap & Terang** — Dapat disimpan otomatis di `localStorage`.  
- 🧭 **Navigasi Smooth Scroll** — Transisi lembut saat klik anchor.  
- 🖼️ **Hero Section 3D** — Canvas dengan GLTF model dan efek bloom.  
- 🖱️ **Cursor Ring & Trail** — Interaktif mengikuti pointer.  
- 📄 **Download CV Langsung** — Tombol unduh CV PDF.  
- 📱 **Desain Responsif** — Optimal untuk desktop & mobile.  
- ⚡ **Animasi Scroll (Reveal)** — Konten muncul dinamis saat discroll.

---

## 🧰 Teknologi

- **HTML5**, **CSS3**, **JavaScript (ES6+)**
- [Three.js](https://threejs.org/) — GLTF Loader, UnrealBloomPass
- [Lottie](https://airbnb.io/lottie/#/) — Animasi logo
- Intersection Observer API
- Responsive Web Design

---

## 🛠 Instalasi

1. **Clone repositori**
   ```bash
   git clone https://github.com/username/PORTO.git
   cd PORTO
   ```

2. **Jalankan secara lokal**  
   Kamu bisa membuka langsung `index.html` melalui browser, atau menggunakan server lokal agar fitur `import module` berjalan optimal.

   Menggunakan **Python**:
   ```bash
   python -m http.server 8000
   ```
   Akses: [http://localhost:8000](http://localhost:8000)

   Menggunakan **Node.js**:
   ```bash
   npx serve .
   ```

---

## 🧱 Struktur Proyek

```
PORTO/
├── index.html
├── assets/
│   ├── foto.jpg
│   ├── cv.pdf
│   ├── lottie/logo.json
│   ├── env_small.hdr
│   └── model/
│       └── hero.glb
└── README.md
```

---

## 🧠 Tips & Kustomisasi

- Ganti `assets/model/hero.glb` dengan model 3D GLTF milikmu sendiri.  
- Ubah warna tema di bagian `:root` & `[data-theme='dark']`.  
- Tambah kartu proyek baru dengan menyalin struktur `.card` di bagian `#projects`.

---

## 🤝 Kontribusi

Kontribusi selalu terbuka!  
Jika kamu ingin berkontribusi:

1. Fork repositori ini.  
2. Buat branch fitur: `git checkout -b fitur-baru`.  
3. Commit perubahan: `git commit -m "Tambah fitur baru"`.  
4. Push ke branch: `git push origin fitur-baru`.  
5. Ajukan Pull Request.

---

## 📜 Lisensi

Proyek ini dirilis di bawah lisensi **MIT** — kamu bebas menggunakannya untuk proyek pribadi maupun publik dengan atribusi yang sesuai.

---

## 👨‍💻 Pembuat

**Giska Aura Muhamad Prasetyo**  
Web Developer • UI/UX Enthusiast  
[🌐 Website](https://giskaaura.dev) • [GitHub](https://github.com/giskaaura) • [LinkedIn](https://www.linkedin.com/in/giskaaura)

---

> Dibuat dengan ❤️, JavaScript, dan sedikit sentuhan anime.
