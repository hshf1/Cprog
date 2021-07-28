# Aufgabe 2

Das zu entwickelnde Programm soll den Mittelwert von drei eingegebenen reellen Zahlen berechnen.
Nach der Ausgabe der Aufgabenstellung sind die drei Zahlen anzufordern.
Geben sie den berechneten Mittelwert im Standardtformat (3 Nachkommastellen) aus.

- [ ] Zahlen anfordern
- [ ] Mittelwert berechnen
- [ ] Ausgabe formatieren


## Tipp - Grundbausteine
<details>
<summary>Klicken zum öffnen</summary>

Für das Programm werden vier Variablen benötigt, die vor der zuweisung deklariert werden müssen. Wählen Sie die passenden Datentypen!
  Es wird nur die standard Bibliothek benötigt.

</details>

## Tipp - Einlesen
<details>
<summary>Klicken zum öffnen</summary>

  Um den Variablen die Werte zu zuordnen kann ```scanf()``` verwendet werden. 

</details>

## Tipp - Berechnung
<details>
<summary>Klicken zum öffnen</summary>
Der Mittelwert ist das Ergebnis aus der Summe der Einzelwerte, geteilt durch die Anzahl der verwendeten Werte. 

</details>

## Tipp - Formatierung
<details>
<summary>Klicken zum öffnen</summary>
  Bei der Ausgabe über ```printf()``` kann aus der kombination von einem Punkt "." mit einer Zahl festgelegt werden wie viel Kommastellen auf dem Bildschirm angezeigt werden.
  Diese Kombination wird zwischen das Prozentzeichen und dem Zeichen für den Datentypen gesetzte.
  
  ```C
  float f = 3.141596;
  
  printf("Pi ist: %.4f", f); // Die Ausgabe ist -> Pi ist: 3.1415
  ``` 
  
  </details>
