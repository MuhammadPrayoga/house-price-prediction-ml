# Prediksi Harga Rumah: Proyek Machine Learning

[![Python][Python-shield]][Python-url]
[![Kaggle][Kaggle-shield]][Kaggle-url]

Proyek portofolio ini mendemonstrasikan alur kerja data science *end-to-end* untuk memprediksi harga rumah menggunakan dataset dari kompetisi Kaggle. Tujuannya adalah untuk membangun model regresi yang akurat melalui analisis data, rekayasa fitur, dan evaluasi model.

## Daftar Isi

- [Tentang Proyek](#tentang-proyek)
- [Teknologi yang Digunakan](#teknologi-yang-digunakan)
- [Struktur Proyek](#struktur-proyek)
- [Panduan Instalasi](#panduan-instalasi)
- [Penggunaan](#penggunaan)
- [Hasil](#hasil)
- [Lisensi](#lisensi)

## Tentang Proyek

Memprediksi harga properti adalah masalah klasik dalam ilmu data dan real estat. Proyek ini bertujuan untuk:
*   Membersihkan dan mempersiapkan data real estat yang kompleks.
*   Menganalisis dan memvisualisasikan hubungan antar fitur properti.
*   Membangun dan melatih model machine learning untuk prediksi harga.
*   Mengevaluasi performa model menggunakan metrik Root Mean Squared Error (RMSE).

Dataset yang digunakan adalah [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) dari Kaggle.

## Teknologi yang Digunakan

*   [Python](https://www.python.org/)
*   [Pandas](https://pandas.pydata.org/)
*   [NumPy](https://numpy.org/)
*   [Scikit-learn](https://scikit-learn.org/)
*   [Matplotlib](https://matplotlib.org/)
*   [Seaborn](https://seaborn.pydata.org/)
*   [XGBoost](https://xgboost.ai/)
*   [Jupyter Notebook](https://jupyter.org/)

## Struktur Proyek

```
.
├── data_description.txt    # Deskripsi setiap kolom dalam dataset
├── house_price_prediction.ipynb # Notebook utama berisi semua analisis dan kode
├── README.md               # Dokumentasi proyek
├── submission.csv          # Hasil prediksi untuk data tes
├── test.csv                # Dataset tes
└── train.csv               # Dataset pelatihan
```

## Panduan Instalasi

Untuk menjalankan proyek ini secara lokal, ikuti langkah-langkah berikut.

1.  **Prasyarat**
    *   Pastikan Anda memiliki [Python](https://www.python.org/downloads/) (versi 3.7+) dan [Git](https://git-scm.com/downloads/) terinstal.

2.  **Clone Repository**
    ```sh
    git clone https://github.com/MuhammadPrayoga/house-price-prediction-ml.git
    cd house-price-prediction-ml
    ```

3.  **Instalasi Dependency**
    Buat *virtual environment* (opsional tapi direkomendasikan) dan instal semua library yang dibutuhkan.
    ```sh
    pip install pandas numpy matplotlib seaborn scikit-learn xgboost jupyter
    ```

## Penggunaan

Setelah instalasi selesai, jalankan Jupyter Notebook:
```sh
jupyter notebook
```
Kemudian, buka file `house_price_prediction.ipynb` dari browser Anda dan jalankan semua sel secara berurutan.

## Hasil

Proyek ini menghasilkan model regresi berbasis XGBoost yang dilatih pada data pelatihan. Prediksi untuk data tes disimpan dalam file `submission.csv`, yang menunjukkan kemampuan model untuk menggeneralisasi pada data baru.

## Lisensi

Proyek ini dilisensikan di bawah Lisensi MIT. Lihat file [LICENSE](LICENSE) untuk detail lebih lanjut.

[Python-shield]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://www.python.org/
[Kaggle-shield]: https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white
[Kaggle-url]: https://www.kaggle.com/c/house-prices-advanced-regression-techniques
