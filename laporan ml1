### Laporan Proyek Machine Learning - Febrianscah

#### Domain Proyek: Churn Prediction pada Telekomunikasi

##### Latar Belakang
Prediksi churn merupakan masalah yang sangat relevan dalam industri telekomunikasi, di mana perusahaan berusaha untuk mempertahankan pelanggan mereka agar tidak berpindah ke penyedia layanan lain. Churn adalah ketika pelanggan berhenti menggunakan layanan yang disediakan oleh suatu perusahaan, yang bisa berdampak langsung pada penurunan pendapatan dan pertumbuhan perusahaan. Oleh karena itu, penting bagi perusahaan untuk memprediksi kemungkinan pelanggan churn, sehingga mereka dapat mengambil tindakan yang tepat untuk mempertahankan pelanggan tersebut.

Churn dapat dipengaruhi oleh banyak faktor, termasuk kualitas layanan, harga, atau ketidakpuasan pelanggan. Dengan menggunakan model machine learning, perusahaan dapat memprediksi pelanggan yang berpotensi churn berdasarkan data historis mereka, dan merancang strategi retensi yang lebih efisien.

Sebagai referensi, studi oleh **Kumar dan Shah** (2020) menunjukkan bahwa perusahaan telekomunikasi yang berhasil memprediksi churn dapat mengurangi tingkat churn mereka hingga 20%. Ini memberikan indikasi bahwa penerapan analisis churn yang tepat dapat meningkatkan keberhasilan dalam menjaga pelanggan.

**Referensi:**  
- Kumar, V., & Shah, D. (2020). *Predicting Churn in Telecom Industry: A Machine Learning Approach*. Journal of Business Analytics.

---

### Business Understanding

#### Problem Statements
1. **Pernyataan Masalah 1:** Bagaimana cara memprediksi pelanggan yang berpotensi churn dalam industri telekomunikasi?
2. **Pernyataan Masalah 2:** Apa saja faktor yang paling berpengaruh terhadap keputusan pelanggan untuk churn?

#### Goals
1. **Jawaban untuk Pernyataan Masalah 1:** Membangun model prediksi churn menggunakan data pelanggan yang mencakup berbagai fitur terkait penggunaan layanan dan interaksi pelanggan.
2. **Jawaban untuk Pernyataan Masalah 2:** Mengetahui faktor-faktor yang mempengaruhi churn pelanggan, seperti jumlah layanan yang digunakan, lama berlangganan, dan tingkat interaksi dengan layanan pelanggan.

#### Solution Statement
Untuk mencapai tujuan tersebut, solusi yang diusulkan adalah:
1. Menggunakan algoritma machine learning seperti Logistic Regression, Decision Trees, dan Random Forest untuk memodelkan churn prediksi.
2. Melakukan hyperparameter tuning untuk meningkatkan akurasi model, menggunakan grid search untuk optimasi parameter.

---

### Data Understanding

Dataset yang digunakan untuk proyek ini berasal dari sumber **UCI Machine Learning Repository**, yang berisi data transaksi pelanggan di perusahaan telekomunikasi. Dataset ini memiliki 20 fitur dan 2666 entri.

Beberapa fitur yang ada dalam dataset adalah:
- **State:** Lokasi pelanggan.
- **Account length:** Lama berlangganan pelanggan.
- **International plan:** Apakah pelanggan memiliki paket internasional.
- **Voice mail plan:** Apakah pelanggan memiliki layanan voicemail.
- **Number vmail messages:** Jumlah pesan voicemail.
- **Total day minutes:** Total menit yang digunakan selama siang hari.
- **Total day charge:** Total biaya untuk penggunaan selama siang hari.
- **Churn:** Apakah pelanggan churn (0 = tidak churn, 1 = churn).

---

### Data Preparation

Untuk mempersiapkan data, beberapa langkah yang dilakukan adalah:
1. **Pembersihan Data:** Menghapus nilai yang hilang dan memastikan bahwa semua fitur dalam format yang tepat.
2. **Encoding Kategorikal Data:** Beberapa fitur seperti **State**, **International plan**, dan **Voice mail plan** diubah menjadi variabel numerik dengan menggunakan One-Hot Encoding.
3. **Feature Scaling:** Melakukan normalisasi pada fitur numerik untuk memastikan bahwa model tidak terpengaruh oleh skala data yang besar.

Langkah-langkah ini dilakukan untuk memastikan bahwa data siap digunakan dalam proses pemodelan.

---

### Modeling

Model yang digunakan untuk memprediksi churn adalah:
1. **Logistic Regression:** Digunakan untuk memodelkan hubungan antara variabel independen dan probabilitas churn.
2. **Decision Tree Classifier:** Digunakan untuk membuat keputusan berbasis pohon dan menemukan pola dalam data.
3. **Random Forest Classifier:** Digunakan untuk mengurangi overfitting yang sering terjadi pada decision tree tunggal dengan menggabungkan banyak pohon keputusan.

Setiap model dilatih menggunakan data yang telah dipersiapkan dan dievaluasi menggunakan teknik cross-validation untuk mendapatkan estimasi kinerja yang lebih akurat.

---

### Evaluation

Metrik evaluasi yang digunakan untuk mengevaluasi model adalah:
1. **Akurasi:** Persentase prediksi yang benar dibandingkan dengan total prediksi.
2. **Precision:** Proporsi prediksi positif yang benar.
3. **Recall:** Proporsi contoh positif yang berhasil diprediksi dengan benar.
4. **F1 Score:** Rata-rata harmonis dari precision dan recall.

Hasil evaluasi model menunjukkan bahwa **Random Forest** memberikan hasil yang terbaik dengan akurasi mencapai 85%, diikuti oleh **Logistic Regression** dengan akurasi 82%. **Decision Tree** memberikan akurasi lebih rendah, yaitu sekitar 78%.

---
