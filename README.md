# Business Yelp Dataset

# Perbandingan Performansi Model SVM (TF-IDF, Word2Vec, GloVe) dan BERT dalam Analisis Sentimen pada Ulasan Restoran di Yelp

## Latar Belakang
Analisis sentimen digunakan untuk mengidentifikasi opini dalam teks apakah bersifat positif, negatif, atau netral. Ulasan daring seperti di Yelp berperan penting dalam membentuk reputasi dan keputusan konsumen, terutama di bidang kuliner. Karena jumlah ulasan yang terus bertambah, analisis manual tidak lagi efisien sehingga diperlukan metode berbasis kecerdasan buatan.

Metode klasik seperti SVM banyak digunakan karena sederhana dan efisien, meski sering mengandalkan TF-IDF yang terbatas dalam menangkap makna semantik. Pendekatan embedding seperti Word2Vec dan GloVe memberikan representasi kata yang lebih kaya, sementara model transformer seperti BERT lebih unggul dalam memahami konteks kalimat.

Masih sedikit penelitian yang secara langsung membandingkan SVM (TF-IDF, Word2Vec, Word2Vec Google, dan GloVe) dengan BERT (cased dan uncased) khusus pada ulasan restoran yang menggunakan bahasa informal. Penelitian ini berupaya menjembatani kesenjangan tersebut dan diharapkan dapat memberikan pemahaman lebih komprehensif sekaligus manfaat praktis bagi pelaku bisnis dalam memahami opini pelanggan.

## Tujuan
1. Membandingkan performa Support Vector Machine (dengan TF-IDF, Word2Vec self-trained, Word2Vec Google pretrained, dan GloVe) dengan model BERT (cased dan uncased) dalam analisis sentimen pada ulasan Yelp.
2. Mengevaluasi kemampuan word embedding dan model berbasis transformer dalam memahami konteks semantik serta pola bahasa.
3. Menganalisis pengaruh ukuran dan jenis data pelatihan terhadap kualitas representasi kata pada Word2Vec (self-trained dengan dataset kecil dan besar).
4. Membandingkan efektivitas embedding domain spesifik (Word2Vec self-trained) dengan embedding umum (Google Word2Vec dan GloVe pretrained) dalam analisis sentimen ulasan restoran.

## Dataset
Sumber dataset: https://business.yelp.com/data/resources/open-dataset/

## Future Works
- Perbaikan dataset
Melakukan labeling manual pada sebagian data untuk meningkatkan kualitas label, serta menambah jumlah data agar model dapat belajar lebih baik dari variasi ulasan yang lebih luas
- Eksperimen dengan arsitektur lain
Mencoba model transformer yang lebih ringan atau lebih baru seperti DistilBERT, RoBERTa, atau IndoBERT, serta membandingkannya dengan pendekatan lain seperti Naive Bayes atau Logistic Regression sebagai baseline tambahan.
- Fine-tuning lebih mendalam 
Melakukan penyesuaian parameter (hyperparameter tuning) atau training lanjutan pada domain kuliner agar BERT dapat lebih kontekstual memahami gaya bahasa ulasan restoran.
- Eksperimen ensemble 
Mengombinasikan keunggulan model klasik (SVM dengan Word2Vec/TF-IDF) dan model transformer (BERT) untuk melihat potensi peningkatan akurasi melalui pendekatan hybrid.
Integrasi ke sistem aplikasi nyata 
Mengembangkan prototipe dashboard analisis sentimen yang dapat digunakan oleh pelaku bisnis restoran untuk memantau opini pelanggan secara real-time.
