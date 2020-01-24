# Calculabilitate si complexitate

## Examen

- [rezumat subiecte examen via @dianamin](https://drive.google.com/drive/folders/0B7PBRdEr5pqnZHN6anpmSEZEZGc)
- [lista subiecte examen (2012)](https://www.dropbox.com/s/9sh5daew5bxn63e/Calculabilitate%20si%20Complexitate%20-%20Lista%20Subiecte%20ianuarie%202012.pdf?dl=0)
- [lista subiecte examen (2013)](https://www.dropbox.com/s/ainarm3xablhi9l/CC%20subiecte%20teorie.txt?dl=0)
- [lista subiecte examen Mitrana (2014)](https://www.dropbox.com/s/vn91d9yp2m7qhsi/lista_subiecte_2014.txt?dl=0)
- [lista subiecte examen Voinescu (2014)](https://plus.google.com/photos/110111587079191484355/albums/6106395225339359665?authkey=CJbTiICI-qL5KA)
- [subiecte vechi Mitrana (2007-2009)](http://fmi.is-a-geek.net/index.php/Calculabilitate_si_complexitate_(Victor_Mitrana))
- [seminarii rezolvate si explicate de profa de seminar Maria Negru (2014)](https://www.dropbox.com/s/kqks970v7clpo0s/C%26C%20-%20explicatii%20exercitii%20%28seminarele%201-5%29.pdf?dl=0)

## Cursuri
- [Seminar + Curs (2013)](https://www.dropbox.com/s/bub3dlcf8kz5xkv/cc.zip?dl=0)
- [Seminar + Curs 1-9 (2012)](https://www.dropbox.com/s/dgfj256eyqw8zw7/CC%20-%20curs%26sem%201-9.pdf?dl=0) și [10-12 (2012)](https://www.dropbox.com/s/i0ujud7kz4dj8f3/CC%20-%20Curs%2010-12.pdf?dl=0)
- [Seminar + Curs (2011)](https://github.com/aliasbind/Sesiune/tree/master/an2/sem1/CC)
- [Curs 2008](https://www.dropbox.com/sh/nil9fllldfc1rln/AACPaV0R49kuMyRtQYkQyYYza?dl=0)
- [teoria de tocit pentru examen (2014 cred)](https://www.dropbox.com/s/9ve437rxiiryk7v/CC.pdf?dl=0) via Budiș
- [tot teorie, insa scrisa in fisiere txt (2013)](https://www.dropbox.com/sh/sp282a3cvyy65lb/AADRBPoUrqNdR9Q_C5V6E1AWa?dl=0)

## Subiecte Examen

### Victor Mitrana (Iarna 2020)
* Teorie: Funcții recursive / Turing calculabile / calculabile cu programe standard
  * Definiții ale noțiunilor - Nota 6
  * Două demonstrații (la alegere) - 2p per demonstrație
* Practică: Descrieți o mașină Turing care să accepte limbajul
   L = { a^n | n = k*(k+1)/2, k > 0 }
  * Rezolvarea corectă - Nota 6
  * Dacă este deterministă - 1p
  * Dacă folosește doar o bandă - 1p
  * Complexitate timp - 1p
  * Complexitate spațiu - 1p

### Victor Mitrana (Feb 2019)
#### Seria 24
* Teorie: Functii recursive
* Practica: L = { a^n b^k c^p | k = 2*n, p = n^2, n>0 }
  * O mașină Turing care acceptă L (punctaj maxim daca are o banda)
    * banda de input se pune ca a 2a banda aici, deci pt punctaj maxim trebuie fara ea
    * in general banda de input nu intra la complexitatea de spatiu, dar aici trebuia adaugat si dimensiunea inputului, inclusiv la rezolvarile in O(logN) spatiu aditional fata de cel ocupat de cuvantul de input
  * Complexitatea spatiu la masina construita la punctul anterior (1 punct)
  * Complexitatea de timp la masina construita la punctul anterior (2 puncte)
  * **sidenote**: din cate tin minte masina putea sa aibe orice complexitate de timp/memorie

### Victor Mitrana (2017)
#### Seria 23 - 233, 234, 235
* Teorie: Complexitate Timp
* Practică:  L = {w din {a, b, c}*| numărul de a-uri = 2 * numărul de b-uri = numărul de c-uri}
  * O mașină Turing care acceptă L în spațiu O(logn)
  * Numărul de pași pe care îi face mașina de la primul punct
  * O mașină Turing care acceptă L și care face O(n) pași

#### Seria 24
* Teorie: Complexitate Timp (da, același subiect)
* Practică:  O mașină Turing care are ca input x, y și verifică dacă y este o putere a lui x utilizând o singură bandă.

### Victor Mitrana (2014)

* Teorie: subiectul 5 din [lista lui](https://www.dropbox.com/s/vn91d9yp2m7qhsi/lista_subiecte_2014.txt?dl=0)
* Practică: să se explice o mașină Turing care verifică dacă un număr primit în baza 1, este palindrom în baza 2 (pe o singură bandă)

### Subiecte test final seminar (Maria Negru 2014)

* descrie o mașină Turing,  unde primești `a, b, c` în ordine crescătoare, de verificat daca a^2 + b^2 = c^2

### Daniel Voinescu (2014)

```
au fost 2 variante de examen
a teorie a dat subiectul 2 din alea propuse
prima a fost teorie + un ex
teoria a fost functii recursive, functii calculabile cu programe standard, funcii turing calculabile
si ex a fost sa descrii o MT care accepta cuvinte de forma a ^ 3 ^k si b ^ 3 ^ k
practic ti se zicea sa descrii ( nu sa faci grafic ci doar sa pov cam cum ar merge) o MT care accepta cuv de forma aia
+ MT trebuia sa aiba o singura banda si sa accepte cuvintele in O(n*logn)
si sa arg complex timp si sp
si varianta a 2-a de examen
era acelasi ex ca asta de mai sus + reprez lui grafica(stari , tranzitii, etc)
```
via [Daniel Radu](https://github.com/TwoOfDiamonds)
