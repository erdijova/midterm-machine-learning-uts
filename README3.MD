# Customer Clustering Analysis using Machine Learning

## Identitas Mahasiswa

- Nama : ERDI JOVA PRADANA
- NIM : 101032300027
- Kelas : TK-47-04

---

## Deskripsi Project

Project ini merupakan implementasi Machine Learning untuk melakukan customer segmentation menggunakan beberapa algoritma clustering seperti K-Means, Hierarchical Clustering, dan DBSCAN. 

Tujuan dari project ini adalah untuk mengelompokkan customer berdasarkan pola penggunaan kartu kredit sehingga dapat membantu memahami karakteristik pelanggan dan mendukung pengambilan keputusan bisnis.

---

## Dataset

Dataset yang digunakan berisi informasi penggunaan kartu kredit customer seperti:

- Balance
- Purchases
- Cash Advance
- Credit Limit
- Payments
- Minimum Payments
- Purchase Frequency
- Dan fitur lainnya

---

## Tahapan Project

Tahapan yang dilakukan pada project ini meliputi:

1. Import Library
2. Load Dataset
3. Exploratory Data Analysis (EDA)
4. Deteksi Missing Value dan Outlier
5. Data Preprocessing
6. Feature Scaling
7. Dimensionality Reduction menggunakan PCA
8. Penentuan jumlah cluster optimal
9. Clustering menggunakan:
   - K-Means
   - Hierarchical Clustering
   - DBSCAN
10. Evaluasi Model Clustering
11. Visualisasi dan Interpretasi Cluster

---

## Evaluasi Model

Model clustering dievaluasi menggunakan beberapa metrik:

- Elbow Method
- Silhouette Score
- Davies-Bouldin Score
- Calinski-Harabasz Score

Berdasarkan hasil evaluasi, jumlah cluster optimal yang dipilih adalah **K = 2**.

---

## Visualisasi

Project ini juga menampilkan beberapa visualisasi seperti:

- Heatmap Korelasi
- Boxplot Deteksi Outlier
- PCA Visualization
- t-SNE Visualization
- Radar Chart Profil Cluster
- Heatmap Profil Cluster
- Distribusi Customer per Cluster

---

## Tools dan Library

Project ini dibuat menggunakan:

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Kesimpulan

Hasil clustering menunjukkan bahwa customer dapat dibagi menjadi dua kelompok utama berdasarkan pola penggunaan kartu kredit. Setiap cluster memiliki karakteristik perilaku customer yang berbeda sehingga dapat digunakan untuk analisis segmentasi pelanggan dan strategi bisnis yang lebih tepat.

---
