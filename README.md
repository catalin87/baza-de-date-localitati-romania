# O baza de date cu localitatile din Romania
O baza de date cu toate asezarile din Romania (Orase, comune, sate)

## Continut

Localitatile sunt preluate din baza de date oferita de **Institutul National de Statistica**

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
Au fost preluate in urma unui raport furnizat de Institutul Național de Statistică actualizat in Septembrie 2016 si comparat cu rezultatele obtinute prin Google Geocoding API

### Populatia
Conform raportului INS pentru recensamantul din 2013 furnizat pe http://www.recensamantromania.ro/

### Coordonate Google Maps (lat, lng)
Au fost obtinute prin interogarea Google Geocoding API si retusate manual in cazurile in care Google Maps nu a putut furniza informatiile. ( Da... :) au fost cateva sate care nu exista pe Google Maps )
