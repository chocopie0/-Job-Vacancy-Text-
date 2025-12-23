# -Job-Vacancy-Text-
Klasifikasi Teks Lowongan Pekerjaan Menggunakan Neural Network dan Transfer Learning (Pretrained BERT)
[Python](https://img.shields.io/badge/Python-3.9%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=for-the-badge&logo=tensorflow&logoColor=white)
![BERT](https://img.shields.io/badge/BERT-Transformer-yellow?style=for-the-badge)

<br>

<p align="center">
  <b>Klasifikasi otomatis teks lowongan pekerjaan berbasis NLP</b><br>
  Neural Network | Transfer Learning | Pretrained BERT
</p>

</div>

---

## 📝 Deskripsi Proyek
Proyek ini bertujuan untuk melakukan **klasifikasi teks lowongan pekerjaan** menggunakan pendekatan **Natural Language Processing (NLP)**.  
Model dikembangkan dengan membandingkan **Neural Network konvensional** dan **Transfer Learning menggunakan pretrained BERT** untuk melihat performa klasifikasi teks yang lebih kompleks.

Proyek ini dibuat sebagai bagian dari **tugas / penelitian Machine Learning** dengan fokus pada pemanfaatan model bahasa modern untuk memahami konteks deskripsi pekerjaan.

---

📊 Dataset
Dataset yang digunakan berupa **teks lowongan pekerjaan** dalam bentuk spreadsheet.

🔗 **Link Dataset:**  
https://docs.google.com/spreadsheets/d/1N1Dm-NXdpa-L4JcxLK76ihNyirI9zgzjh0hG3vZABqY/edit?usp=sharing

### Informasi Dataset:
- **Tipe Data:** Teks (judul & deskripsi lowongan)
- **Label:** Kategori / jenis pekerjaan
- **Bahasa:** Indonesia
- **Format:** Google Spreadsheet (.xlsx / .csv)

---

⚙️ Tahapan Preprocessing
Tahapan preprocessing teks yang dilakukan meliputi:

- Case folding (lowercase)
- Penghapusan tanda baca & karakter khusus
- Tokenisasi teks
- Stopword removal
- Padding & truncation (khusus BERT)
- Encoding label

🧠 Model yang Digunakan
Proyek ini menggunakan dua pendekatan utama:

| Tipe Model | Nama Model | Deskripsi |
|----------|-----------|----------|
| Neural Network | Feed Forward Neural Network | Model dasar berbasis embedding dan dense layer |
| Transfer Learning | **Pretrained BERT** | Model Transformer dengan bobot pretrained untuk bahasa alami |

 📈 Evaluasi Model
Evaluasi dilakukan menggunakan beberapa metrik berikut:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

Ringkasan Hasil (Contoh)
| Model | Accuracy | Keterangan |
|------|----------|------------|
| Neural Network | 0.8x | Cukup baik untuk teks sederhana |
| BERT Pretrained | **0.9x** | Performa terbaik, mampu memahami konteks kalimat |

> **Kesimpulan:**  
Model **BERT pretrained** memberikan hasil paling optimal karena mampu menangkap konteks semantik pada deskripsi lowongan pekerjaan.

👨‍💻 Identitas Pengembang

Proyek ini dibuat sebagai syarat kelulusan praktikum.

Nama: Lika Anjelina

NIM: 👨‍💻 Identitas Pengembang

Proyek ini dibuat sebagai syarat kelulusan praktikum.

Nama: Lika Anjelina

NIM: 202210370311269

Kelas: Machine Learning C

Universitas: Universitas Muhammadiyah Malang

Kelas: Machine Learning C

Program Studi: Informatika

Universitas: Universitas Muhammadiyah Malang
