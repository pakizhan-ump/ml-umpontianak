# 🎯 PRAKTIKUM WEEK-02: STRUKTUR DATA MACHINE LEARNING

## 📋 Informasi Umum
- **Mata Kuliah**: Machine Learning
- **Modul**: Week-02 - Struktur Data Python untuk ML

## 🚀 Instruksi Pengumpulan

### 1. Pengerjaan Latihan
- Kerjakan semua Latihan praktikum dan lengkapi script/kode pada bagian **TODO**
- Gunakan **solusi praktikum** sebagai referensi pembelajaran setelah mengerjakan
- Pahami perbedaan dan penggunaan tiap struktur data dalam manipulasi data

### 2. Teknis Pengerjaan
- Pisahkan tiap Latihan pada masing-masing file
- Dikerjakan menggunakan **Google Colab** atau **VS Code**
- Setiap file harus dapat di-run tanpa error

### 3. Struktur Repository
[NIM]-Pengantar-ML/

└── week-02/

├── latihan-praktikum-1-list-dictionary.ipynb

├── latihan-praktikum-2-numpy.ipynb

├── latihan-praktikum-3-pandas.ipynb

└── (optional) latihan-praktikum-4-pytorch.ipynb

**Contoh Penamaan File:**
- `2301234567-Pengantar-ML/week-02/latihan-praktikum-1-list-dictionary.ipynb`

### 4. Pengumpulan
- **Latihan 1-3**: Wajib dikerjakan
- **Latihan 4**: Tambahan (optional untuk nilai bonus)
- Tautan repository week-02 dikirim ke **LMS (Google Classroom)**

### 5. Deadline
- **⏰**: Cek LMS
  

## 📊 Rubrik Penilaian

### 🎯 Latihan 1: List dan Dictionary (Total: 30 Poin)

#### A. Implementasi Fungsi (20 Poin)
| Kriteria | Poin | Deskripsi |
|----------|------|-----------|
| **Filter Data** | 5 | Filter data dalam range 22-25 derajat |
| **Normalisasi** | 5 | Min-max scaling dengan benar |
| **Moving Average** | 10 | Implementasi moving average window 3 |

#### B. Kualitas Kode (10 Poin)
| Kriteria | Poin | Deskripsi |
|----------|------|-----------|
| **Kebenaran Logika** | 4 | Algoritma sesuai dengan spesifikasi |
| **Readability** | 3 | Kode mudah dibaca dan dikomentari |
| **Efisiensi** | 3 | Menggunakan operasi Python yang efisien |

### 🎯 Latihan 2: NumPy (Total: 30 Poin)

#### A. Implementasi Fungsi (20 Poin)
| Kriteria | Poin | Deskripsi |
|----------|------|-----------|
| **Z-score Normalization** | 7 | Normalisasi dengan mean=0, std=1 |
| **Outlier Handling** | 6 | Clip values dengan threshold 3 std |
| **One-hot Encoding** | 7 | Konversi label kategorikal dengan benar |

#### B. Kualitas Kode (10 Poin)
| Kriteria | Poin | Deskripsi |
|----------|------|-----------|
| **Vectorization** | 4 | Menggunakan operasi vektorisasi NumPy |
| **Error Handling** | 3 | Menangani edge cases dengan baik |
| **Documentation** | 3 | Komentar yang jelas dan informatif |

### 🎯 Latihan 3: Pandas (Total: 30 Poin)

#### A. Analisis Data (20 Poin)
| Kriteria | Poin | Deskripsi |
|----------|------|-----------|
| **Revenue Analysis** | 7 | Groupby dan aggregasi revenue per product |
| **Customer Ranking** | 7 | Top 5 customers berdasarkan spending |
| **Time Series Analysis** | 6 | Daily revenue analysis dengan benar |

#### B. Kualitas Analisis (10 Poin)
| Kriteria | Poin | Deskripsi |
|----------|------|-----------|
| **Data Insight** | 6 | Menemukan pola dan insight yang relevan |
| **Interpretasi** | 4 | Kesimpulan analisis yang logis |

### 🎯 Latihan 4: PyTorch (Bonus: 10 Poin)

#### A. Implementasi Tensor Operations (7 Poin)
| Kriteria | Poin | Deskripsi |
|----------|------|-----------|
| **Linear Layer** | 2 | Implementasi y = XW + b |
| **ReLU Activation** | 2 | Fungsi aktivasi max(0, x) |
| **Batch Normalization** | 3 | Normalisasi per feature across batch |

#### B. Advanced Operations (3 Poin)
| Kriteria | Poin | Deskripsi |
|----------|------|-----------|
| **Matrix Multiplication** | 3 | Implementasi manual matmul |

## 📝 Kriteria Penilaian Detail

### ✅ Kelengkapan (40%)
- Semua TODO telah diimplementasi
- Kode dapat di-run tanpa error
- Output sesuai dengan expected result

### ✅ Kebenaran (30%)
- Logika algoritma benar
- Menggunakan struktur data yang tepat
- Hasil perhitungan akurat

### ✅ Kualitas Kode (20%)
- Penamaan variabel yang deskriptif
- Komentar yang jelas
- Formatting yang konsisten
- Fungsi yang modular dan reusable

### ✅ Kreativitas (10%)
- Solusi yang efisien dan optimal
- Penambahan analisis tambahan (jika ada)
- Implementasi alternatif yang kreatif

## 🚨 Ketentuan Umum

### Yang DIPERBOLEHKAN:
- Diskusi dengan teman sekelas
- Mencari referensi online
- Bertanya kepada asisten/dosen
- Menggunakan AI assistant untuk learning

### Yang DILARANG:
- Copy-paste kode teman
- Plagiarisme dari repository lain
- Melihat solusi sebelum mengerjakan
- Submit pekerjaan yang bukan milik sendiri

## 🆘 Troubleshooting Common Issues

### Error Import Library
```python
# Pastikan library terinstall
!pip install numpy pandas torch

# Untuk Google Colab, torch sudah terinstall
import numpy as np
import pandas as pd
import torch
