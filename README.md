# Naive Bayes Classification - Kelayakan Pembelian Komputer

Proyek ini merupakan implementasi model **Naive Bayes** (menggunakan `CategoricalNB` dari `scikit-learn`) untuk memprediksi kelayakan seseorang membeli komputer berdasarkan fitur kategorikal seperti usia, penghasilan, status mahasiswa, dan riwayat kredit.

## 📂 Struktur Proyek

- `dataset_buys _comp.csv` - Dataset yang digunakan
- `main.py` atau `notebook.ipynb` - File utama untuk preprocessing, pelatihan, dan evaluasi model
- `README.md` - Penjelasan proyek ini

## 🧪 Library yang Digunakan

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## 📝 Langkah-langkah Analisis

### 1. Import dan Muat Dataset
- Memuat dataset CSV menggunakan `pandas`.

### 2. Exploratory Data Analysis (EDA)
- Menampilkan struktur data dan statistik deskriptif.
- Memeriksa nilai hilang dan duplikat.
- Visualisasi distribusi target dan hubungan antar fitur.

### 3. Preprocessing Data
- Encoding fitur kategorikal dengan `LabelEncoder`.
- Memisahkan fitur (X) dan target (y).
- Membagi data menjadi data latih dan data uji (70:30).

### 4. Membangun Model
- Menggunakan model `CategoricalNB` dari `sklearn.naive_bayes`.

### 5. Evaluasi Model
- Menghitung prediksi dan probabilitas kelas.
- Menampilkan confusion matrix.
- Menampilkan classification report.
- Menghitung akurasi model.

## 📊 Hasil Evaluasi

- **Confusion Matrix** divisualisasikan menggunakan heatmap.
- **Classification Report** menunjukkan precision, recall, dan F1-score.
- **Akurasi Model** ditampilkan dalam bentuk persentase.

## 📌 Catatan

- Dataset hanya berisi fitur-fitur kategorikal, sehingga model `CategoricalNB` sangat sesuai.
- Label encoding digunakan karena semua fitur merupakan data kategorikal non-numerik.
- Visualisasi menggunakan `matplotlib` dan `seaborn` untuk memudahkan pemahaman distribusi data dan performa model.

## 🔧 Cara Menjalankan

1. Pastikan Python dan pustaka yang dibutuhkan sudah terinstal.
2. Jalankan file `.py` atau `.ipynb` pada IDE seperti VSCode atau Jupyter Notebook.
3. Pastikan dataset `dataset_buys _comp.csv` berada di direktori yang sama.

---

> Dibuat untuk tujuan pembelajaran klasifikasi dengan data kategorikal menggunakan Naive Bayes.