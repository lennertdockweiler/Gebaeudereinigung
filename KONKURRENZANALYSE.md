# Konkurrenzanalyse Gebäudereinigung Bodensee/Hegau (Stichprobe)

**Methode.** Google selbst ließ sich nicht abfragen. Grundlage sind Suchergebnisse zu 12 Suchanfragen
(Konstanz, Singen, Radolfzell, Stockach, Überlingen, Friedrichshafen, Ravensburg, Villingen,
Rechner/Preise, Großanbieter). Verzeichnisse, Jobbörsen und Ausschreibungen wurden aussortiert.
Von 47 gefundenen Firmen- und Rechner-Websites ließen sich 39 Startseiten abrufen und per Skript
auswerten, 35 davon wurden zusätzlich gerendert und optisch begutachtet. Das ist eine Stichprobe,
kein belastbares Top-50-Ranking.

## Funktionen und Inhalte (Anteil der 39 Startseiten)
| Merkmal | Anteil |
|---|---|
| Telefonnummer klickbar | 77 % |
| Cookie-Banner / Consent-Tool | 74 % |
| Besichtigung / Vor-Ort-Termin erwähnt | 72 % |
| Grundreinigung genannt | 72 % |
| Kontaktformular | 64 % |
| Praxisreinigung genannt | 62 % |
| Bewertungen / Sterne / Google | 59 % |
| Angebot-anfordern-Button | 59 % |
| Treppenhaus | 56 % |
| WhatsApp | 44 % |
| Slider / Karussell | 44 % |
| FAQ | 41 % |
| Winterdienst | 41 % |
| Referenzen / Zertifikate | je 33 % |
| Karriere-Hinweis | 31 % |
| **Online-Preisrechner** | **15 %** |
| Kanzlei / Hausverwaltung als Zielgruppe | je 18 % |
| FAQPage-Strukturdaten | 26 % |

## Design-Muster
- Marineblau, Petrol oder Anthrazit mit Cyan- oder Grün-Akzent. Fast alle sehen gleich aus.
- Hero: Stockfoto von Reinigungskräften mit Handschuhen und Sprühflasche, H1 nach dem Muster
  "Reinigungsfirma [Ort]", zwei Buttons (Anfrage, Anrufen), Vertrauenszeile (Zeiten, Ansprechpartner).
- Zahlenleisten ("208+ Kunden") und Sternebewertung direkt unter dem Hero.
- Cookie-Banner verdeckt oft den halben Bildschirm über dem Falz.
- Schwache Typografie (meist Roboto/Open Sans), kaum Hierarchie, Ortsseiten als Klone derselben Vorlage.

## Lücken, die die Demo nutzt
1. Online-Preisspanne (nur 15 %), hier als Beispielrechnung mit Takt-Leiste.
2. Eigene Seiten für Praxen, Kanzleien, Hausverwaltungen.
3. Keine Cookies, daher kein Banner.
4. Eigene Bildsprache (Fenster-Regler mit Regionsfoto) statt Handschuh-Stockfoto.
5. FAQ mit Strukturdaten, Einsatzgebiet, Karriere-Hinweis, Schnellzugriff-Leiste am Handy.
6. Kennzahlen und Bewertungen als gekennzeichnete Platzhalter statt erfundener Werte.

## Bilder
Alle drei Fotos stammen von Wikimedia Commons (CC BY 2.0 / 3.0, kommerzielle Nutzung mit Namensnennung
erlaubt). Die Nennung steht im Footer. Lizenz vor dem Livegang an der Quelle prüfen und durch
eigene Fotos ersetzen. Geeignete freie Fotos von Reinigungsarbeiten in Büro, Praxis und Treppenhaus
ließen sich nicht in ausreichender Qualität finden, dort stehen gestaltete Platzhalter.

## Eigene Prüfung der gebauten Seite
- axe-core (WCAG 2.1 AA und Best Practice), 400 px hell und dunkel sowie 1280 px: 0 Verstöße
  (zuvor 2: verschachtelte Landmark, Hinweisleiste außerhalb eines Landmarks).
- Kein horizontales Scrollen, keine Konsolenfehler, Skript- und JSON-LD-Syntax gültig.
- Umgesetzte Verbesserungen: Rechner direkt hinter die Leistungen, ruhige Screenreader-Ansage
  (entprellt), größere Touch-Ziele, Bildnachweis als Liste, Schneefoto von 113 auf 76 KB.
