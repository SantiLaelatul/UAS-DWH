# Optimasi ETL Pipeline pada Data Warehouse untuk Analisis HIV/AIDS dan Kesehatan Reproduksi Global Berbasis OLAP

## 📌 Deskripsi Proyek
Proyek ini mengimplementasikan Data Warehouse dengan optimasi ETL Pipeline untuk analisis data kesehatan global, khususnya HIV/AIDS dan kesehatan reproduksi berbasis OLAP. Data berasal dari World Bank Health Nutrition and Population Statistics dengan rentang waktu 2020–2024.

Proses ETL dilakukan untuk membersihkan, mentransformasi, dan mengintegrasikan data ke dalam struktur star schema yang terdiri dari fact table dan dimension table (negara, indikator, dan waktu). Data kemudian dianalisis secara multidimensi menggunakan OLAP untuk menghasilkan insight seperti tren kesehatan global, perbandingan antar negara, dan perubahan indikator dari waktu ke waktu.

## 🎯 Tujuan
- Membangun Data Warehouse untuk data kesehatan global  
- Implementasi ETL Pipeline  
- Analisis OLAP berbasis multidimensi  
- Analisis tren dan perbandingan indikator HIV/AIDS dan kesehatan reproduksi  

## 📊 Dataset
Sumber data berasal dari World Bank Health Nutrition and Population Statistics (2020–2024) yang mencakup indikator HIV/AIDS dan kesehatan reproduksi berbagai negara.

## ⚙️ Proses
- Extract data dari World Bank (Excel/CSV)  
- Transform data (cleaning, unpivot, integrasi metadata, handling missing value)  
- Load ke PostgreSQL dalam bentuk star schema  

## 🧱 Model Data
- Fact table: fact_health  
- Dimension table: dim_country, dim_indicator, dim_time  

## 📈 Output
- Data Warehouse berbasis star schema  
- Analisis OLAP multidimensi  
- Insight tren dan perbandingan kesehatan global  
