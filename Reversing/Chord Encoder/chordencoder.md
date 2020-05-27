# Chord Encoder

# Challenge
I tried creating my own [chords](https://static.tjctf.org/67be5bd036a4be8323314d1da6ad2e673963f76634a62ec47d53fb07a04a3722_chords.txt), but [my encoded sheet music](https://static.tjctf.org/c29857b8d4d1b2dfe502b5053d73844a08358ae681b2af8de6829b765dc2c28e_notes.txt) is a little hard to read. Please play me my song!

[chord_encoder.py](https://static.tjctf.org/da36df431da358250884ff9765e8c0c5f054b845aff31b85e37229159176bb9f_chord_encoder.py)

# Hint
Pathfinding? I just need some sick jams B)

# Solution
1. konversi isi dari [encoded sheet music](https://static.tjctf.org/c29857b8d4d1b2dfe502b5053d73844a08358ae681b2af8de6829b765dc2c28e_notes.txt) kedalam bentuk [lagu1.txt](https://github.com/widyantarif/TJCTF-2020_Widyantari-Febiyanti_05311840000030_EAS-KWA/blob/master/Reversing/Chord%20Encoder/lagu1.txt)
2. setelah itu, konversi kembali isi dari [lagu1.txt](https://github.com/widyantarif/TJCTF-2020_Widyantari-Febiyanti_05311840000030_EAS-KWA/blob/master/Reversing/Chord%20Encoder/lagu1.txt) berdasarkan [chords.txt](https://github.com/widyantarif/TJCTF-2020_Widyantari-Febiyanti_05311840000030_EAS-KWA/blob/master/Reversing/Chord%20Encoder/chords.txt) akan menjadi seperti [lagu2.txt](https://github.com/widyantarif/TJCTF-2020_Widyantari-Febiyanti_05311840000030_EAS-KWA/blob/master/Reversing/Chord%20Encoder/lagu2.txt)
3. jalankan [Chord Encoder.py](https://github.com/widyantarif/TJCTF-2020_Widyantari-Febiyanti_05311840000030_EAS-KWA/blob/master/Reversing/Chord%20Encoder/Chord%20Encoder.py)

# Flag
```flag{zats_wot_1_call_a_meloD}```
