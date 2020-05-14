Nama : Fitrah Ali Hudzaifah Sofyan

NIM : xxxxxxxx

---

**1. Diberikan sebuah kalimat sebagai berikut:**

```
{(P or  (Q and R)) and (P or Q)} ◁  {Q ← not(P or R)}
```

Jelaskan langkah untuk menentukan hasil subtitusinya!

**Jawab :**

Identifikasi F,G,H pada kalimat diatas :
```
F : {(P or  (Q and R)) and (P or Q)}
G : Q
H : not(P or R)
```

Ditentukan semua permunculan Q pada kalimat F

    (P or  (Q and R)) and (P or Q)

Terlihat ada dua permunculan Q pada kalimat tersebut. Sehingga proses subtitusi dilakukan dengan :

a. Mengganti nol permunculan G didalam F, hasilnya :

    (P or  (Q and R)) and (P or Q)

b. Mengganti satu permunculan pertama G didalam F, hasilnya :

    (P or  ((not(P or R)) and R)) and (P or Q)

c. Mengganti satu permunculan kedua G didalam F, hasilnya :

    (P or  (Q and R)) and (P or (not(P or R)))

d. Mengganti semua permunculan G didalam F, hasilnya :

    (P or  ((not(P or R)) and R)) and (P or (not(P or R)))
 


**2. Diberikan sebuah kalimat sebagai berikut :**

    {(Q or R) if and only if (P and not(Q or R))} ◁ {notQ ← notR, (Q or R) ← S, (Q and notR) ← (P or Q)}

Jelaskan langkah untuk menentukan hasil dari subtitusi multi-nya!

**Jawab :**

Identifikasi kalimat dan kalimat bagian-kalimat bagian :


F : (Q or R) if and only if (P and not(Q or R))

>G<sub>1</sub> : notQ

>G<sub>2</sub> : (Q or R)

>G<sub>3</sub> : (Q and notR)

>H<sub>1</sub> : notR

>H<sub>2</sub> : S

>H<sub>3</sub> : (P or Q)

Terlihat pada kalimat bagian yang muncul pada kalimat F hanya G<sub>2</sub> , sehingga, kalimat hasil subtitusi multi totalnya adalah :

```
S if only if (P and not(S))
```



**3. Terdapat sebuah kalimat berikut :**

F : p → (q and ¬ q) or ¬ p

Buktikan dengan tabel kebenaran validitas dari kalimat tersebut!

**Jawab :**

![alt text](tabel.png "Tabel Kebenaran F : p → (q and ¬ q) or ¬ p created by Fitrah Ali Hudzaifah Sofyan")

**Kesimpulan**

Kalimat **F** **bukan merupakan kalimat valid**, karena pada kalimat yang diberikan dan dibuktikan pada tabel kebenaran, **F** tidak ada yang bernilai true dibawah setiap interpretasi untuk **F**