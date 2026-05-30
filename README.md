# PERBANDINGAN-ASIMETRIS-DAN-SIMETRIS
# UTS Kriptografi: Komparasi Performa Algoritma Simetris dan Asimetris

Repositori ini berisi *source code* Python yang dibuat untuk memenuhi tugas Ujian Tengah Semester (UTS) mata kuliah Kriptografi. Program ini bertujuan untuk menguji, mengukur, dan membandingkan performa antara dua metode enkripsi utama, yaitu **Kriptografi Simetris (AES via modul Fernet)** dan **Kriptografi Asimetris (RSA 2048-bit)**.

## Deskripsi Program
Skrip Python ini akan meminta pengguna untuk memasukkan teks (pesan) secara interaktif. Setelah teks diinput, program akan melakukan proses enkripsi dan dekripsi menggunakan kedua metode tersebut secara bergantian, lalu menghitung:
1. **Waktu Komputasi (Kecepatan):** Mengukur waktu spesifik yang dibutuhkan (dalam detik) untuk mengenkripsi dan mendekripsi pesan.
2. **Ukuran Ciphertext:** Menghitung jumlah *byte* yang dihasilkan setelah teks dienkripsi.

## Persyaratan (Prerequisites)
Sebelum menjalankan program ini, pastikan Anda telah menginstal Python 3.x dan *library* `cryptography`. Anda dapat menginstalnya menggunakan pip:

```bash
pip install cryptography
