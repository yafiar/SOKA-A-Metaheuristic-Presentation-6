# Metaheuristik untuk Cloud Task Scheduling

Website presentasi interaktif untuk mata kuliah **SOKA A**, Kelompok 6. Proyek ini membahas penggunaan algoritma metaheuristik untuk menyelesaikan masalah *cloud task scheduling*, yaitu menentukan penempatan task ke virtual machine (VM) agar waktu penyelesaian dan beban komputasi menjadi lebih optimal.

## Anggota Kelompok

| No. | Nama | NRP |
|---:|---|---:|
| 1 | Erlangga Valdhio Putra Sulistio | 5027241030 |
| 2 | Raihan Fahri Ghazali | 5027241061 |
| 3 | Ahmad Yafi Ar Rizq | 5027241166 |
| 4 | Aslam Ahmad Usman | 5027241074 |
| 5 | Az Zahrra Tasya | 5027241087 |

## Materi yang Dibahas

Website menjelaskan:

- Konsep cloud task scheduling dan alasan optimasi diperlukan.
- Representasi task, VM, beban kerja, dan solusi penjadwalan.
- **Cuckoo Optimization Algorithm (COA)**.
- **Teaching-Learning-Based Optimization (TLBO)**.
- Perbandingan pendekatan metaheuristik dengan penjadwalan biasa.
- Penggunaan fungsi objektif untuk mengevaluasi kualitas solusi.

## Cara Kerja Algoritma

Secara umum, algoritma melakukan langkah berikut:

1. Membangkitkan populasi solusi penjadwalan secara acak.
2. Menghitung nilai objektif setiap solusi, terutama berdasarkan *makespan* atau waktu penyelesaian keseluruhan.
3. Memperbarui solusi melalui mekanisme pencarian algoritma:
   - COA menggunakan habitat cuckoo, telur, dan *Levy flight* untuk mencari solusi baru.
   - TLBO menggunakan fase **Teacher Phase** dan **Learner Phase** untuk memperbaiki populasi.
4. Mempertahankan solusi yang lebih baik dan mengulangi proses hingga jumlah iterasi selesai.
5. Menampilkan solusi terbaik pada visualisasi.

## Fitur Interaktif

- Lab visual untuk memilih algoritma **COA** atau **TLBO**.
- Slider jumlah populasi dan kecepatan simulasi.
- Tombol **Play**, **Step**, dan **Reset**.
- Animasi proses pencarian solusi pada grafik.
- Demo menjalankan 60 iterasi.
- Penjelasan tahap algoritma yang sedang berlangsung.
- Tampilan responsif untuk desktop dan perangkat dengan layar lebih kecil.

## Teknologi

- HTML5
- CSS3
- JavaScript vanilla
- SVG dan Canvas untuk visualisasi
- GitHub Pages untuk deployment

## Struktur Proyek

```text
.
├── index.html
└── README.md
```

## Referensi

- Rajabioun, R. (2011). *Cuckoo Optimization Algorithm*. Applied Soft Computing, 11, 5508–5518.
- Rao, R. V., & Kamarullah, M. (2010). *Teaching-Learning-Based Optimization Algorithm*. Engineering Applications of Artificial Intelligence.

