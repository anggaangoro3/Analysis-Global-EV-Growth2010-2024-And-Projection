# 🌍 Analysis Global EV Growth & Projection (2010-2024)

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?logo=jupyter&logoColor=white)](https://jupyter.org/try)
[![Pandas](https://img.shields.io/badge/Data%20Processing-Pandas-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

> **Project Data Science & Analysis**: Analisis komprehensif tren adopsi kendaraan listrik (EV) global serta visualisasi skenario proyeksi masa depan berdasarkan data International Energy Agency (IEA).

---

## 📑 Table of Contents

| Section | Description |
| :--- | :--- |
| [**📖 Overview**](#-overview) | Latar belakang proyek dan sumber data. |
| [**🎯 Objective**](#-objective) | Tujuan analisis dan pertanyaan bisnis. |
| [**⚙️ Process & Methodology**](#️-process--methodology) | Langkah teknis analisis data. |
| [**📊 Key Insights**](#-key-insights) | Temuan utama dari data historis. |
| [**🔮 Future Outlook**](#-future-outlook) | Visualisasi skenario proyeksi IEA (STEPS & APS). |
| [**🛠️ Tech Stack**](#️-tech-stack) | Bahasa dan pustaka yang digunakan. |
| [**💻 Getting Started**](#-getting-started) | Cara menjalankan proyek ini. |

---

## 📖 Overview

Perubahan iklim mendorong transisi energi global, dengan sektor transportasi sebagai fokus utama dekarbonisasi. Proyek ini menganalisis dataset **Global EV Outlook** dari *International Energy Agency (IEA)* untuk memahami dinamika pasar kendaraan listrik.

Analisis ini mencakup evaluasi penjualan historis (2010-2024), perbandingan antar powertrain (BEV vs PHEV), serta dominasi pasar regional (China, Eropa, USA). Selain itu, proyek ini memvisualisasikan data proyeksi resmi dari IEA untuk memberikan gambaran potensi pertumbuhan pasar di masa depan.

---

## 🎯 Objective

Tujuan utama dari analisis ini adalah:

1.  **Historical Analysis**: Memetakan pertumbuhan eksponensial penjualan EV dan *stock share* di berbagai belahan dunia.
2.  **Regional Comparison**: Mengidentifikasi pemimpin pasar dan membandingkan tingkat adopsi antara negara maju dan berkembang.
3.  **Future Outlook**: Menganalisis skenario masa depan berdasarkan data proyeksi IEA (*Stated Policies Scenario* vs *Announced Pledges Scenario*) untuk melihat arah tren industri hingga 2030+.

---

## ⚙️ Process & Methodology

Proyek ini dijalankan melalui pipeline analisis data berikut:

### 1. Data Preparation
* **Data Cleaning**: Menangani *missing values*, standarisasi nama kolom, dan filterisasi data relevan (kategori "EV Sales", "EV Stock", dan "Projection").
* **Feature Selection**: Memilih variabel kunci seperti Tahun, Wilayah, Powertrain (BEV/PHEV), dan kategori Proyeksi.

### 2. Exploratory Data Analysis (EDA)
* Visualisasi tren pertumbuhan tahunan (YoY) menggunakan *Line Chart* dan *Bar Chart*.
* Analisis komposisi pasar (BEV vs PHEV) untuk melihat preferensi konsumen.
* Segmentasi geografis untuk melihat kontribusi regional terhadap pasar global.

### 3. Scenario Analysis (Projections)
* Membandingkan data historis dengan data proyeksi masa depan yang disediakan dalam dataset IEA, yaitu:
    * **STEPS (Stated Policies Scenario)**: Proyeksi berdasarkan kebijakan pemerintah yang sudah ditetapkan saat ini.
    * **APS (Announced Pledges Scenario)**: Proyeksi ambisius jika seluruh target iklim yang dijanjikan negara-negara tercapai.

---

## 📊 Key Insights

Berdasarkan analisis data historis (2010-2024):

* **Pertumbuhan Eksponensial**: Penjualan EV global menunjukkan tren kenaikan yang signifikan, terutama pasca-2020, didorong oleh kebijakan insentif pemerintah dan kematangan teknologi baterai.
* **Dominasi BEV**: *Battery Electric Vehicles* (BEV) secara konsisten mengungguli *Plug-in Hybrid* (PHEV) dalam pangsa pasar, menunjukkan pergeseran konsumen menuju kendaraan full elektrik.
* **China sebagai Pemimpin Pasar**: China memegang pangsa pasar terbesar secara global, diikuti oleh Eropa dan Amerika Serikat, menegaskan posisinya sebagai pusat manufaktur dan adopsi EV dunia.

---

## 🔮 Future Outlook

Visualisasi data proyeksi (STEPS & APS) dalam notebook ini mengindikasikan:

* **Tren Bullish Berlanjut**: Baik skenario konservatif (STEPS) maupun ambisius (APS) menunjukkan bahwa adopsi EV akan terus meningkat drastis.
* **Gap Antar Skenario**: Terdapat perbedaan volume yang signifikan antara kebijakan saat ini (STEPS) dengan target iklim (APS), menyoroti perlunya kebijakan yang lebih agresif untuk mencapai target *Net Zero*.

---

## 🛠️ Tech Stack

* **Bahasa Pemrograman**: Python 3.10+
* **Data Manipulation**: Pandas, NumPy
* **Visualization**: Matplotlib, Seaborn

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
