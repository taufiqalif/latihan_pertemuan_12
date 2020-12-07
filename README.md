# String


## Tetapkan String ke Variabel
Menetapkan **string** ke **variabel** dilakukan dengan nama variabel diikuti dengan tanda sama dengan dan string:

	var1 = 'hello world' # menggunakan kutip satu
	var2 = "python programing" # menggunakan kutip dua

	print(("var1[0]: "), var1[0]) # mengambil karakter pertama
	print(("var2[1:5]: "), var2[1:5]) # karakter ke-2 s/d ke-5

dan akan menghasilkan output sebagai beriku:

	var1[0]:  h
	var2[1:5]:  ytho

gambar!

![01.png](/gambar/01.png)


## Update
Anda dapat "memperbarui" string yang ada dengan menetapkan (kembali) variabel ke string lain. 
Nilai baru dapat dikaitkan dengan nilai sebelumnya atau ke string yang sama sekali berbeda. 
Sebagai contoh:

	var1 = 'hello world'

	print("update string : - ", var1[:6] + 'python')

dan akan menghasilkan output sebagai berikut:

	update string : -  hello python

gambar!

![02.png](/gambar/02.png)


## String Formatting Operator
Salah satu fitur paling keren dari Python adalah operator format string%. 
Operator ini adalah astrings tostring unik dan membuat paket memiliki fungsi dari keluarga printf () C. 
Berikut ini adalah contoh sederhana sederhana:

	print("nama saya %s, umur saya adalah %s tahun" % ('taufiq alif rahman', 22))

dan menghasilkan uotput sebagai berikut:

	nama saya taufiq alif rahman, umur saya adalah 22 tahun


# Latihan 1

![03.png](/gambar/03.png)

hasil dari soal di atas

	txt = 'hello world'

	print(len(txt)) # perintah len untuk menentukan berapa banyak karakter yang terdapat di variable
	print(txt[10]) # mencari nilai paling akhir 
	print(txt[2:5]) # karakter ke-2 s/d ke-5
	print(txt[:5] + 'world') # menghilangkan spasi
	print(txt.upper()) # merubah karakter menjadi huruf besar
	print(txt.lower()) # merubah karakter menjidi huruf kecil
	print(txt.replace("h", "J")) # merubah karakter "h" menjadi karakter "J"

dan akan menghasilkan output sebagai berikut:

	11
	d
	llo
	helloworld
	HELLO WORLD
	hello world
	Jello world
gambar!

![05.png](/gambar/05.png)

# Latihan 2

![04.png](/gambar/04.png)

Hasil latihan di atas

	umur = 24
	txt = 'hallo, nama saya john, dan umur saya adalah {} tahun'
	print(txt.format(umur))

dan akan menghasilkan output sebagai berikut:

	hallo, nama saya john, dan umur saya adalah 24 tahun

gambar!

![06.png](/gambar/06.png)