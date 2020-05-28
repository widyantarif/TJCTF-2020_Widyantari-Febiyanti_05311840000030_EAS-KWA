# Game W

# Challenge
Can you figure out how to [cheat](https://gamer_w.tjctf.org/) the system? Grab his hat to prove your victory!

# Solution
1. Untuk memainkan, ada beberapa aplikasi yang digunakan. Kali ini menggunakan [Chrome Extension Cetus](https://github.com/Qwokka/Cetus). Cetus digunakan untuk memanipulas.
2. Langkah selanjutnya adalah masuk ke dalam shop dan akan mulai memanipulasi. 
3. Manipulasi yang pertama adalah memodifikasi value dari gold sendiri. Search menggunakan Cetus dengan ```comparison operator EQ``` dan ```value type f32```.
<img width="358" alt="cetus" src="https://user-images.githubusercontent.com/55181778/83103639-45f52180-a0e1-11ea-8aa4-8048743392f4.png">
  4. Akan ditemukan ode untuk gold adalah ```0x02111f3c```.


5. Bookmark dan ubah value gold sebanyak mungkin untuk membeli semua item yang ada di shop.


6. Level 1 hanya melawan monster hijau (dikerjakan tanpa cheat).
<img width="691" alt="lv 1" src="https://user-images.githubusercontent.com/55181778/83103791-9a989c80-a0e1-11ea-9c5e-45fb82297db0.png">
7. Level 2 akan melawan 3 monster hijau yang sama dengan level 1 (dikerjakan tanpa cheat).
<img width="687" alt="lv 2" src="https://user-images.githubusercontent.com/55181778/83103871-c451c380-a0e1-11ea-94c7-6b5065cf5644.png">
8. Level 3 akan muncul boss pemilik monster monster tersebut (dikerjakan tanpa cheat). 
<img width="691" alt="lv 3" src="https://user-images.githubusercontent.com/55181778/83103923-e3505580-a0e1-11ea-8549-783a646b6b0e.png">
9. Level 4 boss tersebut akan ter-upgrade dan memiliki machine gun yang dapat menembak banyak peluru hijau sekaligus. Pada level inilah saatnya menggunakan cheat. 
<img width="688" alt="lv 4" src="https://user-images.githubusercontent.com/55181778/83103925-e51a1900-a0e1-11ea-9d2e-433935a428f9.png">
10. Dengan menggunakan Cetus, ubah total hp dari pemain (kita/user). Kode untuk hp pemain adalah 0x2112f1c

11. Bookmark dan ubah valuenya menjadi banyak supaya tidak mati-mati saat terkena tembakan hijau.

12. Level 5 boss akan minum potion yang membuat lifenya regenerate jika terkena serangan (menggunakan cheat untuk ubah hp boss).

13. Boss tersebut memiliki hp ```300``` (diketahui dengan cara menghitung 😏). Kode untuk hp boss adalah 
```
0x2112e4c
``` 

14. Bookmark, freeze, dan ubah valuenya menjadi 0.

15. Win win chicken dinner!


# Flag
```tjctf{c3tus_del3tus_ur_m3ms_g0ne}```
