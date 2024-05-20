-Ukupno ima (Calculator)118+(Start)16= (Total)134 LOC. Podatak je uzet sa programa Codalyze. Sto se tice Licence liniju koda ne mogu izracunati 
s obzirom da je kod ne postoji samo deskripcija.

-Sto se tice Cyclomatic Complexity za Calculator je Kompleksnost 12.
Ovo moze pokazivati na to da ove funkcije imaju veliki broj uslovnih izraza ili petlji, 
sto može otezati razumevanje, testiranje i odrzavanje koda.

-Sto se tice Cyclomatic Complexity za Start je Kompleksnost 3.
Ovo moze pokazivati na to da ove funkcije imaju manji broj uslovnih izraza ili petlji, 
sto može olaksati razumevanje, testiranje i odrzavanje koda.

Neformalan pregled bi se sastojao od: 

Calculator.java

Ovde imamo deo koda koji definise nacin na koji kalkulator radi. 
Postoji poseban deo za matematičke operacije i izracunavanje rezultata.

Start.java

Ovo je deo koda koji korisnik koristi da bi interagovao s kalkulatorom. 
Možeš uneti matematicki izraz i dobiti rezultat.

Zapazanje:

-Kalkulator radi tako sto podeli izraz na brojeve i operacije, a zatim izracuna rezultat.

-Kod nema proveru ulaznih podataka, 
sto znači da ako korisnik unese nesto nevazece poput slova umesto brojeva ili necega sto ne postoji kao operacija, 
program ce se verovatno izbaciti error ili dati netačan rezultat.