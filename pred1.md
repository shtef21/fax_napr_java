
# Prvi labos za 2. tjedan nastave
- podijeliti uloge u timu - 1 bod
- pobrojati product backlog - 2 boda
- napraviti 'Refinement' product backlog itema - razbiti na male taskove - 3 boda
- procijeniti vrijeme potrebno za implem zadataka - 3 boda
- nacrtati 'mockup' ekrana Figma alatom
- kreirati prototip (demonstraciju) aplikacije Figmom


# Uvod u agilnu metodologiju

- SCRUM je okvir upravljanje inkrementalnim razvojem produkta
- temelji se na timovima od oko 7 ljudi koji se samostalno organiz. i surađuju
- omogućava strukturiranje uloga u timu, sastanka, pravila organizacije i artefakata
- timovi su odgovorni za kreiranje i uvođenje svojih procesa unutar Scrum okvira
- koristi iteracije fiksne duljine (Sprint), koji običnost traju 1-2 tjedna, ali nikako više od 30 dana
- rezultat sprinta - testirana verzija produkta


## Alternativa 'waterfall' pristupu

- inkrementalni iterativni pristup Scruma zamjenjuje tradicionalni 'waterfall'
- omogućuje se češće izdavanje parcijalnih verzija produkta
- krajnji korisnik što prije može biti uključen u njegov razvoj

Scrum se temelji na:
- iteration 1
- iteration 2
- iteration 3
- iteration 4



## Uloge

- customer -                        generator posla / zahtjeva
- product owner (product manager) - izvući najviše iz tima; zadovoljan klijent
- sprint / Scrum master - brine se da se održavaju sve sastanice Scruma
- ...

  ### Product owner
- odgovorna osoba za maksimiziranje povrata investicije (return of investment) razvoja
- odg. za viziju
- odlučuje o prioritetima zadataka u Product Backlogu
- prilagođava planove izdavanja verzija produkta
- donosi konačnu odluku oko prihvaćanja zahtjeva od korisnika
- prihvaća ili odbacuje
- odlučuje kada će se izdati nova verzija
- uzima u obzir interese dionika sustava
- može sudjelovati u procesu kao dio tima

  ### Scrum Development Team
- eksperti raznih profila (programeri, testeri, posl. analitičari, eskerte za domenu problema)
- samostalno se organizira i samostalno upravlja (npr samostalno biranje mjesta itd)
- pregovara o preuzimanju obveza s Product Ownerom
- ima autonomiju oko odlučivanja kako će organizirati da se obveze izvrše
- intenzivno kolaborativan
- najuspješniji kad je lociran unutar jedne prostorije - pogotovo u prvih nekoliko sprinteva
- najuspješniji kad je dediciran na duže vrijeme na projektu
- najčešća veličina je 7 (+-2) člana

  ### Scrum master
- pazi da se poštuju pravila Scruma
- pomaže u rješavanju prepreka
- kreira okruženje koje omogućuje timu da se sâm organizira
- tijekom rada koristi empiričke podatke da se naprave što bolje procjene određenih zadataka
- štiti tim od 'vanjskih utjecaja' i distrakcija
- provodi organiziranje posla u vremenskim okvirima
- osigurava da rezultati Sprinta budu vidljivi
-   * Promovira napredne prakse inženjerstva



## Sastavnica

- Product backlog - popis svih zadataka - Jira, Trello, ...  - koliko sati treba raditi
- Sprint review
- Sprint daily standup - Što si radio jučer, što ćeš raditi danas, imaš li kakve probleme

...

  ### Scrum sastanci
  - sastanak za planiranje sprinta (Sprint planning meeting)
  - organiz. ga product owner i ostatak tima prije svakog sprinta
  - odabiru se zadaci iz product backloga koji će se impl u novom sprintu
  - sadržava sve zadatke koji se trebaju izvršiti 
  - product owner odlučuje što je najvažnije za impl
  - tim je odgovoran za odabir količine posla koju mogu izvršiti unutar sprinta
  - za procjenjivanje tim koristi iskustvo iz prošlih sprinteva
  - procjene tima rade u satima i sve inf za ivršavanje zadatka moraju biti poznate
  - procjenjivanje se obavlja grupno
  - zadaci koji će se izvršiti unutar jednog sprinta moraju producirati
    funkcionalnu verziju produkta koja se isporučuje na kraju samog sprinta

  ### Daily Scrum sastanak
  - održava se svaki dan na istom mjestu i traje 15tak min
  - u njemu se izjašnjavaju što su radili prošli dan i što će se raditi sljedeći
  - kako je cijeli tim na okupu, mogu se razrješavati problemi i prepreke oko implementacije

  ### Sprint review sastanak
  - na kraju sprinta tim prezentira
  - ...
  - ...
  - Product backlog
  - Sprint backlog
  - Burndown chart (linija) - kasnimo li i koliko?

  ### Retrospektiva
  - samo za tim - analiziraju se dobre i loše stvari u sprintu te predlažu poboljšanja
  - nije prisutan product owner
  - prisutan je scrum master (on nije nužno jedan od programera)

  ### Backlog refinement sastanak
  - kod procjenjivanja zadataka svaki Product Backlog Item (PBI) mora biti detaljno raspisan s detaljnim manjim zadacima
  - na taj način je lakše procijeniti potrebno vrijeme i svi članovi tima su upoznati što koji zadatak uključuje
  - zadaci se dijele na Epice, Storyje i zadatke (koji mogu biti bugovi)
  - Epic prestavlja modul projekta, Story jedan 'Use case', ...

* Odrediti temu sprinta i odabrati koji su zadaci iz backloga potrebni da bi se riješio
* Primjer sprint backloga -    Backlog items  |  Tasks not started  |  Tasks in progress  |  Tasks compelted
* Npr kanban board - tema tima - svaki programer je jedan nogometaš i autor određ zadatka



## Definition of Done (DoD)

- dokument koji opisuje kada je neki zadatak stvarno završen
- različita značenja za različite role na projektu
- npr za programera:
  - prog kod je pokriven unit testovima
  - pokrivenost je minimalno 75%
  - ...
- za testere i devopse:
  - napisan je QA (Quality assurance) testni plan
  - testiran i od testera koji nije autor QA testnog plana
  - deployan i testiran u odvojenom okruženju
  - automatski UI testovi su napisani i izvršeni
  - nema ozbiljnih bugova 1. i 2. razine
  - product owner je provjerio stanje nakon testiranja
  - ispunjen je kriterij prihvaćanja rješenja
  - deployment plan je provjeren od DevOpsa
  - promjene na bazi podataka su provjerene od DB admina
  - aplikacija je istestirana na vršnim opterećenjima (npr za 10, 100, 1000 korisnika...)
  - aplikacija je deployana na produkcijsku okolinu


## Sprint Burndown chart
- odmah komunicirati rizike
- prednost - odmah imamo priliku javiti klijentu da ćemo kasniti npr 2 tjedna


## Kanban
- na japanskom, kan / visual, ban / chart
- uvedena sredinom 20tog stoljeća u toyoti
- podjela na minimalno 3 stupca - todo, in progress, done
- podjela u redovima, npr 1 red je 1 veliki zadatak - grupiranje


## Procjenja trajanja zadataka
- planning poker - svi predlože i uzima se mjera složenosti (ne nužno dani/sati itd)
                - odredi se značenje svake mjere složenosti
- fist to five - svi istovremeno pokažu šakama od 1 do 5 - zbroje se prsti, uzme se prosjek


## Trello
- zapisivanje zadataka u backlog
  - stupci:
    - product backlog
    - sprint planning
    - current sprint
    - in progress
    - done


## Wireframe alati
- figma
- NinjaMock
- inVision



