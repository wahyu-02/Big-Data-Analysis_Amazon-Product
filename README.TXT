# Analisis Trend Pasar Berdasarkan Dataset

## Judul Produk dari 20 Kategori Berbeda di Amazon

### Anggota Peneliti
1. **Wahyudiyanto**  
   121450040  
   wahyudiyanto.121450040@student.itera.ac.id  
2. **Annisa Novantika**  
   121450005  
   annisa.121450005@student.itera.ac.id  
3. **Putri Intan Kirani**  
   121450055  
   putri.121450055@student.itera.ac.id  
4. **Berliyana Kesuma Hati**  
   121450086  
   berliyana.121450086@student.itera.ac.id  
5. **Nazwa Nabilla**  
   121450122  
   nazwa.121450122@student.itera.ac.id  

## Pendahuluan
Dalam era digital, e-commerce menjadi salah satu kanal utama dalam transaksi bisnis. Amazon, sebagai salah satu platform e-commerce terbesar, menyediakan beragam produk yang menarik bagi konsumen. Dengan meningkatnya belanja online, analisis tren pasar sangat penting untuk memahami pola konsumsi.

Penelitian ini bertujuan untuk menganalisis tren pasar berdasarkan dataset judul produk dari 20 kategori berbeda di Amazon. Dengan menggunakan teknologi big data seperti PySpark dan Hadoop, penelitian ini berupaya mengidentifikasi kata kunci dominan yang dapat memberikan wawasan mengenai preferensi konsumen.

## Metode
### Pengumpulan Data
Data dikumpulkan melalui scraping dari situs web Amazon menggunakan ekstensi Google Chrome **"Simple Scraper"** dan **"Infy Scroll"**. Data yang dikumpulkan mencakup judul produk dari 20 kategori dengan total sekitar satu juta baris data.

### Kategori Produk yang Dikumpulkan
1. Fashion Accessories  
2. Data Storage  
3. Perfume & Cologne  
4. Automotive Tools  
5. Beauty & Personal Care  
6. Bath & Body  
7. Shaving & Hair Removal Products  
8. Handmade Jewellery  
9. Kids & Babies  
10. Luggage & Travel Gear  
11. Home Decor  
12. Pets  
13. Handmade Kitchen & Dining  
14. Outdoor Cooking  
15. Men  
16. Women  
17. Grocery  
18. Work & Safety  
19. Hobbies & Crafts  
20. Toys & Games  

### Pengolahan Data
- Data disimpan dalam **Hadoop HDFS** untuk pemrosesan skala besar.
- Menggunakan **PySpark** untuk menghitung frekuensi kata (**word count**).
- Eksplorasi data dilakukan untuk memahami tren dari masing-masing kategori.
- Hasil word count disimpan dalam file teks terpisah untuk setiap kategori.

## Analisis Statistik
Analisis dilakukan untuk mendapatkan wawasan mengenai tren pasar dengan langkah-langkah berikut:
- **Word Count**: Menghitung frekuensi kemunculan kata dalam judul produk.
- **Visualisasi Data**: Menampilkan hasil dalam bentuk **bar chart** dan **word cloud**.

### Hasil Word Count Per Kategori
- **Fashion Accessories**: Kata yang dominan adalah "watch", "earrings", "necklace".
- **Beauty & Personal Care**: Kata yang dominan adalah "hair", "face", "skin".
- **Home Decor**: Kata yang dominan adalah "wall", "print", "art".

## Kesimpulan
Analisis ini memberikan wawasan tentang tren produk yang diminati dalam e-commerce, khususnya di Amazon. Beberapa temuan utama:
- **Fashion Accessories**: Jam tangan dan perhiasan mendominasi.
- **Beauty & Personal Care**: Produk perawatan rambut dan kulit sangat populer.
- **Home Decor**: Dekorasi dinding dan pencahayaan menjadi fokus utama.

Dengan hasil ini, pemasar dan peneliti dapat lebih memahami perilaku konsumen dan mengembangkan strategi pemasaran yang lebih efektif.

## Referensi
1. Aco, Ambo. "Analisis Bisnis E-Commerce pada Mahasiswa Universitas Islam Negeri Alauddin Makassar."
2. Alwendi. "Penerapan E-Commerce Dalam Meningkatkan Daya Saing Usaha." Jurnal Manajemen Bisnis, 2020.
3. Prabaswara, Irfan R., dan Ragil Saputra. "Implementasi Hadoop dan Spark Untuk Analisis Penyebaran Demam Berdarah Dengue Berdasarkan Data Twitter," 2020.
4. Fauzi, Reza A., Imam M Cholissodin, dan Bayu Rahayudi. "Pemanfaatan Spark untuk Analisis Sentimen Mengenai Netralitas Berita dalam Membahas Pemilu Presiden 2019 Menggunakan Metode Naïve Bayes Classifier," 2021.
5. Ngalup. "Web Scraping Pengertian, Teknik, Manfaat dan Kendala adalah," 2021.

---
Dokumen ini dibuat untuk keperluan penelitian dan dapat digunakan sebagai referensi untuk analisis data e-commerce dengan teknologi big data.

