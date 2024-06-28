# Klasifikasi Data Tidak Seimbang dengan Teknik SMOTE dan Random Forest

## Deskripsi Proyek
Proyek ini bertujuan untuk melakukan klasifikasi pada dataset yang tidak seimbang menggunakan teknik SMOTE (Synthetic Minority Over-sampling Technique) untuk menangani ketidakseimbangan kelas, dan Random Forest sebagai model klasifikasi utama.

## Langkah-langkah
Berikut adalah langkah-langkah utama yang dilakukan dalam proyek ini:
1. **Pemuatan Data**: Memuat dataset dari sumbernya.
2. **Eksplorasi Data**: Menjelajahi dan memahami karakteristik dataset, termasuk distribusi kelas.
3. **Pemrosesan Data**: Menyiapkan data untuk pemodelan, termasuk penanganan data yang hilang atau tidak sesuai.
4. **Pembagian Data**: Membagi dataset menjadi data latih dan data uji.
5. **Penanganan Ketidakseimbangan**: Menggunakan SMOTE untuk oversampling kelas minoritas agar distribusi kelas lebih seimbang.
6. **Inisialisasi Model**: Menyiapkan model Random Forest untuk klasifikasi.
7. **Pelatihan Model**: Melatih model menggunakan data latih yang telah diproses.
8. **Evaluasi Model**: Mengevaluasi performa model menggunakan berbagai metrik seperti akurasi, presisi, recall, dan F1-score.
9. **Prediksi**: Memprediksi kelas data uji menggunakan model yang telah dilatih.

## File Pendukung
- `klasifikasi_data_tidak_seimbang.ipynb`: Notebook Jupyter dengan implementasi kode.
- `dataset.csv`: Dataset yang digunakan untuk klasifikasi.

## Instalasi dan Penggunaan
Untuk menggunakan proyek ini, pastikan Anda memiliki Python dan paket-paket berikut terinstal:
- Pandas
- Scikit-learn
- Jupyter Notebook
