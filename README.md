
# 🧠 Analisis Sentimen Komentar tentang Budaya Carok di Madura menggunakan Algoritma Support Vector Machine (SVM)

Repositori ini berisi kode dan dokumentasi untuk melakukan analisis sentimen terhadap komentar-komentar mengenai budaya **Carok** di Madura menggunakan algoritma **Support Vector Machine (SVM)**. Proyek ini bertujuan untuk mengkategorikan komentar menjadi sentimen **positif** atau **negatif** berdasarkan data yang dikumpulkan dari berbagai sumber.


## 🛠️ Fitur Utama

- **Preprocessing Teks**:
  - Case folding
  - Cleansing
  - Stopword removal menggunakan *Sastrawi*
  - Stemming dengan Sastrawi
  - Normalisasi kata tidak baku

- **Labeling Sentimen**:
  - Manual labeling menjadi positif atau negatif

- **Ekstraksi Fitur**:
  - Menggunakan metode **TF-IDF**

- **Modeling**:
  - Algoritma **Support Vector Machine (SVM)**
  - Pembagian data training dan testing
  - Evaluasi model dengan confusion matrix, akurasi, precision, recall

- **Visualisasi**:
  - Pie chart distribusi sentimen
  - Bar chart hasil prediksi

## 🚀 Cara Menjalankan

1. **Clone repositori** ini:
   ```bash
   git clone https://github.com/username/nama-repo.git
   cd nama-repo
   ```

2. **Install dependensi** (gunakan `requirements.txt` jika disediakan):
   ```bash
   pip install -r requirements.txt
   ```

3. **Jalankan Notebook**:
   Buka file `pengolahan_data_sentimen.ipynb` menggunakan Jupyter Notebook atau JupyterLab, lalu jalankan cell satu per satu.

## 📊 Contoh Hasil

- **Akurasi Model**: 80.23%
- **Confusion Matrix**: ditampilkan dalam notebook
- **Distribusi Sentimen**:
  - Positif: 67.96%
  - Negatif: 32.04%

## 📌 Ketergantungan

- `pandas`
- `scikit-learn`
- `Sastrawi`
- `matplotlib`
- `seaborn`

Instalasi:
```bash
pip install pandas scikit-learn Sastrawi matplotlib seaborn
```

## 👤 Kontributor

- Maulana Akbar — [@maulana-akbar](https://github.com/maulana-akbar)

## 📄 Lisensi

Proyek ini dilisensikan di bawah lisensi MIT. Silakan lihat file `LICENSE` untuk informasi lebih lanjut.
