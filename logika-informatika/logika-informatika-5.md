Nama : Fitrah Ali Hudzaifah Sofyan

NIM : xxxxxxx



---

1. Terdapat interpretasi J atas domain D = {0, 1, 2, 3, 4, 5, 6}, sedemikian sehingga  
   
    {b ← 3, y ← 6, z ← 0, f ← f<sub>I</sub>(d<sub>1</sub>, d<sub>2</sub>, d<sub>3</sub>) = 2(d<sub>2</sub> + d<sub>1</sub>) - d<sub>3</sub> (mod 7), p ← p<sub>I</sub>(d<sub>1</sub>, d<sub>2</sub>): (d<sub>1</sub> + d<sub>2</sub>) <= 10d<sub>1</sub>, q ← q<sub>I</sub>(d<sub>1</sub>, d<sub>2</sub>, d<sub>3</sub>): 3(d<sub>1</sub> - d<sub>3</sub>) < 2(d<sub>2</sub> + d<sub>1</sub>)}

    Tentukan hasil perluasan interpretasi I dengan mengubah  nilai dari b, z, f, dan q.

    **Jawab :**

    Diketahui interpretasi :
    
    J : {b ← 3, y ← 6, z ← 0, f ← f<sub>J</sub>(d<sub>1</sub>, d<sub>2</sub>, d<sub>3</sub>) = 2(d<sub>2</sub> + d<sub>1</sub>) - d<sub>3</sub> (mod 7), p ← p<sub>J</sub>(d<sub>1</sub>, d<sub>2</sub>): (d<sub>1</sub> + d<sub>2</sub>) <= 10d<sub>1</sub>, q ← q<sub>J</sub>(d<sub>1</sub>, d<sub>2</sub>, d<sub>3</sub>) : 3(d<sub>1</sub> - d<sub>3</sub>) < 2(d<sub>2</sub> + d<sub>1</sub>)}

    Hasil perluasan interpretasi J dengan mengubah nilai dari b, z, f, dan q adalah :

    K:<a ← 3> • <z ← 6 > • <f ← f<sub>K</sub> (d<sub>1</sub>, d<sub>2</sub>, d<sub>3</sub>) = 3(d<sub>2</sub>*d<sub>1</sub> + d<sub>3</sub>) (mod 7)> • <q ← q<sub>K</sub>(d<sub>1</sub>, d<sub>2</sub>, d<sub>3</sub>) : 2(d<sub>1</sub>d<sub>3</sub>) ≥ 3(d<sub>1</sub>d<sub>2</sub>)> • J
    

2. Perhatikan pernyataan berikut:  

    ```
    Beberapa orang yang tinggal di Jakarta work from home tetapi beberapa orang yang bekerja di bidang kesehatan tidak work from home.
    ```

    Buatlah sebuah formula kalimat dari pernyataan di atas!

    **Jawab :**


    >(**for some** x)(**p**(x) **and** **r**(x)) **and** (**for some** y)(**p**(y) **and q**(y) **and not r**(y))

    
   **p**(x) = **p** (y)  = orang yang tinggal di jakarta  
    **q**(y) = orang yang bekerja di bidang kesehatan  
    **r**(x) = **r**(y)  = work from home  

3. Perhatikan kalimat berikut:   
    ```
    Saya menyukai basket atau voli. Jika saya menyukai basket, maka saya menyukai voli.
    ```
    Apakah bisa dinyatakan bahwa :  
    ```
    “saya menyukai basket”?
    ```
    Buktikan validitas kalimat tersebut menggunakan tabel kebenaran!

    **Jawab :**

    **Langkah 1**  
    Menentukan premis 1, premis 2, dan kesimpulan

    Premis 1 : Saya menyukai basket atau voli  
    Premis 2 : Jika saya menyukai basket, maka saya menyukai voli.
    Kesimpulan : Jadi, Saya menyukai Basket

    **Langkah 2**  
    Menentukan pemisalan simbol proposional

    Misalkan : 

    P : Saya menyukai basket  
    Q : Saya menyukai voli

    **Langkah 3**  
    Membuat kalimat proporsional

    Premis 1 : Saya menyukai basket atau voli. Dituliskan menjadi P or Q  
    Premis 2 : Jika saya menyukai basket, maka saya menyukai voli. Dituliskan menjadi if P then Q
    Kesimpulan : Saya menyukai Basket. Dituliskan menjadi P

    Kalimat proporsionalnya :

    if (P or Q) and (if P then Q)) then P

    **Langkah 4**  
    Membuat tabel kebenaran

    | P | Q | P or Q | if P then Q |(P or Q) and <br>(if P then Q) | if ((P or Q) and <br>(if P then Q)) then P |
    |:-:|:-:| :----: | :---:       |  :---:                    |  :---:                                |
    | T | T |    T   | T           | T                         |       T                               |
    | T | F |    T   | F           | F                         |       T                               |
    | F | T |    T   | T           | T                         |       T                               |
    | F | F |    F   | T           | F                         |       T                               |

    **Kesimpulan**  
    Berdasarkan tabel kebenaran diatas terdapat nilai yang **false**, sehingga kalimat "Saya menyukai basket atau voli. Jika saya menyukai basket, maka saya menyukai voli. Jadi, saya menyukai basket" bukan merupakan kalimat valid. Jadi tidak bisa dikatakan "saya menyukai basket".
