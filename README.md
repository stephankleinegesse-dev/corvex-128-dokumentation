# Corvex 128

<img src="https://kleinegesse-systemtechnik.de/kleinegesse-systemtechnik.webp" alt="Kleinegesse Systemtechnik" width="240">

Corvex 128 ist eine Software von **Kleinegesse Systemtechnik** für die Vermessung und Dokumentation von Hausanschlüssen und Hauptleitungen. Kolonne, Bauleitung und Netzbetreiber bearbeiten einen Auftrag von der Aufnahme auf der Baustelle bis zum geprüften Aufmaßblatt. Wasser, Gas, Strom, Glasfaser (LWL) und Fernwärme lassen sich einzeln oder gemeinsam erfassen.

**Projektstand am 26. November 2026** · Die Baustellenzentrale läuft im internen Testbetrieb. Eine öffentliche Freigabe der aktuellen Gesamtversion steht aus.

## Vom Auftrag zum Aufmaßblatt

1. **Auftrag anlegen.** Die Kolonne erfasst Baustellenort und Sparten in Field. Das zuständige Büro sieht den neuen Auftrag in seiner geöffneten Auftragsliste. In der Gegenrichtung kann die Disposition der Kolonne einen Auftrag mit Arbeitsanweisung, Lageplan und weiteren Unterlagen zuweisen.
2. **Aufmaß erfassen.** Die AR-Testversion führt durch die Aufnahme von Gebäudekanten, Hauptleitung, Anschlussleitung und Bauteilen. Bis zu zwölf Messläufe können zu einem Aufmaß gehören. Ein Punktfoto hält fest, welche Stelle die Kolonne gemessen hat. Für Handskizzen schlägt die serverseitige Erkennung Texte und Maße zur fachlichen Bestätigung vor.
3. **Prüfen und zurückmelden.** Field übergibt einen bestimmten Bearbeitungsstand an Netz. Die prüfende Person kann Nacharbeit anfordern oder diesen Stand freigeben. In der Messpunktliste sind die relative Höhe eines Punkts und seine vor Ort erfasste Tiefe getrennt ausgewiesen.
4. **Spartenblätter ausgeben.** Bei einem gemeinsamen Wasser- und Stromanschluss bleiben die Messungen in einem Projekt. Nach der Freigabe lässt sich für jede gemessene Sparte das passende Aufmaßblatt öffnen. Der geprüfte Stand kann als `.gw128` im Windows-Manager weiterverwendet werden.

## Die vier Arbeitsbereiche

| Bereich | Für wen | Typische Aufgaben |
| --- | --- | --- |
| **Field** | Bauunternehmen, Kolonnen und Bauleitung | Aufträge zuweisen oder vor Ort anlegen, Baustellendokumente abrufen, Messungen erfassen und Tagesnachweise ans Büro senden. |
| **Netz** | Netzbetreiber und fachliche Prüfer | Baustellenaufträge an Field übergeben, eingegangene Aufmaße prüfen, Nacharbeit anfordern und einen Projektstand freigeben. |
| **Studi** | Auszubildende und Ausbilder | Mit Formelsammlung und Prüfungsmodus üben. Ausbilder können Aufgaben zuweisen und Ergebnisse besprechen. |
| **Solo** | Einzelne Fachkräfte | Eigene Aufmaße und Baustellendokumente bearbeiten. Der Funktionsumfang richtet sich nach der freigeschalteten Lizenz und den Zusatzmodulen. |

Firmenzuordnung, Rolle und Projektfreigabe bestimmen, welche Aufträge eine Person sehen und welche Änderungen sie vornehmen darf.

## Erprobung

| Bereich | Geprüfter Stand |
| --- | --- |
| Baustelle und Büro | Im Test mit zwei getrennten Konten erschien ein neuer Mehrspartenauftrag innerhalb von rund fünf Sekunden im Büro. Ein dort bereits geöffneter Entwurf blieb erhalten. |
| Aufmaßblatt, 2D-CAD und PDF | Der lokale Test umfasste alle fünf Sparten in A4 hoch und A3 quer. Bei dicht liegenden Messpunkten ist die Platzierung einzelner Beschriftungen noch offen. |
| Mobile AR-Vermessung | Eine interne Android-Testversion liegt vor. Kamerafunktion und Punktfoto wurden im Emulator erprobt. Der Nachweis der Messgenauigkeit auf der Baustelle und der iOS-Test über TestFlight stehen aus. |

[Website von Kleinegesse Systemtechnik](https://kleinegesse-systemtechnik.de/) · [Kontakt zu Corvex 128](https://kleinegesse-systemtechnik.de/kontakt.html)
