# Gym

# Challenge
Aneesh wants to acquire a summer bod for beach week, but time is running out. Can you help him [create a plan](https://static.tjctf.org/bed9d7b7327958dab4d07b06772a032f3e97455e310956558579e8838762b5e2_gym) to attain his goal?

```nc p1.tjctf.org 8008```

# Solution
1. jalankan ```nc p1.tjctf.org 8008``` pada terminal ubuntu dan akan menampilkan: ![messageImage_15905857329801](https://user-images.githubusercontent.com/55181778/83024062-fcacbf80-a057-11ea-80a0-d03389600fdb.jpg)
2. dengan menggunakan bantuan [Ghidra](https://ghidra-sre.org/), program tersebut di reverse menjadi c program dengan ketentuan berikut :
```
eat_healthy = -4
do_pushup = -1
go_run = -5
go_sleep = -3
```
3. sesuai dengan perintah, diminta untuk menurukan dari 211 ke 180. dapat dilakukan dengan ```1, 1, 1, 1, 3, 3, 3``` untuk mencapai goal.
4. akan didapatkan flag

# Flag
```tjctf{w3iGht_l055_i5_d1ff1CuLt}```

