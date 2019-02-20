# labpy1
## APA ITU BAHASA PEMROGRAMAN PYTHON?

Bahasa pemrograman python adalah bahasa pemrograman tinggi yang dapat melakukan eksekusi sejumlah intruksi multiguna secara langsung (interpretatif) 
dengan metode orientasi objek (Object Oriented Programming) serta menggunakan sinematik dinamis untuk memberikan tingkat keterbacaan syntax. Sebagai b
ahasa pemrograman tinggi, python dapat dipelajari dengan mudah karena sudah dilengkapi dengan manajemen memori otomatis (pointer). Berikut saya akan 
menjelaskan mengenai langkah-langkah dan penjelasan programnya.

## Praktikum1


Pertama, buka aplikasi PyCharm untuk menulis script bahasa pemrograman. Ketika sudah muncul ke tampilan awal , di PyCharm ini kita menggunakan bahasa pemograman Python
Setelah itu, tulis script pemrograman python seperti gambar dibawah ini:

![1](https://raw.githubusercontent.com/Hadip31/labpy1/master/1.PNG)

Buat Program sederhana untuk menentukan Bilangan Terbesar dan Terkecil dari 3 buah bilangan yang di inputkan dari kyboard
Dengan Script sebagai berikut :

	print("program untuk menentukan bilangan terbesar dan terkecil")
	def pengulangan():

	print("masukkan 3 buah bilangan yang di inginkan")
		a = int(input("Masukan Bilangan Ke 1 = "))
		b = int(input("Masukan Bilangan Ke 2 = "))
		c = int(input("Masukan Bilangan Ke  3 = "))

		if a>b and a>c:
			if b>c:
				print(a, "terbesar dan", c, "terkecil")
			else:
				print(a, "terbesar dan", b, "terkecil")
		elif b>a and b>c:
			if a>c:
				print(b, "terbesar dan", c, "terkecil")
			else:
				print(b, "terbesar dan", a, "terkecil")
			else:
		if a>b:
				print(c, "terbesar dan", b, "terkecil")
			else:
				print(c, "terbesar dan", a, "terkecil")**print("")
				print("ingin mencoba lagi (yes/no)?")
		x = input()
		if x == "yes":
			return pengulangan()
		if x == "tida	k":
				print("terimakasih telah menggunakan program ini.")
	pengulangan()

## Penjelasan program di atas seperti ini :

**Print**

Fungsi Print adalah untuk mencetak atau menampilkan suatu objek ke perangkat keluaran (layar) atau ke file teks. 

**Def**

Def pada python merupakan perintah executable, yang artinya function tidak akan aktif sampai python merunning perintah def tersebut. 
Statement def di ikuti oleh nama fungsinya. Sebuah fungsi dapat memiliki daftar argumen (parameter) ataupun tidak. 
Tanda titik dua ( : ) menandakan awal pendefinisian tubuh dari fungsi yang terdiri dari statement-statement. 

![2](https://raw.githubusercontent.com/Hadip31/labpy1/master/2.PNG)

**If**

Pernyataan if berisi sebuah ekspresi logika menggunakan data yang telah dibandingkan, dan menghasilkan sebuah keputusan 

**If Bersarang**

Pada kondisi tertentu kita dapat menggunakan pernyataan If Bersarang, maksudnya adalah kita dapat menuliskan pernyataan if..else didalam pernyataan if..else.

![3](https://raw.githubusercontent.com/Hadip31/labpy1/master/3.PNG)

**Else**

Pernyataan else biasanya digabungkan dengan pernyataan if diatas. Pernyataan else dapat berisi satu atau beberapa blok pernyataan (kode) yang mana
 akan dijalankan jika kondisi tersebut salah (atau tidak sesuai dengan syarat yang berlaku). 

![4](https://raw.githubusercontent.com/Hadip31/labpy1/master/4.PNG)

**Runn**

Kemudian kita Runn untuk meliat hasil project tersebut

![5](https://raw.githubusercontent.com/Hadip31/labpy1/master/6.png)

**Output**

Berikut hasil screenshot program Latihan1

![output](https://raw.githubusercontent.com/Hadip31/labpy1/master/output.PNG)


## SELESAI
**Hak Cipta @ angga hadi putra**