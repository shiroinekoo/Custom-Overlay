# 🎌 Custom Alert Overlay for Tako

Koleksi template Custom Alert Overlay interaktif dan estetik untuk platform streaming Tako atau Saweria. Buat tampilan live stream kamu jadi makin menarik, interaktif, dan sedap dipandang mata oleh para penonton!

Ingin request karakter atau tema anime tertentu? Yuk, ajukan ide kamu melalui [**Pull Request**](https://github.com/shiroinekoo/Tako-Overlay/pulls)

---

## 🖼️ Galeri Preview Overlay
Berikut adalah beberapa pilihan template overlay anime yang sudah tersedia dan siap pakai:

* [**Mikasa Ackerman (Attack on Titan)**](https://github.com/shiroinekoo/Tako-Overlay/blob/main/template/mikasa_chibi)  
  <img src="https://raw.githubusercontent.com/shiroinekoo/Tako-Overlay/main/asset/preview%20overlay/mikasa-chibi-overlay.png" width="100%" alt="Mikasa Overlay Preview">

* [**Marin Kitagawa (My Dress-Up Darling)**](https://github.com/shiroinekoo/Tako-Overlay/blob/main/template/marin_chibi)  
  <img src="https://github.com/shiroinekoo/Tako-Overlay/blob/main/asset/preview%20overlay/marin-chibi-overlay.png" width="100%" alt="Marin Overlay Preview">

---

## 🚀 Cara Pemasangan
Ikuti langkah-langkah mudah di bawah ini untuk memasang template ke OBS Studio:

1. **Pilih Template:** Buka folder [template](https://github.com/shiroinekoo/Tako-Overlay/tree/main/template) overlay yang kamu inginkan di repositori ini.
2. **Salin Kode:** Masuk ke file `index.html` dari template pilihanmu, lalu **salin seluruh isi kodenya**.
3. **Buka Dashboard Tako:** Buka [Tako](https://tako.id/c/NavLeb/overlay/alert) Lalu pilih Tema-> Custom HTML.
4. **Tempel Kode:** Tempelkan kode yang sudah disalin ke dalam editor yang tersedia, lalu simpan (*Save*).
5. **Pasang di OBS:** Salin URL widget dari Tako, lalu tambahkan sebagai **Browser Source** di OBS Studio kamu.

---

## ⚙️ Cara Kustomisasi (Pengaturan Lanjutan)
Kamu bisa dengan mudah mengubah tampilan teks, warna, hingga jenis font langsung di dalam kode HTML/CSS pada bagian `<style>`:

* **Mengubah Ukuran Font:** Cari bagian `.text` atau `.message` di dalam kode, lalu ubah nilai pada `font-size: 24px;` sesuai selera.
* **Mengubah Warna Font / Aksen:** Cari bagian `:root` di baris atas kode CSS untuk mengganti variabel warna utama (seperti `--jacket-brown` atau `--scarf-red`) dengan kode warna HEX pilihanmu (contoh: `#ff69b4`).
* **Mengubah Jenis Font:** Kamu bisa mengganti tautan `@font-face` atau nama font di properti `font-family` dengan font pilihanmu sendiri.

---

## ☕ Support
Suka dengan template-template ini dan ingin mendukung pengembangan proyek agar terus update? Kamu bisa memberikan dukungan melalui traktir kopi atau donasi di bawah ini:

* **Tautan Donasi:** [Klik di sini untuk Donasi / Traktir](https://saweria.co/shiroinekoo) *(Ganti dengan link saweria/tako kamu)*
* **Atau Scan QRIS:**  
  *(Letakkan gambar QRIS kamu di sini atau buat folder asset)*

---

## 📄 License
Proyek ini bersifat *open-source* dan bebas digunakan oleh siapa saja untuk keperluan live streaming di bawah lisensi [MIT](./LICENSE). Silakan gunakan, modifikasi, dan bagikan ulang sesuka hati!
