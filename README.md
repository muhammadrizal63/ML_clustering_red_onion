# Data Science Portfolio
#  **Segmentation Of Red Onion Farmer**
## Instructions for Running Google Colab Notebook
1. Open Google Colab with any browser.<br>
2. Login with your Google Account and make new notebook.<br>
3. Import Dataset from Google Drive, The data used is kuesioner_1.xlsx
4. Install library python if needed

### **Business Understanding**
Center Of Excellence Universitas Dian Nuswantoro mengadakan penelitian dengan petani bawang merah sebagai mitranya. Adapun dataset yang dihimpun adalah sebagai berikut :
- Pengumpulan dataset dilakukan di 5 Kabupaten di Jawa Tengah
- Dataset bersumber dari kuesioner kepada petani bawang merah
- Data kuesioner terkait profil petani dan kegiatan pertanian bawang merah
### **`Problem`**
Bagaimana mengelompokkan petani bawang merah ke dalam dua kategori utama: pemula dan senior.
### **`Goals`**
Mengidentifikasi dan mengelompokkan petani bawang merah ke dalam dua kategori utama yaitu pemula dan senior dengan tujuan mengembangkan program pelatihan dan dukungan yang disesuaikan untuk masing-masing segmen guna meningkatkan produktivitas dan keberlanjutan.
### **`Objective`**
Membangun model Machine Learning yang dapat membantu mengidentifikasi apa saja karakteristik utama yang membedakan petani pemula dari petani senior sehingga dapat diberikan bantuan dan sumber daya apa yang paling dibutuhkan oleh setiap segmen oleh stakeholder terkait

###  **Solution Strategy**
**Langkah 01. Data Preprocessing :** Pada tahap pertama ini, data akan dikumpulkan dan dipelajari. Nilai yang hilang akan diidentifikasi dan dihapus jika diperlukan.<br>
**Langkah 02. Exploratory Data Analysis :** proses awal dalam analisis data yang digunakan untuk memahami struktur, menemukan pola, mendeteksi anomali, menguji asumsi, dan memeriksa hubungan dalam dataset.<br>
**Langkah 03. Rename Field :** Proses mengubah nama kolom dalam dataset.<br>
**langkah 04. Handling Missing Value :** Mengisi data-data yang kosong dengan nilai konstan, mean, dan modus.<br>
**Langkah 05. Handling Duplicated Data :** Melakukan pengecekan apakah terdapat data duplikat atau tidak, jika terdapat data duplikat maka dilakukan drop.<br>
**Langkah 06. Feature Encoding :** Proses mengubah data kategorikal menjadi tipe data numerik agar dapat digunakan dalam pemrosesan data.<br>
**Langkah 07. Hopkins Test :** Proses menentukan apakah data Anda memiliki kecenderungan alami untuk membentuk kelompok (clusters) atau jika data tersebut tersebar secara acak.<br>
**Langkah 08. Elbow Method :** Dilakukan untuk menetukan jumlah cluster terbaik yang dapat digunakan untuk menghasilkan hasil cluster yang terbaik dan dapat memaksimalkan kualitas hasil cluster.<br>
**Langkah 09. Machine Learning Modelling :** Proses pemodelan data menggunakan algoritma tertentu dalam kasus ini menggunakan model clustering dengan algoritma K-Means.<br>
**Langkah 10. Interpretasi Statistic :** Proses ini membantu dalam mengevaluasi hasil clustering, menemukan pola yang menarik dengan melihat hasil cluster dengan persebaran nilai statistics

### **Exploratory Data Analysis**
![Img 1](screenshot/1.png)

`import missingno`:<br>
- Ini adalah proses pengecekan kolom mana saja yang terdapat value yang kosong (missing value) sehingga perlu dilakukan imputasi untuk mengisi kolom yang kosong dengan value tertentu.

### **Elbow Method**
![Img 2](screenshot/2.png)

### **K-Means Clustering**
![Img 3](screenshot/3.png)

### **K-Means Clustering**
![Img 3](screenshot/3.png)

### **Visualisasi JointPlot Usia dengan Jumlah Hasil Panen**
![Img 3](screenshot/4.png)

### **Visualisasi JointPlot Lama Bertani dengan Jumlah Hasil Panen**
![Img 3](screenshot/5.png)

**Deskripsi Petani** <br>
Berdasarkan persebaran statistik untuk masing-masing cluster dapat disimpulkan sebagai berikut :
- 





