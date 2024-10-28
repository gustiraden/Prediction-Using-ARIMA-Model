# Prediction-Using-ARIMA-Model

# Prediksi Produksi beras Menggunakan Metode ARIMA

## Deskripsi
Proyek ini bertujuan untuk memprediksi produksi beras di Jawa Barat menggunakan model ARIMA (AutoRegressive Integrated Moving Average). Penelitian ini dilakukan berdasarkan data historis produksi beras untuk memberikan wawasan dan analisis yang berguna bagi perencanaan dan pengambilan keputusan di sektor pertanian.

## Tujuan
- Membangun model ARIMA untuk memprediksi produksi beras.
- Menganalisis akurasi model dengan menggunakan Mean Absolute Percentage Error (MAPE).
- Memberikan rekomendasi berdasarkan hasil prediksi.

## Data
Data yang digunakan dalam penelitian ini mencakup:
- Data historis produksi beras di Jawa Barat selama periode tertentu.

## Metodologi
1. **Pengumpulan Data**: Mengumpulkan data historis produksi beras dari sumber yang terpercaya.
2. **Preprocessing Data**: Melakukan pembersihan dan pengolahan data untuk memastikan kualitas data.
3. **Analisis Data**: Menggunakan model ARIMA untuk melakukan analisis dan prediksi.
4. **Evaluasi Model**: Mengukur akurasi model menggunakan MAPE.

## Hasil
Model ARIMA(1,2,1) berhasil memprediksi produksi beras untuk tahun 2023 sebesar 6,046,996 ton dengan MAPE sebesar 4.5%, menunjukkan akurasi 95%. Hasil ini menunjukkan potensi penggunaan analisis prediktif dalam perencanaan pertanian.

## Instalasi
Untuk menjalankan proyek ini, pastikan Anda memiliki Python dan paket yang diperlukan seperti `pandas`, `numpy`, `statsmodels`, dan `matplotlib`. Anda dapat menginstal paket yang diperlukan dengan perintah berikut:

```bash
pip install pandas numpy statsmodels matplotlib
