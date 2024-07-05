# Capstone-Modul-2
![depositphotos_645751410-stock-illustration-supermarket-aisle-perspective-view-vector](https://github.com/sufriana/Capstone-Modul-2/assets/49579041/8c72751d-30a7-4a18-96cc-31f938c8038a)


# **Latar Belakang**

Supermarket modern beroperasi di lingkungan yang sangat kompetitif dan terus berkembang. Dalam upaya untuk tetap relevan dan menarik pelanggan, supermarket harus memahami perilaku konsumen, preferensi belanja, dan efektivitas kampanye pemasaran mereka. Data pelanggan merupakan aset yang sangat berharga dalam menyediakan wawasan yang diperlukan untuk pengambilan keputusan yang berbasis data.
<br>

Data pelanggan ini mencakup berbagai aspek seperti demografi, status pernikahan, pendidikan, pendapatan, serta perilaku belanja. Selain itu, data ini juga mencatat interaksi pelanggan dengan berbagai kampanye pemasaran yang dijalankan oleh supermarket. Dengan menganalisis data ini, supermarket dapat mengidentifikasi pola, dan preferensi pelanggan yang dapat digunakan untuk merancang strategi pemasaran yang lebih efektif dan personalisasi layanan.
<br>

# **Problem Statement**

Berdasarkan latar belakang ini, saya mengidentifikasi beberapa masalah yang perlu diselesaikan dalam upaya meningkatkan strategi pemasaran dan pengalaman pelanggan:

1. Identifikasi segmen pasar yang berbeda berdasarkan kategori yang relevan dan rentang waktu.
    - Apakah terdapat pengaruh antara usia dan minat dalam berbelanja?
    - Apakah pelanggan yang sudah menikah cenderung melakukan pembelian yang lebih besar daripada pelanggan yang belum menikah?
    
2. Identifikasi segmen pelanggan ("Pendidikan","Usia","Status Perkawinan") yang merespon Campaign dengan baik dan menggunakan berbagai kanal pembelian.
    - Apa saja segmentasi pelanggan yang merespon campaign dengan baik?
    - Apa saja segmentasi pelanggan yang menggunakan kanal pembelian berupa web, toko, dan katalog?<br>


Stakeholder terkait dalam analisis ini adalah tim Business Development

# **Goals** 
Tujuan analisis ini adalah untuk mengidentifikasi segmen pasar berdasarkan kategori produk yang relevan, serta menganalisis dampak campaign pemasaran untuk meningkatkan efektivitas strategi pemasaran dan pengalaman pelanggan di supermarket.

## **Data**
Dataset Supermarket Customer berisi 29 kolom terkait demografi, jenis produk, jumlah promosi yang dikirim, dan tempat pelanggan berbelanja setelah diberi promosi. Secara lengkap, berikut adalah deskripsi seluruh kolom data yang terdapat dalam database:


**People**




|Column Name | Description|
|----------|------------|
|ID | Pengidentifikasi unik pelanggan|
|Year_Birth | Tahun kelahiran pelanggan|
|Education | Tingkat pendidikan pelanggan|
|Marital_Status | Status perkawinan pelanggan|
|Income | Pendapatan rumah tangga tahunan pelanggan|
|Kidhome | Jumlah anak dalam rumah tangga pelanggan|
|Teenhome | Jumlah remaja dalam rumah tangga pelanggan|
|Dt_Customer | Tanggal pendaftaran pelanggan dengan perusahaan|
|Recency | Jumlah hari sejak pembelian terakhir pelanggan|
|Complain | 1 jika pelanggan mengeluh dalam 2 tahun terakhir, 0 jika tidak|


**Product**
|Column Name | Description|
|----------|------------|
|MntWines | Jumlah yang dibelanjakan untuk wine dalam 2 tahun terakhir|
|MntFruits | Jumlah yang dibelanjakan untuk buah dalam 2 tahun terakhir|
|MntMeatProducts | Jumlah yang dihabiskan untuk daging dalam 2 tahun terakhir|
|MntFishProducts | Jumlah yang dibelanjakan untuk ikan dalam 2 tahun terakhir|
|MntSweetProducts | Jumlah yang dibelanjakan untuk permen dalam 2 tahun terakhir|
|MntGoldProds | Jumlah yang dibelanjakan untuk emas dalam 2 tahun terakhir| 

**Promotion**
|Column Name | Description|
|----------|------------|
|NumDealsPurchases | Jumlah pembelian yang dilakukan dengan diskon|
|AcceptedCmp1 | 1 jika pelanggan menerima tawaran di kampanye pertama, 0 sebaliknya|
|AcceptedCmp2 | 1 jika pelanggan menerima tawaran di kampanye kedua, 0 sebaliknya
|AcceptedCmp3 | 1 jika pelanggan menerima tawaran di kampanye ketiga, 0 sebaliknya|
|AcceptedCmp4 | 1 jika pelanggan menerima tawaran di kampanye keempat, 0 sebaliknya
|AcceptedCmp5 | 1 jika pelanggan menerima tawaran di kampanye kelima, 0 sebaliknya|
|Response | 1 jika pelanggan menerima tawaran di kampanye terakhir, 0 sebaliknya|

**Place**
|Column Name | Description|
|----------|------------|
|NumWebPurchases | Jumlah pembelian yang dilakukan melalui situs web perusahaan|
|NumCatalogPurchases | Jumlah pembelian yang dilakukan menggunakan katalog
|NumStorePurchases | Jumlah pembelian yang dilakukan langsung di toko|
|NumWebVisitsMonth | Jumlah kunjungan ke situs web perusahaan dalam sebulan terakhir


# **Kesimpulan dan Rekomendasi**

Dari analisis yang telah dilakukan, kesimpulan dan rekomendasi yang bisa diambil mengenai analisis segmentasi pasar ini adalah:

## **Kesimpulan**
1. Identifikasi segmen pasar yang berbeda berdasarkan kategori yang relevan dan rentang waktu.<br>
    - Kelompok usia 70+ di supermarket menunjukkan minat yang tinggi terhadap pembelian produk wine dan daging, namun minat terhadap produk seperti ikan, buah, dan jajanan manis sangat rendah. Mereka juga cenderung membeli emas, sebagai investasi atau aksesoris. Hal ini menyoroti perlunya strategi pemasaran yang lebih baik untuk memenuhi preferensi belanja yang beragam di kalangan konsumen senior ini.<br>
    - Tidak ada perbedaan signifikan dalam pola pembelian antara pelanggan yang sudah menikah dan yang belum menikah di supermarket. Meskipun pelanggan yang sudah menikah cenderung melakukan pembelian yang sedikit lebih besar, perbedaannya tidak terlalu mencolok. Kedua kelompok menunjukkan minat yang konsisten terhadap produk wine dan daging, menunjukkan preferensi yang serupa terhadap jenis produk ini. Hal ini menunjukkan bahwa supermarket dapat mempertahankan strategi pemasaran yang serupa untuk kedua kelompok ini, dengan fokus pada produk-produk yang diminati seperti wine dan daging, sambil mempertimbangkan preferensi individual dan strategi pemasaran yang efektif untuk memaksimalkan pengalaman belanja mereka.<br>
2. Identifikasi segmen pelanggan ("Pendidikan","Usia","Status Perkawinan") yang merespon Campaign dengan baik dan menggunakan berbagai kanal pembelian.<br>
    - Campaign yang merespon dengan baik adalah campaign keenam yang menunjukkan tingkat penerimaan yang signifikan, sementara campaign lainnya perlu evaluasi lebih lanjut untuk meningkatkan efektivitas. Pelanggan dengan gelar Bachelor dan yang menikah cenderung merespons lebih baik terhadap campaign, khususnya di kelompok usia 40-49 tahun. Analisis ini menggarisbawahi pentingnya penyesuaian strategi pemasaran berdasarkan karakteristik pendidikan, usia, dan status pernikahan untuk mencapai keterlibatan yang lebih baik dari pelanggan dalam campaign pemasaran.
    - Usia dan status perkawinan mempengaruhi pola pembelian di berbagai kanal. Pelanggan usia 20-29 tahun yang masih single cenderung berbelanja lebih sedikit di web, toko, dan katalog dibandingkan dengan seumurannya yang sudah menikah. Kelompok usia 30-39 tahun yang sudah menikah menunjukkan kecenderungan untuk berbelanja lebih banyak di semua kanal, sedangkan pelanggan usia 40-49 tahun yang sudah menikah menunjukkan pembelian tertinggi di semua kategori, menandakan keterlibatan yang tinggi dalam berbelanja online maupun offline.

## **Rekomendasi**

1. **Penyesuaian Strategi Pemasaran untuk Kelompok Usia 70+**: Berdasarkan minat yang tinggi terhadap produk wine, daging, dan emas, disarankan untuk mengoptimalkan penempatan produk dan promosi yang lebih menarik bagi konsumen senior ini. Pemasaran yang lebih personal dan fokus pada kebutuhan khusus mereka dapat meningkatkan keterlibatan dan loyalitas pelanggan.

2. **Konsistensi dalam Strategi Pemasaran untuk Pelanggan Berdasarkan Status Pernikahan**: Meskipun tidak ada perbedaan signifikan dalam pola pembelian antara pelanggan yang sudah menikah dan belum menikah, tetap diperlukan konsistensi dalam menawarkan produk-produk yang diminati seperti wine dan daging. Strategi pemasaran yang menyeluruh dan inklusif terhadap semua segmen dapat memastikan pengalaman belanja yang positif bagi semua pelanggan.

3. **Optimalisasi Campaign Berdasarkan Karakteristik Demografis**: Mengingat respons yang lebih baik dari pelanggan dengan gelar Bachelor dan yang menikah, khususnya di kelompok usia 40-49 tahun, disarankan untuk lebih fokus pada segmentasi yang tepat dalam campaign pemasaran. Evaluasi terus-menerus terhadap campaign yang ada dan adaptasi strategi berdasarkan analisis demografis dapat meningkatkan efektivitas dan *Return on Investment* (ROI) dari campaign pemasaran.

4. **Peningkatan Keterlibatan Melalui Kanal Pembelian**: Untuk meningkatkan keterlibatan pelanggan usia muda yang masih single, disarankan untuk mengeksplorasi inovasi dalam strategi pemasaran digital dan promosi yang lebih menarik untuk platform web, toko, dan katalog. Memahami preferensi dan perilaku pembelian mereka secara lebih mendalam dapat membantu supermarket mengoptimalkan penggunaan setiap kanal pembelian untuk mencapai target pasar yang lebih luas dan meningkatkan konversi.

Rekomendasi ini bertujuan untuk membantu supermarket meningkatkan efektivitas strategi pemasaran mereka, memaksimalkan pengalaman pelanggan, dan memperkuat posisi mereka di pasar yang kompetitif.
