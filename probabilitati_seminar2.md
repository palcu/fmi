# Pr 1
O colectie de 18 carti contine si cartea Kamasutra. O persoana doreste sa aleaga 6 din aceste carti pentru vacanta. In cate moduri poate alege 6 carti, si cate din aceste moduri include Kamasutra?

a) C(18,6) = 18564
b) C(17,5) = 

# pr 2
Un comitet de 5 persoane e ales din 6 barbati si 4 femei, in urmatoarele 3 cazuri

a) 3 barbati, 2 femei - 
b) mai multi barbati
c) 3 b, 2 f, dar o femeie refuza sa fie cu un anumit barbat

a) C(6,3) * C(4,2)
b) (C(6,5) * C(4,0)) * (C(6,4) * C(4,1)) * (C(6,3) * C(4,2))
c) C(5,2) - C(3,1) - 30

# pr 3
MATHEMATICS
a) numarul aranjamentelor celor 11 litere
b) probabilitatea ca toate vocalele sa fie plasate impreuna

a) X = 11! / (2! * 2! * 2!)
b) Y = (numarul permutarilor consoanelor plus vocalele luate ca si consoane * numarul permutarilor vocalelor) = 	8! / (2! * 2!) * (4! / 2!)
Y / X

# pr 4
4 litere sunt alese la intamplare din literele cuvantului RANDOMLY. Gasiti probabilitatea ca literele alese sa fie consoane.
C(8,4)/C(6,4)

# pr 5
Parcarea scolii are 13 locuri in linie. Sunt 9 masini ce trebuie parcate.
a) Cate aranjamente diferite sa pot obtine
b) Cate aranjamente diferite a.i. cele 4 locuri libere sunt unul langa altul.
c) Probabilitatea sa nu fie 4 locuri libere.

a) A(13,9)
b) x = A(10,9)
c) 1 - A(10,9) / A(13,9)

# pr 6

http://ro.wikipedia.org/wiki/Variabil%C4%83_aleatoare

Dintr-un lot ce contine 4 piese corespunzatoare si 3 piese defecte se extrag simultan 3 piese, in vederea controlului de calitate. Fie X variabila aleatoare care indica numarul de piese corespunzatoare obtinute in cele 3 extrageri. 
a) Determinati repartitia variabilei aleatoare X.
b) Probabilitatea ca cel putin 2 dintre piesele extrase sa fie corespunzatoare.

a) 
```
0 1 2 3
P(X = 0) = C(3,3)/C(7,3) 
P(X = 1) = C(4,1) * C(3,2) / C(7,3)
P(X = 2) = C(4,2) * C(
```

b) 18/35 + 4/35

Media
E(X) = 0 * 1/35 + 1*(12/35) +2*(18/35) + 3*restul

# pr 7
Dintr-o urna ce contine 50 bile albe si 100 de bile negre, se extrag cu revenire 3 bile.
Fie X, variabila aleatoare care indica numarul bilelor albe

P(X = k) = C(k,n) * p^k * q^(n-k)
q = 1-p

P(X = 0) = (2^3)^3
P(X = 1) = (1/3) * (2/3)^2

# pr 8
Din cei 2.000 de salariati ai unei firme, 300 au studii superioare. Se selecteaza random un esantion de 40 de fraieri si se noteaza cu X variabila aleatoare ce reprezinta numarul salariatilor cu studii superioare. Repartitia vietii

k = 0...40
C(300,k)*C(1700,40k) / C(2000, 40)

# pr 9
Se incearca doborarea unui obiect prin trageri. Pentru doborarea lui e suficienta o tragere reusita cu probabilitatea de succes 1/3. Care este media numarului de trageri?
