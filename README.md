<div align="center">

# 🎌 Custom Alert Overlay for Tako

[![GitHub License](https://img.shields.io/github/license/shiroinekoo/Tako-Overlay?style=flat-square&color=blue)](./LICENSE)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/shiroinekoo/Tako-Overlay?style=flat-square&color=green)](https://github.com/shiroinekoo/Tako-Overlay/commits/main)

Koleksi template Custom Alert Overlay interaktif dan estetik untuk platform streaming Tako atau Saweria. Dirancang khusus agar pas di layar OBS Studio dan mudah dibaca oleh penonton!

</div>

---

## 💡 Request Karakter & Kontribusi
Punya ide karakter anime favorit untuk dijadikan tema overlay berikutnya? Kamu bisa mengajukannya melalui **[Pull Request](https://github.com/shiroinekoo/Tako-Overlay/pulls)** (sertakan klik *function* atau kode pendukungnya), atau buat laporan di menu *Issue*!

---

## 🖼️ Galeri Preview Overlay
Berikut adalah beberapa pilihan template overlay anime yang sudah tersedia dan siap pakai:

* **Mikasa Ackerman (Attack on Titan)**  
  [Template](./template/mikasa_chibi) | [GIF Preview](asset/preview_overlay/mikasa-chibi-overlay.png) 
  <img src="https://raw.githubusercontent.com/shiroinekoo/Tako-Overlay/main/asset/preview%20overlay/mikasa-chibi-overlay.png" width="100%" alt="Mikasa Overlay Preview">

* **Marin Kitagawa (My Dress-Up Darling)**  
  [Template](./template/marin_chibi) | [GIF Preview](./asset/preview overlay/marin-chibi-overlay.png)  
  *(Tambahkan link/gambar preview Marin di sini)*

---

## 🚀 Cara Pemasangan di Tako / Saweria
Ikuti langkah-langkah mudah di bawah ini untuk memasang template ke OBS Studio:

1. **Pilih Template:** Masuk ke folder template overlay pilihanmu di repositori ini.
2. **Salin Code:** Buka file `index.html` dari template tersebut, lalu salin seluruh isi kodenya.
3. **Masukkan ke Tako:** Buka dashboard **Tako / Saweria** kamu, masuk ke bagian **Overlay / Custom HTML CSS**, lalu tempel (*paste*) kode yang sudah disalin ke dalam editor.
4. **Pasang di OBS:** Salin URL Widget dari Tako, lalu tambahkan ke OBS Studio sebagai **Browser Source**. Atur ukuran properti *width* dan *height* sesuai kebutuhan stream kamu.

---

## ⚙️ Cara Kustomisasi
Kamu bisa menyesuaikan tampilan overlay dengan mudah langsung di dalam kode HTML/CSS:
* **Ukuran Font:** Ubah nilai pada properti `font-size` di bagian `.text` atau `.message`.
* **Warna Font:** Sesuaikan variabel warna di bagian `:root` (seperti `--jacket-brown` atau `--scarf-red`) dengan kode warna HEX pilihanmu.
* **Jenis Font:** Ubah tautan `@font-face` atau nama properti `font-family` sesuai selera.

---

## ☕ Support & Commission
Suka dengan template-template ini dan ingin mendukung pengembangan proyek agar terus update? Kamu bisa memberikan dukungan melalui traktir kopi atau donasi di bawah ini:

* **Link Donasi Saweria/Tako:** [Klik di sini untuk Donasi](https://saweria.co/shiroinekoo)
* **Scan QRIS:**  
  *(Letakkan gambar QRIS kamu di sini)*

---

## 📄 Lisensi
Proyek ini bersifat *open-source* dan bebas digunakan oleh siapa saja untuk keperluan live streaming di bawah [Lisensi MIT](./LICENSE). Silakan gunakan, modifikasi, dan bagikan ulang!
