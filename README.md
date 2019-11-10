

  # ALUR ALGORITMA PROGRAM LATIHAN_1

1.	Masukan nilai input, nilai input ini berfungsi untuk menampilkan banyak data. Anda bisa memasukan nilai berapa saja.
2.	Dengan menggunakan fungsi random, yaitu fungsi yang akan menampilkan angka dibawah 0.5 secara acak. Fungsi random sudah otomatis ditampilkan. Masukkan syntak dibawah untuk membangkitkan nilai random().

![random image](https://user-images.githubusercontent.com/57025775/68372088-c4549b00-0172-11ea-815c-4cc82a8f5f3d.jpg) 

3.	Ketika anda sudah memasukan nilai input, maka akan langsung muncul data nilai random.

  code program:
  
       import random
     jumlah = int(input("\nMasukan Nilai :"))

     for i in range(jumlah):
        i=random.uniform(00.0,0.5)      #menampilkan nilai random 0,5
        print("Data ke =: =>",i)
     print("\nSelesai")
     
     
	Contoh hasil nilai random yang kurang dari 0.5 :
![random1](https://user-images.githubusercontent.com/57025775/68374257-1c8d9c00-0177-11ea-843e-7f6475a49875.jpg)

![random2](https://user-images.githubusercontent.com/57025775/68374536-a6d60000-0177-11ea-97df-d853d190a2ba.jpg)

  


 # ALUR ALGORITMA PROGRAM LATIHAN_2

1.	Masukan bilangan
2.	Program akan terus mengulang untuk meminta anda memasukan bilangan selama bilangan yg anda masukan tersebut tidak sesuai syarat berhenti.
3.	Pengulangan akan berhenti ketikan anda memasukan angka 0 (nol). Dimana angka 0 ini adalah syarat agar pengulangan berhenti.
4.	Selanjutnya akan menampilkan bilangan terbesar dari semua bilangan yang diinput. Untuk mencari bilangan terbesar gunakan fungsi max().

  Code Program :
  
    print("\nProgram untuk menampilkan bilangan terbesaar dari n bilangan yang dimasukan\n")
    max = 0
    while True:
      a=int(input("Masukan Bilangan : "))
      if max < int (a):
          max = int(a)
      if a == 0:
          break
    print("Bilangan terbesar adalah : ", max)

	Contoh hasil program :

![loopmax](https://user-images.githubusercontent.com/57025775/68372266-18f81600-0173-11ea-94ba-ef009f43fc8e.jpg) 

  

  # ALUR ALGORITMA PROGRAM_1

1.	Modal awal pengusaha sebesar 100000000
2.	Untuk menghitung laba perbulan maka diinputkan terlebih dahulu sebesar presentase keuntungan perbulan, dimana pada bulan ke-1 dan ke-2 belum mendapatkan laba, bulan ke-3 dan ke-4 mendapat laba sebesar 1%, di bulan ke-5,ke-6 dan ke-7 mendapatkan laba sebesar 5%, lalu di bulan ke-8 mendapat lama 2%.
3.	Dan selanjutnya, hasil laba perbulan akan ditampilkan. Disini anda bias menggunakan looping berupa for/while untuk menampilkan kembali jumlah laba yang telah dihitung berdasarkan presentasinya.
4.	Terakhir akan menampilkan jumlah laba secara keseluruhan yang didapat dengan menggunakan sum .(laba)

  Code Program :
  
    a = 100000000
    for m in range (1,9):
    if (m>=1 and m<=2): 
        b=a*0
        print("laba bulan ke- ",m,":",b)
    if (m>=3 and m<=4):
        c=a*0.1
        print("laba bulan ke- ",m,":",c)
    if (m >= 5 and m <= 6):
        d = a * 0.5
        print("laba bulan ke- ",m,":",d)
    if (m ==7 ):
        e = a* 0.5
        print("laba bulan ke- ",m,":",e)
    if (m==8):
        f = a * 0.2
        print("laba bulan ke- ",m,":",f)
    total = b+b+c+c+d+d+e+f
    print("total laba adalah:",total)


	Contoh hasil prigram :

![laba](https://user-images.githubusercontent.com/57025775/68372376-493fb480-0173-11ea-8f1a-10cb12d40f43.jpg) 


Semoga bermanfaat :simplesmile:
