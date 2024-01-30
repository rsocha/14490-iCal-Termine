# 14490 iCal-Termine

## Beschreibung 

Der Baustein liest ein ics File für die Müllabfuhr ein, und bereitet die Abholtermine auf den Ausgangen aus.

## Eingänge

| Nr. | Name        | Initialisierung | Beschreibung                                                                                            |
|-----|-------------|-----------------|---------------------------------------------------------------------------------------------------------|
| 1   | E1 url      | 0               | Pfad zu dem ics File File                                                                               |
| 2   | E2 Trigger  | 0               | Bei einem Wert <> 0 das File abgerufen.                                                                 |
| 3   | E3 Name 1   | 0               | Hier muss der Name stehen, der im ics File unter "Summery" steht.      |
| 4   | E4 Name 2   | 0               | Hier muss der Name stehen, der im ics File unter "Summery" steht.     |    
| 5   | E5 Name 3   | 0               | Hier muss der Name stehen, der im ics File unter "Summery" steht.     |
| 6   | E6 Name 4   | 0               | Hier muss der Name stehen, der im ics File unter "Summery" steht.     |
| 7   | E7 Name 5   | 0               | Hier muss der Name stehen, der im ics File unter "Summery" steht.     |
| 8   | E8 VWZ 1    | 0               | Eingabe in Tagen ab wann die "Vorwarnung" für den nächsten Termin an den Ausgängen erfolgen soll        |
| 9   | E9 VWZ 2    | 0               | Eingabe in Tagen ab wann die "Vorwarnung" für den nächsten Termin an den Ausgängen erfolgen soll        |
| 10  | E10 VWZ 3   | 0               | Eingabe in Tagen ab wann die "Vorwarnung" für den nächsten Termin an den Ausgängen erfolgen soll        |
| 11  | E11 VWZ 4   | 0               | Eingabe in Tagen ab wann die "Vorwarnung" für den nächsten Termin an den Ausgängen erfolgen soll        |
| 12  | E12 VWZ 1   | 0               | Eingabe in Tagen ab wann die "Vorwarnung" für den nächsten Termin an den Ausgängen erfolgen soll        |


## Ausgänge

| Nr. | Name                 | Initialisierung | Beschreibung                                            |
|-----|----------------------|-----------------|---------------------------------------------------------|
| 1   | A1 Summe Warnungen   | 0               | Ausgabe aller Warnungen einen Tag vor fälligen Datum.   |
| 2   | A2 Text Tonne 1      | ' '             | Text der Tonne.                                         |
| 3   | A3 Vorwarnung 1      | 0               | Ausgabe für Vorwarnung 1 vor Datum von A4               |
| 4   | A4 nächster Termin 1 | ' '             | nächster fälliger Abholtermin.                          | 
| 5   | A5 Wochentag 1       | ' '             | Wochentag zu Datum von A4                               | 
| 6   | A6 anzahl Tage       | 0               | Die Anzahl der Tage von heute bis zum fälligen Datum A4 | 
| 7   | A7 fff               | ' '             | Wiederholt sich wie A2 - A6.                            | 

## Beispielwerte

| Eingang | Ausgang |
| --- | --- |
| - | - |


## Other

- Neuberechnug beim Start: Nein
- Baustein ist remanent: nein
- Interne Bezeichnung: 14490
- Kategorie: Datenaustausch

### Change Log
 - v0.4
   -  div. Anpassungen
 - v0.3
   - Codierung für Umlaute
 - v0.2
   - div. Anpassungen
 - v0.1
   - Initial

   
   


## Licence

Copyright 2023

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

