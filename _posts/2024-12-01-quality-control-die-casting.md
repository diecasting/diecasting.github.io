---
title: "Umfassende Qualitätskontrolle im Druckguss"
date: 2024-12-01 11:45:00 +0800
categories: [Process Optimization, Quality Control]
tags: [quality-assurance, inspection, defect-prevention, testing, standards]
permalink: /posts/quality-control-die-casting/
---

## Qualitätskontrolle im Druckguss

Qualitätskontrolle ist im Druckguss entscheidend, damit Produkte die Spezifikationen erfüllen, Ausschuss reduziert wird und die Kundenzufriedenheit erhalten bleibt. Dieser Leitfaden behandelt umfassende QC-Praktiken von der Prozesskontrolle bis zur Endprüfung.

## Rahmenwerk der Qualitätskontrolle

### Die Qualitätshierarchie

```
1. Vorbeugung (Prozessdesign) — 50 % Wirksamkeit
2. Erkennung (Inspektion) — 30 % Wirksamkeit  
3. Korrektur (Nacharbeit) — 20 % Wirksamkeit
```

**Wichtige Erkenntnis**: Investieren Sie vor allem in Vorbeugung durch robustes Prozessdesign und konsequente Steuerung.

## Prozesskontrollparameter

### Kritische Kontrollpunkte (CCPs)

**Temperaturkontrolle**
- Metalltemperatur: Toleranz ±5°C
- Werkzeugtemperatur: Toleranz ±10°C
- Thermische Überwachung in jedem Zyklus
- Automatische Alarme bei Abweichungen

**Drucküberwachung**
- Erstdruck: ±50 psi
- Nachdruck: ±100 psi
- SPC in Echtzeit (Statistical Process Control)
- Rezeptspeicherung und -vergleich

**Konstante Zykluszeit**
- Innerhalb von ±2 % des Sollwerts halten
- Zeigt die Prozessstabilität an
- Erkennt Werkzeug- oder Maschinenprobleme frühzeitig

### Strategie zur Datenerfassung

Implementieren Sie eine automatisierte Datenerfassung:
- Jede Kavität einzeln
- Mindestens jeden 5. Schuss (ideal: 100 %)
- Kurven für Druck, Temperatur und Zykluszeit
- Analyse der Korrelation zu Defekten

## Prüfmethoden

### Sichtprüfung

**Best Practices für die 100-%-Prüfung**
- Geschulte Prüfer (mindestens 2 Jahre Erfahrung)
- Standardisierte Beleuchtung (mindestens 200-300 Lux)
- Referenzmuster verfügbar
- Referenzkarten für Fehlergrößen

**Typische Fehlerbilder**
- **Porosität**: Gasblasen an oder unter der Oberfläche
- **Lunker**: Vertiefungen in dicken Bereichen
- **Kaltfließstellen**: Nicht vollständig gefüllte Fließlinien
- **Grat**: Überschüssiges Material an der Trennfuge
- **Risse**: Lineare Trennungen im Material

### Maßprüfung

**Erstmusterprüfung (FAI)**
- Alle kritischen Maße erfassen
- CMM (Koordinatenmessmaschine) empfohlen
- Basiswerte für spätere Teile dokumentieren
- Frequenz: jede Charge oder mindestens täglich

**Maßprüfung während der Fertigung**
- Mindestens 5 Teile pro Stunde prüfen
- Fokus auf kritische Maße
- SPC-Diagramme (X̄- und R-Karten)
- Eingriffsgrenzen: ±50 % der Toleranz

### Zerstörungsfreie Prüfung (ZfP)

**Röntgenprüfung**
- Erkennt innere Porosität
- Auflösung: Fehlergrößen von 0,5-1 mm
- Typische Stichprobe: 1-5 %
- Kosten: 2-5 USD pro Teil

**Ultraschallprüfung**
- Erkennt Hohlräume unter der Oberfläche
- Schnell (< 1 Sekunde pro Teil)
- Benötigt Koppelmittel
- Sehr gut für 100-%-Prüfungen

**Wirbelstromprüfung**
- Erkennung von Oberflächenrissen
- Sehr schnell und empfindlich
- Berührungsloses Verfahren
- Kosteneffizient bei hohen Stückzahlen

## Fehleranalyse und Ursachenfindung

### Die 5-Why-Methode

Beispiel: **Hohe Porosität festgestellt**

1. Warum? → Unzureichender Druck
2. Warum? → Druckregelung der Pumpe ist abgedriftet
3. Warum? → Druckaufnehmer falsch kalibriert
4. Warum? → Druckaufnehmer nicht gemäß Plan kalibriert
5. Warum? → Wartungsplan nicht eingehalten

**Lösung**: Automatische Kalibrierungsalarme einführen

### Fehlertrendanalysen

**Wichtige Kennzahlen**
- Fehlerquote (ppm): defekte Teile pro Million
- Verteilung der Fehlertypen: Top 3 Probleme identifizieren (Pareto-Analyse)
- Trendanalyse: Vergleich Monat zu Monat

**Zielwerte**
- Sehr gut: < 500 ppm Fehler
- Gut: 500-2.000 ppm
- Akzeptabel: 2.000-5.000 ppm
- Handlungsbedarf: > 5.000 ppm

## Prüfungen und Validierung

### Mechanische Prüfungen

**Zugprüfung**
- Frequenz: mindestens 1 pro Charge
- Legierungseigenschaften überprüfen
- Kosten: 50-100 USD pro Test

**Härteprüfung**
- Wirksamkeit der Wärmebehandlung überprüfen
- 3-5 Proben pro Charge
- Brinell- oder Vickers-Skala
- Kosten: 20-30 USD pro Test

**Kerbschlagprüfung** (für kritische Anwendungen)
- Überprüfung der Charpy-Kerbschlagzähigkeit
- Gewährleistet Zähigkeit bei Temperaturextremen
- Kosten: 100-150 USD pro Test

### Funktionsprüfungen

**Druck-/Dichtheitsprüfung**
- Kritisch für hydraulische/pneumatische Teile
- 100-%-Prüfung empfohlen
- Kosteneffizient (5-20 USD pro Teil)

**Umweltsimulation**
- Salzsprühnebel (ASTM B117) für Korrosionsprüfungen
- Temperaturwechsel für Ermüdung
- Feuchteprüfung für Elektronikgehäuse

## Statistische Prozesskontrolle (SPC)

### Umsetzung von Regelkarten

**X̄- und R-Karten** (am häufigsten)
- Stichprobenmittelwert und Spannweite darstellen
- Obere und untere Eingriffsgrenze (UCL/LCL)
- Punkte außerhalb von 3 Standardabweichungen untersuchen

**Wichtige Entscheidungsregeln**
- Einzelner Punkt außerhalb von 3σ: sofort prüfen
- 2 von 3 Punkten außerhalb von 2σ: Trendwarnung
- 8 aufeinanderfolgende Punkte auf einer Seite der Mittellinie: Prozessverschiebung
- 6 aufeinanderfolgende steigende/fallende Punkte: Drift erkannt

### Softwarelösungen
- SPC-Dashboards in Echtzeit
- Automatische Warnmeldungen
- Predictive Analytics
- Integration mit Gießmaschinen

## Qualitätsstandards und Zertifizierungen

### Einhaltung von Industriestandards

**ISO 8062** (Metallische Gussteile - Qualität)
- Definiert Maßtoleranzen
- Oberflächenqualitätsstufen
- Fehlergrenzen

**ISO/TS 8062** (Erweiterte Spezifikationen)
- Höhere Präzisionsanforderungen
- Für kritische Anwendungen
- Zusätzliche Prüfanforderungen

**Automotive-Standards**
- IATF 16949 (Automotive-Qualitätsmanagement)
- Dokumentierte QC-Verfahren erforderlich
- Regelmäßige Audits verpflichtend
- Kundenspezifische Anforderungen

## Kosten-Nutzen-Analyse der Qualität

### Präventionskosten vs. Fehlerkosten

| Präventionsmaßnahme | Kosten | Potenzielle Einsparung |
|-------------------|------|-------------------------|
| Prozessleitsystem | 50.000 USD | 200.000 USD/Jahr |
| Bedienerschulung | 5.000 USD | 50.000 USD/Jahr |
| Vorbeugende Wartung | 30.000 USD/Jahr | 150.000 USD/Jahr |
| SPC-Einführung | 10.000 USD | 80.000 USD/Jahr |

**Faustregel**: 1 USD Präventionskosten spart 10 USD an Fehlerkosten

## Fazit

Wirksame Qualitätskontrolle erfordert:
1. **Robustes Prozessdesign** — richtige Kühlung, Anschnittführung und Druckprofile
2. **Überwachung in Echtzeit** — automatische Datenerfassung und SPC
3. **Umfassende Prüfung** — mehrere Prüfmethoden
4. **Kontinuierliche Verbesserung** — Ursachenanalyse und Korrekturmaßnahmen
5. **Teamqualifizierung** — geschulte Bediener und Prüfer

Wer heute in Qualität investiert, sichert Kundenzufriedenheit, reduziert Ausschuss und schützt die Marge.

---

**Verwandte Artikel**:
- [Best Practices für die Werkzeugkonstruktion im Druckguss](/posts/mold-design-best-practices/)
- [Einstieg in den Hochdruck-Druckguss (HPDC)](/posts/getting-started-with-hpdc/)
