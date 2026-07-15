# 📊 E-Commerce Sales Analysis & Customer Segmentation

## Overview
Analisis data transaksi e-commerce Olist (Brazil) untuk mengidentifikasi 
pola penjualan, produk terlaris, dan segmentasi pelanggan menggunakan metode RFM.

## Dataset
- **Source:** [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- **Size:** 100.000+ transaksi (2016–2018)
- **Tables:** 9 file CSV

## Tools & Libraries
- Python 3.14
- Pandas, Matplotlib, Seaborn
- Jupyter Notebook

## Project Structure
project-ecommerce/
├── data/
│   ├── raw/          ← dataset original dari Kaggle
│   └── processed/    ← data setelah cleaning
├── notebooks/
│   ├── 01_eda.ipynb           ← Exploratory Data Analysis
│   ├── 02_cleaning.ipynb      ← Data Cleaning & Sales Analysis
│   └── 03_rfm.ipynb           ← RFM Segmentation
├── output/
│   └── charts/       ← hasil visualisasi
└── README.md

## Key Findings
- Kategori bed_bath_table menyumbang revenue terbesar
- Lonjakan penjualan signifikan terjadi November 2017 (Black Friday)
- Mayoritas pelanggan masuk segmen New Customers — retensi perlu ditingkatkan

## Results
| Segmen | Karakteristik | Strategi |
|---|---|---|
| Champions | Beli baru, sering, nilai besar | Loyalty reward |
| Loyal Customers | Sering beli, nilai sedang | Upsell premium |
| At Risk | Dulu aktif, sudah lama tidak beli | Win-back campaign |
| New Customers | Baru pertama beli | Onboarding |
| Lost Customers | Sangat lama tidak aktif | Re-engagement |

## Author
**Nayla** — Sistem Informasi, Universitas Bakrie 2026