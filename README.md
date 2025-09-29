# 🚢 Titanic Survival Analysis – Week 1 (ML & Deep Learning Basics)

## 📌 Deskripsi
Proyek ini adalah eksplorasi data (EDA) menggunakan dataset **Titanic** yang tersedia secara publik.  
Tujuan utama: memahami pola survival berdasarkan faktor seperti **gender, kelas kabin, dan usia**.  

Proyek ini merupakan bagian dari **Portofolio AI/ML & Deep Learning** (Week 1 – Fondasi Python & Data).  

---

## 📊 Dataset
- **Sumber**: [Titanic dataset (Kaggle)](https://www.kaggle.com/c/titanic/data) atau mirror di [datasciencedojo GitHub](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)  
- **Jumlah data**: 891 baris, 12 kolom  
- Kolom penting:
  - `Survived`: 0 = tidak selamat, 1 = selamat  
  - `Pclass`: kelas kabin (1, 2, 3)  
  - `Sex`: gender  
  - `Age`: umur penumpang  
  - `Fare`: harga tiket  

---

## 🔍 Analisis yang Dilakukan
1. Distribusi survival secara keseluruhan.  
2. Survival rate berdasarkan **gender**.  
3. Survival rate berdasarkan **kelas kabin (Pclass)**.  
4. Analisis usia vs survival (menggunakan visualisasi histogram).  

---

## 🛠️ Tools & Library
- Python 3  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  

---

## 📈 Hasil Utama
- Perempuan memiliki survival rate lebih tinggi dibanding laki-laki.  
- Penumpang kelas 1 lebih banyak selamat dibanding kelas 3.  
- Anak-anak cenderung memiliki peluang survival lebih tinggi daripada orang dewasa.  

Contoh visualisasi:  

![Survival by Gender](example_plot.png)  
*(opsional: bisa tambahkan screenshot grafik dari notebook)*  

---

## 🚀 Cara Menjalankan
1. Clone repo ini:
   ```bash
   git clone https://github.com/username/ai_ml_exploratory.git
   cd ai_ml_exploratory/week1_foundation
