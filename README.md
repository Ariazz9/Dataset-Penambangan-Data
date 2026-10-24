# Dataset Penambangan Data

Repository ini berisi dataset yang digunakan untuk memenuhi tugas mata kuliah **Penambangan Data**.

## Daftar Dataset

### 1. Stroke Prediction Dataset

**File:** [`healthcare-dataset-stroke-data.csv`](healthcare-dataset-stroke-data.csv)

Dataset ini berisi informasi demografis dan kondisi kesehatan individu yang digunakan untuk mempelajari klasifikasi risiko kejadian stroke.

**Tujuan penggunaan:**
- Menampilkan dataset dalam bentuk DataFrame menggunakan Pandas.
- Memahami tujuan dataset dan karakteristik setiap fitur.
- Mengidentifikasi variabel target untuk klasifikasi, yaitu `stroke`.

**Sumber dataset:** [Stroke Prediction Dataset — Kaggle](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset]

### 2. Bank Marketing Dataset

**File:** [`bank.csv`](bank.csv)

Dataset ini berkaitan dengan kampanye pemasaran melalui telepon yang dilakukan oleh sebuah institusi perbankan di Portugal. Dataset digunakan untuk mempelajari klasifikasi apakah seorang nasabah berlangganan deposito berjangka atau tidak.

**Tujuan penggunaan:**
- Menerapkan model klasifikasi pada dataset dengan distribusi kelas yang tidak seimbang.
- Membandingkan performa model sebelum dan sesudah penyeimbangan data pada data pelatihan (*training set*).
- Mengevaluasi performa model menggunakan metrik *accuracy*, *precision*, dan *recall*.

Teknik penyeimbangan kelas yang dapat digunakan meliputi **SMOTE** dan **ADASYN**.

**Sumber dataset:** [Bank Marketing — UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/222/bank%2Bmarketing)

## Tools dan Teknologi

- Python
- Pandas dan NumPy
- Scikit-learn
- Google Colab atau Jupyter Notebook

## Catatan

Dataset pada repository ini digunakan untuk keperluan pembelajaran dan pengerjaan tugas akademik. Hak penggunaan serta atribusi dataset mengikuti ketentuan dari sumber aslinya.

## Referensi

1. Fedesoriano. (n.d.). *Stroke Prediction Dataset* [Dataset]. Kaggle. https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset
2. Moro, S., Rita, P., & Cortez, P. (2014). *Bank Marketing* [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5K306
