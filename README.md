# 📊 Proyek Analisis Sentimen Ulasan Aplikasi MyBCA  
### Natural Language Processing (NLP)

Project ini merupakan implementasi **analisis sentimen** terhadap ulasan pengguna aplikasi **MyBCA** dengan tujuan mengklasifikasikan sentimen menjadi **positif** atau **negatif**.  
Analisis dilakukan menggunakan pendekatan **Natural Language Processing (NLP)** melalui serangkaian tahapan preprocessing teks yang sistematis.

---

## 🎯 Tujuan Proyek
- Mengumpulkan data ulasan aplikasi MyBCA melalui proses scraping
- Membersihkan dan menyiapkan data teks agar siap dianalisis
- Melakukan normalisasi teks termasuk perbaikan slang word
- Memberikan label sentimen positif dan negatif
- Mengidentifikasi kata yang paling sering muncul (*most frequent words*)
- Mendeteksi sentimen baru dari ulasan pengguna

---

## 🧠 Metodologi

### 1️⃣ Data Collection
- Data ulasan aplikasi MyBCA dikumpulkan menggunakan teknik **web scraping**
- Hasil scraping disimpan dalam format `.csv`

### 2️⃣ Text Preprocessing
Tahapan preprocessing yang digunakan meliputi:
- **Cleaning Text**  
  Menghapus karakter khusus, angka, dan simbol yang tidak relevan
- **Case Folding**  
  Mengubah seluruh teks menjadi huruf kecil
- **Tokenizing**  
  Memecah kalimat menjadi token/kata
- **Filtering**  
  Menghapus stopwords
- **Stemming**  
  Mengubah kata ke bentuk dasar
- **Convert List to Sentence**  
  Menggabungkan token kembali menjadi kalimat

### 3️⃣ Text Normalization
- Melakukan **perbaikan slang word** menjadi kata baku

### 4️⃣ Labeling Sentiment
- Pemberian label sentimen **positif** dan **negatif** pada ulasan

### 5️⃣ Exploratory Analysis
- Analisis **kata yang paling sering muncul (most frequent words)**

---

## 🚀 Teknologi & Tools
- Python
- Jupyter Notebook
- Pandas & NumPy
- Matplotlib
- Seaborn
- Wordcloud
- nltk
- gensim
- Natural Language Processing (NLP)
- Text Preprocessing & Normalization

---

## 📊 Output Project
- Dataset ulasan yang telah dipreprocessing
- Label sentimen positif dan negatif
- Daftar kata yang paling sering muncul
- Sistem sederhana untuk mendeteksi sentimen ulasan baru

---

## 📌 Catatan
- Dataset berasal dari ulasan pengguna aplikasi **MyBCA**
- Project ini dapat dikembangkan lebih lanjut dengan:
  - Model klasifikasi (Random Forest, SVM, TF-IDF, Word2Vec dll.)
  - Visualisasi sentimen
  - Implementasi prediksi sentimen secara real-time
- Cocok digunakan sebagai **project akademik, riset NLP, dan portofolio data science**

---

## 👤 Author
**Nama:** Nazril Abi Widiasto  
**Project:** Analisis Sentimen Ulasan MyBCA  
**Bidang:** Natural Language Processing  
