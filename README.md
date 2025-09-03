# Airbnb Data Analysis (2013–2016)

Proyek ini merupakan analisis eksplorasi data (EDA) terhadap dataset **Airbnb tahun 2013–2016**.  
Tujuan utama analisis adalah memahami pola **harga sewa, rating, revenue, tren musiman, harga rental dll** untuk membantu owner bisnis meningkatkan pendapatan.

---

## 📂 Dataset
Dataset yang digunakan:
- `listings.csv` → Informasi properti (harga, lokasi, dll.)
- `calendar.csv` → Data ketersediaan & harga harian
- `reviews.csv` → Data ulasan pengguna
- Dataset dibersihkan menjadi `listings_clean.csv`

Sumber data: [Airbnb Inside Airbnb](http://insideairbnb.com/) (data publik)

---

## 📊 Analisis
Beberapa hal yang dianalisis:
1. **Distribusi Harga** per properti
2. **Review Score Rating vs Revenue**
3. **Peak Season** (musim dengan okupansi tertinggi)
4. **Perbandingan Revenue Properti dengan Rating Tinggi vs Rendah**
5. Scatter plot antara **Review Score Rating dan Price**
6. **Harga Rental** yang cocok
7. Analisa **rating** dan cara mendapatkannya.
8. **lokasi yang cocok**
9. **Properti terbaik yang harus owner bisnis sewa**

---

## 🛠️ Tools
- Python (Pandas, Matplotlib, DuckDB, polars, plotly)
- Jupyter Notebook

---

## 🚀 Cara Menjalankan
1. Clone repo ini:
   ```bash
   git clone https://github.com/rozigithub/Data_Analyst.git
