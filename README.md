Praktikum Probabilistik dan Statistika

Nama : Maisan Auliya

NRP : 5025201137

Kelas : PROBSTAT F

SOAL

1. Seorang penyurvei secara acak memilih orang-orang di jalan sampai dia bertemu dengan seseorang yang menghadiri acara vaksinasi sebelumnya.

        a. Berapa peluang penyurvei bertemu x = 3 orang yang tidak menghadiri acara vaksinasi sebelum keberhasilan pertama ketika p = 0,20 dari populasi menghadiri
        acara vaksinasi ? (distribusi Geometrik)
        b. mean Distribusi Geometrik dengan 10000 data random , prob = 0,20 dimana distribusi geometrik acak tersebut X = 3 ( distribusi geometrik acak () == 3 )
        c. Bandingkan Hasil poin a dan b , apa kesimpulan yang bisa didapatkan?
        d. Histogram Distribusi Geometrik , Peluang X = 3 gagal Sebelum Sukses Pertama
        e. Nilai Rataan (μ) dan Varian (σ²) dari Distribusi Geometrik.
		
    
2. Terdapat 20 pasien menderita Covid19 dengan peluang sembuh sebesar 0.2. Tentukan :
        
        a. Peluang terdapat 4 pasien yang sembuh.
        b. Gambarkan grafik histogram berdasarkan kasus tersebut.
        c. Nilai Rataan (μ) dan Varian (σ²) dari Distribusi Binomial.
    
    
3. Diketahui data dari sebuah tempat bersalin di rumah sakit tertentu menunjukkan rata-rata historis 4,5 bayi lahir di rumah sakit ini setiap hari. (gunakan Distribusi Poisson)
        
        a. Berapa peluang bahwa 6 bayi akan lahir di rumah sakit ini besok?
        b. simulasikan dan buatlah histogram kelahiran 6 bayi akan lahir di rumah sakit ini selama setahun (n = 365)
        c. dan bandingkan hasil poin a dan b , Apa kesimpulan yang bisa didapatkan
        d. Nilai Rataan (μ) dan Varian (σ²) dari Distribusi Poisson.
 
 
4. Diketahui nilai x = 2 dan v = 10. Tentukan:
        
        a. Fungsi Probabilitas dari Distribusi Chi-Square.
        b. Histogram dari Distribusi Chi-Square dengan 100 data random.
        c. Nilai Rataan (μ) dan Varian (σ²) dari DistribusiChi-Square.
    
    
5. Diketahui bilangan acak (random variable) berdistribusi exponential (λ = 3). Tentukan
        
        a. Fungsi Probabilitas dari Distribusi Exponensial
        b. Histogram dari Distribusi Exponensial untuk 10, 100, 1000 dan 10000 bilangan random
        c. Nilai Rataan (μ) dan Varian (σ²) dari Distribusi Exponensial untuk n = 100 dan λ = 3    
    
        Petunjuk:
        ● Gunakan set.seed(1)
        ● Gunakan fungsi bawaan R
    
    
6. Diketahui generate random nilai sebanyak 100 data, mean = 50, sd = 8. Tentukan
        
        a. Fungsi Probabilitas dari Distribusi Normal P(X1 ≤ x ≤ X2), hitung Z-Score Nya dan plot data generate randomnya dalam bentuk grafik. Petunjuk(gunakan fungsi         plot()).
        Keterangan :
                X1 = Dibawah rata-rata
                X2 = Diatas rata-rata
        Contoh data :
                1,2,4,2,6,3,10,11,5,3,6,8
                rata-rata = 5.083333
                X1 = 5
                X2 = 6
        b. Generate Histogram dari Distribusi Normal dengan breaks 50 dan format penamaan:
        NRP_Nama_Probstat_{Nama Kelas}_DNhistogram
                Contoh :
                312312312_Rola_Probstat_A_DNhistogram
        c. Nilai Varian (σ²) dari hasil generate random nilai Distribusi Normal.
    
    

Output dan Penjelasan singkat

1.  
	![image](https://user-images.githubusercontent.com/103273340/162612666-822ceccc-38f6-4139-8b15-1a43d18e5993.png)
	![image](https://user-images.githubusercontent.com/103273340/162612979-8e71ef7b-b070-4f59-aec9-5b7050277a8e.png)
	![image](https://user-images.githubusercontent.com/103273340/162613007-85144c77-da4b-4581-b3ea-a1b82e88874f.png)

	
		a. diminta mencari probabilitias dengan distribusi geometrik (dengan ketentuan yang disebutkan di soal). 
		b. mencari mean dari data random sejumlah n
		c. menganalisis hasil output dari poin a dan poin b, dimana pada poin a kita mencari probabilitas secara teorytical sedangkan pada poin b secara 		    simulasi, dan ternyata hasil nya sangat dekat, sehingga dapat dibuktikan benar.
		d. merupakan histogram pada kasus yang tertera di soal
		e. mean dan variance pada distribusi geometrik berdasarkan kasus tersebut


2. 	
	
	![image](https://user-images.githubusercontent.com/103273340/162613235-5c569b9a-4ed2-4345-86d9-dbec9817c23e.png)
	![image](https://user-images.githubusercontent.com/103273340/162613256-6f754fec-561c-4eb3-9341-1b9e4ad8a8d5.png)
	
		a. disini menggunakan distribusi binomial karena pilihannya antara sembuh atau tidak sembuh. langsung dimasukan saja kedalam persamaannya sesuai 		    kondisi yang diinginkan soal.
		b. membuat histogram nya dengan generate data random untuk 20 pasien (n=20)
		c. hitung mean dan variance pada distribusi binomial berdasarkan kasus tersebut
		


3.
	![image](https://user-images.githubusercontent.com/103273340/162613442-4aa7cf0e-9006-4ffe-8752-f10f2e77f719.png)
	![image](https://user-images.githubusercontent.com/103273340/162613457-27e2cf1b-c0c3-42cf-8f61-6e585c55ef4e.png)

		a. diminta mencari probabilitias dengan distribusi poisson (dengan ketentuan yang disebutkan di soal).
		b. membuat sebuah histogram berdasarkan kasus yang tertera di soal (menggunakan fungsi random dengan n = 365 atau setahun )
		c. hitung mean dan variance pada distribusi poisson berdasarkan kasus tersebut
		

4. 
	
	![image](https://user-images.githubusercontent.com/103273340/162613599-1520986d-4600-4c1e-8396-7f8dd8e53efb.png)
	![image](https://user-images.githubusercontent.com/103273340/162613613-9666665c-0ac8-4583-b3c6-d93f49806d78.png)
	
		a. diminta mencari probabilitias dengan distribusi chisquare (dengan ketentuan yang disebutkan di soal).
		b. membuat histogram dengan data random n = 100
		c. hitung mean dan variance pada distribusi chisquare berdasarkan kasus tersebut

5.
	![image](https://user-images.githubusercontent.com/103273340/162620487-dff6b2cc-e32b-43d1-b7dd-3385df582051.png)
	![image](https://user-images.githubusercontent.com/103273340/162620510-eb5d9a88-452c-425f-93ab-a88426ed5aa4.png)
	![image](https://user-images.githubusercontent.com/103273340/162620540-2635afd0-dc1a-42cf-b5fc-1f43259d5069.png)
	![image](https://user-images.githubusercontent.com/103273340/162620560-7eb688c5-7533-443d-bd1b-44feb7e1781a.png)
	![image](https://user-images.githubusercontent.com/103273340/162620570-b597f6c1-ee16-4380-a7ea-3f77d59ecc4e.png)

		a. diminta mencari probabilitias dengan distribusi exponensial (dengan ketentuan yang disebutkan di soal).
		b. kemudian membuat histogram dengan sample data random sebanyak n = 10 , 100 , 1000 dan 10000, menggunakan set.seed(n) agar data random nya tidak 		      berubah (mempengaruhi bentuk histogram).
		c. mencari mean dan variance pada distribusi exponensial berdasarkan ketentuan soal
		
		
6.
	![image](https://user-images.githubusercontent.com/103273340/162620839-d0871d1a-7780-4774-84c0-c391d9af5648.png)
	![image](https://user-images.githubusercontent.com/103273340/162620884-f81dce04-778a-46c7-975e-6ba4f6a61b08.png)
	![image](https://user-images.githubusercontent.com/103273340/162620861-148952ec-0e04-4284-82a0-4c356b547ff4.png)
	
		a. membuat fungsi probabilitas distribusi normal dengan data random sebanyak n = 100, kemudian mencari rata-rata dari data tersebut, mencari meat atas 			  & bawah dari data tersebut (menggunakan floor and round) yang nantinya digunakan untuk penghitungan z score nya, kemudian dibuatlah sebuah grafik 		       dari z score tersebut (menggunakan plot).
		b. membuat histogram dengan breaks = 50 dan nama histogram nya menjadi sesuai ketentuan soal
		c. menghitung variance dari distribusi normal sesuai yang tertera pada soal.






		






    
