# O baza de date cu localitatile din Romania
## Actualizata conform datelor disponibile in Februarie 2019

Contine o lista cu toate orasele si satele din Romania alcatuite din datele disponibile online in Februarie 2019.
Fiecare intrare contine informatii despre judet, coordonate GPS, populatie si cod postal.

## Continut

Informatiile sunt preluate din mai multe baze de date oferite de **Institutul National de Statistica**, **Posta Romana**, **Google Maps**

Baza de date contine **13.851 inregistrari**

## Format

Tabelele contin urmatoarele coloane:

"**id**" - id generat la introducerea in baza de date

"**nume**" - numele localitatii 

"**diacritice**" - numele cu diacritice

"**judet**" - judetul parinte

"**auto**" - prescurtarea judetului

"**zip**" - codul postal (pentru localitatile cu mai mult de 50.000 de locuitori, codul postal folosit apartine unei strazi oarecare din orasul respectiv)

"**populatie**" - populatia conform recensamantului din Octombrie 2011

"**lat**" - coordonate oferite de Google Maps

"**lng**" - coordonate oferite de Google Maps

## Fisiere disponibie

SQL, JSON, XML, XLS, XLSX, CSV, TSV, ODS si HTML

Toate fisierele contin aceleasi date, dar au fost generate pentru a va usura munca in cazul in care aveti nevoie de un anumit format.

## Sursa informatiilor

### Numele Localitatilor
Au fost combinate, validate si introduse localitati furnizate de INS prin http://data.gov.ro/ 

### Codurile Postale
Au fost preluate in urma unui raport furnizat de Institutul Național de Statistică actualizat in Septembrie 2016 si comparat cu rezultatele obtinute prin Google Geocoding API.

Unde nu au fost obtinute rezultate valide, au fost folosite informatii furnizate de Posta Romana

### Populatia
Conform raportului INS pentru recensamantul din 2013 furnizat pe http://www.recensamantromania.ro/

### Coordonate Google Maps (lat, lng)
Au fost obtinute prin interogarea Google Geocoding API si retusate manual in cazurile in care Google Maps nu a putut furniza informatiile. ( Da... :) au fost cateva sate care nu exista pe Google Maps )


### Metoda de agregare a datelor
Datele furnizate de toate sursele au fost introduse in baze de date si sortate, validate si corectate.

Toata procedura a fost una automata ce a raportat erori de validare ce nu au putut fi corectate automat, cazuri in care a fost intervenit manual.

### Raportare erori

Daca gasiti probleme va rog sa raportati aceste erori pentru a fi remediate.

# Enjoy!
