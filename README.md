# Analisis Sentimen dengan SVM

Proyek ini bertujuan untuk melakukan **analisis sentimen** pada teks (Statement) menggunakan **Support Vector Machine (SVM)**.  
Dataset dapat berupa komentar pengguna dengan label Status `Normal`, `Depression`,  `Suicidal`, `anxiety`, `bipolar`, `stress`, `personality disorder`

---

## Library yang Digunakan
- `pandas`, `numpy` → manipulasi data
- `nltk` → text preprocessing (tokenisasi, stopwords, stemming)
- `sklearn` → vectorisasi (TF-IDF), SVM, evaluasi
- `matplotlib`, `wordcloud` → visualisasi

---

## Preprocessing Teks
1. Lowercasing  
2. Tokenisasi  
3. Stopword removal (kata-kata umum, tanda baca, angka)  
4. Stemming / Lemmatization 
5. Normalisasi teks  

---

python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

---

pip install -r requirements.txt


---

## Instalasi & Setup

1. Clone repository ini:

```bash
git clone https://github.com/username/repo-analisis-sentimen.git
cd repo-analisis-sentimen
