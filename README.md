# labpy1
## Praktikum1

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

**keterangan :**

print("...") ** digunakan untuk menampilkan output teks.**

**pada Fungsi Python digunakan Fungsi** Def, **lalu diikuti dengan fungsinya. Mis:** Def pengulangan()

Integer **Input pada a,b, dan c digunakan untuk mengambil data bilangan1, bilangan2, dan bilangan3.**

**If digunakan untuk menjalankan perintah dalam suatu kondisi. Maka kita tulis :** if a>b and a>c

Elif **digunakan ketika kondisi** if a>b and a>c **tidak tercapai.

Fungsi** Else **digunakan jika kondisi** if **tidak dapat di penuhi.**

x=input() **digunakan untuk menerima panggilan dari user, karena diatasnya terdapat tulisan print("ingin mencoba lagi (ya/tidak)?"). Kita diminta untuk menuliskan ya/tidak sebagai opsi pilihan.
Lalu save script bahasa pemrograman dengan menekan tombol ctrl+s.

## TERIMA KASIH
**Hak Cipta @ angga hadi putra**