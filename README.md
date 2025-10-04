# Voting-Sistem-Pemilihan-Ketua-OSIS-Baru
Voting Sistem Pemilihan Ketua OSIS Baru

---

# 🗳️ Website Voting OSIS

Website sederhana untuk melakukan **pemilihan ketua & wakil OSIS** secara online. Proyek ini dibuat menggunakan **HTML, CSS, dan JavaScript** dengan penyimpanan data di **LocalStorage** (tanpa database server).

---

## ✨ Fitur

* 📌 **Pendaftaran Kandidat**
  Admin dapat menambahkan pasangan calon ketua & wakil OSIS dengan foto.
* 📌 **Voting Online**
  Siswa dapat memilih pasangan calon yang tersedia.
* 📌 **Hasil Voting**
  Hasil suara ditampilkan secara real-time dengan jumlah perolehan suara tiap pasangan.
* 📌 **Pemilihan Ulang (Seri)**
  Jika terjadi hasil seri, sistem hanya menampilkan kandidat seri untuk dipilih kembali.
* 📌 **Mudah Digunakan**
  Hanya perlu browser, tanpa instalasi server/database.

---

## 📂 Struktur Folder

```
/osis-voting
│── index.html          # Halaman utama / home
│── pendaftaran.html    # Halaman pendaftaran kandidat
│── vote.html           # Halaman voting & hasil
│── style.css           # File CSS untuk styling
│── script.js           # File JavaScript utama
│── /assets             # Folder gambar kandidat / icon
│── README.md           # Dokumentasi proyek
```

---

## 🚀 Cara Menjalankan

1. **Clone repositori ini**:

   ```bash
   git clone https://github.com/username/osis-voting.git
   ```
2. **Masuk ke folder proyek**:

   ```bash
   cd osis-voting
   ```
3. **Buka file `index.html` di browser**
   Tidak perlu server tambahan, cukup buka di Chrome/Edge/Firefox.

---

## 🔧 Teknologi yang Digunakan

* **HTML5**
* **CSS3**
* **JavaScript (Vanilla)**
* **LocalStorage** (penyimpanan data di browser)

---

## 🛠️ Pengembangan

Jika ingin mengembangkan lebih lanjut:

* Ganti LocalStorage dengan **Firebase / MySQL + PHP / Node.js** agar data tersimpan online.
* Tambahkan **login system** untuk memverifikasi siswa.
* Tambahkan **chart** untuk visualisasi hasil (misalnya pakai Chart.js).

---

## 📜 Lisensi

Proyek ini bebas digunakan untuk keperluan sekolah.
Lisensi: **MIT License**

---
