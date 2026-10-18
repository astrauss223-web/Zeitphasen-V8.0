# Zeitphasenmodell V8.0 – Robustes Portfolio

**Gespiegelter 3D-Zylinderturm „Robustes Portfolio“, dezent ein-/ausblendbar (Zylinder-Icon), harmonische Tagesgeld-Schichtung & differenzierte Asset-Allocation**

---

## 🎯 Highlights & Neuerungen in Version 8.0

Version 8.0 führt den innovativen **gespiegelten 3D-Zylinderturm „Robustes Portfolio“** ein, der die Allokation aus den Zeitphasen in einer vertikal geschichteten Struktur visualisiert:

---

### 1. 🏛️ Gespiegelter 3D-Zylinderturm „Robustes Portfolio“

* **Aufeinander geschichtete 3D-Zylinder:**
  * **Spezialitäten / Themen** (Immobilien, PE, Gold, Beteiligungen) – *cyanblau*
  * **Märkte** (Weites & Enges Benchmarking auf Aktien) – *mittelblau*
  * **Dynamische Vermögensverwalter** (Weites Benchmarking auf Aktien) – *hellgrün*
  * **Ausgewogene Vermögensverwalter** (Balance aus Chance & Sicherheit) – *mittelgrün*
  * **Defensive Vermögensverwalter** (Stabilitätsorientiert) – *dunkel-/olivgrün*
  * **Kapitalreservefonds** (Kasse / Wertsicherung) – *goldgelb/bernstein*
* **Automatische Live-Spiegelung:**
  * Die in den Zeitphasen 1–6 sowie Sonderbausteinen ausgewählten Fonds und Beträge (Einmalbeitrag & Sparrate) spiegeln sich in Echtzeit in die entsprechenden Zylinderschichten.
* **Schreibgeschützte Spiegelung:**
  * Der Zylinderturm dient der klaren und anschaulichen Visualisierung. Die Bearbeitung und Zuweisung verbleibt exklusiv und unverändert in den Zeitphasen.
* **Kristallklare Zuordnung & Badge-Positionierung:**
  * Alle Summen- und Fondsanzahl-Badges sind exakt **innerhalb des jeweiligen Zylindersegments** verankert:
    * **Links unten:** Fondsanzahl (z. B. `4 Fonds` im türkisen Pill-Badge).
    * **Rechts unten:** Gespiegelte Summe (z. B. `151.783,97 €` bzw. bei Sparrate `+ 250,00 € mtl.`).
    * **Thematischer Farbrand:** Jedes Summen-Badge besitzt einen feinen Rahmen in der Primärfarbe der jeweiligen Zylinderschicht für sofortige Zuordenbarkeit.
    * **Keine Überdeckung:** Der 3D-Deckel wird vor den Beschriftungen gezeichnet; Überschneidungen sind ausgeschlossen.
* **Interaktiver Info-Tooltip:**
  * Beim Überfahren jeder Schicht erscheint ein strukturierter Tooltip mit Betrag, prozentualer Gesamtgewichtung, Sparrate und detaillierter Liste aller gespiegelten Fonds. Ein Klick hebt die entsprechende Quell-Zeitphase dezent hervor.

---

### 2. 🛢️ Minimalistischer Ein-/Ausblendschalter (Zylinder-Icon)

* **Standardmäßig geschlossen:** Beim Aufruf von Version V8.0 ist der Zylinderturm zunächst geschlossen (ausgeblendet) und zeigt das durchgestrichene Zylinder-Icon. Tagesgeld und Spezialitäten erscheinen horizontal nebeneinander wie in V7.0.
* Ein Klick auf das dezente **Zylinder-/Datenbank-Icon** links oben blendet den Turm ein bzw. wieder aus:
  * **Turm ausgeblendet (Standard):** Durchgestrichenes Zylinder-Icon mit feiner roter Diagonallinie (`Zylinderturm 'Robustes Portfolio' einblenden`).
  * **Turm eingeblendet:** Sauberes Zylinder-Icon (`Zylinderturm 'Robustes Portfolio' ausblenden`).
* **Maximale Schlichtheit:** Kein störender Text, keine Trennlinie und kein separates Auge-Icon – exakt auf den schnellen Klick ausgelegt.

---

### 3. 📐 Kollisionsfreie Platzierung von Tagesgeld

* **Bei aktivem Zylinderturm:**
  * Der Zylinderturm „Robustes Portfolio“ nimmt den Platz auf der linken Seite ein (wo sich zuvor Tagesgeld befand).
  * Das Tagesgeld platziert sich sauber **unterhalb** von *„Echte / unechte Anlageklassen mit unternehmerischen Risiken“*.
  * Ein großzügiger Sicherheitsabstand (`gap: 52px` plus oberer Zusatzabstand) garantiert, dass die gewölbten 3D-Böden, Deckel und Badges sich zu keinem Zeitpunkt berühren oder überlappen.
* **Bei ausgeblendetem Zylinderturm:**
  * Tagesgeld und Spezialitäten ordnen sich wieder horizontal nebeneinander an – optisch und funktional exakt identisch zur bewährten Version V7.0.

---

## 🎯 Highlights & Kernfunktionen aus Version 7.0

---

### 1. 🌐 Differenzierte Asset-Allocation & Top 5 Länder nach Anlageklassen (Aktien & Anleihen)

* **Keine Halluzinationen, 100 % gesicherte Daten:**
  * Daten basieren ausschließlich auf Factsheets, Verkaufsprospekten und verifizierten Morningstar-/MSCI-Fondsdaten.
  * Ein reiner Anleihenfonds (z. B. *Basis-Fonds I*, *iShares EUR Govt Bond 0-1yr*) hat einen **0,0 % Aktienanteil** und weist folgerichtig bei den Aktien-Top-5-Ländern 0,0 % aus.
  * Ein reiner Aktienfonds weist entsprechend einen **0,0 % Anleihenanteil** aus.
  * Bei Mischfonds (z. B. *Allianz Income and Growth*, *ACATIS Datini Valueflex*, *DWS Concept Kaldemorgen*, *MEAG EuroBalance*) erfolgt die Aufteilung nach tatsächlicher Quote von Aktien, Anleihen und sonstigen Anlageklassen (Kasse, Gold, Rohstoffe).
* **Relative Gewichtung zum Gesamtportfolio des Fonds:**
  * Ländergewichtungen spiegeln exakt den Anteil am gesamten Fonds wider (z. B. in einem Mischfonds mit 40 % Aktienanteil und 60 % US-Aktienquote trägt die US-Aktienallokation 24,0 % zum Gesamtfonds bei).

---

### 2. 📊 Strukturierter Hover-Tooltip mit Allokations-Mini-Balken

* **Visualisierter Mini-Balken am Kopf des Tooltips:**
  * Zeigt auf einen Blick die Allokation: Blau = Aktien, Grün = Anleihen, Bernstein = Sonstige/Kasse/Gold.
* **Getrennte Sektionen für Aktien & Anleihen:**
  * Eigene farbcodierte Header mit Kennzeichnung der jeweiligen Quote.
  * Listet die bis zu 5 wichtigsten Länder der Anlageklasse auf.
  * Weist bei 0,0 % Quote einen klaren Vermerk aus (`0,0% Aktienanteil` bzw. `0,0% Anleihenanteil`).
* **Dynamische Positionierung:**
  * Passt Höhe, Breite und Ausrichtung adaptiv an, sodass der Tooltip weder oben noch an den Bildschirmrändern abgeschnitten wird.

---

### 3. ↕️ Ländercluster Auf-/Zuklappen (Einzelschalter & Global-Doppelpfeil)

* Analog zu den Schichten im Hauptpanel können die Cluster unter *Länder (Einmalbeitrag)* und *Länder (Sparrate)* nun über interaktive Pfeil-Icons einzeln ein- und ausgeklappt werden.
* Über den Doppelpfeil-Button im Header lassen sich alle Ländercluster mit einem Klick global öffnen oder schließen.
* Die Zustände werden isoliert in `portfolio_collapsed_clusters_einmal_v7` und `portfolio_collapsed_clusters_sparrate_v7` gespeichert.

---

### 4. 🤖 Erweiterter Crawler & Gemini-Analyse (V7.0)

* `update_country_data.py` und `crawler_server.py` extrahieren Factsheets nun gezielt nach der neuen kombinierten Struktur:
  * `assetAllocation`: `{"aktien": float, "anleihen": float, "sonstige": float}`
  * `countryWeightingsAktien`: Top 5 Länder der Anlageklasse Aktien
  * `countryWeightingsAnleihen`: Top 5 Länder der Anlageklasse Anleihen
  * `countryWeightings`: Konsolidierte Top-Länderliste
* Nahtloses Schreiben in `fund_data.js` mit vollständiger Abwärtskompatibilität.

---

## 🎯 Bisherige Kernfunktionen aus Version 6.0

---

### 1. 💵 Intelligente Zuzahlungs- & Neuanlagen-Erkennung (Farbleitsystem Smaragdgrün)

Bei der Beratung und Betreuung bestehender Depots ist es entscheidend, auf einen Blick zu erfassen, wo frisches Kapital hinfließt. Version 6.0 führt hierfür eine automatisierte Zustandserkennung mit visuellem Leitsystem ein:

* **Bisheriger Bestand (Baseline-Schutz):**
  * Beim Importieren eines Depots (per Excel, CSV, PDF oder aus der Bibliothek) werden die eingelesenen Beträge und Sparraten als historische Referenzbasis (`initialInvestments` / `initialSparrates`) gespeichert.
  * Dies schützt den ursprünglichen Depotbestand vor Verwechslungen mit neuen Transaktionen.
* **Zuzahlung bei bestehenden Positionen:**
  * Erhält ein bereits im Depot geführter Fonds weiteres Kapital, wird die Differenz automatisch als Zuzahlung erkannt.
  * In der Liste *„Auswahl operative Manager“* erscheint ein auffälliges Badge: `+ 20.000,00 € Zuzahlung`.
  * Neben dem Badge werden sowohl der ursprüngliche **Bestand** als auch die neue **Gesamtsumme** transparent angezeigt.
* **Neuanlage bei neu hinzukommenden Fonds:**
  * Wird ein neuer Fonds in ein bestehendes Portfolio aufgenommen (ursprünglicher Bestand = `0,00 €`), deklariert das System die Allokation automatisch als **Neuanlage** (`+ 10.000,00 € Neuanlage`).
* **Sparraten-Erhöhung vs. Neuanlage:**
  * Analog zu den Einmalbeiträgen erkennt das System monatliche Sparraten:
  * Bestehende Sparraten, die aufgestockt werden, erhalten den Vermerk `+ X € mtl. Erhöhung`.
  * Erstmalig für einen Fonds eingerichtete Sparraten erhalten den Vermerk `+ X € mtl. neu`.
* **Smaragdgrünes Signalfarb-System (`#15803d` / `#ecfdf5` / `#86efac`):**
  * Frisches Smaragdgrün signalisiert sofort Kapitalzuflüsse:
    * In den Fondskarten der rechten Seitenleiste (*„Auswahl operative Manager“*).
    * Im zusammenfassenden Banner am Kopf des rechten Panels (`+ 25.000,00 € Zuzahlung (+ 250,00 € mtl. neu)`).
    * In der tabellarischen Übersicht und im PDF-Export.

---

### 2. 🔄 Durchgängig konsistente Struktur (8 Managementansätze von links nach rechts)

Die Nomenklatur und Reihenfolge wurde im gesamten System harmonisiert und vereinheitlicht:

* **Umbenennung:**
  * Die frühere Bezeichnung *„Verteilung nach Schicht“* heißt nun präzise und fachlich korrekt **„Verteilung nach Managementansatz“**.
* **Kanonische Sortierung (Dashboard, Seitenleiste, PDF):**
  * Alle Ansichten folgen exakt der links-nach-rechts-Logik des Zeitphasen-Dashboards:
    1. **Tagesgeld** (Bankeinlagen)
    2. **Zeitphase 1: Geldmarkt** (`< 1 Jahr`)
    3. **Zeitphase 2: Zielrendite / WB Anleihen / EB Anleihen** (`> 2 Jahre`)
    4. **Zeitphase 3: Zielrendite / WB Anleihen / EB Anleihen** (`> 4 Jahre`)
    5. **Zeitphase 4: WB Aktien/Anleihen** (`> 6 Jahre`)
    6. **Zeitphase 5: WB Aktien** (`> 8 Jahre`)
    7. **Zeitphase 6: EB Aktien** (`> 10 Jahre`)
    8. **Echte / unechte Anlageklassen mit unternehmerischen Risiken** (Opportunistisch)
* **Lückenlose 0,00-€-Darstellung:**
  * Auch Zeitphasen bzw. Managementansätze, denen aktuell kein Kapital zugewiesen ist, werden verbindlich gelistet:
    * **Übersicht *„Verteilung nach Managementansatz“*:** Alle 8 Ansätze sind aufgeführt; leere Ansätze weisen `0,00 €` aus.
    * **Rechtes Panel *„Auswahl operative Manager“*:** Alle 8 Managementansätze werden als strukturierte Karten dargestellt. Unbesetzte Ansätze zeigen `0,00 €`, den Hinweis *„Keine Manager ausgewählt (0,00 €)“* sowie einen Schnellwahl-Button **`+ Auswählen`**, der direkt den passenden Auswahldialog öffnet.
    * **Anlagevorschlag PDF:** Unbesetzte Phasen werden sauber als separate Zeile mit `0,00 €` in dezenter, kursiver Typografie aufgeführt.

---

### 3. 📂 Interaktive Auf- & Zuklappfunktion (Akkordeon) & 1:1 Drucksynchronisation

Um auch bei umfangreichen Portfolios mit vielen Managern stets die volle Übersicht zu behalten, bietet Version 6.0 ein dynamisches Akkordeon-System:

* **Individuelles Auf- & Zuklappen je Managementansatz:**
  * Durch Klick auf die Kopfzeile einer Zeitphase in der Liste *„Auswahl operative Manager“* lässt sich die Liste der enthaltenen Fonds auf- bzw. zuklappen.
  * **Eindeutige Pfeil-Indikatoren:**
    * **Geschlossen (`▶` Pfeil nach rechts):** Die Fondsliste ist eingeklappt. Es wird ausschließlich die kompakte Übersichtskarte mit Bezeichnung der Zeitphase, Gesamtsumme und smaragdgrünem Zuzahlungs-/Neuanlagen-Badge angezeigt.
    * **Geöffnet (`▼` Pfeil nach unten):** Die vollständige Fondsliste (aktive Fonds, delistete Fonds sowie die Schaltfläche `+ Weitere Manager auswählen`) wird angezeigt.
* **Globaler Schnell-Umschalter („Alle Zeitphasen auf-/zuklappen“):**
  * Neben dem Sichtbarkeits-Auge befindet sich ein Button mit Doppel-Chevron-Icon, mit dem sich alle 8 Zeitphasen mit einem Klick simultan aufklappen oder zuklappen lassen.
* **Länder-Akkordeon (Einmalbeitrag & Sparrate):**
  * Analog zur Auswahl operativer Manager verfügen die Spalten *„Länder (Einmalbeitrag)“* und *„Länder (Sparrate)“* über interaktive Akkordeons.
  * **Pfeil-Indikatoren (`▶` / `▼`):** Durch Klick auf die Regionen (Nordamerika, Europa, Asien etc.) klappen die Top-5-Länderlisten auf bzw. zu.
  * **Doppel-Chevron `[ ︾ ]`:** Jede Länderspalte besitzt einen Schnell-Umschalter im Kopfbereich, um alle Regionen mit einem Klick simultan auf- oder zuzuklappen.
* **Zustandsspeicherung (Persistence):**
  * Der gewählte Zustand (welche Phasen geöffnet oder geschlossen sind) wird im lokalen Browserspeicher (`localStorage`) abgelegt und bleibt auch beim Neuladen oder Wechseln der Eingaben erhalten.
* **1:1 Synchroner Gesamtausdruck („Drucken“-Button):**
  * Beim Klick auf **„Drucken“** (neben *Länder aktualisieren*) übernimmt der Druck exakt die Ansicht des Bildschirms:
    * **Nahtlose 1-Seiten-Passung (Executive Dashboard):** Bei zugeklappten Zeitphasen passt das gesamte Dashboard (Matrix Phasen 1–6, Zylinder für Tagesgeld & Unternehmerische Risiken, Anlageplanung sowie das rechte Manager-Panel) exakt und ohne Umbruch auf Seite 1 (DIN A4 Querformat).
    * **Schutz vor zerschnittenen Zylindern (`break-inside: avoid`):** Weder die Schicht Tagesgeld noch Unternehmerische Risiken (Spezial) oder die Anlageplanung können jemals horizontal durch einen Seitenumbruch getrennt werden.
    * **Sauberer Umbruch für Detailanalysen (`break-before: page`):** Die untere Informationsleiste (Länderallokation & Managementansatz-Verteilung) beginnt sauber auf einer Folgeseite, wodurch Seite 1 stets als makellose Vorstands-/Beratungsübersicht erhalten bleibt.
    * **Perfekt ausgerichtete Zuzahlungs-Badges:** Kein Zeilenumbruch mehr zwischen dem Pluszeichen `+` und dem Betrag; Betrag und Label *„Zuzahlung/Neuanlage“* sind sauber zweizeilig rechtsbündig unter der Gesamtsumme angeordnet.
    * **Ausblendung aller Arbeits-Icons:** Sämtliche Aktionsschaltflächen (Auge, Setup laden/speichern, Reset, Baseline, Modal-Buttons) werden im Ausdruck vollständig unterdrückt.

---

### 4. 📄 Optimierte Druckdatei & PDF-Anlagevorschlag

* **Gesamtsumme ausschließlich auf der letzten Seite (`showFoot: 'lastPage'`):**
  * Zuvor wurde die Fußzeile mit der Gesamtsumme auf jeder Zwischenseite wiederholt, was zu Missverständnissen führte, wenn auf Seite 1 nur ein Teil der Zuzahlungen gelistet war.
  * Die Gesamtsumme erscheint nun exklusiv auf der finalen Seite als Abschluss des Dokuments.
* **Saubere Umbrüche für 6-stellige Eurobeträge:**
  * Durch eine Neujustierung der Spaltenbreiten (Fondsname 56 mm, WKN/ISIN 28 mm, Bisheriger Bestand 30 mm, Zuzahlung/Neuanlage 34 mm, Gesamtanlage 34 mm) werden auch große sechsstellige Zuzahlungen (z. B. `+ 250.000,00 €`) garantiert ohne unschönen Zeilenumbruch einzeilig dargestellt.
* **Centgenaue Neuanlagen-Kennzeichnung im PDF:**
  * Neue Fonds erhalten in der Spalte *„Bisheriger Bestand“* automatisch eine `0,00 €`, in *„Zuzahlung / Neuanlage“* den Anlagebetrag in kräftigem Grün (`[21, 128, 61]`) und in *„Gesamtanlage“* die finale Summe.
* **Kopfbereich mit Finanz-Synthese:**
  * Das PDF weist übersichtlich *Bisheriger Depotbestand*, *Geplante Zuzahlung / Neuanlage* und *Neues Gesamtvermögen* (inklusive Sparraten) aus.

---

### 5. 🛡️ Vollständige Integration & Kennzeichnung delisteter Fonds

* **Aufnahme historischer & delisteter Fonds:**
  * Delistete Fonds (gekennzeichnet durch das interne Flag `_isDelistet: true`) stammen aus der offiziellen VEM-Erweiterungsliste und können weiterhin im Bestand geführt und analysiert werden.
* **Intelligente Investitionssperre (`disabled` / `.delisted-input-locked`):**
  * Für delistete Fonds ohne Vorabbestand (Einmalanlage = `0,00 €` und monatliche Sparrate = `0,00 €`) sind die Eingabefelder im Auswahl-Dialog **gesperrt** und optisch ausgegraut.
  * Ein Hinweistooltip informiert: *„Erstinvestition in delistete Fonds nicht möglich“*.
  * **Bestandsschutz:** Bereits investierte Bestände (> `0,00 €`) bleiben voll editierbar, um bestehende Positionen anpassen, umschichten oder abbauen zu können.
* **Dezentes, gedimmtes Kartendesign:**
  * In der rechten Seitenleiste (*„Auswahl operative Manager“*) heben sich delistete Fonds durch ein unaufdringliches, helles Design (`.panel-fund-delisted-card`: Hintergrund `#f8fafc`, dezent gestrichelter Rahmen `#cbd5e1`, gedimmte Typografie `#64748b` / `#94a3b8`, `opacity: 0.82`) ab.
  * Dadurch wird jede optische Verwechslung mit farbigen Schichten oder Ländergewichtungs-Balken vermieden.
* **Alphabetische A–Z-Sortierung mit Trennlinie:**
  * Innerhalb jedes Managementansatzes erscheinen zuerst die aktiven Fonds (A → Z) und nach einer dezenten Trennlinie die delisteten Fonds (A → Z).
  * Prominente Banner im Modal: Grün (`AKTIV`) und Rot (`DELISTET`).

---

### 6. 📥 Hochpräzise Depot-Import Engine (CSV / XLSX / PDF / JSON)

* **Behebung des WKN-False-Positive-Filters (`getRowMonetaryAmount`):**
  * Deutsche Währungsbeträge mit Tausendertrennpunkten (z. B. `9.773,02 €`, `6.386,93 €`, `5.042,79 €`, `7.371,50 €` etc.) ergaben nach dem Entfernen von Sonderzeichen exakt 6 Ziffern (`977302`, `638693` usw.) und wurden von älteren Parsern fälschlicherweise als WKN interpretiert und übersprungen.
  * Die Erkennung prüft nun dediziert auf Währungsmerkmale (Komma, `€`, geschützte Leerzeichen) und liest alle Positionen centgenau ein (z. B. Testdatei `AW21_ursprüngliche Formatierung beibehalten.xlsx` mit exakt **643.458,11 €** statt zuvor unvollständigen 599.758,33 €).
* **Mehrzeilige Tabellenerkennung:**
  * Erkennt Summenzeilen und Gruppenköpfe (z. B. wenn der Betrag in Zeile 1 steht und die WKN in Zeile 2).
* **Empfehlungslisten-Automatik:**
  * Fonds ohne direkte WKN-Übereinstimmung in der Datenbank werden anhand ihres Anlageschwerpunkts automatisch dem passenden Managementansatz zugeordnet und als aggregierte Position (*„Von Empfehlungsliste genommen“*) geführt.

---

### 7. ⏱️ Das Zeitphasenmodell & die Managementansätze im Überblick

| # | Managementansatz | Horizont | Primäre Strategie / Anlageklasse | Block-ID |
|---|---|---|---|---|
| **0** | **Tagesgeld** | Flexibel | Bankeinlagen / Liquiditätsreserve | `block-tagesgeld` |
| **1** | **Zeitphase 1: Geldmarkt** | `< 1 Jahr` | Geldmarkt & extrem kurzlaufende Anleihen | `block-kasse` |
| **2** | **Zeitphase 2: Zielrendite / WB / EB** | `> 2 Jahre` | Zielrendite / WB Anleihen / EB Anleihen | `block-defensiv` |
| **3** | **Zeitphase 3: Zielrendite / WB / EB** | `> 4 Jahre` | Zielrendite / WB Anleihen / EB Anleihen | `block-ausgewogen` |
| **4** | **Zeitphase 4: WB Aktien/Anleihen** | `> 6 Jahre` | Ausgewogene Misch- & Multi-Asset-Strategien | `block-dynamisch` |
| **5** | **Zeitphase 5: WB Aktien** | `> 8 Jahre` | Weltweit anlegende Aktienfonds (breit gestreut) | `block-maerkte-weit` |
| **6** | **Zeitphase 6: EB Aktien** | `> 10 Jahre` | Einzeltitelorientierte Aktienfonds (Fokussiert) | `block-maerkte-eng` |
| **7** | **Spezial-Risikoklassen** | Opportunistisch | Echte / unechte Anlageklassen mit unternehmerischen Risiken | `block-spezial` |

---

### 8. 🛠️ Weitere Komfort- & Analysefunktionen

* **Klarer Hard-Reset-Dialog:**
  * Textänderung zu: *„Alle Eingaben werden gelöscht“* – stellt unmissverständlich klar, dass lediglich die aktuellen Eingabefelder geleert werden, während gespeicherte Bestände in der Bibliothek sicher bleiben.
* **Auto-Transfer im Fondsauswahl-Modal:**
  * Das Verlassen eines Eingabefeldes (`blur`) oder Drücken von `Enter` übernimmt eingetippte Beträge sofort in den Zylinder und die Portfolioberechnung, ohne störende doppelte Ziffernanzeige.
* **Zwei-Nachkommastellen-Begrenzung:**
  * Betragseingaben werden automatisch auf zwei Nachkommastellen gerundet und formatiert.
* **👁️ Sichtbarkeits-Umschalter für operative Manager:**
  * Mit einem Klick auf das Auge-Icon im rechten Panel lassen sich alle Fondskarten temporär ausblenden (ideal für kundenorientierte Strategiegespräche). Schicht-Zylinder und Summen bleiben dabei aktiv.
* **🔍 Sofort-Suche mit Sprungmarke & Flash-Highlight:**
  * Schnelle Fonds-Suche nach Name, WKN oder ISIN mit automatischer Öffnung des Topfes und goldener 2,5-Sekunden-Hervorhebung.
* **💾 Depot-Bibliothek:**
  * Beliebig viele Portfolios lokal im Browser sichern, benennen, laden oder als `.json`-Datei teilen.
* **🌍 Ländergewichtungen:**
  * Detaillierte Top-5-Länderallokationen mit Clusterung (Nordamerika, Europa, Asien, Schwellenländer, Sonstige) per Hover-Tooltip.

---

## 🧭 Bedienungsanleitung

### Depot importieren (CSV, Excel oder PDF)
1. In der oberen Menüleiste auf **„Depot laden (CSV / Excel)“** klicken (oder das Upload-Icon `[ ⬆ ]` in der rechten Seitenleiste nutzen).
2. Eine `.xlsx`-, `.xls`-, `.csv`- oder `.pdf`-Datei auswählen.
3. Die Engine analysiert WKNs, ISINs, Fondsnamen, Anlageschwerpunkte und Beträge.
4. Das Import-Modal zeigt die Trefferquote und den Gesamtwert an. Mit einem Klick wird das Portfolio direkt in die Zeitphasen überführt. Der eingelesene Stand wird als Baseline gespeichert.

### Zuzahlungen oder Neuanlagen erfassen
1. Auf einen der 3D-Zylinder im Dashboard oder direkt in der rechten Spalte auf einen Managementansatz bzw. **`+ Auswählen`** klicken.
2. Fonds auswählen und den neuen Wunschbetrag eingeben:
   - Liegt der Betrag über dem bisherigen Bestand, berechnet das System die Zuzahlung und hebt sie grün hervor.
   - Handelt es sich um einen neuen Fonds, wird der gesamte Betrag als grüne Neuanlage markiert.
3. Genauso für monatliche Sparraten verfahren.

### Zeitphasen & Länder auf- & zuklappen (Akkordeon)
* **Operative Manager / Zeitphasen:** Auf die Titelzeile einer Zeitphase im rechten Panel klicken (`▶` / `▼`) oder den globalen Umschalter `[ ︾ ]` links oben nutzen.
* **Länderallokationen (Einmalbeitrag / Sparrate):** Auf eine Region (Nordamerika, Europa, Asien etc.) klicken (`▶` / `▼`) oder das Doppel-Chevron-Icon `[ ︾ ]` in der Kopfzeile der jeweiligen Länderspalte nutzen, um alle Regionen simultan auf- oder zuzuklappen.

### Portfolio sichern & drucken
* **In Bibliothek:** Auf **„Bibliothek“** klicken → Setup benennen und speichern.
* **JSON-Export:** Auf das Download-Symbol `[ ⬇ ]` im rechten Panel klicken, um eine (`.json`)-Sicherungsdatei herunterzuladen.
* **Drucken (1:1 Bildschirmsynchron):** Den Button **„Drucken“** (neben *Länder aktualisieren*) nutzen. Der Ausdruck übernimmt exakt den aktuellen Auf-/Zuklapp-Status der Zeitphasen (geschlossene Phasen als Summenzeile, geöffnete Phasen mit allen Fonds).
* **PDF-Bericht generieren:** Unten im rechten Panel auf **„Anlagevorschlag PDF“** klicken (erzeugt ein formatiertes mehrseitiges A4-Berichtsdokument mit Summenzeile auf der letzten Seite).

---

## 🗂️ Dateistruktur Version 8.0

```text
V8.0/
├── index.html               # Hauptanwendung (Layout, Zeitphasen-Grid, Zylinderturm, Modals & Toolbar)
├── styles_v8.0.css          # Styling (MLP-Design, 3D-Zylinderturm, dezenter Zylinderschalter, Badges)
├── app_v8.0.js              # Gesamte App-Logik (Live-Spiegelung, Zylinderturm-Rendering, Tooltips, PDF)
├── fund_data.js             # Fondsdatenbank (inkl. delisteter Fonds, WKNs, ISINs & Länderdaten)
├── crawler_server.py        # Lokaler Python-Server zum Crawlen aktueller Fondsdaten
├── update_country_data.py   # Skript zur automatischen Aktualisierung der Ländergewichtungen
└── README.md                # Ausführliche Dokumentation Version 8.0
```

---

## 💻 Systemvoraussetzungen & Browser

Vollständig clientseitige Single-Page-Applikation. Keine Serverinstallation oder Datenbank erforderlich.

* **Unterstützte Browser:**
  * Google Chrome / Chromium (empfohlen)
  * Apple Safari (macOS & iPadOS)
  * Mozilla Firefox
  * Microsoft Edge

---

*Zeitphasenmodell V8.0 · Stand: Oktober 2026*
