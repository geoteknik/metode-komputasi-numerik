# Galat Numerik
Metode numerik adalah cara pendekatan untuk memecahkan masalah matematika. Metode ini digunakan dalam berbagai bidang, termasuk sains, teknik, ekonomi, dan sebagainya. Meskipun metode numerik sangat berguna dan efektif, namun metode ini tidak sepenuhnya akurat karena mempunyai galat error, yang disebut galat numerik (*numerical error*). Sehingga galat numerik merupakan salah satu faktor penting dalam metode numerik. 

Galat numerik (*numerical error*) adalah ketidaktepatan atau penyimpangan dari nilai sebenarnya ketika melakukan komputasi matematika menggunakan metode numerik atau algoritma. Meskipun metode numerik merupakan alat yang powerful untuk menyelesaikan masalah matematika, tetapi metode ini melibatkan aproksimasi dan estimasi, dan tidak akurat secara mutlak. Oleh karena itu, galat numerik dapat terjadi karena beberapa alasan, termasuk:
1. Galat pembulatan: Ini terjadi karena presisi terbatas dari komputer yang digunakan untuk perhitungan. Komputer hanya dapat menyimpan jumlah digit yang terbatas, sehingga beberapa digit mungkin dipotong atau dibulatkan, menyebabkan kesalahan kecil dalam hasil perhitungan.

2. Galat pemangkasan: Ini terjadi ketika algoritma atau metode memangkas deret atau fungsi tak hingga menjadi jumlah terbatas. Pemangkasan ini menyebabkan galat, yang mungkin signifikan jika jumlah term yang digunakan terlalu kecil. Untuk keterangan lebih lanjut tentang galat ini, akan kita jelaskan pada deret taylor

3. Galat diskritisasi: Ini terjadi ketika masalah kontinu diaproksimasi menjadi diskrit. Hal ini sering terjadi dalam simulasi numerik sistem fisik, di mana variabel kontinu sistem diskritisasi menjadi elemen terbatas atau titik grid.

4. Galat konvergensi: Ini terjadi ketika terdapat perbedaan antara solusi yang mencapai konvegen sepenuhnya dengan solusi yang baru mencapai konvergensi sebagian. Hal ini dapat terjadi karena user menghentikan iterasi sebelum solusi mencapai konvergensi, atau user memilih nilai toleransi galat yang terlalu besar.

## Jenis berdasarkan pengukuran galat
Ada dua jenis galat pada metode numerik, yaitu galat absolut dan galat relatif. Galat absolut merupakan perbedaan antara nilai hasil perhitungan yang diperoleh melalui metode numerik dengan nilai sebenarnya dari hasil tersebut. Sedangkan galat relatif adalah perbandingan antara galat absolut dan nilai sebenarnya dari hasil tersebut.

## Cara mengurangi galat
Galat numerik dapat diminimalkan dengan menggunakan metode numerik yang cocok untuk masalah yang dipecahkan, menggunakan aritmetika presisi tinggi, meningkatkan jumlah term yang digunakan dalam aproksimasi, atau dengan menggunakan teknik analisis galat untuk menentukan sumber-sumber galat dan memperbaikinya. Penting untuk menyadari galat numerik dan mengambil langkah-langkah untuk meminimalkannya, karena galat ini dapat menyebabkan ketidakakuratan yang signifikan pada hasil akhir.

Penting untuk diingat bahwa galat pada metode numerik tidak bisa dihilangkan sepenuhnya, namun dapat diperkecil sebanyak mungkin dengan menggunakan teknik-teknik yang tepat. Oleh karena itu, sangat penting bagi para ilmuwan dan ahli matematika untuk memahami konsep galat pada metode numerik dan menggunakan teknik yang tepat untuk mengurangi galat tersebut agar hasil perhitungan yang diperoleh dapat digunakan secara efektif dan akurat dalam berbagai aplikasi.
