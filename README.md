# Praktikum Week 14

## Nama : Jud Amal Mukhtar

## Kelas : TI-3C 

## NIM : 2041720168

1. Slide 30 - Movie Lens Recommendation
	
	Mount Google Drive, menginstal pyspark, dan membuat SparkSession baru.
    
	![SS](img/01_1.png)
	
	Mengimport dataset <code>ratings.dat</code>.
	
	![SS](img/01_2.png)
	
	Kemudian melakukan RDD mapping dan Membuat model rekomendasi menggunakan ALS pada training data yang telah dibuat sebelumnya.
	
	![SS](img/01_3.png)
	
	Hasilnya
	
	![SS](img/01_4.png)
##

2. Slide 48 dan 49
	
	Import dataset <code>ratings.dat</code> lalu parallelize variable myData dan mapping file yg telah diimport. Kemudian train totalRatings menggunakan metode ALS untuk mendapatkan rekomendasi produk.
	
	![SS](img/02_1.png)
	
	hasilnya
	
	![SS](img/02_2.png)
	
	Menampilkan statistik summary mulai dari rata", varian, dll dari vectorRdd rating yang telah di proses sebelumnya
	
	![SS](img/02_3.png)
##

3. Slide 52
	
	Import library KMeans dan Vectors. Kemudian mengimport <code>kmeans_data.txt</code> . Selanjutnya mapping dataset dan konversi menjadi dari RDD menjadi DataFrame dan memasukkan variable parsedData pada method kmeans.fit kemudian Menampilkan summary dari training cost dan prediksi cluster tiap data.
	
	![SS](img/03_1.png)
	
	Hasilnya
	
	![SS](img/03_2.png)
##

4. Slide 53-54
	
	Import library Kmeans, Numpy, dan Math. Kemudian mengimport <code>kmeans_data.txt</code> setelah itu melakukan mapping dengan patokan tiap data dipisahkan menggunakan delimiter spasi . kemudian training data dengan Kmeans. dengan jumlah kluster 2 dan maksimal iterasi 10 dan Menghitung WSSE dari parsedData kemudian melakukan saving model pada folder yang telah disesuaikan
	
	![SS](img/04_1.png)
	
	hasilnya di sidebar
	
	![SS](img/04_2.png)
