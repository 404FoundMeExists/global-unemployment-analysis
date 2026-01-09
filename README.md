#Global Unemployment Analysis (1991-2021)

#Deskriptif Proyek
proyek ini bertujuan untuk menganalisis tren pengangguran global pada periode 1991-2021
menggunaakan data dari World Bank. 
Analisis ini dilakukan untuk memahami pola perubahan tingkat pengangguran dari waktu ke
waktu serta membandingkan kondisi antara kelompok negara.

#Sumber Data
- World Bank
- Periode data : 1991-2021
- Format data :cvs

#tahapan analisis
1. data loading
   -memuat data csv dari folder 'data'
   -menggunakan pandas
2. data cleaning
   - Mengubah format data dari wide ke long
   - Konversi tipe data `year` dan `unemployment_rate` ke numerik
   - Menghapus nilai kosong (NaN)
3. Exploratory Data Analysis (EDA)
   - Analisis tren pengangguran global dari tahun ke tahun
   - Visualisasi rata-rata pengangguran global
   - Identifikasi pola fluktuasi dan anomali
4. Insight & Interpretasi
   - Mengamati periode kenaikan dan penurunan signifikan
   - Analisis kondisi ekstrem

# Insight Utama
Beberapa insight yang diperoleh dari analisis:
- Tingkat pengangguran global cenderung fluktuatif sepanjang 1991–2021
- Terjadi kenaikan bertahap pada awal periode analisis
- Terdapat penurunan tajam dan lonjakan tidak normal pada tahun-tahun tertentu
- Faktor global seperti krisis ekonomi dan pandemi sangat memengaruhi tren pengangguran

#Tools & Library
- Python
- Google Colab / Jupyter Notebook
- Pandas
- Matplotli
