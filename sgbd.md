# Sisteme de Gestiune a Bazelor de Date - prof Velcescu

O arhiva [mare cu chestii](https://www.dropbox.com/sh/wozcxaz1u7c90tg/AABZEuDF2SdWs4ROjFU6WveNa?dl=0). Nu am rabdare sa le selectez ca mi se pare de căcat materia și nu am de gând să învăț.

## Exemple examen

- [2015-05-07](https://www.dropbox.com/s/eujg4xqpbiamu93/sgbd%202015-05-07%2022.47.26.jpg?dl=0)

## Teste de laborator

### Unu

Schemele relationale ale modelului folosit sunt:

```
PREZENTARE (cod_pr, data, oras, nume)
SPONSOR (cod_sponsor, nume, info, tara_origine)
SUSTINE (cod_pr, cod_sp, suma)
VESTIMENTATIE (cod_vestimentatie, denumire, valoare, cod_prezentare)
```

Exercitii :

1. Sa se creeze tabelul CITY_FASHION, care va include pe prima coloana un nume de oras, iar pe a doua coloana numarul de prezentari care au avut loc in orasul respectiv. Sa se adauge constrangerea de cheie primara pe prima coloana si constrangerea not null pe coloana a doua. (2p)

2. Sa se creeze un subprogram care, pentru un an furnizat ca parametru, afiseaza denumirile prezentarilor desfasurate in acel an, iar pentru fiecare dintre acestea obtine numele sponsorilor care le-au sustinut. Sa se apeleze subprogramul. (3.5p)

3. Sa se creeze un subprogram care primeste ca parametru un cod de sponsor si returneaza denumirea prezentarii celei mai recente pe care a sustinut-o si in care a fost expusa cel putin o vestimentatie cu valoarea mai mica decat 1500. Sa se apeleze subprogramul. (3.5p)



### Doi
Schemele relationale ale modelului folosit sunt:

```
PERSONAL (id_salariat, nume, prenume, adresa, data_nastere, salariu, id_functie, id_specializare)
PACIENTI (id_pacient, nume, prenume, data_nastere)
TRATEAZA (id_salariat, id_pacient, data_internare, data_externare)
FUNCTII (id_functie, nume_functie, salariu_minim, salariu_maxim)
SPECIALIZARE (id_specializare, nume_specializare, id_manager)
```

Exercitii:

1. Subprogram care primeste ca parametru un cod de angajat si returneaza lista pacientilor de care acesta a avut grija, impreuna cu numarul de zile de internare pentru fiecare. Apelati.(3p)

2. Subprogram care afiseaza pentru fiecare functie denumirea acesteia impreuna cu lista angajatiilor care au salariul mai mare decat media salariilor colegilor (aceeasi functie) si care au avut cel putin doi pacienti. Tratati erorile care pot sa apara.(3p)

3. Trigger care la stergerea unui angajat care este manager de specializare, pune in locul acestuia angajatul care a avut cei mai multi pacienti dintre personalul cu specializarea respectiva (se considera ca acesta este unic). (3p)



### Trei

Schemele relationale ale modelului folosit sunt:
︎
```
PREZENTARE (cod_pr, data, oras, nume)
SPONSOR (cod_sponsor, nume, info, tara_origine)
SUSTINE (cod_pr, cod_sp, suma)
VESTIMENTATIE (cod_vestimentatie, denumire, valoare, cod_prezentare)
```

Exercitii:

1. Sa se creeze un subprogram care primeste ca parametru un cod de prezentare si afiseaza lista cuprinzand:
- numele sponsorilor care au sustinut prezentarea respectiva;
- procentul corespunzator sponsorului din totalul finantarilor pe care le-a efectuat;
- numarul sponsorizarilor pentru acea prezentare.
Sa se apeleze subprogramul. (3.5p)

2. Se presupune ca aplicatia nu va permite ca o sponsorizare pentru o prezentare din Paris sa fie mai mica decat 2000. Implementati aceasta regula. Testati. (2p)

3. Sa se creeze un subprogram care verifica daca toate vestimentatiile au un cod de prezentare specificat. In caz contrar, sa se actualizeze valoarea coloanei cod_prezentare ca fiind codul prezentarii celei mai recente (se considera ca este unic). Sa se returneze numarul de linii modificate. (3.5p)
