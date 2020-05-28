# Broken Button

# Challenge
This [site](https://broken_button.tjctf.org/) is telling me all I need to do is click a button to find the flag! Is it really that easy?

# Solution
1. Inspect element dan hanya mendapatkan: ```<button>button</button>```
2. Terdapat button yang mengarah ke ```"find_the_flag!.html"```.
```
<button class="hidden" href="find_the_flag!.html"></button>
```
3. Button pertama diubah menjadi ```a``` dan tambahkan href="find_the_flag!.html" dan menjadi 
```
<a href="find_the_flag!.html">button</a>
```
4. Akan diarahkan menuju [html](https://broken_button.tjctf.org/find_the_flag!.html) dan mendapatkan flag

# Flag
```tjctf{wHa1_A_Gr8_1nsp3ct0r!}```


