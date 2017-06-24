# Metode de Dezvoltare Software - Alin Ștefănescu

- [curs Moodle](http://moodle.fmi.unibuc.ro/course/view.php?id=486)
- Cheat sheet pentru examen updatat 2017 [aici](https://github.com/Vlaaaaaaad/FMI-public-materials/blob/master/MetodeDeDezvoltareSoftware/MDSv2.pdf) (©Sonia Horchidan)
- [rezumat online putin vechi](http://vladionescu.me/mds.html) cu sursa [aici](https://github.com/Vlaaaaaaad/FMI-public-materials/tree/master/MetodeDeDezvoltareSoftware) si cheat-sheet vechi pentru examen [aici](https://github.com/Vlaaaaaaad/FMI-public-materials/blob/master/MetodeDeDezvoltareSoftware/MDS.pdf)


## Examen seria 23 - 2017
1. 10 întrebări scurte de teorie
2. O temă cu un joc
 - 5 user stories / UML use case
 - o posibilă arhitectura (o diagramă UML cu 5 clase)
 - să comentăm o metodă dată și să definim minimal clasele folosite în metodă
 - să scriem 2 teste (JUnit)

## Examen seria 24 - 2017

La subiectul de exercitii a dat o tema cu site de internships:
 - Scrie 5 user stories.
 - UML cu cel putin 5 clase.
 - Doua metode de testare in ce limbaj vrei.
 - Si de refactorizat un cod (aflat si in curs, cel cu dayOfMonth).

## Recapitulare pentru examen (30.06.2017)

Punctare:
50p - 10 intrebari scurte cu raspunsuri scurte (de genul Care sunt avantajele X? sau Ce inseamna X?)
50p - un exercitiu practic:
  - Presupunem ca facem o aplicatie cu ...
  - Scrieti user stories, diagrame
  - Partea de arhitectura, design (MVC, ...)
  - Partea de testare (presupunem ca avem functie si scriem cod pentru testare)
  - Source control (ni se da o bucata de cod, sa gasim un bug, sa il corectam, sa optimizam)
    - tool de versionare
    - facem branch, merge (comenzi git)
    - refactorizare (sa punem codul duplicat in functie)

1. Backlog management
  - Ce contine un typical backlog?
  - definitia user stories.
  - exemple (Cine - ce - de ce).
  - caracteristici user stories ( + INVEST)
  - estimari
  - scrum framework - ca proces, ce contine
  - kanban

2.
  - Cerinte -> definitie, tipuri, clasificare + exemple
  - Posibilitati de reprezentare a cerintelor.

3.
  - Procesul de dezvoltare "cascada" (waterfall) - elemente de baza.
  - procesul incremental.
  - metodologia agile (Agile Manifest) - principii generale
  - 2-3/12 principii concrete.
  - programare extrema.
  - valori XP (eXtreme Programming).

  - Testare -> Test Driven Development.
  - Programarea in echipe de 2 - avantaje
  - Scrum - proces, elemente, roluri
  - Tool-uri

  - UML -> definitie, tipuri de diagrame, avantaje, dezavantaje
  - cazuri de utilizare -> definitie, exemple (reprezentare vizuala sau textuala)
  - elemente principale.

4.
  - Diagrame de clase - definitie, ce clase exista si relatia dintre ele
                      - reprezentare, asocieri (sa putem face o diagrama de clase la exercitiu).
  - agregare si compunere

  - sfaturi si perspective arhitecturale -> diagrame (+ explicatii)
  - diagrame de clase (standard)

  - modele de arhitectura software
  - MVC - descriere, avantaje, dezavantaje.

5.
  Mediu integrat de dezvoltare

  - Ce contine un IDE, organizarea structurala (elemente de baza).

  Refactorizare
  - definitie, scop, rezultate
  - tehnica de refactorizare (3/6-7), bune practici cand refactorizezi

  Build si versionare
  - Versionare - definitie, exemple de sisteme(framework) de versionare (minim 2)
  - Concepte VCS
  - Git -> comenzi uzuale (pt. exercitii) si sa explicam in cuvinte.
  - build -> definitie, faze, exemple(2/4).

6.
  - Inspectiile codului -> descrierea traceului.
  - Depanare (debugging) -> functionalitati.

  - Stadiul de viata al unui defect (bug) - sa stiu etapele.
  - exemple de mecanisme de limbaj.
  - atributele unui debugger.

7.
  - Testare -> cate ceva despre fiecare model de testare (acceptance, regression, ...)
  - Load testing, stress testing.
  - Exemple de metode de testare "cutie neagra"
  - partitionare clase de echivalenta.
  - testarea "cutie alba" -> definitie, tipuri de acoperiri (ce inseamna fiecare)
                                         \-- la nivel de ... -> definitie fara exemple
  - testarea unitara -> definitie, exemple.

11. performante
  - Criterii de masurare a performantei + pt. aplicatii web + pt. aplicatii desktop,
      2 instrumente de testare a performantei (un stress tester, un profiler).
  - Continous delivery.
  - Instrumente de deployment -> exemple, definitii, 2 tool-uri
  - Live monitoring system (tot slide-ul).
  - Diagrame de secventa -> elemente de baza (+ de reprezentat procesul/scenariul prin diagrama)
  - Diagrame de stari -> elemente.

13. sabloane
  - Sabloane - design patterns -> descrieri, scop, tipuri, sa stim ce face fiecare, comparatie.

