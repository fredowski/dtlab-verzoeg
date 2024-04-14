# Beispielmessbericht für die Messung einer Verzögerungszeit

Dieses Repository enthält den Latexcode für einen Messbericht.

Der Messbericht beschreibt die Messung der Verzögerungszeit einer Kette von vier Invertern, die aus den NAND Gattern eines 74HC00 Bausteins aufgebaut ist. Der Leser soll einzelne Schritte der Messungen nur mit Hilfe des Berichts nachvollziehen und mögliche Fehler bei der Messung identifizieren können. Es ist also nicht ausreichend einfach zu schreiben: "Die gemessene Verzögerungszeit bei 5V Betriebsspannung beträgt 39 ns."

In diesem Messbericht kann man beispielweise anhand des Fotos in Abbildung 3 erkennen, dass die Schaltung in Abbildung 2 nicht die Schaltung auf dem Board ist. Auf dem Foto in Abbildung 3 sieht man, dass jeweils ein Eingang der NAND Gatter auf Vcc liegt. Die Eingänge der Gatter sind nicht zusammengeschaltet.

Bei der in Abbildung 4 dargestellten Messung sind die Kanäle 1 und 2 des Oszilloskops gegenüber der Darstellung in Abbildung 2 vertauscht. Auf Kanal 2 ist jetzt der Eingang und auf Kanal 1 der Ausgang. Das stimmt weder mit der Darstellung in Abbildung 2 noch mit dem Foto in Abbildung 3 überein. Es stellt sich dann die Frage wo die Probes überhaupt angeschlossen sind.

Die Beschreibung der Elemente in Abbildung 4 für die Messung bei 5V Betriebsspannung ist sehr detailliert. Es wird genau beschrieben warum die Cursor Y1, X1 und X2 wo positioniert sind und wie daraus die Verzögerungszeit abgeleitet wird.

Die Beschreibung der Abbildung 5 für 2V ist kürzer und sollte nicht weiter gekürzt werden. Es kann hier kürzer sein, weil die Messung analog zur Messung bei 5V in Abbildung 4 ist.

Bei beiden Messungen wird die Genauigkeit der Messung abgeschätzt und angegeben.

In dem Messbereicht werden die gemessenen Verzögerungszeiten mit den Werten aus dem Datenblatt verglichen. Dazu gehört eine Einordnung und Beurteilung. Es wird beurteilt werden ob die gemessenen Werte sich im zu erwartenden Bereich laut Datenblatt bewegen.

Der Messbericht hat die folgenden inhaltlichen Merkmale:

  * Beschreibung des Messaufbaus mit Schaltplan, Position der Probes, Einstellungen der Geräte wie Labornetzteil und Funktionsgenerator
  * Dokumentation der Messungen mit den abgelesenen Werten am Multimeter und Screenshots vom Scope
  * Beschreibung der Screenshots mit der Begründung für die Position der Cursor
  * Abschätzung der Messgenauigkeit für die relevanten Messungen wie hier der Verzögerungszeit
  * Einordnung und Bewertung der Messergebnisse - hier der Vergleich mit den Werten im Datenblatt

Der Messbericht hat die folgenden formalen Merkmale:

  * einen Titel
  * einen Autor oder mehrere Autoren
  * Datum der Messung
  * Datum des Berichts
  * eine Zusammenfassung (englisch abstract)
  * Tabellen und Abbildungen sind numeriert
  * Tabellen haben eine Tabellenüberschrift
  * Abbildungen haben eine Abbildungsunterschrift
  * Alle Abbildungen und Tabellen werden im Text erwähnt und beschrieben

