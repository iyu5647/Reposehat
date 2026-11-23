# Preprocessing Teks Ulasan E-Commerce Berbahasa Indonesia

**Nama :** Hafizh Akramullah
**NIM  :** 24146054

## Deskripsi
Repositori ini berisi tugas preprocessing teks (NLP) pada dataset ulasan produk e-commerce berbahasa Indonesia untuk analisis sentimen.

Dataset: [dipawidia/ecommerce-product-reviews-sentiment](https://huggingface.co/datasets/dipawidia/ecommerce-product-reviews-sentiment)

## Isi Repositori
| File | Keterangan |
|------|------------|
| `Preprocessing_Sentimen_Ecommerce.ipynb` | Jupyter Notebook (kode lengkap + output) |
| `README.md` | Identitas dan penjelasan singkat proyek |

## Tahapan yang Dikerjakan
1. Memuat dataset dari Hugging Face (`datasets`)
2. Menampilkan informasi dataset: jumlah data, kolom, dan distribusi label sentimen
3. Preprocessing teks:
   - Case folding
   - Cleaning (URL, angka, tanda baca, karakter khusus)
   - Tokenisasi
   - Stopword removal (Sastrawi, kata negasi dipertahankan)
   - Stemming (Sastrawi)
4. Menampilkan 10 contoh teks sebelum dan sesudah preprocessing
5. Analisis pengaruh preprocessing terhadap kualitas data teks (lihat laporan PDF)

## Cara Menjalankan
Disarankan memakai Google Colab. Buka notebook, lalu jalankan semua sel secara berurutan (`Runtime > Run all`). Library yang dipakai: `datasets`, `pandas`, `Sastrawi`.

```bash
pip install datasets pandas Sastrawi
```

## Ringkasan Dataset
- Jumlah data: 11.606 ulasan
- Kolom: `review`, `translate`, `sentimen`
- Distribusi label: 5.803 (label 0) dan 5.803 (label 1), seimbang# Reposehat
