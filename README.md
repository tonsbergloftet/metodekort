# Metodekort – Fra elevstemme til handling

Redigerbar mal for forsiden, introkortet, de fire metodekortene og plakaten «Reisen».
Kortene kan lastes ned i A6, A5, A4 eller 12,5 × 7,5 cm. Reisen lastes ned i A4 eller A3 (stående).
Designet er låst, bare teksten kan endres. Last ned som PDF (alle kort) eller PNG (300 dpi).

## Publisere på GitHub Pages
1. Lag et nytt repo og last opp alt innholdet i denne mappen (index.html, assets/, fonts/, lib/).
2. Settings → Pages → «Deploy from a branch» → main / (root) → Save.
3. Etter et minutt ligger siden på https://<brukernavn>.github.io/<repo>/

## Endre utgangsteksten
Teksten står i `KORT` øverst i skriptet i index.html. Endringer som gjøres på siden
lagres bare i nettleseren til den som redigerer.

## Legge til et nytt kort
Legg til et objekt i `KORT` med `type:"metode"`, og lag `assets/sirkel-5.png`
(tallsirkel) og `assets/illus-5.png` (illustrasjon). Bildene er laget som
«multiply»-lag: papirfargen er gjort hvit, så de smelter inn i bakgrunnen.

## Utskrift
- PDF er best til trykk. Kryss av for «3 mm utfallende» hvis trykkeriet ber om det.
- Velg «Kort (12,5 × 7,5 cm)» for å få knappen «Utskriftsark»: fire kort per A4 med skjæremerker, til vanlig skriver.
- Skriv ut med «faktisk størrelse» / 100 %, ikke «tilpass til side».
