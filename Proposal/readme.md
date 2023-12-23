### Penjelasan Ringkas
Riset ini mengambil topik yaitu "Menganalisis dan Memprediksi Harga Rumah ke Depannya Menggunakan LGBM Regressor dan XGB Regressor". Dataset yang digunakan berisi beberapa data yang mencakup luas, jumlah kamar mandi serta kamar tidur, lingkungan, tahun dibangun, dan harga.

### Metode yang Digunakan
Ada beberapa metodologi yang dilakukan sebagai berikut.
1. Analisis data eksploratif :
Untuk mengecek dan memperbaiki data agar bisa digunakan untuk proses selanjutnya
![image](https://github.com/miadw/Riset-Informatika/assets/118716343/82feea3b-d17a-4384-a272-1ef2870f5444)

2. Seleksi fitur :
Menyeleksi fitur yang akan digunakan untuk proses selanjutnya menggunakan beberapa model, yaitu XGBRegressor, LGBNRegressor, dan CatboostRegressor.
![image](https://github.com/miadw/Riset-Informatika/assets/118716343/da7604f1-87a1-47e8-8635-ee9bfdb8d42d)

3. Modeling :
Melakukan evaluasi antara model XGBRegressor dengan LGBNRegressor untuk mencari yang terbaik sebagai pengujian prediksi.
![image](https://github.com/miadw/Riset-Informatika/assets/118716343/2021b65b-3050-4d7c-9ebb-eaf5b0bea38b)

4. Pengujian prediksi :
Melakukan pengujian prediksi dan membandingkan metrik pengujian yang terbaik untuk digunakan.
![image](https://github.com/miadw/Riset-Informatika/assets/118716343/1018d77d-ba4b-4300-b87d-565e30279962)


### Referensi
Sumber referensi kodingan.
https://www.kaggle.com/code/guanlintao/ml-optuna-eda-housing-price-prediction 

### Dataset
Dataset diambil dari tautan sebagai berikut.
https://www.kaggle.com/datasets/muhammadbinimran/housing-price-prediction-data

### Coding
Codingan dapat diakses pada tautan berikut.
https://colab.research.google.com/drive/1tARHqDvX94zKkzy8F4T9wodyJYJ_oA3s?usp=sharing

### Analisis (Metrik Pengujian)
index,Model,MedAE(eval),MedAE(test),R2_Score(eval),R2_Score(test)
1,LGBM,186.17341056949718,183.84724170730294,0.5559453054033903,0.5660168322285046
0,XGB,186.59938010200517,184.99956979116507,0.5352705575275362,0.5467528343421337
![image](https://github.com/miadw/Riset-Informatika/assets/118716343/d41e9df3-1d86-4d4e-b3ec-4dfc23353cb1)

### Draft Paper
https://docs.google.com/document/d/1ByJVezSTXUxATDAQId11JqYZdzwyYd4mE7eiaesF2NU/edit?usp=sharing

