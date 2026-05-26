# 2303010082-MUHAMMADFAIZFAHRUROZI

## Informasi Pribadi

* **NIM** : 2303010082
* **Nama** : Muhammad Faiz Fahrurozi
* **Kelas** : D

---

## Informasi Ujian

* **Mata Kuliah** : Praktikum Algoritma dan Struktur Data
* **Semester** : Genap 2025/2026
* **Media Pengumpulan** : GitHub Pull Request
* **Bahasa Pemrograman** : C++
* **IDE** : Dev C++

---

# DAFTAR ISI

1. [Soal 1](#soal-1)
2. [Soal 2](#soal-2)

---

# SOAL 1 — Array & Struct

## Analisis

Pada soal pertama, saya menggunakan konsep **Array of Struct** untuk menyimpan dan mengelola data mahasiswa. Struct digunakan agar beberapa atribut data dapat disimpan dalam satu variabel terstruktur.

Data yang disimpan meliputi:

* NIM
* Nama Mahasiswa
* Semester
* IPK

Program menggunakan array dengan kapasitas maksimal 5 data mahasiswa.

---

## Pembahasan

Program meminta pengguna memasukkan jumlah mahasiswa, kemudian menginput seluruh data mahasiswa satu per satu.

Fitur yang dibuat pada program:

1. Menampilkan seluruh data mahasiswa dalam bentuk tabel.
2. Mencari mahasiswa dengan IPK tertinggi.
3. Menghitung rata-rata IPK seluruh mahasiswa.
4. Menampilkan mahasiswa berdasarkan semester yang dipilih pengguna.

Konsep Array of Struct mempermudah pengelolaan data yang memiliki banyak atribut dalam satu kesatuan.

---

# SOAL 2 — Stack & Queue

## Analisis

Pada soal kedua, digunakan implementasi struktur data:

* Stack
* Queue

Seluruh struktur data dibuat secara manual menggunakan array statis tanpa menggunakan library STL.

---

## Bagian A — Stack: Tumpukan Buku Kembali

### Pembahasan

Stack menggunakan konsep:

```text id="k1m7v3"
LIFO (Last In First Out)
```

Artinya data terakhir yang masuk akan menjadi data pertama yang keluar.

Pada program ini, stack digunakan untuk menyimpan data buku yang dikembalikan ke perpustakaan.

Fungsi yang digunakan:

* push()
* pop()
* peek()
* isEmpty()
* isFull()

Program mensimulasikan proses:

* menambahkan buku
* melihat buku teratas
* menghapus buku
* menampilkan isi stack

---

## Bagian B — Queue: Antrian Peminjaman

### Pembahasan

Queue menggunakan konsep:

```text id="q4v9m2"
FIFO (First In First Out)
```

Artinya data yang pertama masuk akan menjadi data pertama yang keluar.

Pada program ini, queue digunakan untuk simulasi antrian anggota perpustakaan yang ingin meminjam buku.

Fungsi yang digunakan:

* enqueue()
* dequeue()
* peek()
* isEmpty()
* isFull()

Program mensimulasikan:

* penambahan anggota antrian
* penghapusan antrian
* melihat antrian terdepan
* menampilkan isi queue

---

# Kesimpulan

Dari pengerjaan soal ini dapat dipahami bahwa:

* Struct mempermudah pengelolaan data mahasiswa yang memiliki banyak atribut.
* Array dapat digunakan untuk menyimpan banyak data dalam satu variabel.
* Stack cocok digunakan pada proses dengan konsep LIFO.
* Queue cocok digunakan pada sistem antrian dengan konsep FIFO.
* Implementasi manual membantu memahami cara kerja dasar struktur data.

---

# Sumber Belajar

* Modul Praktikum Algoritma dan Struktur Data
* Modul Struktur Data Dasar (Stack & Queue)
* Dokumentasi Dasar Bahasa C++
* Video Pembelajaran Online (YouTube)
