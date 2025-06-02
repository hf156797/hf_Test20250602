# Klausur/Test 02.06.2025


## Aufgabe 1

Erstellen Sie aus dem ausgeteilten Template ein eigenes, öffentliches Projekt namens K_20250602_Nachname_Vorname bzw. T_20250602_Nachname_Vorname.
Die App ist im Wesentlichen die App aus dem Unterricht ohne große Änderungen.
Am Ende müssen Sie Ihr Projekt commiten und pushen. Senden Sie mir den Link in Teams zu.

## Aufgabe 2

Auf der Seite der AGB sind logische und syntaktische Fehler eingebaut. Finden und korrigieren Sie die Fehler. Schreiben Sie jeweils einen kurzen Kommentar an jede Fundstelle, in dem Sie beschreiben, was falsch ist.

## Aufgabe 3

In der ```app.post('/kreditBeantragen...``` sehen Sie mehrfach den Ausdruck ```// Kommentar```. Erstetzen Sie den Platzhalter jeweils durch zwei möglichst präzise Sätze, in denen Sie beschreiben, was konkret in den Anweisungen darunter passiert.

## Aufgabe 4

Das dem Kunden in ```/kreditBeantragen``` angezeigte Ergebnis sieht beispielsweise so aus: ```Rückzahlungsbetrag: 121.00000000000001 €.```

Formatieren Sie das Ergebnis kaufmännisch gerundet mit zwei Nachkommastellen. Fragen Sie ggfs. den Copilot.

## Aufgabe 5

Auf der Seite Profil soll beim Laden der Seite der Kunde mit all seinen Eigenschaften angezeigt werden. 

Darunter hat der Kunde bereits die Möglichkeit seine E-Mail-Adresse zu ändern. Wenn der Kunde den Button "Mail-Adresse ändern" klickt, sollen direkt alle Kunden-Eigenschaften inkl. neuer Mail-Adresse angezeigt werden.

## Aufgabe 6 

Ergänzen Sie beim Kunden-objekt die Eigenschaft Telefonnummer. Die Telefonnumer soll der Kunde (analog zur Mail-Adresse) auf der Profil-Seite selbst ändern können. 

## Aufgabe 7 - Nur Klausurschreiber

Es dürfen auf der Profil-Seite nur E-Mail-Adressen aus Deutschland (erkennbar an der Endung *.de angegeben werden). 

Um das zu prüfen, verwenden Sie die Funktion ```.endsWith()```. Dazu ein Beispiel:

``` javascript

let wort = "Borken"   

wort.endsWith("en")  // true
wort.endsWith("feld") // false
wort.includes("rk"); // true
wort.startsWith("Coes") // false

```
Geben Sie eine möglichst konkrete Rückmeldung an den Kunden, wenn er versucht eine Adresse mit einer anderen Endung anzugeben.


## Aufgabe 8 - Nur Klausurschreiber

Suchen Sie nach der Anweisung ```let kredit = zinsbetrag * Math.pow(1+zinssatz/100,laufzeit);```

Ersetzen Sie die Anweisung durch mit einer ```for```for Schleife.

Hier ein Beispiel für den Einsatz der Schleife:

``` javascript

for (let i = 0; i < 5; i++) {
  // Läuft 5x mit den Werten 0 bis 4.
  console.log("Zähle hoch: " + i);
}

```



