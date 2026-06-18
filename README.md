# Analisis Modularitas Arsitektur Moodle

Kode dan data pendukung untuk paper *"Analisis Modularitas Moodle 
Berdasarkan Struktur Direktori dan Dependensi File"* (Jurnal Pustaka Data).

## Deskripsi
Analisis statis ringan berbasis regular expression untuk mengekstrak 
dependensi tingkat file pada Moodle dan mengevaluasi modularitasnya 
menggunakan Information Flow Metrics (Fan-In, Fan-Out, Instability, Cohesion).

## Objek Penelitian
- Moodle 5.3dev (Build 20260616, commit 08d193e8f)
- ~50.028 file PHP, 1.247.184 baris relasi

## Struktur Repositori
- `notebooks/` : Notebook Fase 1 (data mining) & Fase 2 (analisis arsitektur)
- `data/`      : Dataset dependensi & rapor metrik modularitas (CSV)

## Cara Menjalankan
1. Buka notebook di Google Colab.
2. Jalankan Fase 1 (kloning + ekstraksi), lalu Fase 2 (pemodelan + metrik).
3. Dependensi: Python 3, pandas, networkx.

## Penulis
Arzaki Muhamad Fadil, Muhammad Fachri Hafizh Saleh
Pembimbing: Muhammad Ainul Yaqin — UIN Maulana Malik Ibrahim Malang

## Lisensi
MIT License (lihat file LICENSE)
