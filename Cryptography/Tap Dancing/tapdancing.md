# Tap Dancing

# Challenge
My friend is trying to teach me to dance, but I am not rhythmically coordinated! They sent me a list of [dance moves](https://static.tjctf.org/518d6851c71c5482dbd5bbe812b678684238c8f4e9e9b3d95a188f7db83a0870_cipher.txt) but they're all numbers! Can you help me figure out what they mean so I can learn the dance?

NOTE: Flag is not in flag format.

# Solution 
1. membuka link _dance moves_ dan akan mendapatkan berbagai angka: ```1101111102120222020120111110101222022221022202022211```
2. angka tersebut adalah kode morse yang dapat diterjemahkan menjadi: 
  - 1 = -
  - 2 = .
  - 0 = (space) 

setelah itu akan mendapatkan kode morse sebagai berikut: 
```
-- ----- .-. ... . -. ----- - -... ....- ... . ...--
```
3. menerjemahkan menggunakan [website morse decoder](https://morsecode.world/international/translator.html)

# Flag
```{M0RSEN0TB4SE3}```
