# labpy1
##Praktikum1

**Buat Program sederhana untuk menentukan Bilangan Terbesar dan Terkecil dari 3 buah bilangan yang di inputkan dari kyboard**
Dengan Script sebagai berikut :

**print("program untuk menentukan bilangan terbesar dan terkecil")**
**def pengulangan():**
**print("masukkan 3 buah bilangan yang di inginkan")**
	**a = int(input("Masukan Bilangan Ke 1 = "))**
	**b = int(input("Masukan Bilangan Ke 2 = "))**
	**c = int(input("Masukan Bilangan Ke  3 = "))**

	**if a>b and a>c:**
		**if b>c:**
			**print(a, "terbesar dan", c, "terkecil")**
		**else:**
			**print(a, "terbesar dan", b, "terkecil")**
	**elif b>a and b>c:**
		**if a>c:**
			**print(b, "terbesar dan", c, "terkecil")**
		**else:**
			**print(b, "terbesar dan", a, "terkecil")**
		**else:**
		**if a>b:**
			**print(c, "terbesar dan", b, "terkecil")**
		**else:**
			**print(c, "terbesar dan", a, "terkecil")**print("")
	**print("ingin mencoba lagi (yes/no)?")**
	**x = input()**
	**if x == "yes":**
		**return pengulangan()**
	**if x == "tidak":**
		**print("terimakasih telah menggunakan program ini.")**

**pengulangan()**
 Setelah program tersebut di eksekusi maka akan menghasilkan Output pada
gambar berikut : 
![output](https://raw.githubusercontent.com/Hadip31/labpy1/master/output.PNG)
Dari program diatas digunakan type data integer pada bilangan
, if untuk digunakan dalam mengolah bilangan tersebut.
 
**if a>b and a>c: if b>c:**

Pada program diatas bahwa jumlah data yang akan diinputkan melalui kyboard. Dimulai dari inputan pertama
dan akan menghitung naik hingga sampai inputan data ke 3.
 
**a =int(input(Masukan Bilanagan Ke 1 = "))**

Setelah proses penginputan selesai maka program akan mengeksekusi 
data tersebut sesuai dengan rumus berikut, dimana nilai yang diinputkan, kemudian dari ke 3 data tersebut akan mencari bilangan terbesar dan terkecil. dan menggunakan pengulanagn

**x = input ()**
**if x == "yes":**
**return pengulanagan()**
**if x == "tidak":**

Untuk menghasilkan jumlah bilangan tersebut sehingga akhirnya menghasilkan terbesar dan terkecil 
##Terima kasih