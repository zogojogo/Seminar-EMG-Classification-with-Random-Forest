# Seminar-EMG-Classification-with-Random-Forest
Aplikasi yang dibuat dalam rangka mata kuliah seminar dengan topik pemrosesan sinyal digital

Algoritma Decision Tree seringkali digunakan pada machine learning untuk mengklasifikasikan sinyal biomedis. Selain itu De-noising dan ekstraksi fitur juga kerap digunakan untuk meningkatkan akurasi klasifikasi. Tujuan penelitian pada paper kali ini adalah mencari algoritma decision tree terbaik untuk mengklasifikasikan sinyal ElectroMyoGram (EMG) pada kelainan-kelainan otot dan syaraf. Algoritma decision tree sangat baik Ketika digunakan untuk mengklasifikasikan sinyal EMG. Pada paper ditunjukkan hasil akurasi dengan CART adalah sebesar 90%, C4.5 91.1%, dan Random Forest sebesar 96%. Tingginya akurasi ini juga didukung oleh denoising yang menggunakan MSPCA dan juga DWT untuk melakukan ekstraksi cirinya.

Alur pada program : 
1. Baca Data
2. Denoising dengan PCA
3. Decomposing sinyal menggunakan Discrete Wavelet Transform
4. Klasifikasi penyakit dengan metode Random Forest

referensi paper : http://www.sciencedirect.com/science/article/pii/S1746809414002006
