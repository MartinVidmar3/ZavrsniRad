## ProjektR
U direktoriju ProjektR nalazi se sve sto sam napravio na Projektu R (analiza podataka, graficki prikazi i odvajanje povoljnih). Vecinu tih datoteka cu ponovno iskoristiti uz manje promjene (dodavanje fcu tipa).

# Zavrsni Rad
U sklopu ovog završnog rada implementirano je matematičko modeliranje klimatizacijskog sustava na Fakultetu elektrotehnike i računarstva (FER). Na temelju dostupnih ulaznih podataka i poznavanja domene problema, kreiran je strukturirani skup podataka pripremljen za proces treniranja modela. Analizirani su povijesni podatci prikupljeni u razdoblju od 2018. do 2022. godine. Ključan korak u predobradi podataka bio je identifikacija stacionarnih vremenskih intervala kako bi se osigurala stabilnost promatranog sustava.

Nakon provedenog procesa filtriranja, nad podacima je istreniran model algoritma slučajnih šuma (Random Forest), implementiran pomoću programskog jezika Python. Model funkcionira na principu "crne kutije" (black-box). Dobiveni rezultati pokazali su visoku točnost i robusnost, s obzirom na to da se black-box model uspješno prilagodio različitim, često ponavljajućim scenarijima unutar dinamike sustava.


## Diplomski projekt
U nastavku istraživanja provedena je komparativna analiza u kojoj su prethodno opisani podatci, umjesto modelom "crne kutije" (black-box), trenirani primjenom algoritma linearne regresije. Skup podataka segmentiran je prema režimima rada sustava (grijanje, hlađenje i isključen stanje) te prema intenzitetu rada ventilatora. Na temelju ovih parametara optimiran je vektor koeficijenata regresije $\theta$.Primjenom konvencionalne linearne regresije dobiveni su visoki pokazatelji točnosti, uz uočenu pojavu većih ekstremnih odstupanja (anomalija u predikciji) u usporedbi s prethodnim black-box modelom.S ciljem poboljšanja interpretabilnosti i usklađenosti s domenom problema, razvijen je i fizikalno utemeljeni regresijski model uvođenjem ne-negativnih ograničenja na prostor parametara ($\theta \ge 0$). Sukladno teorijskim očekivanjima, uvođenje fizikalnih ograničenja rezultiralo je blagim padom ukupne metričke točnosti na testnom skupu, no model je pokazao znatno veću robusnost, eliminaciju fizikalno nemogućih rješenja te stabilnije ponašanje u rubnim uvjetima rada sustava.


## Diplomski seminar

