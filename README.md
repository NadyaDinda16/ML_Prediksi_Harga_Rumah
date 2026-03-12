# ML_Prediksi_Harga_Rumah 🏠

Proyek ini bertujuan untuk membangun model *Machine Learning* yang dapat memprediksi harga rumah secara objektif berdasarkan karakteristik properti.

---

## 1. Project Background
Harga rumah memiliki variasi yang sangat tinggi tergantung pada berbagai faktor kompleks. Pendekatan tradisional seringkali bersifat subjektif, sehingga diperlukan solusi berbasis data untuk memberikan estimasi harga yang lebih akurat.

Dengan menggunakan **Machine Learning**, kita dapat membedah pola dari data historis properti untuk membantu calon pembeli, penjual, maupun pengembang dalam mengambil keputusan finansial.

## 2. Tujuan Project
* **Analisis Faktor:** Mengidentifikasi variabel apa saja yang paling signifikan mempengaruhi fluktuasi harga rumah.
* **Pembangunan Model:** Membuat sistem prediksi harga otomatis berdasarkan fitur-fitur teknis properti.
* **Komparasi Algoritma:** Membandingkan performa beberapa algoritma untuk menemukan model dengan tingkat error (RMSE/MAE) terendah.

## 3. Fitur Data (Dataset)
Model ini menggunakan variabel-variabel kunci sebagai berikut:
* **Luas Bangunan:** Total luas lantai dalam satuan $m^2$.
* **Luas Tanah:** Total luas lahan dalam satuan $m^2$.
* **Kamar Tidur:** Jumlah ketersediaan kamar tidur.
* **Kamar Mandi:** Jumlah ketersediaan kamar mandi.
* **Garasi:** Kapasitas kendaraan yang dapat ditampung.
* **Harga (Target):** Nilai jual rumah yang akan diprediksi.

---

## 4. Alur Kerja (Workflow)
Proyek ini mengikuti tahapan standar *Data Science*:

1.  **Exploratory Data Analysis (EDA):** Visualisasi distribusi harga dan matriks korelasi antar fitur.
2.  **Data Preprocessing:** Penanganan *missing values*, penghapusan *outliers*, dan *feature scaling*.
3.  **Model Selection:** Pengujian beberapa algoritma seperti:
    * **Linear Regression** (Baseline)
    * **Random Forest Regressor** (Ensemble)
    * **XGBoost** (Gradient Boosting)
4.  **Evaluasi Model:** Mengukur performa menggunakan metrik $R^2$ Score, *Mean Absolute Error* (MAE), dan *Root Mean Squared Error* (RMSE).

---

## 5. Teknologi & Library
* **Bahasa:** Python
* **Library Utama:** `Pandas`, `NumPy`, `Scikit-Learn`, `Matplotlib`, `Seaborn`, `XGBoost`.

---
