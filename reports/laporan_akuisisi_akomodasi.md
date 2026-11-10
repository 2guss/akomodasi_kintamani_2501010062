# LAPORAN AKUISISI DATA AKOMODASI
## Kecamatan Kintamani, Kabupaten Bangli, Bali

**Nama:** [Isi nama lengkap]
**NIM:** 2501010062
**Mata Kuliah:** BIFP-243 Akuisisi dan Manajemen Data

## 1. Tujuan
Akuisisi ini bertujuan mengumpulkan dan memeriksa data akomodasi di Kecamatan
Kintamani menggunakan OpenStreetMap (OSM), kemudian membandingkannya dengan
sumber statistik resmi dan mendokumentasikan kualitas serta keterbatasan data.

## 2. Sumber dan Metode
Sumber data utama adalah OpenStreetMap melalui Overpass API.
Data mentah disimpan dalam format JSON sebelum diolah menjadi CSV.
Atribusi: © OpenStreetMap contributors.

Query, waktu akuisisi, dan berkas data mentah didokumentasikan dalam folder docs
dan data/raw. Data hasil olahan disimpan di data/interim.

## 3. Hasil Akuisisi
Jumlah baris CSV: [Isi dari hasil Colab]
Jumlah titik yang divisualisasikan: 32 (berdasarkan keluaran peta).
Jumlah data unik setelah pemeriksaan duplikat: [Isi hasil pemeriksaan]

Distribusi jenis akomodasi:
[Masukkan tabel jumlah berdasarkan jenis]

## 4. Kualitas Data
Duplikat berdasarkan osm_type dan osm_id: [Isi hasil]
Nama kosong: [Isi hasil]
Latitude kosong: [Isi hasil]
Longitude kosong: [Isi hasil]

Jelaskan temuan aktual dan tindakan yang dilakukan tanpa menghapus atau
mengubah data mentah.

## 5. Perbandingan dengan Statistik Resmi
Gunakan publikasi BPS yang relevan dan catat tahun data serta kategori yang
digunakan. Pastikan kategori OSM tidak dianggap sama persis dengan kategori BPS
jika definisinya berbeda.

Jumlah menurut BPS: [Cantumkan angka dan tahun dari sumber yang diperiksa]
Jumlah hasil OSM: [Isi angka aktual]
Persentase perbandingan: [Isi dari perbandingan yang telah dihitung]

## 6. Verifikasi Sampel
Pilih hingga 10 sampel dan periksa secara manual menggunakan sumber yang diizinkan.
Laporkan jumlah yang sesuai, tidak sesuai, dan belum dapat dipastikan berdasarkan
bukti yang benar-benar diperiksa.

## 7. Visualisasi
Sisipkan peta akomodasi yang telah dibuat. Jelaskan bahwa titik menunjukkan
koordinat yang tersedia dan belum tentu semuanya telah dipastikan berada di
dalam batas administratif Kecamatan Kintamani.

## 8. Etika dan Keterbatasan
Atribusi sumber OSM dicantumkan. Data kontak pribadi tidak dikumpulkan.
Verifikasi manual dilakukan tanpa scraping otomatis situs pemesanan akomodasi.
Bahas keterbatasan kelengkapan, nama kosong, koordinat, perbedaan kategori,
dan perbedaan tahun antara sumber jika ditemukan.

## 9. Refleksi (150–200 kata)
[Tulis refleksi pribadi mengenai proses akuisisi, kendala teknis, kualitas data,
etika penggunaan data, dan hal yang perlu ditingkatkan.]