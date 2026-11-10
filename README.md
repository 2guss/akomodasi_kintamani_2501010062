# Akuisisi Data Akomodasi Kecamatan Kintamani

## Identitas
- Nama: Putu Agus Arta Wiguna
- NIM: 2501010062
- Institusi: INSTIKI
- Program Studi: Informatika
- Mata Kuliah: BIFP-243 Akuisisi dan Manajemen Data

## Tujuan
Praktik ini bertujuan mengakuisisi dan mengelola data akomodasi
di Kecamatan Kintamani menggunakan OpenStreetMap melalui Overpass API.

## Sumber Data
- Sumber utama: OpenStreetMap (OSM).
- API: Overpass API.
- Sumber pembanding: Kecamatan Kintamani Dalam Angka 2025,
  Badan Pusat Statistik.
- Tahun data pembanding BPS: 2024.
- Tanggal akuisisi: 10 November 2026.

## Metode Akuisisi
Data diperoleh menggunakan query Overpass API dengan batas
administratif Kecamatan Kintamani dan tag tourism:
hotel, guest_house, hostel, motel, apartment, dan chalet.

Data mentah disimpan dalam format JSON tanpa perubahan.
Selanjutnya data diratakan menjadi CSV untuk analisis dan
pemeriksaan kualitas.

Query lengkap tersedia pada:
docs/query_overpass.txt

## Ringkasan Dataset
Jumlah objek hasil akuisisi: 32 objek.

Rincian:
- Hotel: 16
- Guest house: 9
- Hostel: 4
- Chalet: 2
- Motel: 1

## Pemeriksaan Kualitas Data
- Duplikasi berdasarkan osm_type dan osm_id: 0.
- Data tanpa nama: 1 objek.
- Koordinat kosong: 0.
- Data desa kosong: 32 objek.
- Verifikasi manual: 10 sampel.

Hasil pemeriksaan tersedia di folder docs.

## Perbandingan dengan BPS
Perbandingan dilakukan menggunakan data BPS tahun 2024.
Angka BPS menunjukkan jumlah desa yang memiliki fasilitas
akomodasi, bukan jumlah unit usaha akomodasi.

Oleh karena itu, persentase perbandingan OSM dan BPS
hanya merupakan rasio indikatif dan bukan ukuran
kelengkapan data OSM.

## Etika dan Lisensi
- Tidak melakukan scraping Google Maps.
- Tidak melakukan scraping situs Online Travel Agency.
- Tidak mengumpulkan nomor telepon atau email untuk dataset.
- Permintaan API dilakukan secara terbatas.
- Data mentah disimpan tanpa perubahan.
- Atribusi: © OpenStreetMap contributors.
- Data OpenStreetMap tersedia di bawah lisensi ODbL.

Informasi lisensi:
https://www.openstreetmap.org/copyright

## Struktur Folder
- data/raw: data mentah JSON.
- data/interim: data hasil perataan CSV.
- notebooks: notebook proses akuisisi dan analisis.
- docs: dokumentasi, provenance, dan pemeriksaan data.
- reports: laporan PDF dan peta persebaran.

## Cara Menjalankan Ulang
1. Buka notebook akuisisi di Google Colab.
2. Jalankan sel secara berurutan.
3. Pastikan koneksi internet tersedia.
4. Jika melakukan akuisisi ulang, perhatikan etika
   penggunaan Overpass API dan hindari permintaan berulang.
5. Hasil proses disimpan pada struktur folder proyek ini.

## Catatan Keterbatasan
OpenStreetMap merupakan data kolaboratif sehingga tidak
menjamin seluruh akomodasi telah terdaftar atau diperbarui.
Sebagian atribut tidak tersedia dan seluruh data desa
belum terisi. Verifikasi sampel yang dilakukan merupakan
pemeriksaan konsistensi informasi pada objek OSM, bukan
validasi lapangan independen.