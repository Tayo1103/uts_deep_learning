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
│   └── notebook_titanic.ipynb          # Prediksi kelangsungan hidup penumpang Titanic
├── Case_2_Image/
│   └── notebook_mnist.ipynb            # Klasifikasi digit tulisan tangan (0-9)
├── Case_3_Text/
│   └── notebook_disaster_tweets.ipynb  # Klasifikasi tweet bencana (Real vs Not Real)
├── Report/
│   └── Laporan_UTS_Nama_NIM.pdf        # Laporan teknis lengkap format PDF
└── README.md
```

---

### 📊 Ringkasan Arsitektur Model
Eksperimen ini membandingkan metode konvensional dengan pendekatan *deep learning* untuk mengevaluasi *trade-off* antara akurasi, waktu training, dan kompleksitas model sesuai dengan capaian pembelajaran mata kuliah.

| Kasus | Baseline (Konvensional) | Deep Learning |
| :--- | :--- | :--- |
| **Tabular (Titanic)** | Logistic Regression, Random Forest | Multi-Layer Perceptron (MLP) |
| **Image (MNIST)** | HOG + SVM, PCA + Random Forest | Convolutional Neural Network (CNN) |
| **Text (Twitter)** | LR + TF-IDF, MNB + TF-IDF, Linear SVM + TF-IDF | Embedding + LSTM, DistilBERT |

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
