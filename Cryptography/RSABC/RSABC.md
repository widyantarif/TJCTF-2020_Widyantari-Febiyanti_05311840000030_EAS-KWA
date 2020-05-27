# RSABC
# Cryptography

# Challenge: 

I was just listening to some relaxing ASMR when a notification popped up with ```this```.

saat ```this``` dibuka, maka akan terpampang: 

```
n=57772961349879658023983283615621490728299498090674385733830087914838280699121
e=65537
c=36913885366666102438288732953977798352561146298725524881805840497762448828130
```

# Hint: 

It's easy as R-S-A! Wait..

# Solution:

1. Setelah mengetahui hint yang terdapat di Challenge, bisa mencari referensi pengerjaan di ```TJCTF-2019 Easy as RSA```
2. Melakukan faktorisasi (mendapatkan p dan q) pada alamat factordb.com

```
p = 202049603951664548551555274464815496697
q =  285934543893985722871321330457714807993
```
3. Selanjutnya adalah menginputkan n, e, c serta p dan q kedalam Ruby Script:

```
$ruby main.rb
tjctf{BOLm1QMWi3c}
```

# Flag: 

```
tjctf{BOLm1QMWi3c}
```
