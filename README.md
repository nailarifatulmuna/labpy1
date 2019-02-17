# labpy1
# labpy1

Program 1 (Program mencari bilangan terbesar)
1).Alur Agoritma :

a.Mendefinisikan perulangan dengan mengetikkan ;
	def pengulangan():
   
b.Memasukkan 3 bilangan yang anda inginkan ;
	 print ('Masukkan 3 bilangan yang diinginkan!')
    	 a=int(input('Bilangan Pertama : '))
    	 b=int(input('Bilangan Kedua   : '))
    	 c=int(input('Bilangan Ketiga  : '))

c.Membandingkan nilai a,b,c dengan rumus if ;
    if a>b:
        if a>c:
            print ('Bilangan terbesarnya adalah :',a)
        else:
            print ('Bilangan terbesarnya adalah :',c)
    else:
        if b>c:
            print ('Bilangan terbesarnya adalah :',b)
        else:
            print ('Bilangan terbesarnya adalah :',c)

-Pilihan menu apakah anda ingin mencoba lagi ;
	 print ('Ingin coba lagi? (Y/T)')
*jika Iya (Y) ;
	x=input()
        if x=='Y':
	return pengulangan()
*dan jika Tidak (T) ;
	if x=='T':
	print('Terimakasih telah menggunakan program ini.')

-Jangan lupa ketikkan "pengulangan()" ,
 apabila lupa mengetikkan kata tersebut 
 maka definisi perulangan tidak akan muncul pada saat program dijalankan.
2).Berikut kode lengkapnya :


def pengulangan():
    print ('Masukkan 3 bilangan yang diinginkan!')
    a=int(input('Bilangan Pertama : '))
    b=int(input('Bilangan Kedua   : '))
    c=int(input('Bilangan Ketiga  : '))

    if a>b:
        if a>c:
            print ('Bilangan terbesarnya adalah :',a)
        else:
            print ('Bilangan terbesarnya adalah :',c)
    else:
        if b>c:
            print ('Bilangan terbesarnya adalah :',b)
        else:
            print ('Bilangan terbesarnya adalah :',c)

    print ('')
    print ('Ingin coba lagi? (Y/T)')
    x=input()
    if x=='Y':
        return pengulangan()
    if x=='T':
        print('Terimakasih telah menggunakan program ini.')

pengulangan()
3).Flowchatnya:

![img](https://github.com/nailarifatulmuna/labpy1/blob/master/labpy1/FlowProgram1.png)

4).Screenshotnya:

![img](https://github.com/nailarifatulmuna/labpy1/blob/master/labpy1/Program1.png)
