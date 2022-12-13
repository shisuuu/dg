---
{"dg-publish":true,"permalink":"/fi-si/lernfeld-5/2022-09-16-klausur/phasen-des-vorgehensmodells/"}
---


# Phasen des Wasserfallmodells und dessen Ablauf

Das Wasserfallmodell findet man in der Praxis in unterschiedlichen Variationen. 
Royce hat in seiner Publikation 1970 7 Phasen skizziert. 
![](http://info.itemis.com/hubfs/Bildschirmfoto%202017-03-17%20um%2013.57.43.png)

Je nach Quelle wird der Wasserfallansatz in unterschiedliche Phasen eingeteilt. 
Die Einteilung der Schritte legen Unternehmen selbst fest, da diese stark von den Anforderungen des jeweiligen Projekts abhängen. 

Das einfachste Wasserfallmodell besteht aus lediglich 4 Phasen:
	1. Anforderungsdefinition
	2. Design
	3. Implementation
	4. Test

Das Prinzip des Wasserfallmodells der Softwareentwicklung besteht aus 5 Phasen. 
In der Softwareentwicklung werden die "Bereitstellung" und "Wartung" als eine weitere Phasen mit dem Oberbegriff "Betrieb" ergänzt.

Die Anzahl der Schritte hängt vom Umfang und von den Anforderungen des Projekts ab.
Am verbreitesten sind fünf- bis siebengeteilte Planungsmodelle.

Die Einteilung der Schritte legen Unternehmen selbst fest, da diese stark von den Anforderungen des jeweiligen Projekts abhängen.

Der Endpunkt jeder Phase stellt einen Meilensteim im Projektmanagement dar.
Dieser Meilenstein ist im Wasserfall-Modell im Allgemeinen mit einer analytischen Qualitätssicherung der Ergebnisse der Anwendungsentwicklung verbunden.
**Ein Übergang zur vorhergehenden Phase der System-Entwicklung ist im Wasserfallmodell nur im Ausnahmefall (Mängeln) möglich.**
http://www.infforum.de/themen/anwendungsentwicklung/se-wasserfall-modell.htm
## Phasen

Quellen: 
- https://projekte-leicht-gemacht.de/blog/projektmanagement/klassisch/wasserfallmodell/
- https://www.lucidchart.com/blog/de/wasserfallmodell-fur-das-projektmanagement


1\. **Anforderungsanalyse (Requirements)**
Je genauer die Anforderungen zu Beginn definiert werden, desto höher ist die Erfolgswahrscheinlichkeit im Projekt.
Die Grundfrage: Was soll entwickelt werden?

1.1.  **Erfassen und Dokumentieren der Anforderungen** 
In dieser Phase sollten Sie umfassende Informationen über die Anforderungen des Projekts sammeln.
Sie können diese Informationen auf vielfältige Weise erfassen, von Gesprächen über Umfragen bis hin zu interaktivem Brainstorming.
Am Ende dieser Phase sollten die Porjektanforderungen klar sein, und Sie sollten ein Anforderungsdokument an Ihr Team verteilen.


2\. **Entwurf (Design)**
In dieser Phase werden die anforderungen vom Projektteam in Spezifikationen umgesetzt. 
Anders gefragt: Wie wollen wir die Anforderungen umsetzen?

2.1. **Systemdesign**
Anhand der festgelegten Anforderungen entwirft Ihr Team das System.
In dieser Phase des Wasserfallmodells wird nicht programmiert, sondern das Team legt die Spezifikationen fest, z.B. die Programmierspare oder die Hardwareanforderungen.

3\. **Implementierung (Implementation)**
Auf der Basis der Spezifikation werden die Anforderungen umgesetzt – ein funktionierendes Produkt entsteht.

3.1. Implementierung
In dieser Phase findet die Programmierung statt.
Die Programmierer nehmen die Informationen aus der vorherigen Phase auf und erstellen ein funktionales Produkt.
In der REgel implementieren sie den Codei n kleinen Teilen, die am Ende dieser Phase oder zu Beginn der nächsten integriert werden.

4\. **Test (Verficiation)**
In dieser Phase wird ermittelt, ob alles implementiert wurde. Jetzt finden alle Beteiligten heraus, ob das Produkt den ursprünglichen Anforderungen entspricht.

4.1. **Prüfung**
Sobald das Programmieren abgeschlossen ist, kann mit dem Testen des Produkts begonnen werden. 
Die Tester suchen methodisch nach Probleme nund melden diese.
Wenn schwerwiegende Probleme auftauchen, muss Ihr Projekt möglicherweise z ur Neubewertung in die erste Phase zurückkehren.

5\. **Inbetriebnahme und Wartung (Maintenance)**
Nach erfolreichen Tests wird das Produkt in einer produktiven Umgebung eingesetzt sowie regelmäßig auftretende Fehler behoben

5.1. **Bereitstellung / Wartung**
In dieser Phase ist das Produkt fertiggestellt, und Ihr Team reicht die zu liefernden Produkte zur Bereitstellung oder Freigabe ein.
Wurde das Produkt an den Kunden geliefert, muss Ihr Team beim Auftreten von Problemen möglicherweise durch Patches und Updates beheben.
Auch hier können große Probleme eine Rückkehr in Phase eins erfordern.

## Alternative Nutzung

Eine andere häufig genutzte Alternative macht aus dem Wasserfall-Modell für die Softwareentwicklung 6 Phasen:

1. Die Planung mit Erstellung des [[FiSi/Lernfeld 5/2022-09-16 Klausur/Lastenhefts\|Lastenhefts]], der Projektkalkulation und der Projektplanung (System engineering)
2. Die Definitionsphase mit Erstellung des [[FiSi/Lernfeld 5/2022-09-16 Klausur/Pflichtenhefts\|Pflichtenhefts]], dem Produktmodell, dem GUI-Modeell und möglicherweise auch schon mit einem Grundmodell für das Benutzerhandbuch (Analysis)
3. Die Entwurfsphase mit UML-Diagrammen und Struktorogrammen (Design) 
4. Die Implementierung (Coding / Implementation)
5. Das Testen (Testing)
6. Der Einsatz und die Wartung (Maintenance)

## Leitlinien

Damit das Wasserfall-Modell sauber funktioniert, gibt es folgende Leitlinien:

1. Aktivitäten sind in der vorgegebenen Reihenfolge vollständig durchzuführen
2. Das Wasserfall-Modell ist ein dokumentengetriebenes Modell.
Das bedeutet, dass am Ende jeder Aktivität ein fertiggestelltes Dokument entsteht (typischerweise in Software-Tools)
3. Der Entwicklungsablauf ist sequentiell: eine Aktivität kann erst dann gestartet werden, wenn ale dafür notwendigen Grundlagen "vollständig" verfügbar sind, die zumeist in den vorherigen Aktivitäten erstellt werden
4. Arbeitet in eine Richtung
5. Das Modell ist einfach und auch für Außenstehende leicht zu verstehen und leicht zu überblicken
6. In der ersten Phase des Wasserfall-Modells ist die Begleitung des Fachbereichs oder des Kunden ausdrücklich vorgesehen. Ab das zweiten Phase ist der Fachbereich oder Kunde nicht mehr vorgesehen