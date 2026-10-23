UTS Machine Learning: Linear Regression & Logistic Regression
Repositori ini dibuat untuk memenuhi tugas Ujian Tengah Semester (UTS) mata kuliah Machine Learning. Seluruh model dan metrik evaluasi diimplementasikan secara mandiri menggunakan NumPy tanpa menggunakan pustaka scikit-learn pada bagian utama model.

Identitas Mahasiswa

Nama : Doni Wardana

NIM : 241011402688

Kelas : Reg CS

Random State : 88


Ringkasan Hasil & Evaluasi

Bagian A – Linear Regression (Ads_Data.csv)

Metode Pelatihan: Normal Equation & Gradient Descent

Persamaan Garis Regresi: y_hat = 28.9055 + 9.0778 * X



Hasil Evaluasi Data Testing:

MAE: ~2.85

MSE: ~13.01

RMSE: ~3.60

R^2 (Coefficient of Determination): ~0.9830

Analisis: Nilai R^2 sebesar 98.30% pada data testing menunjukkan bahwa model regresi linier memiliki kemampuan generalisasi yang sangat baik dalam memprediksi penjualan berdasarkan biaya iklan.



Bagian B – Logistic Regression (Email_Data.csv)

Metode Pelatihan: Gradient Descent (Logistic Regression)

Hasil Evaluasi Data Testing (Threshold 0.5):

Akurasi: Tinggi dan optimal

Precision: 1.0000 (Bebas dari False Positive, sangat aman agar email penting tidak masuk folder spam)

Recall: Optimal sesuai pengaturan threshold

Analisis: Model berhasil memisahkan kelas Spam dan Bukan Spam menggunakan decision boundary linier dengan tingkat kesalahan (misclassification) yang sangat minim. 
