# UTS Pengantar Deep Learning - Semester Genap 2025/2026
## Analisis Komparatif Deep Learning vs Machine Learning Konvensional

Repositori ini disusun untuk memenuhi tugas **Ujian Tengah Semester (UTS)** mata kuliah Machine Learning / Pembelajaran Mesin. Proyek ini berfokus pada implementasi pipeline *end-to-end* serta analisis perbandingan performa antara metode *Classical Machine Learning* dan arsitektur *Deep Learning* pada tiga domain data berbeda: Tabular, Image, dan Text.

---

### 👤 Identitas Mahasiswa
* **Nama** : Rio Ramadhani Harllambang
* **NIM** : 1202220205
* **Kelas**: SI-46-EDM
* **Link Repository**: https://github.com/Tayo1103/uts_deep_learning.git

---

### 📂 Struktur Direktori
Penyusunan file dalam repositori ini mengikuti struktur berikut untuk memastikan aspek *reproducibility*:

```text
├── Case_1_Tabular/
│   ├── UTS_Deep_Learning_Kasus_1_Data_Tabular_(ML).ipynb      # Notebook Prediksi kelangsungan hidup penumpang Titanic (ML)
│   ├── UTS_Deep_Learning_Kasus_1_Data_Tabular_(DL).ipynb      # Notebook Prediksi kelangsungan hidup penumpang Titanic (DL)
│   ├── case1_submission_ml.csv                                # Kaggle Submission File Prediksi kelangsungan hidup penumpang Titanic (ML)
│   └── case1_submission_dl.csv                                # Kaggle Submission File Prediksi kelangsungan hidup penumpang Titanic (DL)
├── Case_2_Image/
│   ├── UTS_Deep_Learning_Kasus_2_Data_Image_(ML).ipynb        # Notebook Klasifikasi digit tulisan tangan (0-9) (ML)
│   ├── UTS_Deep_Learning_Kasus_2_Data_Image_(DL).ipynb        # Notebook Klasifikasi digit tulisan tangan (0-9) (DL)
│   ├── case2_submission_ml.csv                                # Kaggle Submission File Klasifikasi digit tulisan tangan (0-9) (ML)
│   └── case2_submission_dl.csv                                # Kaggle Submission File Klasifikasi digit tulisan tangan (0-9) (DL)
├── Case_3_Text/
│   ├── UTS_Deep_Learning_Kasus_3_Data_Text_(ML).ipynb         # Notebook Klasifikasi tweet bencana (Real vs Not Real) (ML)
│   ├── UTS_Deep_Learning_Kasus_3_Data_Text_(DL).ipynb         # Notebook Klasifikasi tweet bencana (Real vs Not Real) (DL)
│   ├── case3_submission_ml.csv                                # Kaggle Submission File Klasifikasi tweet bencana (Real vs Not Real) (ML)
│   └── case3_submission_dl.csv                                # Kaggle Submission File Klasifikasi tweet bencana (Real vs Not Real) (DL)
├── Report/
│   └── Laporan_UTS_Rio Ramadhani Harllambang_1202220205_SI-46-EDM.pdf      # Laporan teknis lengkap format PDF
└── README.md
```

---

### 📊 Ringkasan Arsitektur Model
Eksperimen ini membandingkan metode konvensional dengan pendekatan *deep learning* untuk mengevaluasi *trade-off* antara akurasi, waktu training, dan kompleksitas model sesuai dengan capaian pembelajaran mata kuliah.

| Kasus | Baseline (Konvensional) | Deep Learning |
| :--- | :--- | :--- |
| **Tabular (Titanic)** | Logistic Regression, Random Forest | Multi-Layer Perceptron (MLP) |
| **Image (MNIST)** | HOG + SVM, PCA + Random Forest | Convolutional Neural Network (CNN) |
| **Text (Twitter)** | LR + TF-IDF, MNB + TF-IDF, Linear SVM + TF-IDF | Embedding + LSTM, Embedding + 1D-CNN |

---

### 🚀 Cara Menjalankan Notebook
Untuk memenuhi aspek *reproducibility*, ikuti langkah-langkah berikut guna menjalankan file `.ipynb` di Jupyter Notebook atau Google Colab:

1. **Persiapan Kaggle API**:
   * Notebook menggunakan dataset langsung dari Kaggle.
   * Pastikan Anda mengganti bagian autentikasi Kaggle API dengan berkas `kaggle.json` (API Token) milik Anda sendiri agar dataset dapat terunduh secara otomatis.
2. **Eksekusi Cell**:
   * Jalankan cell secara berurutan dari **atas ke bawah**.

---

### 📝 Catatan Penting
* **Analisis Objektif**: Perbandingan dilakukan dengan *train-validation-test split* yang konsisten antara metode konvensional dan deep learning untuk memastikan perbandingan yang adil (*fair comparison*).
* **Justifikasi**: Pemilihan arsitektur didasarkan pada karakteristik data (tabular, image, text).
* **Integritas Akademik**: Seluruh analisis, pemilihan metode, dan kesimpulan merupakan hasil pemikiran mandiri sesuai dengan instruksi ujian.

---

### 🏆 Kaggle Leaderboard
* **Kasus 1** :
<img width="1920" height="1080" alt="Screenshot (348)" src="https://github.com/user-attachments/assets/eaa3955d-7252-4431-b062-8ecc50a2114f" />
<img width="1920" height="1080" alt="Screenshot (349)" src="https://github.com/user-attachments/assets/2117ce3c-5739-4e20-b8ef-8276d47ba915" />

<br></br>
* **Kasus 2** :
<img width="1920" height="1080" alt="Screenshot (350)" src="https://github.com/user-attachments/assets/adc0f0a2-c637-4476-b2fc-f2c86e96fa6a" />
<img width="1920" height="1080" alt="Screenshot (351)" src="https://github.com/user-attachments/assets/63c7b043-4b90-47cf-bc26-203a10295130" />

<br></br>
* **Kasus 3** :


---

<p align="center">
  © 2026 Rio Ramadhani Harllambang - 1202220205
</p>
