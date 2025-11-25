# 🌍 Analysis Global EV Growth & Projection (2010-2024)

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?logo=jupyter&logoColor=white)](https://jupyter.org/try)
[![Scikit-Learn](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-F7931E?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Data%20Processing-Pandas-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

> **Project Data Science & Forecasting**: Analisis komprehensif tren adopsi kendaraan listrik (EV) global menggunakan data historis IEA dan pemodelan prediktif untuk memproyeksikan pertumbuhan masa depan.

---

## 📑 Table of Contents

| Section | Description |
| :--- | :--- |
| [**📖 Overview**](#-overview) | Latar belakang proyek dan sumber data. |
| [**🎯 Objective**](#-objective) | Tujuan analisis dan pertanyaan bisnis. |
| [**⚙️ Process & Methodology**](#️-process--methodology) | Langkah teknis dari *cleaning* hingga *modeling*. |
| [**📊 Key Insights**](#-key-insights) | Temuan utama dari data historis. |
| [**🔮 Future Projection**](#-future-projection) | Hasil prediksi model Machine Learning. |
| [**🛠️ Tech Stack**](#️-tech-stack) | Bahasa dan pustaka yang digunakan. |
| [**📂 Project Structure**](#-project-structure) | Struktur direktori repositori. |

---

## 📖 Overview

Perubahan iklim mendorong transisi energi global, dengan sektor transportasi sebagai fokus utama dekarbonisasi. Proyek ini menganalisis dataset **Global EV Outlook 2024** dari *International Energy Agency (IEA)* untuk memahami dinamika pasar kendaraan listrik.

Analisis ini mencakup evaluasi penjualan historis (2010-2024), perbandingan antar powertrain (BEV vs PHEV), serta dominasi pasar regional (China, Eropa, USA). Selain itu, proyek ini menerapkan algoritma *Machine Learning* untuk memprediksi tren adopsi EV di tahun-tahun mendatang.

---

## 🎯 Objective

Tujuan utama dari analisis ini adalah:

1.  **Historical Analysis**: Memetakan pertumbuhan eksponensial penjualan EV dan *stock share* di berbagai belahan dunia.
2.  **Regional Comparison**: Mengidentifikasi pemimpin pasar dan membandingkan tingkat adopsi antara negara maju dan berkembang.
3.  **Future Forecasting**: Membangun model regresi untuk memproyeksikan volume penjualan EV global hingga tahun 2030, memberikan wawasan bagi pemangku kepentingan industri energi dan otomotif.

---

## ⚙️ Process & Methodology

Proyek ini dijalankan melalui pipeline analisis data berikut:

### 1. Data Preparation
* **Data Cleaning**: Menangani *missing values*, standarisasi nama kolom, dan filterisasi data relevan (kategori "EV Sales" dan "EV Stock").
* **Feature Selection**: Memilih variabel kunci seperti Tahun, Wilayah, Powertrain (BEV/PHEV), dan Nilai Penjualan.

### 2. Exploratory Data Analysis (EDA)
* Visualisasi tren pertumbuhan tahunan (YoY) menggunakan *Line Chart* dan *Bar Chart*.
* Analisis komposisi pasar (BEV vs PHEV) untuk melihat preferensi konsumen.
* Segmentasi geografis untuk melihat kontribusi regional terhadap pasar global.

### 3. Predictive Modeling
* Menggunakan **Polynomial Regression** (Scikit-Learn) untuk menangkap pola pertumbuhan non-linear (eksponensial) dari data adopsi EV.
* Evaluasi model menggunakan metrik statistik untuk memastikan akurasi garis tren prediksi.

---

## 📊 Key Insights

Berdasarkan analisis data historis (2010-2024):

* **Pertumbuhan Eksponensial**: Penjualan EV global menunjukkan tren kenaikan yang signifikan, terutama pasca-2020, didorong oleh kebijakan insentif pemerintah dan kematangan teknologi baterai.
* **Dominasi BEV**: *Battery Electric Vehicles* (BEV) secara konsisten mengungguli *Plug-in Hybrid* (PHEV) dalam pangsa pasar, menunjukkan pergeseran konsumen menuju kendaraan full elektrik.
* **China sebagai Pemimpin Pasar**: China memegang pangsa pasar terbesar secara global, diikuti oleh Eropa dan Amerika Serikat, menegaskan posisinya sebagai pusat manufaktur dan adopsi EV dunia.

---

## 🔮 Future Projection

Model **Polynomial Regression** yang dikembangkan dalam notebook ini memproyeksikan:

* Kelanjutan tren positif (bullish) untuk adopsi EV global di tahun-tahun mendatang.
* Kurva adopsi diprediksi akan semakin curam, mengindikasikan percepatan transisi energi massal menjelang 2030.
* *(Lihat notebook untuk grafik proyeksi detail dan angka spesifik prediksi tahunan)*.

---

## 🛠️ Tech Stack

* **Bahasa Pemrograman**: Python 3.10+
* **Data Manipulation**: Pandas, NumPy
* **Visualization**: Matplotlib, Seaborn
* **Machine Learning**: Scikit-Learn (LinearRegression, PolynomialFeatures, Train-Test Split)

---

## 💻 Getting Started

1. Clone repositori ini:
   ```bash
   git clone [https://github.com/anggaangoro3/Analysis-Global-EV-Growth2010-2024-And-Projection.git](https://github.com/anggaangoro3/Analysis-Global-EV-Growth2010-2024-And-Projection.git)
   ```
2. Install library yang dibutuhkan:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Buka file notebook:
   `Analysis_Global_EV_Growth2010_2024_And_Projection.ipynb`

## 📂 Project Structure

```text
analysis-global-ev-growth/
│
├── 📂 data Link: https://www.kaggle.com/datasets/patricklford/global-ev-sales-2010-2024/data
│
├── 📓 Analysis_Global_EV_Growth...ipynb       # Notebook utama (EDA & Modeling)
└── 📄 README.md                               # Dokumentasi Proyek
