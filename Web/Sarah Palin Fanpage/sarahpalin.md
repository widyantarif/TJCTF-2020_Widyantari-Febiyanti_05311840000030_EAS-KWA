# Sarah Palin Fanpage

# Challenge
Are you a true fan of Alaska's most famous governor? Visit the [Sarah Palin fanpage](https://sarah_palin_fanpage.tjctf.org/).

# Solution 
1. Pergi ke sub menu [VIP Area](https://sarah_palin_fanpage.tjctf.org/exclusive) dan lakukan pencarian flag dengan Inspect Element.
2. Buka tab ```Application > Storage > Cookies```dan didapatkan berbagai value. 
3. Copy semua value dan di decode dengan [base64](https://www.base64decode.org/)
4. Maka akan didapatkan hasil menjadi
```
{"1":false,"2":false,"3":false,"4":false,"5":false,"6":false,"7":false,"8":false,"9":false,"10":false}
```
5. Ubah setiap kata ```false``` menjadi ```true```.
6. Encode kembali ke [base64](https://www.base64decode.org/), dan letakkan kembali pada ```Application > Storage > Cookies```. Selanjutnya refresh page
7. Akan didapatkan flag

# Flag
```tjctf{wkDd2Pi4rxiRaM5lOcLo979rru8MFqVHKdTqPBm4k3iQd8n0sWbBkOfuq9vDTGN9suZgYlH3jq6QTp3tG3EYapzsTHL7ycqRTP5Qf6rQSB33DcQaaqwQhpbuqPBm4k3iQd8n0sWbBkOf}```
