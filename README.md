Buatlah sebuah model prediction menggunakan Random Forest Reggression untuk memprediksi perkembangan penyakit diabetes yang disimbolkan dengan variable y dari data
diabetes di library Scikit-Learn.

Cobalah n_estimators berikut dan pilih satu model dengan tingkat error RMSE dan MAE
terendah:

a. n_estimators = 50

b. n_estimators = 100

c. n_estimators = 200

Berikut penjelasan tentang data:

Data diabetes berisi pengukuran yang diambil dari 442 pasien diabetes yang terdiri dari:

a. 10 variabel dasar (fitur):

age – umur dalam tahun

sex - pria atau wanita

bmi - indeks massa tubuh

bp - tekanan darah rata-rata

s1 - TC : kolesterol serum total

s2 - LDL: lipoprotein densitas rendah

s3 - HDL: lipoprotein densitas tinggi

s4 - TCH : kolesterol total / HDL

s5 - LTG: kemungkinan log kadar trigliserida serum

s6 - GLU : kadar gula darah

b. Variable target (Y)

Satu variabel target: ukuran kuantitatif perkembangan penyakit satu tahun setelahdata dasar

Todo:

1. Lakukan perhitungan train model dengan ketiga hyperparameter di atas

2. Lakukan predict dan bandingkan metrik RMSE dan MAE model dengan hyperparameter mana yang memiliki error lebih kecil

3. Screenshoot hasil predict

4. Load ke Github
