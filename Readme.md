# Dataset Pidana Khusus PN SERANG 2022-2023

[![N|Solid](https://i.ibb.co/yV97wyP/logo.png)](https://nodesource.com/products/nsolid)

Hasil scrape PDF hasil putusan pidana khusus narkotika dan psikotropika PN Serang pada tahun 2022-2023. Jumlah file PDF yang berhasil terkumpul sebanyak 50 file.

## Deskripsi Proyek
Proyek ini bertujuan untuk memenuhi tugas Temu Kembali Informasi mengenai pengumpulan data dari putusan pidana khusus narkotika dan psikotropika yang dikeluarkan oleh Pengadilan Negeri Serang selama tahun 2022-2023. Tujuan analisis ini adalah untuk memberikan gambaran dan wawasan mengenai tren, pola, dan keputusan hukum dalam kasus narkotika dan psikotropika.

## Metodologi Pengumpulan Data
- Jumlah File: 50 file PDF.
- Sumber Data: Pengadilan Negeri Serang.
- Periode: 2022-2023.
- Metode: Scraping data dari website resmi menggunakan teknik otomatisasi.
- Kriteria File: Hanya file yang berkaitan dengan putusan pidana narkotika dan psikotropika.

## Proses Scraping
Alat Scraping: Python dengan libraries BeautifulSoup, requests, lxml, urllib, re, io, pandas, dan concurrent.futures
>
Langkah-langkah:
- Menggunakan URL dari website Pengadilan Negeri yang menyediakan data putusan, khususnya untuk kasus narkotika dan psikotropika di PN Serang pada tahun 2022-2023
- Menerapkan requests dan BeautifulSoup untuk menguraikan konten halaman web dan menemukan link yang mengarah ke file PDF kemudian menggunakan urllib untuk mengunduh file PDF dari link yang ditemukan
- Menyimpan file PDF yang telah diunduh ke direktori yang telah ditentukan menggunakan fungsi 'create_path'.
- Menggunakan library io dan high_level untuk ekstraksi teks dari file PDF dan menerapkan fungsi clean_text untuk menghilangkan teks yang tidak relevan atau format yang tidak diperlukan.
- Menyimpan data yang terstruktur ke dalam file CSV untuk analisis lebih lanjut

## Struktur Repositori
Repositori ini berisi :
- Dataset
Dataset sudah dikompress dalam format file .zip
- Overview
Overview berisi ringkasan putusan dari hasil scraping, Terdapat 4 kolom yaitu Nomor Pidana, Lembaga Peradilan, Bukti, dan Amar Putusan dengan format file xlsx


- Readme.md

## Kontributor
- Clarissa Sanindita Reikisyifa (202010370311232)
- Alviatul Nazila (202010370311293)

**Universitas Muhammadiyah Malang** - 2023