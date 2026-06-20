# manipulasi-citra-digital
# Proyek Manipulasi Dasar Citra Digital

### Identitas Mahasiswa
* **Nama:** [Nama Lengkap Kamu]
* **NIM:** [Nomor Induk Mahasiswa Kamu]
* **Mata Kuliah:** Pengolahan Sinyal Digital / Pengolahan Citra Digital

---

## 1. Deskripsi Singkat Project
Proyek ini merupakan eksperimen laboratorium untuk memahami bagaimana operasi matematis sederhana (baik linier maupun non-linier) berbasis *point processing* dan *multi-input* dapat mengubah karakteristik visual, nilai piksel, kecerahan (*brightness*), kontras, dan detail dari sebuah citra digital. Eksperimen ini diimplementasikan menggunakan bahasa pemrograman Python dengan pustaka utama OpenCV.

## 2. Citra yang Digunakan
Eksperimen ini wajib menggunakan minimal dua citra berbeda yang disimpan di dalam folder `images/`:
1. `image1.jpg`: [Deskripsikan gambar 1 kamu, misal: Foto pemandangan alam / Foto personal ukuran 600x400]
2. `image2.jpg`: [Deskripsikan gambar 2 kamu, misal: Tekstur hujan / Foto objek arsitektur]

## 3. Library yang Digunakan
Proyek ini berjalan menggunakan Python dengan dependensi sebagai berikut:
* `OpenCV (opencv-python)` - Untuk membaca, mengubah ukuran (*resize*), dan operasi warna citra.
* `NumPy` - Untuk manipulasi array matriks piksel secara efisien.
* `Matplotlib` - Untuk visualisasi citra dan analisis sebaran histogram.

## 4. Struktur Folder Project
Struktur repositori ini disusun berdasarkan ketentuan tugas sebagai berikut:
```text
manipulasi-citra-digital/
|-- notebook/
|   |-- image_manipulation.ipynb
|-- images/
|   |-- image1.jpg
|   |-- image2.jpg
|-- report/
|   |-- laporan.pdf
|-- README.md
|-- requirements.txt
