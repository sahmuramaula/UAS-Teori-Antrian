# UAS-Teori-Antrian
# UAS Teori Antrian

Notebook ini dibuat sebagai tugas UAS mata kuliah **Teori Antrian**, yang membahas analisis sistem antrian menggunakan data nyata dari beberapa restoran atau kafe. Notebook ini memodelkan sistem antrian **multi channel single server** (M/M/s) dan menampilkan visualisasi antrian.

## 📄 Deskripsi Singkat

Notebook ini memuat analisis data antrian dari tiga tempat berbeda:

- **Starbucks**
- **Allio**
- **Nelayan**

Data di masing-masing file CSV (misalnya `Starbucks.csv`, `Allio.csv`, `Nelayan.csv`) dianalisis untuk memahami karakteristik antrian, termasuk:

- Rata-rata kedatangan pelanggan
- Rata-rata layanan
- Jumlah server
- Waktu tunggu rata-rata
- Probabilitas sistem sibuk

Selain itu, notebook juga memvisualisasikan sistem antrian dalam bentuk diagram sederhana.

## 🧑‍💻 Struktur Notebook

Notebook terdiri dari beberapa bagian utama:

1. **Import Library**
   - `pandas` untuk pengolahan data
   - `matplotlib` untuk visualisasi

2. **Membaca Data**
   - Membaca data dari file CSV masing-masing restoran.

3. **Visualisasi Antrian**
   - Diagram alur antrian (misalnya M/M/3).

4. **Perhitungan Teori Antrian**
   - Menghitung parameter antrian: laju kedatangan (λ), laju layanan (μ), utilization, Lq (jumlah rata-rata pelanggan di antrian), Wq (waktu tunggu rata-rata), dsb.

5. **Analisis Kesimpulan**
   - Membahas interpretasi hasil perhitungan untuk setiap restoran.

## 💾 Cara Menjalankan

1. Pastikan sudah menginstal dependensi berikut:
   ```bash
   pip install pandas matplotlib
   ```
2. Letakkan file CSV (`Starbucks.csv`, `Allio.csv`, `Nelayan.csv`) di direktori yang sama dengan notebook.
3. Jalankan seluruh sel notebook secara berurutan.

## 📊 Output

- Tampilan tabel data awal masing-masing restoran.
- Visualisasi diagram antrian.
- Hasil perhitungan performa antrian, seperti waktu tunggu rata-rata, panjang antrian, probabilitas tidak dilayani, dsb.

## 📚 Teori yang Digunakan

Notebook ini menggunakan model antrian **M/M/s**, yaitu:

- **M**: distribusi kedatangan Poisson
- **M**: distribusi layanan eksponensial
- **s**: jumlah server lebih dari satu

## ✍️ Penulis

- **Nama:** [Isi Nama Mahasiswa]
- **NIM:** [Isi NIM]
- **Mata Kuliah:** Teori Antrian
- **Dosen Pengampu:** [Isi Nama Dosen]

---
