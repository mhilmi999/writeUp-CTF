# Vishwa CTF 2021
## Redeeem
### Informasi Soal
| Kategori | Poin |
|----------|------|
| Web | 382 |

## Deskripsi
![image](https://raw.githubusercontent.com/mhilmi999/writeUp-CTF/main/vishwaCTF/Web/Redeeem/screenshot/soalRedeem.png)\
One of our seller has the flags. and it seems you don't have enough money to buy the same. \
The only way to get money is by redeeming the coupon code. TRY UR LUCK !\
![image](https://raw.githubusercontent.com/mhilmi999/writeUp-CTF/main/vishwaCTF/Web/Redeeem/screenshot/lamanRedeem.png)\
[Redeeem VishwaCTF 2021](https://redeeeem.vishwactf.com/) <br />

## Penyelesaian Soal
Diberikan sebuah *clue* untuk mencari *Flag* yang tertanam pada *form* \
link [Redeeem VishwaCTF 2021](https://redeeeem.vishwactf.com/) <br /> 
Soal ini diselesaikan dengan menggunakan Tools Burpsuite dengan melakukan intercept on dan mengubah *current=0* menjadi *current=6969*
![image](https://raw.githubusercontent.com/mhilmi999/writeUp-CTF/main/vishwaCTF/Web/Redeeem/screenshot/lamanAwal.png)\
Setelah itu tekan tombol forward dan kita mendapatkan *Flag* balikan dari website.<br />
![image](https://raw.githubusercontent.com/mhilmi999/writeUp-CTF/main/vishwaCTF/Web/Redeeem/screenshot/brupProcess1.png)\
![image](https://raw.githubusercontent.com/mhilmi999/writeUp-CTF/main/vishwaCTF/Web/Redeeem/screenshot/flag.png)\

## Flag
> vishwaCTF{@DDed_T0_C@rT_}
