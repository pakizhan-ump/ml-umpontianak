# Tugas Minggu 1: Setup Environment dan Hello World di Colab

**Tenggat Waktu:** Lihat di LMS (Google Classroom) 
**Bobot:** 2% dari total nilai akhir  
**Status:** **Tugas Individu** (Wajib dikerjakan sendiri)  
**Bentuk Pengumpulan:** **Link Repository GitHub** yang telah dibuat via LMS.

## 1. Tujuan Pembelajaran

Setelah menyelesaikan tugas ini, mahasiswa diharapkan mampu:
1.  Membuat dan mengelola akun GitHub.
2.  Membuat repository GitHub untuk mata kuliah ini.
3.  Menggunakan Google Colab untuk membuat dan menjalankan notebook Python sederhana.
4.  Menghubungkan Google Colab dengan GitHub untuk menyimpan hasil kerja.
5.  Mengirim tautan repository yang telah dibuat sebagai bukti pengerjaan.

## 2. Latar Belakang

Sebelum mempelajari algoritma machine learning yang kompleks, hal paling fundamental yang harus dikuasai adalah kemahiran dalam menggunakan *tools* atau *environment* tempat kita menulis code (koding). Dalam industri saat ini, **Google Colab** adalah standar untuk eksperimen yang cepat dan kolaboratif, sementara **GitHub** adalah standar untuk menyimpan, mengelola, dan berbagi kode. Tugas minggu ini dirancang untuk memastikan Anda familiar dengan kedua tools ini.

## 3. Instruksi Tugas (Step-by-Step)

### Langkah 1: Setup GitHub
1.  Jika belum memiliki akun, buat akun GitHub di [github.com](https://github.com/).
2.  Setelah login, buat sebuah **repository publik** baru dengan nama `[NIM]-Pengantar-ML` (Contoh: `1234567890-Pengantar-ML`).
3.  Pada saat pembuatan, centang opsi **"Add a README file"**.
4.  Pada deskripsi repository, tulis: `Repository untuk mata kuliah Pengantar Machine Learning - [Nama Lengkap Anda] - [NIM]`.

### Langkah 2: Setup Google Colab & Hello World
1.  Buka [Google Colab](https://colab.research.google.com/).
2.  Login dengan akun Google Anda (disarankan menggunakan akun institusi/kampus).
3.  Buat **notebook baru** dengan klik `File` > `New notebook`.
4.  Beri judul notebook menjadi `Tugas_Minggu_1_Hello_World.ipynb`.
5.  Pada *cell* pertama, tulis kode Python sederhana berikut:
    ```python
    print("Hello, World!")
    print("Selamat datang di Mata Kuliah Pengantar Machine Learning!")
    print("Nama: [Nama Lengkap Anda]")
    print("NIM: [NIM Anda]")
    ```
6.  Ganti `[Nama Lengkap Anda]` dan `[NIM Anda]` dengan data Anda.
7.  Jalankan cell tersebut (gunakan tombol `Play` atau shortcut `Ctrl+Enter`).

### Langkah 3: Menghubungkan Colab dengan GitHub
1.  Di Google Colab, pada menu atas, klik **`File`** -> **`Save a copy in GitHub`**.
2.  Anda akan diminta untuk mengotorisasi (menyetujui) Colab untuk mengakses akun GitHub Anda (jika belum). Ikuti prosesnya.
3.  Pada pop-up yang muncul:
    *   Pilih repository yang baru saja Anda buat (`[NIM]-Pengantar-ML`).
    *   Untuk branch, biarkan `main`.
    *   Pada kolom "Commit message", tulis: `"Commit pertama: Menambahkan Tugas Minggu 1"`.
    *   Pastikan opsi **`Include a link to Colab`** dicentang.
4.  Klik **`OK`**. Colab akan secara otomatis menyimpan notebook Anda ke repository GitHub dan membuka tab baru menuju file tersebut di GitHub.

### Langkah 4: Kustomisasi README.md (Nilai Tambah)
1.  Di repository GitHub Anda, klik file **`README.md`** lalu klik ikon pensil (edit).
2.  Edit file tersebut untuk mendeskripsikan repository Anda. Gunakan template berikut atau kustomisasi sendiri:

    ````markdown
    # [NIM] - Pengantar Machine Learning

    **Nama:** [Nama Lengkap Anda]
    **NIM:** [NIM Anda]
    **Kelas:** [Kelas Anda]

    Repository ini berisi semua tugas, proyek, dan catatan untuk mata kuliah **Pengantar Machine Learning** Semester Ganjil 2025/2026.

    ## Daftar Tugas
    - **Minggu 1:** [Setup Environment - Hello World](https://colab.research.google.com/github/[Username_Github_Anda]/[NIM]-Pengantar-ML/blob/main/Tugas_Minggu_1_Hello_World.ipynb)
    ````

    Ganti `[Username_Github_Anda]` dengan username GitHub Anda yang sebenarnya (biasanya muncul di URL profil Anda).

## 4. Pengumpulan (Submission)

1.  **Salin tautan (URL) repository GitHub Anda** (contoh: `https://github.com/username-Anda/1234567890-Pengantar-ML`).
2.  **KUMPULKAN** tautan tersebut ke dalam **form assignment** yang telah disediakan di **LMS (SPADA/Google Classroom/Form Link)**.
3.  **Pastikan repository Anda bersifat *Public*** agar dapat diakses oleh dosen dan asisten.

## 5. Kriteria Penilaian

| Kriteria | Bobot | Keterangan |
| :--- | :---: | :--- |
| **Kebenaran & Kelengkapan** | 60% | Repository dibuat dengan nama yang sesuai (`[NIM]-Pengantar-ML`), berisi file `README.md`, dan notebook `Tugas_Minggu_1_Hello_World.ipynb` yang dapat diakses dan berjalan dengan benar (menampilkan nama dan NIM). |
| **Ketepatan Waktu** | 20% | Tugas dikumpulkan sebelum tenggat waktu. |
| **Kualitas Dokumentasi** | 20% | `README.md` di repository rapi, informatif, tertata dengan baik, dan telah dikustomisasi. |

## 6. Sumber Daya & Referensi

1.  [Slide Materi Minggu 1: Intro ML](https://github.com/Pengantar-Machine-Learning-2024/Modules/Week-01/Slides/) *(Link akan diupdate)*
2.  [Panduan Dasar GitHub](https://docs.github.com/en/get-started/quickstart/hello-world)
3.  [Panduan Dasar Google Colab](https://colab.research.google.com/notebooks/intro.ipynb)

---
**Catatan Penting:**
*   Tugas ini bertujuan untuk memastikan Anda siap untuk minggu-minggu selanjutnya.
*   **Dilarang keras** untuk melakukan plagiarisme. Hasil kerja harus murni buatan sendiri. Repositories yang terindikasi copy-paste akan mendapatkan nilai 0.
*   Jika mengalami kendala, jangan sungkan untuk bertanya di **forum diskusi** yang telah disediakan di LMS.

**Selamat mencoba!**
