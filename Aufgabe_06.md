# Aufgabe 6

Für ganzzahlige Radie von 1<=R<=10 soll die Kreisfläche und das Kugelvolumen berechnet werden.
Die Werte sollen Tabelarisch mit zwei Stellen nach dem Komma ausgegeben werden.
Die berechnung von Kreisfläche und Kugelvolumen ist in Unterfunktionen zu realisieren.
Das Programm kann auch zuerst ohne Unterfunktionen geschrieben werden.

- [ ] Unterfunktionen/Berechnung
- [ ] Tabelarische Ausgabe


## Tipp - Unterfunktion
<details>
<summary>Klicken zum öffnen</summary>
  
Unterfunktionen sind immer dann sehr hilfreich, wenn Sie eine Aufgabe erfüllen, welche mehrfach benötigt wird. (z.B. in Schleifen)
  Überlegen Sie sich, was Sie für das Unterprogramm benötigen. Welchen Rückgabe-Typ soll die Funktion haben, welche und wie viele Parameter möchten Sie der Unterfunktion übergeben.
  Es kann nur ein Wert zurückgegeben werden!
  
  ```C
  int berechneSumme(int iZahl1, int iZahl2){ 
    /* Die Unterfunktion ist vom Typen Int und bekommt zwei Integer Werte übergeben.
    Diese heißen für die Unterfunktion iZahl1 und iZahl2
    Im Hauptprogramm können die Werte andere Namen haben(s.u.)! */
    int iBums;                // Nur für die Unterfunktion wird eine weitere Variable mit dem Namen iBums angelegt
    iBums = iZahl1 + iZahl2;  // In iBums wird das Ergebnis aus iZahl1 und iZahl2 gespeichert
    return iBums;             // Die Zahl aus iBums ist der Rückgabewert
  }
  
  int main (){
  
  int iZahlA = 5;
  int iZahlB = 12;
  int iZahlC;
  
  iZahlC = berechneSumme(iZahlA, iZahlB);
  /*iZahlC wird der Rückgabewert aus der Unterfunktion berechneSumme() zugewiesen.
    iZahlA aus dem Hauptprogramm heißt für die Unterfunktion iZahl1 und iZahlB ist iZahl2.
    Wichtig ist, dass die Datentypen übereinstimmen sonst kommt es zu Fehlern.*/
  
  }
  ```

</details>


### Tipp - Ausgabe
<details>
<summary>Klicken zum öffnen</summary>

Benutzen Sie den Zeilenverschub nach jeder Erhöhung, um nicht alle Werte in einer Zeile zu haben.

</details>
