# Dashboard Kualitas Udara Beijing (PM2.5)

Proyek analisis data menggunakan dataset Beijing Multi-Site Air Quality (12 stasiun, Maret 2013 sampai Februari 2017). Analisis berfokus pada PM2.5 untuk menjawab dua pertanyaan:

1. Stasiun mana yang rata-rata PM2.5-nya tertinggi dan terendah, dan berapa persen selisihnya?
2. Musim apa yang rata-rata PM2.5-nya tertinggi, dan berapa persen jam pengamatan yang melewati ambang 75 µg/m³?

**Link dashboard:** https://dashboard-air-quality-asah-hwhqqnbnpfdlumpqbspsd8.streamlit.app/

## Struktur Folder

- `dashboard/` : berisi `dashboard.py`, `all_data.csv`, dan `station_geo.csv`
- `data/` : dataset mentah (12 file CSV)
- `Proyek_Analisis_Data.ipynb` : notebook analisis data
- `requirements.txt` : daftar library yang dibutuhkan
- `url.txt` : link dashboard

## Cara Menjalankan Dashboard di Lokal

1. Pastikan Python sudah terpasang.
2. Install library yang dibutuhkan:

   ```
   pip install -r requirements.txt
   ```

3. Jalankan dashboard dari folder utama proyek:

   ```
   streamlit run dashboard/dashboard.py
   ```

4. Buka `http://localhost:8501` di browser.
