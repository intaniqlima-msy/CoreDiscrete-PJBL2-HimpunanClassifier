# CoreDiscrete-PJBL2-HimpunanClassifier

Sistem Klasifikasi Data dengan Himpunan (PJBL-2, Matematika Diskrit).
Kelompok **Core Discrete**, dosen pengampu Ully Muzakir, S.MT.

Aplikasi web Python + Streamlit yang memodelkan kategori data sebagai himpunan, lalu menghitung operasinya otomatis.

## Fitur
- Memuat dataset contoh atau unggah file CSV (kolom `item,kategori`).
- Operasi himpunan: union, irisan, selisih, komplemen terhadap semesta U.
- Diagram Venn otomatis untuk 2 atau 3 himpunan.
- Prinsip Inklusi-Eksklusi (PIE) beserta verifikasi dengan union langsung.
- Tabel 8 daerah untuk 3 himpunan, kalkulator PIE, dan padanan operasi SQL (SQLite).

## Cara menjalankan
```bash
pip install -r requirements.txt
streamlit run app.py
```

## Dataset
- `dataset1_ekstrakurikuler.csv`: Basket, Programming, Musik (semesta 11 elemen).
- `dataset2_pelanggan_toko_online.csv`: Buku, Elektronik, Fashion (semesta 10 elemen).

## Tautan
- Video demo: https://youtu.be/P9JEttIpkuA
- Deployment: https://corediscrete-pjbl2-himpunanclassifier-m7kqdst9igtgteuhpqpy6x.streamlit.app

## Anggota
| NIM | Nama |
|---|---|
| 25210251 | M. Fahril Kal Kausar |
| 25210231 | Mirja Rahmat |
| 25210254 | Intan Iqlima |
| 25210272 | Nur 'Amasari |
