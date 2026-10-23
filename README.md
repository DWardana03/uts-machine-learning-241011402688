# 🤖 UTS Machine Learning: Linear Regression & Logistic Regression

Repositori ini dibuat untuk memenuhi tugas Ujian Tengah Semester (UTS) mata kuliah Machine Learning[cite: 2]. Seluruh model dan metrik evaluasi diimplementasikan secara mandiri menggunakan NumPy tanpa menggunakan pustaka scikit-learn pada bagian utama model[cite: 2].

---

## 👤 Identitas Mahasiswa
* **Nama:** Doni Wardana[cite: 2]
* **NIM:** `241011402688`[cite: 2]
* **Kelas:** Reg CS[cite: 2]
* **Random State:** 88[cite: 2]

---

## 📊 Ringkasan Hasil & Evaluasi

### Bagian A – Linear Regression (`Ads_Data.csv`)
* **Metode Pelatihan:** Normal Equation & Gradient Descent[cite: 2]
* **Persamaan Garis Regresi:** $\hat{y} = 28.9055 + 9.0778 \cdot X$[cite: 2]

| Metrik Evaluasi (Data Testing) | Nilai |
| :--- | :--- |
| **MAE** | ~2.85[cite: 2] |
| **MSE** | ~13.01[cite: 2] |
| **RMSE** | ~3.60[cite: 2] |
| **$R^2$ (Coefficient of Determination)** | ~0.9830[cite: 2] |

> **Analisis Bagian A:** Nilai $R^2$ sebesar **98.30%** pada data testing menunjukkan bahwa model regresi linier memiliki kemampuan generalisasi yang sangat baik dalam memprediksi penjualan berdasarkan biaya iklan[cite: 2].

---

### Bagian B – Logistic Regression (`Email_Data.csv`)
* **Metode Pelatihan:** Gradient Descent[cite: 2]
* **Threshold:** 0.5[cite: 2]

| Metrik Evaluasi | Nilai / Status | Keterangan |
| :--- | :--- | :--- |
| **Akurasi** | Tinggi & Optimal[cite: 2] | - |
| **Precision** | `1.0000`[cite: 2] | Bebas dari False Positive, sangat aman agar email penting tidak masuk folder spam[cite: 2]. |
| **Recall** | Optimal[cite: 2] | Sesuai pengaturan threshold[cite: 2]. |

> **Analisis Bagian B:** Model berhasil memisahkan kelas Spam dan Bukan Spam menggunakan *decision boundary* linier dengan tingkat kesalahan (*misclassification*) yang sangat minim[cite: 2].
