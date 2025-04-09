# Tugas NLP - Pemodelan Sekuens dengan RNN dan LSTM untuk Klasifikasi Teks

Repositori ini merupakan hasil pengerjaan tugas mata kuliah **Natural Language Processing** yang berfokus pada klasifikasi teks berita BBC menggunakan model **Recurrent Neural Network (RNN)** dan **Long Short-Term Memory (LSTM)**.

## Tujuan
- Mengimplementasikan model RNN dan LSTM untuk klasifikasi teks
- Menggunakan pre-trained word embeddings (GloVe)
- Melakukan analisis kinerja model berdasarkan hidden size dan panjang sequence
- Visualisasi hidden state dan evaluasi hasil klasifikasi

## Dataset

- Sumber: [BBC Articles Dataset - Kaggle](https://www.kaggle.com/datasets/jacopoferretti/bbc-articles-dataset)
- Jumlah Kategori: `business`, `entertainment`, `politics`, `sport`, `tech`
- Total samples: 2,225 articles


## Alur Pengerjaan : 

- Load Data
- Exploratory Data Analysis
- Preprocessing: Tokenization, stopwords removal, stemming
- Embedding: Pretrained GloVe vectors (100D)
- Model Variants: RNN and LSTM with hidden sizes 128, 256, 512
- Evaluation: Accuracy, Precision, Recall, F1-score

## Evaluasi Model

> Hasil menunjukkan bahwa **LSTM mengungguli RNN** secara signifikan dalam menangani dependensi panjang pada teks.


