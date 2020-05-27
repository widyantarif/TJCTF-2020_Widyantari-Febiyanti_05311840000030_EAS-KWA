# Zipped Up

# Challenge
My friend changed the password of his Minecraft account that I was using so that I would stop being so addicted. Now he wants me to work for the password and sent me this zip file. I tried unzipping the folder, but it just led to another zipped file. Can you find me the password so I can play Minecraft again?

# Solution
1. Lakukan pengunduhan terhadap **_zip file_** di terminal dengan command _wget_,  
	```wget "https://static.tjctf.org/663d7cda5bde67bd38a8de1f07fb9fab9dd8dd0b75607bb459c899acb0ace980_0.zip```
2. Unzip pada **_zip file_** tersebut secara manual
3. Akan terdapat file ```1.tar.bz2``` di dalam folder ekstrak
4. Kita akan menggunakan sebuah **_python script_**  untuk melakukan pengekstrakan __semua file__ yang ada di dalam folder ekstrak 
	```html
	from os import system

	system('unar ./1.tar.bz2')
	for i in range(1.1000,1):
		system('unar./{}/{}.*'.format(i, i+1))
	```

5.   **_python script_** tersebut dijalankan dalam folder ekstrak.
6. Ada  __1000 folder__ dalam folder ekstrak. lakukan pengecekan satu persatu

7. ```cat``` pada salah satu folder misalnya folder ```1```
	```html
	cat 1.txt
	```
8. Gunakan ```grep``` untuk mengetahui ```flag```
	```html
	grep -v -r "tjctf{n0t_th3_fl4g}" /home/febiyanti/Documents/ZippedUp/0
	```
9. didapatkan flag 

  ![248302](https://user-images.githubusercontent.com/55181778/83018003-cc145800-a04e-11ea-9600-dc7d9a66fcbe.jpg)

# Flag
```tjctf{p3sky_z1p_f1L35}```
