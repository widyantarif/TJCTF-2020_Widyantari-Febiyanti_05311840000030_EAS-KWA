# Censorship

# Challenge
My friend has some top-secret government intel. He left a message, but the government censored him! They didn't want the information to be leaked, but can you find out what he was trying to say?

```nc p1.tjctf.org 8003```

# Solution
1. membuka program Wireshark yang nantinya akan berguna untuk membuka packet-packet pencari flag
2. jalankan perintah ```nc p1.tjctf.org 8003``` di terminal 
![01baru](https://user-images.githubusercontent.com/55181778/83016669-8c4c7100-a04c-11ea-99cc-f30f9225b9d1.jpg)
3. pada wireshark pilih ```File - Export Packet Disserctions - As Plain Text... ;```
![02baru](https://user-images.githubusercontent.com/55181778/83016679-8f476180-a04c-11ea-9b08-ad235ace83b9.jpg)
4. akan didapatkan flag
![03](https://user-images.githubusercontent.com/55181778/83016681-90788e80-a04c-11ea-92a7-18803f338dc2.jpg)

# Flag
```tjctf{TH3_1llum1n4ti_I5_R3aL}```

