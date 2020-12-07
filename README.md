# String


## Tetapkan String ke Variabel
Menetapkan **string** ke **variabel** dilakukan dengan nama variabel diikuti dengan tanda sama dengan dan string:

	var1 = 'hello world'
	var2 = "python programing"

	print(("var1[0]: "), var1[0])
	print(("var2[1:5]: "), var2[1:5])

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
