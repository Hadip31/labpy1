# labpy1
## Praktikum1

**Pertama, buka aplikasi PyCharm untuk menulis script bahasa pemrograman. Ketika sudah muncul ke tampilan awal , di PyCharm ini kita menggunakan bahasa pemograman Python
Setelah itu, tulis script pemrograman python seperti gambar dibawah ini:**

![1](https://raw.githubusercontent.com/Hadip31/labpy1/master/1.PNG)

**Buat Program sederhana untuk menentukan Bilangan Terbesar dan Terkecil dari 3 buah bilangan yang di inputkan dari kyboard
Dengan Script sebagai berikut :**

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
	if x == "tidak":
	print("terimakasih telah menggunakan program ini.")
	pengulangan()

**Setelah program tersebut di eksekusi maka akan menghasilkan Output pada gambar berikut :** 

![output](https://raw.githubusercontent.com/Hadip31/labpy1/master/output.PNG)

**KETERANGAN**

**pada Fungsi Python digunakan Fungsi** Def, **lalu diikuti dengan fungsinya. Mis:** Def pengulangan()
Integer **Input pada a,b, dan c digunakan untuk mengambil data bilangan1, bilangan2, dan bilangan3.

![2](https://raw.githubusercontent.com/Hadip31/labpy1/master/2.PNG)

**If digunakan untuk menjalankan perintah dalam suatu kondisi. Maka kita tulis :** if a>b and a>c

![3](https://raw.githubusercontent.com/Hadip31/labpy1/master/3.PNG)

Elif **digunakan ketika kondisi** if a>b and a>c **tidak tercapai.
Fungsi** Else **digunakan jika kondisi** if **tidak dapat di penuhi.**

![4](https://raw.githubusercontent.com/Hadip31/labpy1/master/4.PNG)

x=input() **digunakan untuk menerima panggilan dari user, karena diatasnya terdapat tulisan print("ingin mencoba lagi (ya/tidak)?"). Kita diminta untuk menuliskan ya/tidak sebagai opsi pilihan.
Lalu save script bahasa pemrograman dengan menekan tombol ctrl+s.**

![5](https://raw.githubusercontent.com/Hadip31/labpy1/master/5.PNG)

## TERIMA KASIH
**Hak Cipta @ angga hadi putra**