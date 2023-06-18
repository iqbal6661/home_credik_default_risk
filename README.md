1. Full Name & Batch
   nama : Iqbal Awis Nurdiansyah
   batch : FTDS RMT - 019

2. Dashboard / Deployment Link
   https://lookerstudio.google.com/reporting/a0d16fe7-cfbf-4766-8076-f09e48535c8a
   
3. Project Title
   Home Credit Default Risk
   
4. Project Description
   melakukan pra-pemrosesan data, eksplorasi data, pemilihan fitur yang tepat, dan membangun model machine learning.
   
5. Conclusion
   **EDA**
Kondisi Keuangan Pelanggan: Sebagian besar pelanggan Home Credit, yaitu 91.9%, memiliki kemampuan untuk membayar kredit mereka. Hal ini mengindikasikan bahwa sebagian besar pelanggan memiliki kondisi keuangan yang stabil dan mampu memenuhi kewajiban pembayaran kredit.

Gender dan Penggunaan Kredit: Wanita memiliki andil yang signifikan dalam penggunaan kredit, dengan 65.8% pelanggan Home Credit adalah wanita. Hal ini menunjukkan bahwa wanita memiliki kebutuhan yang lebih tinggi dalam menggunakan kredit untuk memenuhi kebutuhan keuangan mereka.

Jenis Pinjaman: Cash loans (pinjaman tunai) adalah jenis pinjaman yang paling umum digunakan oleh pelanggan Home Credit, dengan jumlah entri yang jauh lebih tinggi dibandingkan dengan revolving loans (pinjaman berputar). Hal ini menunjukkan bahwa pelanggan lebih cenderung memilih pinjaman tunai daripada pinjaman berputar.

Pekerjaan dan Penggunaan Kredit: Pekerjaan dengan jumlah pelanggan terbanyak adalah "Laborers" (pekerja kasar/fisik). Pekerjaan ini mungkin membutuhkan tambahan dana atau kredit untuk memenuhi kebutuhan sehari-hari mereka. Oleh karena itu, pekerjaan ini menjadi target utama bagi Home Credit.

Tingkat Pembayaran Kredit: Meskipun terdapat perbedaan dalam tingkat kredit macet antara jenis pekerjaan dan gender tertentu, kesimpulan utama adalah bahwa tidak ada faktor tunggal yang secara signifikan mempengaruhi kemampuan pelanggan untuk membayar kredit mereka. Artinya, faktor seperti jenis pekerjaan atau gender tidak dapat dijadikan prediktor tunggal dalam menentukan apakah seseorang akan membayar kredit atau tidak.

**Model**
Dari ketiga model yang digunakan LogisticRegression, XGBoost, dan RandomForest. LogisticRegression merupakan model yang terbaik dan menghasilkan nilai ROC-AUC sebesar 57% .

Karena keterbatasan waktu dan pengerjaan Model masih kurang baik dalam segi performance, Model dapat ditingkatkan dengan memlilih fitur - fitur yang lebih berkorelasi dengan target.

**Rekomendasi**
Mengingat mayoritas pelanggan dapat membayar kredit, perusahaan dapat terus fokus pada menarik pelanggan baru dengan menawarkan produk dan layanan yang menarik.

Menyadari bahwa wanita merupakan segmen pelanggan yang dominan, perusahaan dapat mengembangkan strategi pemasaran yang lebih terfokus untuk menarik lebih banyak pelanggan wanita.

Meskipun cash loans lebih umum, perusahaan dapat mempertimbangkan untuk mengoptimalkan penawaran revolving loans untuk memberikan variasi kepada pelanggan.

Mengingat "Laborers" adalah jenis pekerjaan yang paling banyak digunakan, perusahaan dapat mengembangkan program khusus atau penawaran yang sesuai untuk menarik dan mempertahankan pelanggan dengan pekerjaan ini.

Meskipun tidak ada faktor tunggal yang signifikan dalam memprediksi pembayaran kredit, perusahaan dapat terus memperkuat analisis risiko dan keuangan untuk mengidentifikasi faktor-faktor lain yang mungkin mempengaruhi pembayaran kredit.
