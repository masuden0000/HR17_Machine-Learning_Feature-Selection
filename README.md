# ✨ Feature Selection in Machine Learning

### Sumber Data
Data dummy dari sklearn.datasets

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk melakukan **Feature Selection** dalam Machine Learning, yaitu proses memilih fitur yang paling relevan untuk meningkatkan kinerja model. Berbagai metode seleksi fitur digunakan untuk memahami kontribusi setiap fitur dalam dataset.

### 🔍 Metode yang digunakan:
- **📥 Data Loading**: Memuat dataset ke dalam lingkungan pemrosesan.
- **🔀 Data Splitting**: Membagi dataset menjadi data latih dan data uji.
- **📊 Metode Feature Selection**:
  - **🛠️ Filter Method**: Menggunakan teknik statistik untuk memilih fitur yang paling signifikan.
  - **📦 Wrapper Method**: Menggunakan model Machine Learning untuk mengevaluasi kombinasi fitur.
  - **🧠 Embedded Method**: Menggunakan model dengan built-in feature selection, seperti LASSO.
- **📈 Evaluasi Model**: Mengukur performa model setelah seleksi fitur diterapkan.

## 🎯 Tujuan
1. ✅ Mengurangi kompleksitas model dengan memilih fitur yang paling berpengaruh.
2. ✅ Meningkatkan akurasi model Machine Learning dengan menghilangkan fitur yang tidak relevan.
3. ✅ Mengoptimalkan waktu komputasi dengan menyederhanakan dimensi dataset.

## 📊 Hasil Evaluasi Model
| Metode Seleksi | Akurasi |
|---------------|---------|
| 📊 Filter Methods | 0.89 |
| 📦 Wrapper Methods | 0.94 |
| 🧠 Embedded Methods | 1.00 |
