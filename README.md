# 🌌 VibeSpace - Real-Time Group Chat App

VibeSpace adalah aplikasi web obrolan grup *real-time* berbasis room privat yang dirancang dengan antarmuka modern, interaktif, dan responsif. Pengguna dapat membuat ruangan obrolan sendiri dengan kata sandi terproteksi atau bergabung ke ruangan yang sudah ada.

![Halaman Login VibeSpace](screenshots/login.png)
![Halaman Chat VibeSpace](screenshots/chat.png)

👉 **[COBA APLIKASI SEKARANG (LIVE DEMO)](https://USERNAME_KAMU.github.io/vibespace-chat)**

---

## ✨ Fitur Utama

* **Real-Time Messaging:** Kirim dan terima pesan secara instan tanpa perlu memuat ulang halaman (*real-time synchronization*).
* **Protected Room System:** Keamanan masuk ruangan menggunakan sistem kecocokan ID Room dan Password.
* **Dynamic Theme Switcher:** Tersedia 3 pilihan tema warna estetik yang bisa diubah secara dinamis langsung dari dalam aplikasi:
  * 🎨 *Classic Teal*
  * 🎨 *Cyber Violet*
  * 🎨 *Elegant Slate* (Optimal untuk kenyamanan visual)
* **Seamless Light/Dark Mode Toggle:** Dukungan penuh peralihan Mode Gelap (Dark) dan Mode Terang (Light) pada komponen global dan room chat secara konsisten.
* **Message Management:** Pengguna dapat mengedit kembali teks pesan atau menghapus pesan secara permanen dari database.
* **Built-in Emoji Picker:** Menyediakan panel emoji bawaan (😊, 😂, 👍, dsb.) tanpa bergantung pada keyboard bawaan perangkat.
* **Auto-Cleanup & Presence Handling:** Otomatis menghapus data presensi pengguna di dalam room ketika tab browser ditutup atau koneksi terputus menggunakan fitur `onDisconnect` Firebase.

---

## 🚀 Teknologi yang Digunakan

* **Front-End UI:** [Tailwind CSS](https://tailwindcss.com) (via CDN)
* **Database & Realtime Backend:** [Firebase Realtime Database](https://firebase.google.com/) (v8 Web SDK)
* **Language:** HTML5, Modern JavaScript (ES6+), CSS3

---

## 📦 Struktur Proyek

```text
├── index.html          # File utama aplikasi (UI, Tailwind Styling, & Logic JS)
└── README.md           # Dokumentasi dan panduan proyek
