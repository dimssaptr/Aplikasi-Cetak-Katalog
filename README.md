# Aplikasi Cetak Katalog Induk & Label Perpustakaan 📚

Aplikasi berbasis web sederhana (HTML/JS/CSS) yang dirancang untuk membantu pustakawan dan pengelola perpustakaan dalam proses inventarisasi bahan pustaka.

Aplikasi ini berfokus pada kemudahan penggunaan dan presisi cetak, tanpa memerlukan instalasi software yang rumit.

🔗 **Link Demo Aplikasi:** [https://dimssaptr.github.io/Aplikasi-Cetak-Katalog/](https://dimssaptr.github.io/Aplikasi-Cetak-Katalog/)

---

## ✨ Fitur Utama

✅ **Client-Side Only**
Tidak perlu instalasi server (XAMPP/MySQL) atau koneksi database. Cukup buka file di browser (Chrome/Edge) dan langsung gunakan.

✅ **Auto-Layout & Custom Fields**
Format isian otomatis menyesuaikan template Kartu Induk standar. Kini dilengkapi fitur tambah **baris kustom (custom rows)** untuk kebutuhan data spesifik.

✅ **Smart Label (DDC Color)**
Warna pada Label Punggung otomatis berubah sesuai kelas utama DDC (Misal: 600 = Merah, 000 = Coklat, dst), memudahkan 
visualisasi rak (Shelving).

✅ **Barcode Generator**
Menghasilkan Barcode standar **Code 128** yang dapat dibaca oleh scanner umum.

✅ **Flexible Print Modes**
Tersedia berbagai opsi cetak sesuai kebutuhan:
* **Kartu Induk** (Standar 12.5 x 7.5 cm)
* **Label Punggung + Barcode** (Gabungan)
* **Label Saja** atau **Barcode Saja**

---

## 🚀 Cara Penggunaan

1.  Kunjungi link aplikasi atau unduh repositori ini.
2.  **Input Data**: Isi metadata buku pada form yang tersedia (Judul, Penulis, DDC, dll). Anda juga bisa menggunakan fitur **Import CSV** jika memiliki data dari SLiMS.
3.  **Generate**: Klik tombol "Generate" untuk melihat preview.
4.  **Cetak**: Klik tombol Cetak / Print.

### 🖨️ Pengaturan Printer (Penting!)
Agar ukuran kartu dan label presisi (tidak terpotong/kekecilan), pastikan pengaturan berikut saat jendela Print muncul:

* **Paper Size**: A4
* **Margins**: Pilih **None** atau **Minimum** (Jangan Default).
* **Scale**: Default / 100%.
* **Background Graphics**: **Centang/Aktifkan** (Agar warna strip klasifikasi tercetak).

---

## 👨‍💻 Tentang Pengembang

Aplikasi ini dikembangkan sebagai alat bantu praktikum dan operasional perpustakaan agar lebih efisien.

**Dimas Saputra**
Mahasiswa Prodi Perpustakaan dan Sains Informasi
Universitas Pendidikan Indonesia (UPI)

---
*Open Source Project - Silakan dikembangkan lebih lanjut.*
