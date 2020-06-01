Nama : Fitrah Ali Hudzaifah Sofyan

NIM : xxxxxxxx


---

Perlihatkan kalimat 

F : (**for some** x)((**if** p(x) **then** p(a)) **and** (**if** p(x) **then** p(b))) 

adalah satisfiable

Kalimat F dikatakan satisfiable jika bernilai true dibawah suatu interpretasi untuk F

Pada kalimat tersebut terdapat aturan **and**, maka nilai  (**for some** x) (**if** p(x) **then** p(a) dan (**if** p(x) **then** p(b)) keduanya harus memiliki nilai true agar keseluruhan kalimat bernilai true sehingga memenuhi syarat untuk satisfiable

Kali ini saya akan membuktikan dengan tabel kebenaran.

Kalimat F : (**for some** x)((**if** p(x) **then** p(a)) **and** (**if** p(x) **then** p(b))) 

Notasi logikanya : ∃x ( (p(x)→p(a)) ∧ (p(x)→p(b)))

jika kita analogikan kedalam kalimat sehari hari akan menjadi :

__Ada__  **orang** pendukung **Persib** dan **Persija**

**∃x** = ada  
**p(x)** = orang  
**p(a)** = Persib  
**p(b)** = Persija  

Permis 1 : Ada orang yang pendukung Persib  
Premis 2 : Ada orang yang pendukung Persija  
Kesimpulan : Ada orang yang pendukung Persib dan Persija

Membuat tabel kebenaran :

P = Ada orang  
Q = Pendukung Persib  
R = Pendukung Persija  
P → Q ∧ P → R = Ada orang pendukung Persib dan Persija

**Table Kebenaran**

| P | Q | R | P → Q | P → R | (P → Q) ∧ (P → R) |
|:-:|:-:|:-:|:-----:|:-----:|:-----------------:|
| T | T | T |   T   |   T   |         T         |
| T | T | F |   T   |   F   |         F         |
| T | F | F |   F   |   F   |         F         |
| T | F | T |   F   |   T   |         F         |
| F | T | T |   T   |   T   |         T         |
| F | T | F |   T   |   T   |         T         |
| F | F | T |   T   |   T   |         T         |
| F | F | F |   T   |   T   |         T         |

Berdasarkan tabel kebenaran tersebut, maka kalimat F adalah satisfiable

