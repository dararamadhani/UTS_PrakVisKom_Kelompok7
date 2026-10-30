# Live Webcam Drawing Using OpenCV

## Deskripsi
**Live Webcam Drawing Using OpenCV** adalah proyek *computer vision* yang memungkinkan pengguna menggambar secara langsung melalui webcam. Proyek ini dikembangkan menggunakan Python dengan memanfaatkan OpenCV dan MediaPipe untuk mendeteksi objek berwarna serta gerakan tangan.

Proyek ini memiliki dua pendekatan, yaitu pelacakan objek berdasarkan warna dan menggambar menggunakan gerakan jari telunjuk melalui deteksi tangan.

## Fitur
- Deteksi dan pelacakan objek berdasarkan warna menggunakan HSV.
- Deteksi tangan dan posisi ujung jari telunjuk menggunakan MediaPipe.
- Menggambar secara langsung melalui webcam.
- Gestur jempol ke atas untuk menjeda proses menggambar.
- Pengaturan ketebalan garis menggunakan keyboard.
- Fitur menghapus coretan pada kanvas.

## Teknologi dan Library
- **Python** — bahasa pemrograman.
- **OpenCV** — memproses video webcam dan menggambar garis.
- **NumPy** — mengelola data gambar dan membuat kanvas.
- **MediaPipe** — mendeteksi tangan dan landmark jari.

## Cara Menjalankan
1. Pastikan Python dan library yang dibutuhkan sudah terpasang.
2. Siapkan berkas model `hand_landmarker.task` untuk deteksi tangan.
3. Buka notebook proyek menggunakan Jupyter Notebook.
4. Jalankan setiap bagian kode sesuai urutan.
5. Pastikan webcam dapat diakses oleh program.

## Kontrol Keyboard
| Tombol | Fungsi |
|---|---|
| `1` | Mengatur ketebalan garis menjadi 3 piksel |
| `2` | Mengatur ketebalan garis menjadi 5 piksel |
| `3` | Mengatur ketebalan garis menjadi 10 piksel |
| `4` | Mengatur ketebalan garis menjadi 15 piksel |
| `C` | Menghapus coretan |
| `Q` | Menghentikan program |

## Tujuan Proyek
Proyek ini bertujuan mempelajari penerapan visi komputer, pengolahan citra, deteksi warna, pelacakan objek, dan pengenalan gestur tangan untuk membangun aplikasi menggambar secara *real-time*.

## Pengembang
Dara Ramadhani (2408107010028)
Dedek Saleha (2408107010023)
Illiza Khairamisa (2408107010017)

Proyek ini dibuat sebagai bagian dari pembelajaran mata kuliah **Praktikum Visi Komputer**.

