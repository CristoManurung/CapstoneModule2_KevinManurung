## Latar Belakang
Industri transportasi kota, terutama layanan taksi, mengalami transformasi yang signifikan dengan adopsi teknologi dan peningkatan persaingan antar penyedia layanan. Sebagai bagian dari evolusi ini, perusahaan transportasi perlu secara cermat mengevaluasi kinerja mitra dan penyedia layanan untuk memastikan kepuasan pelanggan yang optimal dan efisiensi operasional. Analisis data New York City TLC Trip Record menunjukkan perbandingan kinerja antara dua Vendor utama, yaitu Creative Mobile Technologies, LLC. (VendorID1) dan VeriFone (VendorID2).

Creative Mobile Technologies, LLC. dan VeriFone merupakan dua pemain utama dalam penyediaan layanan transportasi di kota ini. Dalam rangka meningkatkan kualitas layanan, efisiensi operasional, dan keuntungan bisnis, perusahaan perlu memahami secara mendalam perbedaan kinerja antara kedua Vendor tersebut.

Analisis data mencakup parameter-parameter kunci seperti jumlah penumpang, tipe perjalanan, total biaya, dan jarak perjalanan. Hasil analisis ini memberikan wawasan yang jelas tentang keunggulan kinerja VeriFone dibandingkan Creative Mobile Technologies, LLC., yang dapat membimbing keputusan perusahaan dalam pemilihan Vendor untuk meningkatkan kualitas layanan dan kepuasan pelanggan.

Dalam konteks perubahan dinamis dalam industri transportasi, pemahaman mendalam tentang kinerja Vendor menjadi krusial. Latar belakang ini memberikan landasan bagi perusahaan untuk mengambil langkah-langkah strategis yang sesuai dengan tujuan bisnis mereka, sekaligus memberikan dasar untuk pengambilan keputusan yang efektif dalam mengelola hubungan dengan mitra penyedia layanan.  

## Pernyataan Masalah
Perusahaan ingin mengetahui **Vendor penyedia layananmana yang kinerja dan performanya nya lebih baik**. Informasi ini akan membantu perusahaan untuk mengetahui dan memilih Vendor mana yang memiliki kinerja yang baik, berdasarkan:

    1. Passanger_Count 

    2. Trip_type  

    3. Total_amount

    4. Trip_distance

    Data
![image](https://github.com/CristoManurung/CapstoneModule2_KevinManurung/assets/150712167/443e4d60-bd28-4c25-88ad-45e44f4d8c24)


![image](https://github.com/CristoManurung/CapstoneModule2_KevinManurung/assets/150712167/c3e9be7c-b905-466d-9b18-6d43e7d4047e)



## Data Understanding and Cleaning
Sebelum kita mulai menganalisis data, mari kita kenali dataset kita lebih jauh dalam tahap Pemahaman Data. Langkah ini membantu kita mengidentifikasi anomali dalam dataset yang perlu ditangani pada tahap Pembersihan Data. Setiap tindakan pembersihan data akan disertai dengan penjelasan mengenai langkah yang diambil, baik dari sudut pandang pengetahuan domain maupun statistik.

Mari kita perhatikan informasi penting dalam dataset New York City TLC Trip Record:

Secara umum, kita bisa melihat bahwa:
1. store_and_fwd_flag:

Persentase Missing Values: 6.34%
Tindakan: Hapus baris dengan nilai yang hilang atau gantilah dengan nilai yang sesuai jika memungkinkan.

2. RatecodeID, passenger_count, payment_type, trip_type, congestion_surcharge:

Persentase Missing Values: 6.34% - 6.35%
Tindakan: Hapus baris dengan nilai yang hilang atau gantilah 
dengan nilai yang sesuai jika memungkinkan.

3. ehail_fee:

Persentase Missing Values: 100%
Tindakan: Hapus kolom ini karena semua nilainya hilang.

Setelah tindakan pembersihan ini, dataset akan lebih siap untuk digunakan dalam analisis lebih lanjut. Pemahaman terhadap persentase nilai yang hilang membantu kita menentukan langkah-langkah yang sesuai untuk mempertahankan integritas dataset.

## Dashboard
https://public.tableau.com/app/profile/kevin.manurung/viz/CAPSTONE2_17036102096980/NewYorkCityTLCTripRecordData

## Kesimpulan dan Rekomendasi 

Dari analisis yang telah dibuat, kita dapat membuat kesimpulan tentang VendorID New York City TLC Trip Record:

* VeriFone. (VendorID2) paling unggul dibandingkan dengan Creative Mobile Technologies, LLC. (VendorID1) berdasarkan, sebagai berikut: 

    1. passenger_count
    2. trip_type
    3. total_amount
    4. trip_distance

* Kualitas dan performa dari Creative Mobile Technologies, LLC. (VendorID1) dan VeriFone. (VendorID2), yaitu sebagai berikut:

    1. Dari passenger_count, menjelaskan bahwa kualitas dan performa VendorID2 lebih baik dibandingkan VendorID1, dimana VendorID2 mempunyai total penumpang sebanyak 69203 yang dimana jauh lebih tinggi dan unggul dari Vendor1 yang total penumpangnya hanya sebanyak 9220.
    
    2. Dari trip_type, menjelaskan bahwa VendorID2 mempunyai kualitas dan performa lebih baik dari VendorID1 ,kedua Vendor sama sama memiliki tipe penumpang 1.0 atau Street-Hail daripada 2.0 yaitu dispatch. VendorID2 memiliki total trip_type 1.0 (street-hail) sebanyak 51332 dan 2.0 (dispatch) sebanyak 923 sedangkan VendorID1 memiliki total trip_type 1.0 (street-hail) sebanyak 8014 dan 2.0 (dispatch) sebanyak 41

    3. Dari total_amount, menjelaskan bahwa kualitas dan performa pada total_amount Vendor2 lebih bagus dibandingkan Vendor 1, dimana total_amount Vendor2 sebanyak 949689 dan total_amount VendorID1 sebanyak 142515.

    5. Dari trip_distance, menjelaskan bahwa kualitas pada trip_distance di VendorID2 jauh lebih baik dibandingkan dengan VendorID1 , dimana total trip_distance VendorID2 sebanyak 105963 sedangkan VendorID1 sebanyak 14250.

**Rekomendasi**
Berdasarkan kesimpulan dari analisis data, kami memberikan beberapa rekomendasi untuk perusahaan terkait VendorID New York City TLC Trip Record:

1. Prioritaskan Penggunaan VeriFone (VendorID2):
Mengingat kualitas dan performa yang lebih baik dari VeriFone (VendorID2) dalam parameter seperti jumlah penumpang, tipe perjalanan, total biaya, dan jarak perjalanan, disarankan untuk memberikan prioritas pada penggunaan VeriFone sebagai penyedia layanan.

2. Optimalkan Pemanfaatan Trip Type 1.0 (Street-Hail):
Diketahui bahwa trip type 1.0 (Street-Hail) lebih umum digunakan daripada trip type 2.0 (Dispatch). Oleh karena itu, perusahaan dapat mempertimbangkan untuk mengoptimalkan pemanfaatan trip type 1.0 sebagai strategi utama dalam layanan mereka.

3. Perhatikan Faktor Total Amount dalam Penentuan Vendor:
Total amount merupakan indikator penting dalam menilai performa Vendor. VeriFone (VendorID2) menunjukkan jumlah total_amount yang signifikan lebih tinggi daripada Creative Mobile Technologies, LLC. (VendorID1). Oleh karena itu, dalam pemilihan Vendor, perusahaan sebaiknya mempertimbangkan total amount sebagai faktor kunci.

4. Monitor dan Evaluasi Secara Berkala:
Perusahaan disarankan untuk melakukan pemantauan dan evaluasi secara berkala terhadap kinerja kedua Vendor. Analisis rutin dapat membantu dalam mengidentifikasi perubahan tren, kebutuhan pasar, dan memastikan bahwa Vendor yang dipilih terus memberikan layanan yang optimal.

5. Pertimbangkan Pengembangan Kerja Sama Lebih Lanjut:
Berdasarkan perbandingan kinerja, perusahaan dapat mempertimbangkan untuk mengembangkan kerja sama lebih lanjut dengan VeriFone (VendorID2), seperti negosiasi kontrak jangka panjang atau pemberian insentif untuk mendorong pertumbuhan kerja sama.

Dengan menerapkan rekomendasi ini, diharapkan perusahaan dapat meningkatkan efisiensi, kepuasan pelanggan, dan hasil bisnis secara keseluruhan. Selain itu, fleksibilitas untuk beradaptasi dengan perubahan pasar dan kebutuhan pelanggan juga menjadi kunci keberhasilan jangka panjang.




