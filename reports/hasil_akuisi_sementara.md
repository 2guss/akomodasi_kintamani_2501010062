# Hasil Akuisisi Data Akomodasi Kecamatan Kintamani

## 1. Hasil akuisisi

Akuisisi melalui OpenStreetMap (OSM) menghasilkan 32 baris data akomodasi.
Data hasil olahan disimpan dalam format CSV, sedangkan visualisasi koordinat
dibuat menggunakan Folium.

## 2. Distribusi jenis akomodasi

| Jenis | Jumlah |
|---|---:|
| Hotel | 16 |
| Guest house | 9 |
| Hostel | 4 |
| Chalet | 2 |
| Motel | 1 |
| **Total** | **32** |

Hotel merupakan kategori terbanyak, yaitu 16 baris, sedangkan motel berjumlah
1 baris.

## 3. Pemeriksaan kualitas data

| Indikator | Hasil |
|---|---:|
| Total baris | 32 |
| Duplikat berdasarkan osm_type dan osm_id | 0 |
| Nama kosong | 1 |
| Latitude kosong | 0 |
| Longitude kosong | 0 |

Pemeriksaan menemukan satu baris tanpa nama. Data tersebut perlu diperiksa lebih
lanjut dan tidak boleh diberi nama berdasarkan tebakan. Tidak ditemukan
duplikat berdasarkan pasangan osm_type dan osm_id.

## 4. Perbandingan indikatif dengan BPS

Publikasi BPS Kecamatan Kintamani Dalam Angka 2023 memuat data tahun 2021
dengan 19 hotel dan 39 penginapan, total 58 sarana akomodasi.

Perbandingan jumlah baris OSM dengan total BPS:
32 / 58 × 100% = 55,17%.

Angka 55,17% merupakan rasio perbandingan jumlah, bukan bukti bahwa OSM telah
mencakup tepat 55,17% seluruh akomodasi. Tahun data dan definisi kategori
antara kedua sumber berbeda, sehingga hasilnya harus ditafsirkan secara hati-hati.

## 5. Verifikasi sampel

Pemeriksaan manual hingga 10 sampel: BELUM DILENGKAPI.
Jumlah sesuai, tidak sesuai, dan belum dapat dipastikan harus diisi setelah
sampel benar-benar diperiksa dan bukti sumber dicatat.

## 6. Keterbatasan

Peta menampilkan titik koordinat, tetapi visualisasi tanpa latar peta dan
pemeriksaan batas administratif belum cukup untuk memastikan seluruh titik
berada di dalam Kecamatan Kintamani. Kualitas data juga perlu dinilai dari
hasil verifikasi manual.