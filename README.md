# Sentiment Analysis PeduliLindungi

Proyek ini bertujuan untuk menganalisis sentimen pengguna terhadap aplikasi PeduliLindungi, platform yang digunakan selama pandemi COVID-19 di Indonesia. Analisis ini dilakukan dengan mengumpulkan ulasan dari pengguna di Google Play Store dan App Store, kemudian memproses data tersebut untuk menentukan apakah sentimen yang diberikan bersifat positif, netral, atau negatif.

Langkah-Langkah Proyek
1. Pengumpulan Data
   - Scraping ulasan pengguna dari Google Play Store dan App Store menggunakan Google Play Scraper dan App Store API.
   - Membersihkan data dengan menghapus duplikasi, tanda baca, serta kata-kata tidak relevan (stopwords).

2. Preprocessing Teks

   - Tokenisasi: Memecah kalimat menjadi kata-kata individual.
   - Stemming & Lemmatization: Mengubah kata ke bentuk dasar untuk menyamakan variasi kata.
   - Stopword Removal: Menghapus kata-kata umum yang tidak memiliki nilai sentimen.

3. Labeling Sentimen

Menggunakan lexicon-based approach (kamus sentimen) atau model machine learning untuk mengklasifikasikan sentimen.
Sentimen dikategorikan menjadi positif, negatif, atau netral.

4. Pelatihan Model

Pelatihan Model pada project ini menggunakan metode supervised Learning yaitu Multinomial Naive Bayes
