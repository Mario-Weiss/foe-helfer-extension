##Changelog - Chrome Extension



#####v2.3.4
**Update**
- FP-Lager Anzeige:
	- wird nun beim Spielstart ermittelt
- Kostenrechner:
	- Ab sofort erscheint in der letzten Spalte eine "0" wenn +-0 erreicht würde (verlustfrei) => [#80](https://github.com/dsiekiera/foe-helfer-extension/issues/80) 


**BugFix**
- Kostenrechner:
	- Erntedatum des LGs entfernt, wurde von Inno ausgebaut
	
- Außenposten:
	- wird korrekt erkannt und geöffnet	[#61](https://github.com/dsiekiera/foe-helfer-extension/issues/61), ggf. Reload!

- Tavernenboost:
	- zeigt wirklich nur noch den extra Zug an [#75](https://github.com/dsiekiera/foe-helfer-extension/issues/75), wenn aktiviert
	
---


#####v2.3.3
**BugFix**
- Kostenrechner:
	- erkennt nun Besitzer, gelöschte User und P6 ohne Gewinn

- Eigenanteilsrechner:
	- erkennt nun Besitzer, gelöschte User und P6 ohne Gewinn

---


#####v2.3.2
**BugFix**
- Menü:
	- Neue Startup-Prozedur, stabilerer Start der Extension
	
- Erntehelfer:
	- Neuer Filter um Gebäude mit "Gildenmacht" (als Produktion) zu erkennen, verhinderte die Darstellung der Box

---


#####v2.3.1
**BugFix**
- Außenposten:
	- Erkennung der Güter angepasst, startet nun sauber
	
- Boxen:
	- eine Box kann nun auch geschlossen werden wenn der Inhalt nicht geladen wird (bei einem Fehler)

---

#####v2.3.0
**BugFix**
- Extension:
	- überarbeitet, Cache Problem gelöst
	- neue stabilere StartUp Prozedur integriert

---

#####v2.2.16
**BugFix**
- Außenposten:
	- kleiner Logikfehler verhindert den ersten Start des Fensters

---

#####v2.2.15

**Neu**
- TavernenBooster:
	- wenn in den Einstellungen aktivert, wird ein verschiebbares Overlay mit der Restzeit eingeblendet
	
- Außenposten:
	- erkennt automatisch das richtige Event und führt alle benötigten Güter auf

**Update**
- Eigenanteilsrechner:
	- "Bitte leveln" wurde hinter den LG Namen verschoben

**BugFix**
- Kostenrechner:
	- bei TA, Zeus usw. erschien "Invalid date"

---

#####v2.2.14

**Update**
- Live-Chat:
	- Neue Spalte für Anwesende Mitglieder
	- neue Sounds ergänzt
	- Erwähnung verbaut => Wird eine Zeile mit einem "@" begonnen gefolgt vom Namen des Spielers, wird in seiner Anzeige sein Name hervorgehoben
	- Lesemodus verbaut (kleines Augen-Icon oben links) => Chat scrollt nicht selbstständig (zum nachlesen bei Abwesenheit)
	
- Kostenrechner:
	- Countdowntimer für Erntezeitpunkt eingefügt
	
- Einstellungen:
	- **_HINWEIS_**: neuer Schalter für FP Investitionen eingefügt	

**BugFix**
- Einstellungen:
	- der Verknüfung zwischen "Globale Kommunikation" und Erntehelfer entfernt

---

#####v2.2.13

**Update**
- Extension:
	- Globalen Schalter integriert; wenn "inaktiv" läuft die Extension nur im Browser ohne Kontakt zu foe-rechner.de (autark)
	

- Live-Chat:
	- Läuft nun stabil wenn min. 1 Spieler aus der Gilde Daten an foe-rechner.de übermittelt
	- Avatar integriert, bessere Lesbarkeit
	- alle [Funktionen](/extension/index#Gilden_Livechat) auf einen Blick

---

#####v2.2.12
**Update**
- Kostenrechner:
	- Erntezeitpunkt des offnen LGs wird dargestellt
	- Box verbreitert => lesbarer

---


#####v2.2.11
**Update**
- Kostenrechner:
	- eigene Einzahlungen werden blau markiert
	- wenn zu viel bezahlt wird rot markiert
	- es werden alle 5 Ränge dargestellt, falls BPs gesucht werden
	- Archebonus-Feld => Stufen 1-80 "_0.5_" Schritte > ab Stufe 80 "_0.1_" Schritte

**Neu**
- LG-BP Inventar:
	- Vorbereitet => zeigt dann an wie viele BPs von jedem LG verfügbar sind

**BugFix**
- Eigenanteilsrechner:
	- wenn minimiert wird auch die links ausgeklappte Box ausgeblendet

---

#####v2.2.10
**Update**

- Eigenanteilsrechner:
	- Hakenvariante wie auf feo-rechner.de, Plätze können selbst gewählt werden
	
- LG Daten:
	- jeder Spieler kann nun selbst seine LG Daten auswerten und ist nicht auf jemand anderen angewiesen, werden beim betreten des Spieles übertragen

- Erntehelfer:
	- übersichtlicher nach "Abgeschlossende Produktionen", "Laufende Produktionen"
	- neuer Filter verbaut 

---

#####v2.2.9
**Update**
- Boxen:
	- Können ab sofort minimiert werden wenn der Platz knapp ist
	- "Merken" sich ihre letzte Position an der sie geschlossen wurden

- Menü:
	- Neuer Button für Einstellungen, hier werden die Übermittlungen gesteuert
	- Neuer Button für FAQ
	- Neuer Button für Features / Bugs

---

#####v2.2.8
**Bugfix**
- Eigenanteilsrechner:
	- Kopierbuttons zeigen falsche Werte, behoben
	- Mäzen Anteil wurde nicht immer berechnet, gefixt

---

#####v2.2.7
**Bugfix**
- Eigenanteilsrechner:
	- Fehlendes Objekt mit den Plätzen für die Kopierbuttons ergänzt

---

#####v2.2.6
**Update**
- Kostenrechner:
	- Zeigt an wann die letzte Einzahlung war, so kann geprüft werden ob das LG derzeit überhaupt gelevelt wird
- Eigenanteilsrechner:
	- Arche-Prozente sind von der Popup-Box entkoppelt und werden nun individuell nur für diesen Rechner benutzt (Einstellung direkt im Rechner)
	- berechnet alle Werte unter einbezug von externen Belegungen
	- _Achtung_: Die Berechnung der externen Plätze ist in der BETA-Phase! Falls hier irgend welche Fehler auftreten, bitte im [GitHub](https://github.com/dsiekiera/foe-helfer-extension/issues) melden

---

#####v2.2.5
**Update**
- FP Produktion:
	- Gruppierung und Sortierung integriert
	
	
- Kostenrechner:
	- einmalig zwischen den Tabs [Nachbarn, Gilde, Freunde] wechseln, dann wird beim FP Snipen oder befüllen der Namen des Besitzers angezeigt
	- es wird nun auch "+-0" angezeigt falls BPs oder Meds gewonnen werden können, aber keine FPs hängen bleiben

---

#####v2.2.4
**Update**
- Eigenanteilsrechner:
	- Archeprozente von den eigenen Arche Werten entkoppelt => eigenes Eingabefeld für Einzahlungen

---

#####v2.2.3
**Update**
- Eigenanteilsrechner:
	- Dropdowns entfernt, maximale Stufen aufgehoben
	- Erechnet die Belegung aus den Daten beim öffnen des LGs

---

#####v2.2.2
**Update**
- Kostenrechner: 
	- Zeigt nun an ob ein Platz mit den eingezahlten FP "save" ist. Danke an Lashandan von Rugnir dafür!
- Eigenanteilsrechner:
	- Überarbeitung Teil 1: Werte können mit Namen (dauerhaft änderbar) des Spielers und des Lgs (z.B.: Burg von Himeiji => BvH) kopiert werden

---

#####v2.2.1
**Update**
- Gildenchat: 
	- Emotes wie im WhatsApp integriert und auswählbar
	- Bild URLs werden als Vorschau dargestellt und automatisch verlinkt
	- Strings die als URL erkannt werden, werden zu URLs umgebaut und sind anklickbar

---
#####v2.2.0
**Update**
- Gildenchat: - wurde in ein eigenes Fenster verschoben, ebenso wurden Emojis hinzugefügt (Zeichen wie ;) oder :D aber auch named Emoyies wie :beer:, :heart: oder :cat: sind möglich)
- Extension: - Stylesheet wird ab sofort mit Versionsnummer geladen, sorgt immer für eine aktuelle Ansicht

---

#####v2.1.1
**Update**
- Extension: Komplette Größe der Extension verkleinert

**Bugfix**
- Helfer-Klasse: - Typo im Code (verhinderte das Starten der Button-Klasse)

---

#####v2.1.0
**Neu**
- GildenChat: - BetaPhase _(Funktioniert wirklich nur wenn er offen ist und nur innerhalb der Gilde)_

**Update**
- Kostenrechner: - Zeigt die ermittelte Stufe und den Spielernamen an, aktualisiert sich automatisch beim öffnen eines anderen LGs selbstständig
- Eigenanteilsrechner: - einmal offen, werden zuerst die Werte des eigenen geöffneten LGs übernommen

**Bugfix**
- Eigenanteilsrechner: - merkt sich in der Session die letzten Werte

---

#####v2.0.2
**Bugfix**
- "Erntehelfer": wurde Aufgrund eines Objektfehlers nicht dargestellt

---

#####v2.0.1
**Update**
- Gebäudenamen sind aktuell

**Bugfix**
- Eigenanteilsrechner: holte Daten der falschen Stufe

---

#####v2.0.0
**Neu**
- Menü: neues Menü am rechten Bildrand
- Kostenrechner: aktiviert sich beim ersten öffnen eines fremden LGs
- Eigenanteilsrechner komplett überarbeitet

---


#####v1.9.5
**Neu**
- Kostenrechner: die Anzeige im Fenster aktualisiert sich beim einzahlen

**Bugfix**
- Eigenanteilsrechner: Button Darstellung korrigiert
- Kostenrechner: Button Darstellung korrigiert

---


#####v1.9.4
**Bugfix**
- Eigenanteilsrechner: Button arbeitet jetzt sauber mit den Tabs
- Kostenrechner: Button arbeitet jetzt sauber mit den Tabs

---

#####v1.9.2
**Bugfix**
- Scripte: Versionierung eingefügt

---

#####v1.9.1
**Bugfix**
- Einstellungen: Bonus ließ sich nicht speichern

---

#####v1.9.0
**Update**
- Scripte: Performance Schub durch neue Logik

**Bugfix**
- Multiworld: Trackt nun korrekt in allen Bereichen

---

#####v1.8.5
**Update**
- Einstellungen: Es muss keine Player-ID oder Gilden-ID mehr angegeben werden

**Bugfix**
- Eigenanteilsrechner: Zeigt wieder korrekte Werte an

---

#####v1.8.4
**Bugfix**
- Eigenanteilsrechner: Button wird wieder korrekt angezeigt

---

#####v1.8.3
**Update**
- Motivationen: Es wird nun auch der Rang innerhalb der Freundesliste übertragen

---

#####v1.8.2
**Update**
- Nachbar-Produktionen: Alle Übersetzungen sind Verfügbar

---

#####v1.8.1
**Update**
- Mutliworld: Extra Kennung für den Chrome Storage ergänzt

---

#####v1.8.0
**Neu**
- Mutliworld: Ab sofort werden alle Welten eines Spielers unterstützt

---

#####v1.7.3
**Update**
- Nachbar-Produktionen:
	- Jede Menge Übersetungen eingefügt

---

#####v1.7.2
**Update**
- Benachrichtigungen sind Zeitgesteuert und verschwinden nun schneller, je nach Typ
- Mit der ESC-Taste können alle Buttons + Overlays geschlossen werden
- Nachbar-Produktionen werden komplett ausgelesen

**Bugfix**
- kleinen Bug im Script beim extenden von JS-Klassen behoben
- Arche-Bonus verschwand

---

#####v1.7.1
**Update**
- Initial-Scripte konnten blockiert werden, geht nun

---

#####v1.7.0
**Neu**
- Eigenanteilsrechner integriert

**Update**
- Kostenrechner: an das FoE Design angepasst

_Hinweis: Beide Rechner reagieren auf den [X]- und [Schliessen]-Button des Hauptfensters_ 

---

#####v1.6.0
**Update**
- App: Name geändert
- Benachrichtigung: System eigene Benachrichtigungen, weniger Code, App ist schneller

**Neu**
- Extension kann auch ohne Acc bei foe-rechner.de genutzt werden => nur Kostenrechner
- Kostenrechner: Schalter verbaut, kann nun auch deaktivert werden

---

#####v1.5.2
**Update**
- Benachrichtigung: neues Stack-Message System integriert (Nachrichten können sich oben rechts sammeln)

---

#####v1.5.1
**Update**
- Motivationen: kleine Ergänzung um alle Freunde korrekt zu ermitteln

---

#####v1.5.0
**Neu**
- Motiviation (Moppeln): Werden aus der Eventübersicht ermittelt und und können in den [Statistiken](/stats/motivations) eingesehen werden => [FAQ / Bedienung](/faq/chrome-extension#motivationskontrolle)


**Update**
- Kostenrechner: wurde das Spieldesign angepasst


**Bugfix**
- Kostenrechner: beim wechsel des LGs sind die hinteren Plätze verschwunden

---

#####v1.4.1
**Update**
- Im Einstellungsfenster kann ein eigener Arche Standard Wert hinterlegt werden, für den Kostenrechner

**Bugfix**
- Kostenrechner: macht nun 0.1 Steps statt 0.5
- Kostenrechner: Arche Bonus niedrigster möglicher Wert ist nun 12

---

#####v1.4.0
**Neu**
- Kostenrechner: zeigt beim öffnen eines nicht eigenen LGs die Plätze und dessen Bonus an

---

#####v1.3.0
**Neu**
- Freundes Taverne kann ausgewertet auswerten


---
#####v1.2.0
**Neu**
- LG Investitionen werden übergeben und ausgewertet


---
#####v1.1.0
**Bugfix**
- das Mitteilungsfenster erschien nicht immer trotz Datenübertragung

---

#####v1.0.0
- Werte der Gildenmitglieder werden übertragen und ausgewertet
- LGs der Gildenmitglieder werden ausgewertet
- Plazierung der Gilde in der GEX wird ausgewertet
- Plazierung der einzelnen Mitglieder in der GEX wird ausgewertet