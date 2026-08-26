# Analisis Sentimen Publik terhadap Penggunaan Artificial Intelligence di Media Sosial X

Proyek ini merupakan penelitian analisis sentimen untuk mengklasifikasikan opini publik berbahasa Indonesia terhadap penggunaan Artificial Intelligence (AI) pada media sosial X.

Penelitian menggunakan algoritma Complement Naive Bayes dengan fitur teks yang diekstraksi menggunakan TF-IDF.

## Objective

- Mengumpulkan dan mengolah data teks dari media sosial X terkait Artificial Intelligence.
- Mengklasifikasikan sentimen publik ke dalam kategori positif dan negatif.
- Mengevaluasi performa model Complement Naive Bayes dalam klasifikasi teks.

## Dataset

Dataset terdiri dari 624 tweet publik berbahasa Indonesia yang berkaitan dengan Artificial Intelligence.

Distribusi data:
- Positive: 435 tweets (69.71%)
- Negative: 189 tweets (30.29%)

Dataset kemudian dibagi menjadi:
- Training set: 499 tweets
- Testing set: 125 tweets

Pembagian data menggunakan rasio 80:20 dengan stratified split dan random_state = 42.

> Dataset mentah tidak disertakan dalam repository karena berasal dari data publik hasil scraping dan digunakan untuk keperluan penelitian akademik.

## Methodology

1. Data Collection / Scraping
2. Text Preprocessing
   - Cleaning
   - Case Folding
   - Normalization
   - Tokenizing
   - Stopword Removal
   - Stemming
3. Sentiment Labeling
4. Train-Test Split
5. TF-IDF Feature Extraction
6. Complement Naive Bayes Classification
7. Model Evaluation

## Tools & Libraries

- Python
- Google Colab
- Scikit-learn
- NLTK
- Sastrawi
- Pandas
- Matplotlib
- Seaborn

## Results

Model evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

Additional analysis includes:
- Sentiment distribution
- Word frequency analysis
- Classification error analysis

## Project Files

- `notebook/` — Google Colab notebook containing the analysis workflow
- `presentation/` — Project presentation
- `results/` — Selected visualization and model evaluation results

## Academic Context

This project was developed as part of an undergraduate thesis at Universitas Bina Sarana Informatika.

**Title:**  
"Analisis Sentimen Publik terhadap Penggunaan Artificial Intelligence pada Media Sosial X Menggunakan Algoritma Naive Bayes"

## Author

Sherly Meilani
