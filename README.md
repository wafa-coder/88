# 🥭 Deteksi Gambar Buah Mangga

Sistem deteksi otomatis buah mangga menggunakan computer vision dan machine learning.

## Deskripsi Proyek

Proyek ini adalah implementasi sistem deteksi objek yang dirancang khusus untuk mengenali dan mengidentifikasi buah mangga dalam gambar. Sistem ini menggabungkan teknologi Python untuk pemrosesan gambar dan machine learning dengan antarmuka web HTML untuk kemudahan penggunaan.

### Fitur Utama
- 🎯 Deteksi otomatis posisi buah mangga dalam gambar
- 📊 Klasifikasi kualitas atau tingkat kematangan mangga (jika ada)
- 🌐 Antarmuka web yang user-friendly
- 📁 Mendukung upload gambar dari berbagai format
- 🔍 Visualisasi hasil deteksi dengan bounding box

## Teknologi yang Digunakan

- **Backend**: Python
  - OpenCV (pemrosesan gambar)
  - TensorFlow / PyTorch (model deep learning)
  - Flask / FastAPI (API web)

- **Frontend**: HTML/CSS/JavaScript
  - Antarmuka upload gambar
  - Visualisasi hasil deteksi
  - Dashboard atau galeri hasil

## Struktur Direktori

```
88/
├── index.html          # Halaman utama aplikasi
├── app.py / main.py    # Backend Python
├── requirements.txt    # Dependencies Python
├── static/             # CSS, JavaScript, aset statis
├── models/             # Model machine learning (.h5, .pth, dll)
└── README.md           # Dokumentasi ini
```

## Cara Menjalankan

### Prerequisite
- Python 3.7+
- pip atau conda
- Browser modern

### Langkah-langkah

1. **Clone repositori:**
   ```bash
   git clone https://github.com/wafa-coder/88.git
   cd 88
   ```

2. **Instal dependensi Python:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Jalankan aplikasi:**
   ```bash
   python app.py
   # atau jika menggunakan Flask dengan development server
   flask run
   ```

4. **Buka di browser:**
   - Akses `http://localhost:5000` atau sesuai port yang ditampilkan

5. **Gunakan aplikasi:**
   - Upload gambar buah mangga
   - Sistem akan memproses dan menampilkan hasil deteksi
   - Lihat visualisasi dengan bounding box di sekitar mangga yang terdeteksi

## Contoh Penggunaan

1. Buka aplikasi web di browser
2. Klik tombol "Upload Gambar" atau drag-drop gambar
3. Tunggu proses deteksi selesai
4. Lihat hasil deteksi dengan mangga yang terberi highlight

## Kontribusi

Kami menerima kontribusi! Silakan:

1. Fork repositori ini
2. Buat branch fitur: `git checkout -b feature/nama-fitur`
3. Commit perubahan: `git commit -m "Tambah: deskripsi fitur"`
4. Push ke branch Anda: `git push origin feature/nama-fitur`
5. Buat Pull Request

## Kontak & Informasi

- **GitHub**: [@wafa-coder](https://github.com/wafa-coder)
- **Repositori**: [wafa-coder/88](https://github.com/wafa-coder/88)

## Lisensi

Lihat file LICENSE di repositori ini untuk informasi lisensi.

---

**Dibuat dengan ❤️ untuk deteksi mangga yang lebih baik**
