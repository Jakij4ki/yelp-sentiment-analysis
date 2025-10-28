# Yelp Business Dataset – Sentiment Analysis  

## 📌 Judul  
Perbandingan Performa SVM (TF-IDF, Word2Vec, GloVe) dan BERT dalam Analisis Sentimen pada Ulasan Restoran Yelp

---

## 📖 Latar Belakang  
Analisis sentimen bertujuan untuk mengklasifikasikan opini dalam teks menjadi positif, negatif, atau netral. Ulasan daring seperti di Yelp memiliki pengaruh besar terhadap reputasi bisnis dan keputusan konsumen, khususnya pada sektor kuliner. Dengan jumlah ulasan yang terus bertambah, analisis manual tidak lagi efisien sehingga diperlukan pendekatan berbasis Machine Learning dan Deep Learning.  

Metode klasik seperti SVM dengan TF-IDF populer karena sederhana dan efisien, namun terbatas dalam menangkap makna semantik. Embedding seperti Word2Vec dan GloVe memberikan representasi kata yang lebih kaya, sementara BERT mampu memahami konteks kalimat secara lebih mendalam.  

Masih jarang penelitian yang membandingkan secara langsung SVM (TF-IDF, Word2Vec, Word2Vec Google, GloVe) dengan BERT (cased & uncased) pada domain ulasan restoran yang cenderung bersifat informal. Penelitian ini berupaya menjembatani kesenjangan tersebut sekaligus memberikan manfaat praktis bagi pelaku bisnis dalam memahami opini pelanggan.  

---

## 🎯 Tujuan  
1. Membandingkan performa SVM (TF-IDF, Word2Vec self-trained, Word2Vec Google pretrained, GloVe) dengan BERT (cased & uncased).  
2. Mengevaluasi kemampuan embedding klasik vs transformer dalam memahami konteks semantik.  
3. Menganalisis pengaruh ukuran dan jenis data pada Word2Vec (small vs big dataset).  
4. Membandingkan embedding domain-spesifik (Word2Vec self-trained) dengan embedding umum (Word2Vec Google, GloVe pretrained).  

---

## 📂 Dataset  
Sumber dataset: [Yelp Open Dataset](https://business.yelp.com/data/resources/open-dataset/)  

---

## 🚀 Future Works  
- Perbaikan dataset: labeling manual tambahan & memperbesar jumlah data.  
- Eksperimen arsitektur lain: DistilBERT, RoBERTa, IndoBERT, serta baseline klasik lain seperti Naive Bayes & Logistic Regression.  
- Fine-tuning lebih dalam: hyperparameter tuning & domain adaptation untuk ulasan kuliner.  
- Ensemble model: kombinasi SVM + BERT untuk peningkatan akurasi.  
- Implementasi aplikasi nyata: dashboard analisis sentimen real-time untuk pelaku bisnis restoran.  

---

## 👨‍💻 Credits  
Project developed by:  
- Dzaky Rezandi
- Muhammad Faris El Hakim
