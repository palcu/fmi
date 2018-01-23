# Dezvoltarea Aplicatiilor Web - Radu Ionescu

## Subiecte

### 332 - iarna 2018

```
1. (1 p)
   Sa se creeze o baza de date cu informatii despre sportivii participanti la Jocurile Olimpice de Iarna de la Pyeongchang. 
   Baza de date contine urmatoarele doua tabele:
   
   + Proba:
	- IDProba - int - id-ul probei (cheie primara)
	- Denumire - varchar - denumirea probei
	- Data - date - data la care are loc proba
	
   + Sportiv:
	- IDSportiv - int - id-ul sportivului (cheie primara)
	- Nume - varchar - numele sportivului
	- Prenume - varchar - prenumele sportivului
	- Tara - varchar - tara din care provine sportivul
	- DataNasterii - date - data nasterii sportivului
	- IDProba - int - proba la care participa sportivul (cheie externa)
	
   Creati cele doua tabele si adaugati cateva inregistrari (4-5  in fiecare tabel) folosind IDE-ul.
    
2. (4 p)
   Creati o aplicatie web care implementeaza cele 4 operatii fundamentale (Create, Read, Update, Delete) pe entitatea Sportiv
	Create (1 p) - Creeaza (insereaza) un nou sportiv;
	Read   (1 p) - Listeaza sportivii (impreuna cu denumirea probei la care participa);
	Update (1 p) - Actualizeaza informatiile despre un sportiv;
	Delete (1 p) - Sterge un sportiv.

   Nota: Pentru operatiile Create/Update/Delete nu se accepta folosirea controalelor de tipul GridView, FormView, DetailsView, cu exceptia situatiei cand puneti
   hyperlink-uri catre paginile de Create/Update/Delete.

3. (1 p)
   Asigurati-va, la fiecare pas, de validitatea datelor de intrare, folosind controalele de validare astfel incat sa fie respectate tipurile din baza de date.
   
5. (2 p)
   Integrati in aplicatie facilitatea de cautare a sportivilor. Acestia vor putea fi cautati dupa nume, tara si dupa proba la care participa. 
   In cazul specificarii tuturor campurilor se va folosi operatorul AND.
   
4. (1 p)
   Folositi un masterpage cu un meniu pentru accesarea facila a paginilor aplicatiei web.

Note:
	- Atentie la restrictiile de integritate si referentialitate ale bazei de date (chei primare, chei externe, campuri NOT NULL)!
	- Timp de lucru: 1 ora si 20 minute.
	- Se acorda 1 punct din oficiu.
```

### 333 - iarna 2018

```
1. (1 p)
   Sa se creeze o baza de date cu informatii despre albumele muzicale disponibile intr-o librarie.
   Baza de date contine urmatoarele doua tabele:

   + Artist:
	- IDArtist - int - id-ul artistului (cheie primara)
	- Nume - varchar - numele artistului/trupei
	- AnDebut - int - anul in care a debutat artist

   + Album:
	- IDAlbum - int - id-ul albumului (cheie primara)
	- IDArtist - int - id-ul artistului caruia ii apartine albumul (cheie externa)
	- TitluAlbum - varchar - titlul albumului
	- DataAparitie - date - data in care a fost lansat albumul
	- GenMuzical - varchar - genul muzical din care face parte albumul
	- NrExemplare - int - numarul de exemplare vandute

   Creati cele doua tabele si adaugati cateva inregistrari (4-5) folosind IDE-ul.
   Creati constrangerile de cheie primara, cheie externa, auto-increment, campuri NOT NULL. 

2. (4 p)
   Creati o aplicatie web care implementeaza cele 4 operatii fundamentale (Create, Read, Update, Delete) pe entitatea Album:
	Create (1 p) - Creeaza (insereaza) un nou album;
	Read   (1 p) - Listeaza albumele (impreuna cu numele artistului autor) in ordinea descrescatoare a numarului de exemplare vandute;
	Update (1 p) - Actualizeaza informatiile despre un album;
	Delete (1 p) - Sterge un album.

   Nota: Pentru operatiile Create/Update/Delete nu se accepta folosirea controalelor de tipul GridView, FormView, DetailsView, cu exceptia situatiei cand puneti hyperlink-uri catre paginile de Create/Update/Delete.

3. (1 p)
   Asigurati-va, la fiecare pas, de validitatea datelor de intrare, folosind controalele de validare astfel incat sa fie respectate tipurile din baza de date.

4. (0.5 p)
   Folositi un MasterPage cu un meniu pentru accesarea facila a paginilor aplicatiei web.

5. (1 p) 
   Sa se afiseze un tabel/lista cu numarul total de exemplare vandute de fiecare artist, in ordinea descrescatoare a numarului de exemplare.

6. (1.5 p)
   Integrati in aplicatie facilitatea de cautare a albumelor. Acestea vor putea fi cautate dupa genul muzical sau dupa numele artistului. In cazul completarii ambelor campuri se va folosi operatorul AND.

Note:
	- Atentie la restrictiile de integritate si referentialitate ale bazei de date!
	- Timp de lucru: 1 ora si 20 minute.
	- Se acorda 1 punct din oficiu.

```
### Model subiect rezolvat de prof 2018

- [Link](https://drive.google.com/file/d/1dxX6oHleWyJlUbAAL_4nWWFKR_gxDlJq/view?usp=sharing)

### 343 - 18.01.2015

```
1. (1 p)
   Sa se creeze o baza de date cu informatii despre telefoane si sisteme de operare mobil.
   Baza de date contine urmatoarele doua tabele:

   + Os:
        - IDOs - int - id sistemului de operare (cheie primara)
        - Denumire - varchar - numele sistemului de operare
        - Versiune - varchar - descrierea sistemului de operare

   + Smartphone:
        - IDPhone - int - id model smartphone (cheie primara)
        - IDOs - int - id sistemului de operare (cheie externa)
        - Denumire - varchar - numele modelului de telefon
        - Data - date - data lansarii modelului de telefon
        - Producator - varchar - numele producatorului
        - Descriere - varchar - descrierea telefonului (specificatii tehnice, etc)

   Creati cele doua tabele si adaugati informatii despre cateva telefoane si sisteme de operare folosind IDE-ul.
   Campurile nu pot avea valori NULL.

2. (4 p)
   Creati o aplicatie web care implementeaza cele 4 operatii fundamentale (Create, Read, Update, Delete) pe entitatea Smartphone:
        Create (1 p) - Creaza (insereaza) un nou tip de telefon;
        Read   (1 p) - Listeaza telefonaele mobile grupate dupa sistemul de operare;
        Update (1 p) - Actualizeaza informatiile despre un tip de telefon;
        Delete (1 p) - Sterge un tip de telefon.

   Nota: Pentru operatiile Create/Update/Delete nu se accepta folosirea controalelor de tipul GridView, FormView, DetailsView, etc.

3. (1 p)
   Asigurati-va, la fiecare pas, de validitatea datelor de intrare, folosind controalele de validare astfel incat sa fie respectate tipurile din baza de date.

4. (2 p)
   Integrati in aplicatie facilitatea de cautare a telefoanelor. Se pot cauta telefoane dupa denumire sau dupa producator.
   Se vor folosi doua textbox-uri pentru fiecare camp. In cazul specificarii ambelor campuri se va folosi operatorul OR.

5. (1 p) Folositi un Master Page cu un meniu pentru toate functionalitatile de mai sus.

Note:
        - Atentie la restrictiile de integritate si referentialitate ale bazei de date!
        - Timp de lucru: 1 ora si 20 minute.
        - Se acorda 1 punct din oficiu.

```

### mai vechi

```
1) Creati o baza de date care sa contina:
        a) tabelul „Angajat”:
                - id (cheie primara)
                - nume (sir de caractere maxim 64)
                - prenume (sir de caractere maxim 64)
                - data_nasterii (data)
                - data_angajare (data)
        b) tabelul „Departament”:
                - id (cheie primara)
                - id_angajat (cheie externa în „Angajat” (id))
                - denumire (sir de caractere maxim 128)
                - de_la_data (data)
                - pana_la_data (data)
        c) tabelul „Salarii”:
                - id_angajat(cheie externa în „Angajat” (id))
                - de_la_data (data)
                - pana_la_data (data)
                - valoare_salariu (întreg pozitiv)

    Atentie:
        - nici un cîmp (din nici o tabela) nu poate fi NULL
        - veti implementa restrictiile de integritate (chei primare) si referentialitate (chei externe)


        Adaugati, cu ajutorul IDE-ului, cîteva informatii în tabele (pentru 7 angajati).

    2)
        a) afisati toti angajatii care au salariu care depaseste o anumita valoare(introdusa în prealabil de utilizator)
        b) permiteti utilizatorului sa introduca în sistem angajati noi
        c) permiteti utilizatorului sa actualizeze informatiile unui angajat (angjatul de actualizat va fi ales în prealabil de utilizator)
        d) permiteti utilizatorului sa stearga un angajat care face parte dintr-un anumit departament (aleas în prealabil de utilizator)
        si care este angajat in acel departament de mai mult de 1 luna

    Nota: pentru operatiile de la punctele b)–d) nu aveti voie sa folositi controale databound
        (i. e. GridView, DetailsView, FormView, ListView etc.)

    3)
        a) permiteti utilizatorului sa caute angajati dupa nume sau prenume
        b) pentru o data introdusa de utilizator, afisati lista angajatiilor nascuti la data respectiva, cu toate detaliile asociate

    4)
        a) asigurati-va, la fiecare pas, de corectitudinea datelor de intrare (implementati validarea plecînd de la
                schema bazei de date)
        b) realizati un MasterPage folosit de fiecare pagina care sa prezinte un meniu cu operatiile de la punctele 2) si 3).

Barem:
        Subiectul 1):
                - crearea tabelelor: 1p
                - implementarea constrîngerilor:
                        - chei primare: 0,25p
                        - chei externe: 0,25p
                - introducere date: 0,5p
        Subiectul 2):
                a) 1p
                b) 1p
                c) 1p
                d) 1p
        Subiectul 3):
                a) 1p
                b) 1p
        Subiectul 4):
                a) 0,5p
                b) 0,5p
        1p din oficiu.

Timp de lucru: 90 de minute.
```


```
1) Creati o baza de date care sa contina:
        a) tabelul "Client":
                - id (cheie primara)
                - nume (sir de caractere maxim 64)
                - prenume (sir de caractere maxim 64)
                - data_nasterii (data)
                - adresa_mail (sir de caractere maxim 64)
        b) tabelul "Factura":
                - id_factura (cheie primara)
                - data_livrare (data)
                - data_emitere(data)
                - denumire (sir de caractere maxim 128)
                - cantitate (intreg pozitiv)
                - discount (intreg pozitiv)
                - valoare (real pozitiv)
        c)tabelul "facturaClient":
                - id_factura (cheie externa in "Factura" (id))
                - id_client (cheie externa in "Client" (id))

    Atentie:
        - nici un camp (din nici o tabela) nu poate fi NULL
        - veti implementa restrictiile de integritate (chei primare) si referentialitate (chei externe)


        Adaugati, cu ajutorul IDE-ului, cateva informatii in tabele (pentru 7 clienti).

2)
        a) afisati toti clientii care au o factura care depaseste o anumita valoare(introdusa in prealabil de utilizator)
        b) permiteti utilizatorului sa introduca in sistem facturi noi
        c) permiteti utilizatorului sa actualizeze informatiile unui client (clientul de actualizat va fi ales in prealabil de utilizator)
        d) permiteti utilizatorului sa stearga un client dupa adresa de email(aleas in prealabil de utilizator)

    Nota: pentru operatiile de la punctele b-d) nu aveti voie sa folositi controale databound
        (i. e. GridView, DetailsView, FormView, ListView etc.)

3)
        a) permiteti utilizatorului sa caute clienti dupa nume sau prenume
        b) pentru o data introdusa de utilizator, afisati lista clientilor care au acea data de emitere a facturii, cu toate detaliile asociate

4)
        a) asigurati-va, la fiecare pas, de corectitudinea datelor de intrare (implementati validarea plecand de la
                schema bazei de date)
        b) realizati un MasterPage folosit de fiecare pagina care sa prezinte un meniu cu operatiile de la punctele 2) si 3).

Barem:
        Subiectul 1):
                - crearea tabelelor: 1p
                - implementarea constrangerilor:
                        - chei primare: 0,25p
                        - chei externe: 0,25p
                - introducere date: 0,5p
        Subiectul 2):
                a) 1p
                b) 1p
                c) 1p
                d) 1p
        Subiectul 3):
                a) 1p
                b) 1p
        Subiectul 4):
                a) 0,5p
                b) 0,5p
        1p din oficiu.

Timp de lucru: 90 de minute.
```
