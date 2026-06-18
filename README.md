# MindFlow

Aplikasi asisten virtual berbasis konsol untuk membantu keseimbangan emosional dan produktivitas pengguna. Dibuat sebagai Tugas Besar mata kuliah Algoritma dan Pemrograman 2, Program Studi Informatika, Universitas Telkom.

## Deskripsi

MindFlow membantu pengguna mencatat suasana hati harian, mengelola daftar tugas, dan menyimpan riwayat percakapan dalam satu sistem yang terintegrasi. Aplikasi ini ditujukan untuk mahasiswa, pekerja kantoran, dan siapa pun yang ingin menjaga kesejahteraan mental sekaligus memantau produktivitas hariannya.

## Fitur

- **Kelola Catatan Mood** — tambah, lihat, ubah, dan hapus data suasana hati (tanggal, skor emosi 1–10, dan deskripsi perasaan).
- **Kelola Tugas Harian** — tambah, lihat, ubah, hapus, dan tandai selesai untuk tugas harian (tanggal, nama tugas, prioritas 1–5, durasi pengerjaan, dan status).
- **Riwayat Percakapan** — tambah, lihat, dan hapus catatan riwayat percakapan harian.
- **Pencarian Data** — menggunakan Sequential Search (mood berdasarkan tanggal, tugas berdasarkan nama) dan Binary Search (mood berdasarkan perasaan, tugas berdasarkan prioritas dan durasi).
- **Pengurutan Data** — menggunakan Selection Sort (berdasarkan prioritas) dan Insertion Sort (berdasarkan durasi).
- **Statistik** — menampilkan tren suasana hati mingguan dan tingkat penyelesaian tugas harian.

## Cara Menjalankan

Pastikan [Go](https://go.dev/dl/) sudah terpasang di komputer Anda, lalu jalankan:

```bash
git clone https://github.com/alifb012008-jpg/projek-apk-mindflof.git
cd projek-apk-mindflof
go run main.go
```

Program akan menampilkan menu utama di terminal. Pilih nomor menu sesuai fitur yang ingin digunakan.

## Struktur Data

Program menggunakan tiga struct utama yang disimpan dalam array statis berukuran 1000 elemen sebagai variabel global:

| Struct     | Atribut                                                              |
|------------|-----------------------------------------------------------------------|
| `mood`     | Hari, Bulan, Tahun, SkorEmosi, Perasaan                                |
| `tugas`    | Tanggal, NamaTugas, Prioritas, Durasi, Selesai                         |
| `riwayat`  | Tanggal, Pesan, Catatan                                                |

## Tim Pengembang

| Nama | NIM |
|------|-----|
| Raymundus Alif E Beoang | 108072500094 |
| Umi Habibah | 108072500117 |

Dosen Pengampu: Kharisma Monika Dian Pertiwi, S.Kom.

## Mata Kuliah

Algoritma dan Pemrograman 2 — Program Studi Informatika, Fakultas Informatika, Universitas Telkom.
