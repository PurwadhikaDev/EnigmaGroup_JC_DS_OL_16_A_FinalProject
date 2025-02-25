# Enigma Group - Final Project Purwadhika
Bank Marketing Campaign - Opening Deposito

CREATED BY : ELISA - ANGEL - EDWARD F.B.H.HUTAPEA
## Overview
Deposito berjangka memberi manfaat bagi bank dan nasabah—bank mendapat likuiditas stabil, sementara nasabah memperoleh bunga lebih tinggi dengan risiko rendah. Namun, rendahnya minat membuka deposito membuat strategi pemasaran yang efektif menjadi penting. 

`Dynamic personalization cashback` adalah strategi pemasaran yang menyesuaikan penawaran cashback berdasarkan profil, perilaku, dan preferensi individu nasabah secara real-time atau berbasis data historis. 

Dengan pendekatan ini, Manajemen Bank dan Tim Marketing dapat memberikan cashback yang lebih relevan bagi setiap nasabah, meningkatkan efektivitas promosi dalam membuka deposito. Tim Customer Service juga dapat memahami kebutuhan dan perilaku nasabah, agar dapat memberikan informasi yg tepat dan relevan kepada nasabah terkait produk deposito.

## Problem Statement
Tidak semua nasabah yang dihubungi tertarik membuka deposito berjangka, data Statistik menunjukan 36.537 (88,7%) orang nasabah menolak buka deposito. Di simulasikan, total kehilangan potential revenue dan biaya telemarketing mencapai Rp 21 Miliar. Dengan strategi pemasaran yang menawarkan cashback secara sistematis, bank dapat meningkatkan konversi deposito dan mengurangi biaya marketing.

https://github.com/PurwadhikaDev/EnigmaGroup_JC_DS_OL_16_A_FinalProject/blob/main/Problem%20Statement.png 

## Goals
Tujuan utama dari proyek adalah untuk membangun model pembelajaran mesin yang dapat mengidentifikasi calon nasabah yang kemungkinan tidak tertarik dengan produk deposito, sehingga bank dapat membuat strategi pemasaran kustom (personalized) yang dapat memberikan penawaran cashback yang menarik untuk nasabah guna meningkatkan peluang mereka membuka deposito dan mendorong pertumbuhan pendapatan bank.

## Stakeholders
👥 Siapa yang membutuhkan analisis ini?

Marketing 📣: Targeting calon nasabah & meningkatkan konversi.

Manajemen Bank 💼: Keputusan strategis & efisiensi biaya.

IT & CTO 💻: Implementasi model prediksi dalam aplikasi.

Data Science 🔬: Analisis pola nasabah & kampanye.

Customer Service 📞: Pemahaman nasabah & layanan tepat sasaran.

## Scope of Project
📌 Cakupan Analisis:
Hanya mencakup kampanye pemasaran via telepon dan selular.

Fokus pada keputusan nasabah dalam membuka deposito.

Tidak mempertimbangkan faktor eksternal seperti kampanye pemasaran melalui email atau iklan digital.


## Analytic Approach 
Tahapan analisis akan mengikuti framework DIKW (Data  => Information => Knowledge => Wisdom). Dengan data yang ada, kita akan melakukan data wrangling untuk mendapatkan data bersih. Lalu kita akan melakukan descriptive analysis dan diagnostic analysis utnuk mendapatkan insight dari informasi masa lalu, lalu digabungkan dengan domain knowledge/ experience yang dimiliki untuk mendapatkan wisdom.

Selanjutnya kita akan melakukan feature engineering dengan mengubah fitur-fitur kategorik menjadi numerik dengan menggunakan ordinal encoding, numerical encoding dan binary encoding.

Lalu kita akan masuk dalam tahap Model Selection untuk menguji model dengan melatih dan mengevaluasi model-model klasifikasi seperti Logistic Regression, K-Nearest Neighbors (KNN), Decision Tree Classifier, Random Forest Classifier, XGBoost Classifier, LightGBM Classifier dan Gradient Boosting Classifier. 

Setelah menentukan model mana yang performanya paling bagus dan kita akan lanjut pada tahap Hyperparameter Tuning, pada tahap ini, kita akan mencari value untuk hyperparameter. Lalu kita akan mengevaluasi performa model sebelum dan sesudah tuning.
Matric Evaluation
Mengingat tujuan utama adalah mengenali sebanyak mungkin nasabah yang bersedia membuka deposito, recall menjadi matrik evaluasi utama. Recall fokus pada mengurangi false negative (FN), yaitu menghindari kesalahan dalam mengklasifikasikan calon nasabah yang sebenarnya bersedia membuka deposito tetapi tidak ditargetkan.

## Tableau Dashboard
Berikut adalah link untuk Dashboard yang telah kita buat :
https://public.tableau.com/views/Enigma-PortugalBankDepositCampaignPerformanceCustomerTrends/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link 

Berikut adalah screenshot dari Dashboard

## Monetisasi
Perhitungan MONETISASI dengan adanya improvement Machine Learning dan Personalized Marketing Campaign:


Dengan breakdown di atas, terlihat bahwa penerapan model dengan recall 53% dapat mengurangi biaya telemarketing dan kehilangan revenue yang lebih besar.
Penghematan Biaya Telemarketing = Rp 1.287.975.000** (47.0% penghematan).
Penghematan Kehilangan Revenue = Rp 9.687.500.000** (53.0% penghematan).
Total Penghematan = Rp 10.975.475.000

