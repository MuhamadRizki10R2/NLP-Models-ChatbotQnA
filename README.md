# 🤖 Chatbot.Stella — NLP Mini Project

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

---

## 📌 Deskripsi Project

**Chatbot.Stella** adalah chatbot berbasis **Natural Language Processing (NLP)** yang dibuat menggunakan Python.  
Project ini dirancang untuk menjawab pertanyaan seputar **SMK Telkom Lampung** berdasarkan dataset pertanyaan dan jawaban yang telah disediakan.

Sistem bekerja dengan mencocokkan pertanyaan pengguna terhadap dataset menggunakan metode **TF-IDF Vectorizer** dan **Cosine Similarity**.

---

## 🚀 Fitur Utama

✅ Membersihkan teks otomatis (Text Preprocessing)  
✅ Mengubah teks menjadi data numerik menggunakan TF-IDF  
✅ Mengukur kemiripan pertanyaan dengan Cosine Similarity  
✅ Menampilkan jawaban otomatis dari dataset  
✅ Visualisasi data dengan WordCloud, TF-IDF, dan PCA  
✅ Bisa dikembangkan ke Flask / Gradio / Website

---

## 🧠 Algoritma yang Digunakan

### 🔹 Text Preprocessing
Membersihkan teks dengan cara:
- lowercase
- menghapus simbol
- menghapus spasi berlebih

### 🔹 TF-IDF (Term Frequency - Inverse Document Frequency)
Digunakan untuk mengetahui kata penting pada setiap pertanyaan.

### 🔹 Cosine Similarity
Mengukur tingkat kemiripan antara pertanyaan user dengan dataset.

### 🔹 PCA (Principal Component Analysis)
Digunakan untuk visualisasi sebaran data ke 2 dimensi.

---

## 📚 Library yang Digunakan

| Library | Fungsi |
|--------|--------|
| Pandas | Manipulasi dataset |
| NumPy | Operasi numerik |
| re | Text preprocessing |
| Matplotlib | Visualisasi grafik |
| Seaborn | Grafik statistik |
| Scikit-learn | TF-IDF, Cosine Similarity, PCA |
| WordCloud | Visualisasi kata populer |

---

## 📊 Visualisasi Data

Project ini menampilkan:

- ☁️ WordCloud kata paling sering muncul  
- 📈 15 kata kunci terpenting berdasarkan TF-IDF  
- 🔵 Scatter Plot PCA sebaran pertanyaan  

---

## 💬 Cara Menjalankan

```bash
pip install pandas numpy matplotlib seaborn scikit-learn wordcloud

## 📂 Struktur Project
📁 Chatbot-Stella
 ┣ 📄 chatbot_stella.py
 ┣ 📄 dataset_Qa.csv
 ┣ 📄 README.md
