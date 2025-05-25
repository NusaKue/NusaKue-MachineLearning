# 🍰 NusaKue: Klasifikasi Gambar Kue Tradisional Indonesia

Selamat datang di repositori Machine Learning untuk proyek capstone **NusaKue** — sebuah inisiatif pelestarian budaya melalui teknologi! 

🎯 Proyek ini bertujuan untuk mengenali berbagai **kue tradisional Indonesia** secara otomatis dari gambar, serta menyajikan **informasi budaya** yang edukatif dan menarik.

---

## 📌 Ringkasan Proyek

Indonesia memiliki ratusan jenis kue tradisional dari berbagai daerah yang kaya akan makna budaya dan sejarah. Sayangnya, generasi muda semakin jarang mengenal kue-kue tersebut. Oleh karena itu, kami mengembangkan:

> 🔍 **Model klasifikasi gambar** yang dapat mengenali jenis kue tradisional dari foto, kemudian menyajikan nama, deskripsi, daerah asal, bahan pembuatan, cara pembuatan dan signifikansi budaya dari kue tersebut.

---

## 🧠 Teknologi yang Digunakan

- **TensorFlow** & **Keras** untuk model klasifikasi gambar
- **Transfer Learning** dengan arsitektur **MobileNetV2** dengan tambahan **Feature Extraction**
- **Scikit-learn**, **Pandas**, **Matplotlib**, dan **Seaborn** untuk eksplorasi & evaluasi data
- Model dikonversi ke **TensorFlow.js** (`.tfjs`) untuk integrasi web oleh tim backend
- Jupyter Notebook (`.ipynb`) sebagai environment pengembangan dan dokumentasi model

---

## 📁 Struktur Repositori

- `klasifikasi_gambar_kue_tradisional.ipynb` – Notebook utama untuk pelatihan model  
- `inference_model.ipynb` – Notebook inferensi model .h5  
- `model.h5` – Model hasil training  
- `model_tfjs/` – Model hasil konversi untuk deploy (TFJS)  
- `labels.json` – Label nama kue dan ID-nya  
- `sample_data/` – Contoh gambar input untuk uji coba  
- `requirements.txt` – Daftar dependensi  
- `README.md` – Dokumentasi proyek (file ini)  

---

## 🔎 Dataset

Dataset dikumpulkan secara manual dari sumber publik (Google Images, dll) dan dikategorikan menjadi 20 jenis kue tradisional beberapa daerah, dapat diakses melalui link berikut : 
[Datasets](https://drive.google.com/drive/folders/1p1v5iuci8TDE_e2e09F6p8bLk41tcnZm?usp=sharing)

---

## 📈 Hasil & Evaluasi

Model yang dibangun menunjukkan akurasi yang cukup baik dengan menerapkan :
- **Augmentasi Data**
- **Early Stopping**
- **Transfer Learning (Feature Extraction)**
- **Optimisasi hyperparameter**
  
📊 Evaluasi model disediakan dalam notebook dan mencakup:
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

---

## 🚀 Cara Menjalankan Inferensi

1. Pastikan sudah install `requirements.txt`:
   ```bash
   pip install -r requirements.txt
2. Jalankan inference_model.ipynb dan masukkan path gambar uji Anda.

---

## 👨‍💻 Tim Machine Learning

Tim Machine Learning bertanggung jawab dalam seluruh proses pengembangan model klasifikasi gambar — mulai dari pengumpulan data, pemrosesan, pelatihan, hingga konversi model untuk integrasi ke dalam sistem web.

### Anggota Tim ML:
- Fiyanda Ma'muri
- Bagus Dzakiy Rahman Saputra 
- Ady Subagya Junior
 

> Kami bekerja secara kolaboratif untuk memastikan hasil model tidak hanya akurat, tetapi juga dapat digunakan langsung oleh tim backend dan frontend sebagai bagian dari ekosistem aplikasi **NusaKue**.

