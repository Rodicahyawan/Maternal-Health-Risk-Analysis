# Machine Learning-Maternal Health Risk Analysis
📊 Maternal Health Risk Analysis

Proyek ini bertujuan untuk melakukan analisis dan prediksi risiko kesehatan ibu hamil menggunakan teknik machine learning berdasarkan dataset Maternal Health Risk. Dataset ini berisi berbagai faktor medis seperti tekanan darah, kadar gula, suhu tubuh, dan detak jantung yang berpengaruh terhadap tingkat risiko kehamilan.

Dataset yang digunakan berasal dari data kesehatan ibu hamil yang dikumpulkan dari rumah sakit dan klinik melalui sistem monitoring berbasis IoT, dengan fitur utama seperti Age, SystolicBP, DiastolicBP, Blood Sugar, Body Temperature, dan Heart Rate serta target Risk Level (Low, Mid, High) .

🎯 Tujuan
Menganalisis faktor-faktor yang mempengaruhi risiko kesehatan ibu hamil
Membangun model machine learning untuk klasifikasi tingkat risiko
Membandingkan performa beberapa algoritma klasifikasi
Memberikan insight berbasis data untuk mendukung deteksi dini risiko kehamilan

🧠 Metodologi
Proyek ini terdiri dari beberapa tahapan utama:
1. Data Understanding
Menampilkan struktur dataset
Mengecek missing values dan distribusi data
2. Data Preprocessing
Data cleaning (jika diperlukan)
Encoding label pada kolom target
Feature selection & normalization (jika digunakan)
3. Exploratory Data Analysis (EDA)
Visualisasi distribusi data
Analisis hubungan antar fitur
Identifikasi pola pada tiap level risiko
4. Modeling
Beberapa algoritma machine learning digunakan, seperti: (Logistic Regression, Decision Tree, Random Forest)
5. Evaluation
Menggunakan metrik seperti: (Accuracy, Confusion Matrix, Classification Report)

📈 Hasil
Model yang dibangun mampu mengklasifikasikan tingkat risiko kehamilan ke dalam tiga kategori:
Low Risk
Mid Risk
High Risk
Beberapa model menunjukkan performa yang baik dalam memprediksi risiko berdasarkan fitur kesehatan yang tersedia.

🛠️ Teknologi yang Digunakan
Python
Pandas & NumPy
Matplotlib & Seaborn
Scikit-learn
Jupyter Notebook
📌 Insight
Faktor seperti tekanan darah, gula darah, dan detak jantung memiliki pengaruh signifikan terhadap risiko kehamilan
Model machine learning dapat membantu proses deteksi dini risiko kesehatan ibu hamil
Analisis ini dapat menjadi dasar pengembangan sistem pendukung keputusan di bidang kesehatan
⚠️ Disclaimer

Proyek ini hanya untuk keperluan pembelajaran dan analisis data. Hasil prediksi tidak dapat digunakan sebagai pengganti diagnosis medis profesional.
