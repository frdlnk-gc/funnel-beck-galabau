# Creatives + Copies – Siegfried Beck Garten- und Landschaftsbau (Kunde 06)

Stelle: **Vorarbeiter GaLaBau (m/w/d)** · Ort: **Lohfelden (34253)**, direkt bei Kassel
Funnel: https://beck-galabau.green-careers.de
CI aus dem Logo gesampelt: Primary **#008C57**, Secondary **#630D56** (Flächenvariante #006B43)
Anzeige nennt **kein Gehalt** → auf keinem Creative und in keiner Copy eine Geldzahl.

## Medienlage

Ungewöhnlich stark: professionelles Shooting (candidateflow.de) mit Team-Banner + 5 Betriebsfotos,
dazu 7 echte Projektfotos aus der Anzeige. Kein Video.
Die **Originaldateien** (Storage-URL ohne `-lg`) waren bei diesem Kunden öffentlich abrufbar
(4–6 MB, bis 5712 px) – deshalb wurden Hero/Galerie aus den Originalen gerechnet statt aus `-lg`.

| Datei | Motiv |
|---|---|
| img/hero.jpg | komplette Belegschaft vor dem Firmen-Transporter (Anzeigen-Banner) |
| img/f1.jpg | Mannschaft mit Motorsensen/Geräten vor den Fahrzeugen |
| img/f2.jpg | drei Mitarbeiter auf dem CAT-Minibagger, Daumen hoch |
| img/f3.jpg | fertig gepflasterter Weg mit frischer Bepflanzung |
| img/f4.jpg | zwei Mitarbeitende mit Stihl-Motorsäge |
| img/f5.jpg | Baustelle Kassel, Mobilbagger + Radlader |
| img/f6.jpg | Team am LKW |
| img/f7.jpg | Bagger + L-Steine |
| img/f8.jpg | Baumpflanzung |
| img/f9.jpg | Werkstatt / Maschinenpark |
| img/f10.jpg | Naturstein-Detail |
| img/karte.jpg | OSM-Ausschnitt, Lohfelden exakt mittig (Zoom 10) |

## Die 4 Creatives (4:5, 1024×1280)

1. **creative-1-benefit-checkliste** – Foto (Team auf Bagger) oben, dunkelgrüne Fläche unten,
   Headline „VORARBEITER GaLaBau (m/w/d)", Standortzeile, 4 Benefit-Pills, lila CTA-Balken.
2. **creative-2-team-collage** – Logo + „22 Kollegen · seit 1974 · 2. Generation"-Leiste,
   3 echte Fotos als Kacheln, lila CTA-Kachel.
3. **creative-3-karte-lokal** – Karten-Hook mit Pin auf Lohfelden, Städte-Zeile, 2 Pills,
   lila CTA-Balken, OSM-Credit unten rechts.
4. **creative-4-dein-arbeitsplatz** – Vollbild-Belegschaftsfoto, „Deine eigene Kolonne.",
   3 Pills, grüner CTA-Balken.

### ⚠️ Creative 3 wurde NICHT von gpt-image-2 gesetzt

Drei Läufe, drei Fehlschläge:
1. eigene Headline „WIR SUCHEN DICH!" + **falsche Berufsbezeichnung „Gärtner*in"** + erfundene
   Claims („REGIONAL. NATURNAH. ZUKUNFTSSICHER.") statt der vorgegebenen Texte;
2. mit hartem „erfinde keinen Text"-Guard: **sämtlicher Text weggelassen**, nur Logo + Karte;
3. zurück im Stil von Creative 1: Pin + Label korrekt, Textblock trotzdem komplett fehlend.

Muster: Sobald ein **formatfüllendes Kartenbild** die Referenz ist, behandelt das Modell den
Auftrag als reine Bildbearbeitung und ignoriert die Textvorgaben. Creative 3 ist deshalb
deterministisch mit PIL komponiert (Karte cover-gecropt, Ort bleibt mittig; Logo mit
weggeschnittenem Original-Grafikrahmen; exakt die vorgegebenen Texte; OSM-Credit).
Die Prompts stehen weiter in `creatives.json` + im GDrive-Prompts-Doc als Fallback.

## Die 2 Copies

Stehen strukturiert in `copies.json` (copy_a/copy_b) und ausformuliert im GDrive-Doc
„Ad-Copies für den Ads Manager – Siegfried Beck Garten- und Landschaftsbau".

- **Copy A (direkt):** Umkreis-Ansprache + „bereit für deine eigene Kolonne?" + 4 Häkchen-Benefits.
- **Copy B (Verantwortung & Betrieb):** Führungs-Winkel + 22 Kollegen / seit 1974 / 2. Generation.

**4 Ads = je Creative eine Anzeige, beide Copies als Meta-Textoptionen** (asset_feed_spec).

## Umkreis-Städte (echte Distanzen, für Copies/Creatives/Targeting)

Kassel 5,9 km · Baunatal 8,4 km · Vellmar 11,4 km · Melsungen 14,6 km · Hann. Münden 21,0 km ·
Fritzlar 23,1 km · Hofgeismar 27,3 km · Homberg (Efze) 29,7 km

## Meta

Anzeigengruppe „Siegfried Beck Garten- und Landschaftsbau +30km" **120254487446140063**,
PAUSED, 20 €/Tag, 30 km um Lohfelden, Laufzeit 60 Tage (Ende 23.10.2026), 4 Ads ACTIVE.
