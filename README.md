# Analisis Sentimen Counter-Strike 2 (CS2) dengan Support Vector Machine (SVM)

<img src="https://drive.google.com/uc?export=view&id=1KvWT7JU8iYAhCEeOguLqZjqqID2_LZjT" alt="CS2 Banner" width="800">

Proyek ini merupakan implementasi dari penelitian **Analisis Sentimen Komunitas Counter-Strike 2 (CS2) Menggunakan Support Vector Machine (SVM)**:contentReference[oaicite:0]{index=0}.  
Fokus penelitian adalah mengklasifikasikan ulasan pemain di **Steam** menjadi tiga kategori: **positif, negatif, netral** menggunakan metode **Text Mining + TF-IDF + SVM**.

---

## 📌 Abstrak
Counter-Strike 2 (CS2) adalah game yang mendapat banyak antusiasme sejak rilis.  
Ulasan pengguna di Steam digunakan untuk memahami sentimen komunitas. Data dikumpulkan via **Apify**, diproses melalui *cleaning, tokenisasi, stopword removal, lemmatization*, lalu diekstraksi menggunakan **TF-IDF**.  
Model **SVM (One-vs-Rest)** digunakan untuk klasifikasi.  

- Akurasi tanpa SMOTE: **81,95%**  
- Akurasi dengan SMOTE: **82,18%**  

Penelitian ini membuktikan potensi SVM dalam analisis sentimen berbasis teks:contentReference[oaicite:1]{index=1}.

---

## 📂 Struktur Repo
```bash
analisis-sentimen-cs2-svm/
├─ notebooks/                
│  ├─ cleaning_dataset.ipynb
│  ├─ tfidf_vectorizer.ipynb
│  ├─ svm_model_final.ipynb
├─ data/
│  └─ dataset_non_indonesian.csv     
├─ requirements.txt          
├─ LICENSE                   
└─ README.md
