# Hotel Booking Analysis - End-to-End Business Intelligence Project

Proyek ini mendemonstrasikan alur kerja (*workflow*) lengkap seorang *Data Analyst* / *BI Developer* dalam mengolah data reservasi hotel. Dimulai dari pengambilan data mentah, proses ETL, manajemen basis data, hingga pembuatan *dashboard* interaktif.

## Alur Kerja Proyek (*Project Workflow*)
1. **Extraction**: Mengambil dataset mentah (*Hotel Booking Demand*) dari platform Kaggle.
2. **ETL (Extract, Transform, Load)**: Pembersihan data, penanganan *missing values*, dan rekayasa fitur menggunakan **Python (Pandas)** di Google Colab.
3. **Database Management**: Migrasi data terstruktur ke dalam **PostgreSQL** sebagai *Single Source of Truth*.
4. **Data Visualization**: Transformasi data menjadi wawasan bisnis menggunakan **Power BI**.

## Teknologi yang Digunakan
* **Language**: Python 3.x
* **Libraries**: Pandas, NumPy
* **Database**: PostgreSQL
* **Visualization**: Power BI Desktop

## Struktur Repositori
* `UTS_business_intelligence.ipynb`: Notebook proses ETL.
* `Buisness.sql`: Skema database dan dump data PostgreSQL.
* `powerbi_hotel.csv`: Dataset hasil transformasi (siap pakai).
* `Dashboard_Hotel.pbix`: File project Power BI.
