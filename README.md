# Stun Bound: Boss Dodger

**Stun Bound** adalah game aksi *bullet-hell* berbasis peramban (web) di mana pemain harus bertahan hidup dari serangan bos yang tak henti-hentinya, mencari celah, dan melancarkan serangan balik saat bos dalam kondisi *stunned* (lemah).

## 🎮 Fitur Utama
* **Boss Fight Mekanik:** Bos memiliki status "Immortal" saat menyerang dan hanya bisa dilukai saat stamina mereka habis.
* **Variasi Bos:** Hadapi berbagai jenis bos dengan pola serangan unik (Vortex, Wall, Mother Hive, Gear).
* **Sistem Dash:** Gunakan mekanik *dash* untuk menghindari proyektil mematikan dengan jendela *invincibility* singkat.
* **Tingkat Kesulitan:** Pilih mulai dari *Easy* hingga *Nightmare* (brutal).
* **UI Dinamis:** HUD yang bersih dan responsif, dengan fitur transparansi otomatis agar pandangan tidak terhalang.

## 🕹️ Kontrol

| Aksi | Mouse & Keyboard | Keyboard Only |
| :--- | :--- | :--- |
| **Gerak** | WASD | WASD / Tombol Panah |
| **Bidik** | Mouse | Auto-Aim |
| **Tembak** | Klik Kiri | SPASI |
| **Dash** | Klik Kanan | J |
| **Pause** | ESC | ESC |

## 🚀 Cara Menjalankan
1. Pastikan kamu memiliki browser modern (Chrome, Edge, atau Firefox).
2. Unduh file `index.html` ini ke komputer kamu.
3. Klik dua kali file `index.html` untuk membuka game di browser.
4. *Tidak perlu instalasi atau server tambahan!*

## 🛠️ Arsitektur Teknis
* **Engine:** Vanilla JavaScript Canvas API (tanpa library eksternal).
* **Optimasi:** Menggunakan sistem *pooling* untuk proyektil dan partikel guna mencegah *lag* (DOM Thrashing diminimalisir).
* **Rendering:** *Frame-based update loop* yang dioptimalkan dengan `requestAnimationFrame`.

## 📝 Catatan Pengembangan
Game ini dibuat sebagai proyek optimasi performa tinggi untuk memproses ratusan objek proyektil secara bersamaan di layar tanpa menurunkan *frame rate*.

---
*Dibuat untuk tantangan game development cepat.*
