# UAS

# Random-Forest-Classifier

NAMA : ARDY YUNIARTO

NIM : 181011402254

KELAS 06TPLE023

Teknik klasifikasi ini merupakan teknik yang memiliki akurasi cukup tinggi, yaitu random forest classification. Pembahasan mengenai teknik ini mirip seperti random forest regression, hanya saja tujuannya bukan memprediksi sebuah nilai tetapi mengklasifikasikan data.


 
Teknik ini mengenerate (membuat) banyak decision tree classification, kemudian mengambil keputusan berdasarkan beberapa decision tree yang sudah dibuat. Langkah-langkahnya sebagai berikut:

Pilih beberapa data di training set sebanyak K buah (Jika datanya terlalu sedikit, misal kurang dari 30, tidak perlu dibagi ke dalam training dan test set).
Buat Decision Tree-nya dari K data yang sudah dipilih sebelumnya.
Pilih jumlah N-tree (kumpulan pohon-pohon) yang ingin dibuat. Selanjutnya ulangi langkah 1 dan 2. Intinya terus membuat decision tree sebanyak-banyaknya (umumnya sebanyak 200 kali, 300, 500, dst).
Untuk dataset yang baru, buat setiap N-tree memprediksi kelompok dari dataset yang baru. Kemudian dataset yang baru akan masuk ke kelompok yang memiliki probabilitas tertinggi dari semua kombinasi N-tree.
