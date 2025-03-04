# 🚲 Bike Sharing Dashboard

## 📌 Deskripsi
Dashboard interaktif yang menganalisis pola peminjaman sepeda berdasarkan cuaca, waktu, dan faktor lainnya. Dibangun menggunakan Python dan Streamlit untuk visualisasi data yang menarik dan mudah dipahami.

## 🚀 Cara Menjalankan
### 1. Pastikan Python dan Streamlit sudah terinstal
Jika belum, instal dengan perintah berikut:
```sh
pip install streamlit pandas numpy matplotlib seaborn
```

### 2. Install dependensi tambahan
Jalankan perintah berikut untuk menginstal library yang dibutuhkan:
```sh
pip install -r requirements.txt
```

### 3. Jalankan dashboard
Gunakan perintah berikut untuk menjalankan dashboard Streamlit:
```sh
streamlit run dashboard/dashboard.py
```

### 4. Akses dashboard
Setelah dijalankan, dashboard akan terbuka secara otomatis di browser.

## 📊 Fitur
- **Visualisasi Data**: Menampilkan pola peminjaman sepeda berdasarkan berbagai faktor.
- **Analisis Waktu**: Tren peminjaman berdasarkan jam, hari, dan musim.
- **Analisis Cuaca**: Pengaruh cuaca terhadap jumlah peminjaman.
- **Filter Interaktif**: Memungkinkan eksplorasi data dengan filter dinamis.

## 📂 Struktur Folder
```
submission/
├───dashboard/
│   └───dashboard.py     # Kode utama untuk dashboard
├───data/
│   ├───day.csv          # Dataset harian
│   └───hour.csv         # Dataset per jam
├───notebook.ipynb       # Notebook analisis data
├───requirements.txt     # Daftar library yang digunakan
└───README.md            # Panduan menjalankan proyek
```

## 🌍 Deployment (Opsional)
Jika ingin mendepoy ke Streamlit Cloud:
1. Push kode ke repository GitHub.
2. Buka [Streamlit Cloud](https://share.streamlit.io/) dan buat aplikasi baru.
3. Hubungkan ke repository, pilih `dashboard/dashboard.py` sebagai entry point.
4. Setelah proses selesai, salin link dan tambahkan ke file `url.txt`.

## 👤 Kontributor
**Nama Anda** – [LinkedIn](https://www.linkedin.com/in/dewi-puspita-241517272/)

---

Selamat mengeksplorasi data! 🚀

