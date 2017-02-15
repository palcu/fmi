# Sisteme de Operare - Andrei Baranga

## Grupa 235 (29.01.2017)

1. Enumerați cele 3 mecanisme de comunicare de la IPC System V.
2. Enumerați două apeluri de sistem pentru gestiunea fișierelor și două apeluri de sistem pentru gestiunea proceselor.
3. Enumerați 3 componente după arhitectura lui Von Neumann.
4. Dați signatura apelului de sistem care creează un proces fiu.
5. Scrieți o funcție int myFunct() care așteaptă terminarea tuturor proceselor fiu și returnează 0 dacă toate procesele s-au terminat normal și -1 altfel.
6. Scrieți o funcție int myFunct(MYSTRUCT *p, int n) unde MYSTRUCT are două câmpuri - char *nume și int prioritate, iar vectorul p are n elemente. Funcția va crea un proces fiu care execută procesul cu prioritatea maximă și returnează pid-ul procesului în caz de succes și -1 în caz de eroare.

## Grupa 235 (08.02.2016) via Ciprian Olariu

1. Dati signatura apelului de sistem care blocheaza/deblocheaza portiuni de fisiere.
2. Numiti teoria matematica care sta in spatele detectiei situatiei de deadlock.
3. Numiti algoritmul folosit in UNIX pentru planificarea proceselor.
4. Numiti o tehnica de inlocuire a paginilor din memorie.
5. Scrieti o functie int myFunct(char *fis, int m, int *n) care deschide fisierul BINAR cu numele fis si citeste de la pozitia m din fisier *n valori intregi. Functia va calcula minimul dintre aceste valori si il va returna. In caz de eroare, in pointerul n se va stoca valoarea -1, altfel 0.
6. Scrieti o functie int myFunct(char *fis) care deschide fisierul BINAR cu numele fis si dintre numerele intregi din el le va sterge pe cele de valoare maxima. Functia intoarce -1 in caz de eroare, alfel 0. P.S.: Este permisa folosirea unui fisier auxiliar (care sa nu existe deja in director si care sa fie sters inainte de return), dar nu este permisa maparea fisierului in memorie.

## Seria 23 restanță 06.02.2015

1. Numiți o extensie de arhive.
2. Numiți cele 3 feluri de permisii ale fișierelor.
3. Numiți 4 apeluri de sistem.
4. Scrieți o funcție `int myFunct(int *pid, int *sig, int n)`, în care ambii vectori sunt de lungime n, primul reprezintă o listă de identificatori de procese, al doilea reprezintă o listă de semnale. Pentru fiecare proces `i` din `pid`, trimiteți semnalul `i` din `sig`. Dacă unul dintre apeluri nu a mers, returnați numărul de semnale care au fost trimise. Dacă toate au mers, returnați `n`.
5. Scrieți o funcție `int myFunct(key_t cheie, void (*f)())` care primește cheia de la un semafor și o funcție. Decrementați semaforul, apelați funcția, incrementați la loc. Dacă nu a mers vreun apel, returnează -1, altfel return 0.

## grupa 241 (2014)

```
1. Dacă o pagină are 512 octeți, câte pagini sunt în 1MB?
2. Care sunt politicile de înlocuire ale paginilor?
3. Ce este fragmentarea discului?
4. Care sunt părțile componente ale unui hard disk?
5. Scrieti o functie în C `int myFunct(char *dir)` care returneaza suma mărimilor fișierelor din acel director.
6. Scrieți o funcție în C `int myFunct(char *fis)` care citește acel fișier și scrie un număr de octeți astfel încât mărimea acelui fișier modulo 256 să fie 0.
```

[Solutii](https://github.com/palcu/homework/blob/master/so/examen-2014-grupa-241/pr5.c).

## grupa 234 (2014)

```
Subiecte SO 234:

1. Signatura apelului sistemului unix princare se citesc date dintr-un fisier;
2. Se considera variabilele:
- int a,b;
Scrieti o secventa de cod care interschimba valorile celor doua variabile fara a folosi o variabila auxiliara.
3. Enuntati problema filozofilor;
4. Enumerati tipurile de IPC SystemV;
5. Scrieti o functie c int myfunc(int semid, void (*f)());
care apeleaza functia data de f decrementand in prealabil semaforul cu identificatorul intern dat de semid., dupa apel, incrementeaza semaforul. Se returneaza 0 in caz de succes si -1 in caz de eroare.
6. Scrieti o functie c int myfunc(char *fis, char *s, int nr);
care creaza fisierul cu numele dat de fis si il umple cu valorile lui s de nr ori. In caz de eroare se returneaza -1 si 0 in caz de succes.
```

## seria 24 (2014)

```
Subiecte SO de azi:
- cand un fisier e sters complet
- tipuri de interfete cu utilizatorul
- multiprocesor (nu stiu daca tipuri de arhitecturi)
- o problema cu semnale
- functie care sa calculeze nr de aparitii al unui sir intr-un fisier
```

## Grupa 234 2015

[Poză](https://www.dropbox.com/s/1cn4wu5n8kv5frw/subiect_examen_2015.jpg?dl=0) cu subiectele via Theodor Stanbeca

[Solutii](https://github.com/palcu/homework/tree/master/so/examen-2014-seria-24)

## Alte subiecte

* [subiecte examen 2013](https://www.dropbox.com/s/ll82pfkopgi3q57/subiecte_examen_2013.txt?dl=0)
* [subiecte examen 2012](https://www.dropbox.com/s/pd50ijoozna0s0k/subiecte_examen_2012.pdf?dl=0)
* [subiecte oral](https://www.dropbox.com/sh/zgehw54xqqt2yy9/AABeq3DIgWz0wldQ09BrTfq_a?dl=0)
* [subiecte pe is-a-geek](http://fmi.is-a-geek.net/index.php/Sisteme_de_operare_%28Andrei_Baranga%29#Cursuri)
* [probabil subiecte 2010-2012](https://www.dropbox.com/s/x200dlay1g7849b/subiecte_vechi.txt?dl=0)
* [probabil subiecte ceva mai noi](https://www.dropbox.com/s/gkq0tia7a73h9w4/alte_subiecte.txt?dl=0) via Leo Stanescu
* [subiect examen 2011](https://www.dropbox.com/s/8rztqwl0k2owuk2/subiect_examen_2011.jpg?dl=0) + [rezolvare](https://www.dropbox.com/s/5zu9mtnrahicqpz/rezolvare_subiect_2011.txt?dl=0)

# Cursuri

* [slides](https://www.dropbox.com/sh/dwml865r63x5soq/AACBBCl08v-ycJo4PzqToZB-a?dl=0)
* [notițe 2013](https://www.dropbox.com/sh/mume4oo6rc4jhnh/AAClbYH4clSsmug4SXUQWmnWa?dl=0)
* [notițe 2013 scris urât](https://www.dropbox.com/s/l6bn0sevg6p6kg6/curs_2013_scris_urat.pdf?dl=0)
* [notițe 2013 again](https://www.dropbox.com/sh/mume4oo6rc4jhnh/AAClbYH4clSsmug4SXUQWmnWa?dl=0)

## Utile
* [main-uri cu semafoare, cozi de mesaje, shared memory, semnale, fisiere binare, execl](https://www.dropbox.com/sh/74kwcgg59x57hs7/AACuQDtpFQYNlnNfTqygwSDqa?dl=0)

# Recomandări @palcu

* [cursul de la Poli](http://ocw.cs.pub.ro/courses/so) e mult mai bun dacă vrei să înveți ceva
* [o grămadă](https://hn.algolia.com/?query=operating%20system&sort=byPopularity&prefix&page=0&dateRange=all&type=story) de URL-uri și discuții despre sisteme de operare

[Aici](https://www.dropbox.com/sh/n8107fznkb8zboa/AABennEy8Xg7mbWB-DtGBA6Ma?dl=0) e adresa cu întreg folderul.
