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
- source venv/bin/activate   # Linux/Mac
- venv\Scripts\activate      # Windows

---

pip install -r requirements.txt


---

## Instalasi & Setup

1. Clone repository ini:

```bash
git clone https://github.com/username/repo-analisis-sentimen.git
cd repo-analisis-sentimen
```
## Classification Report

| Label                  | Precision | Recall | F1-Score | Support |
|------------------------|-----------|--------|----------|---------|
| Anxiety                | 0.81      | 0.81   | 0.81     | 779     |
| Bipolar                | 0.87      | 0.72   | 0.79     | 580     |
| Depression             | 0.71      | 0.73   | 0.72     | 3100    |
| Normal                 | 0.87      | 0.95   | 0.91     | 3327    |
| Personality Disorder   | 0.68      | 0.60   | 0.63     | 248     |
| Stress                 | 0.73      | 0.48   | 0.58     | 557     |
| Suicidal               | 0.67      | 0.65   | 0.66     | 2018    |
| **Accuracy**           |           |        | 0.77     | 10609   |
| **Macro Avg**          | 0.76      | 0.71   | 0.73     | 10609   |
| **Weighted Avg**       | 0.77      | 0.77   | 0.77     | 10609   |


