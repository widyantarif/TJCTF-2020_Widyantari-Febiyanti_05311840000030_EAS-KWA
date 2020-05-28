# Login

# Challenge
Could you login into this very secure [site](https://login.tjctf.org/)? Best of luck!

# Solution
1. Melakukan pencarian flag pada Inspect Element. Pada bagian Sources, didapatkan nama file ```md5.js```. Kemungkinan flag yang tertera telah di hash kedalam md5. 
2. Pada file Index akan didapatkan kunci selanjutnya yang berisi: 
```
var _0xb31c=['value','c2a094f7d35f2299b414b6a1b3bd595a','Sorry.\x20Wrong\x20username\x20or\x20password.','admin','tjctf{','getElementsByName','toString'];
```
3. Dapat dilihat bahwa ```c2a094f7d35f2299b414b6a1b3bd595a``` adalah bentuk hash dan sesuai dengan diatas, bisa jadi menggunakan MD5. Langkah selanjutnya adalah dekrip menggunakan [md5 decoder](https://www.md5online.org/md5-decrypt.html). Didapatkan bahwa bentuk aslinya adalah ```inevitable```
4. Masukkan: 
```
Username : Admin
Password : inevitable
```

# Flag
```tjctf{inevitable890898}```
