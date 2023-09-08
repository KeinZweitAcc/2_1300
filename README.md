# Projekt-Dokumentation

Manuel Greub

## Informieren

Als Informationsquelle habe ich für dieses Proejkt einen [Kurs von Udemy](https://www.udemy.com/course/basics-of-object-oriented-programming-with-csharp/) verwendet.
Ausserdem habe ich mir die Arbeitsaufträge des Moduls 320 noch einmal angeschaut, um zu sehen, was mir noch Probleme bereitet.

Mit den oben genannten Informationen habe ich mich anschliessend dazu entschieden, eine Applikation zu entwickeln, welche eine To-Do Liste in der Konsole erstellen kann.


## Planen

| Datum | Arbeitspaket | Verantwortliche Person  | 
| ---- | --------------- | ---- |
|18.08.23| Udemy-Kurs abschliessen | Manuel Greub |
|18.08.23| Probleme bei Aufträgen suchen | Manuel Greub |
|18.08.23| Projektdokumentation erstellen | Manuel Greub |
|25.08.23| Es soll eine Aufgabe erstellt werden können | Manuel Greub |
|25.08.23| Eine Aufgabe soll Eigenschaften haben wie Beschreibung, Datum, Relevanz, Erledigt etc. | Manuel Greub |
|01.09.23| Die Liste soll in der Konsole ausgegeben werden können | Manuel Greub |
|01.09.23| Eigenschaften von Aufgaben sollen geändert werden können mit Hilfe von einfachen Befehlen | Manuel Greub |
|01.09.23| Die Aufgaben sollen gespeichert werden können | Manuel Greub |


##Testen

| Nr  | Ausgangslage    |     Eingabe       |   Erwartete Ausgabe |
| ---  | -------------  |   --------------  |  ----------------   |
|  1  | Programm gestartet |  create aufgabe1  | Description:     |
|  2  | Programm gestartet |  create       |  Fehlerhafte Eingabe |
|  3  | Aufgabe Erstellt   | list        |   *Aufgabe mit Id, Date etc. wird ausgegeben* |
|  4  | Aufgabe Erstellt   | edit id      |   New Id:             |
|  5  | Aufgabe Erstellt   | edit description |   New Description: |
|  6  | Aufgabe Erstellt   | edit date      |   New Date:             |
|  7  | Aufgabe Erstellt   | edit done      |   Done?             |
|  8  | Aufgabe Erstellt   | edit         |   Fehlerhafte Eingabe |
|  9  | Programm gestartet | exit         |   *Programm schliesst sich* |
| 10  | Aufgabe erstellt, Programm schliessen, Programm öffnen | list  |  *Vorherige Aufgabe wird angezeigt* |

| Testfall | Datum | Resultat | Tester  |
| ------- | ----- | --------- | ------  |
|    1    | 8.9.23 | OK       | Manuel Greub |
|    2    | 8.9.23 | OK       | Manuel Greub |
|    3    | 8.9.23 | OK       | Manuel Greub |
|    4    | 8.9.23 | OK       | Manuel Greub |
|    5    | 8.9.23 | OK       | Manuel Greub |
|    6    | 8.9.23 | OK       | Manuel Greub |
|    7    | 8.9.23 | OK       | Manuel Greub |
|    8    | 8.9.23 | OK       | Manuel Greub |
|    9    | 8.9.23 | OK       | Manuel Greub |
|   10    | 8.9.23 | NOK       | Manuel Greub |

Fazit: Die allermeisten Features konnten ohne Probleme umgesetzt werden. Ich hatte nur Schwierigkeiten beim Speichern von Aufgaben, da ich hierfür zu wenig Zeit hatte.




