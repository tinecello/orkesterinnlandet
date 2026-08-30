# Bilder og tekstredigering

## Slik endrer du tekst

Alle fire HTML-filene er vanlig, lesbar HTML. Du kan åpne dem i GitHub, klikke
blyantikonet og søke med Ctrl+F / Cmd+F etter teksten du vil endre. Kommentarene
i koden (`<!-- ===== KONSERT 1 ... ===== -->`) viser hvor hver blokk begynner.

Endre bare selve teksten mellom `>` og `<`. La `style="..."` stå urørt.

| Vil endre | Fil | Søk etter |
| --- | --- | --- |
| Gjest på konsert 23.09 | `index.html` | `Trygve Seim, saksofon` (første treff) |
| Overskriften «Gjest» | `index.html` | `>Gjest<` |
| Rullebanner øverst | `index.html` | `23. september · Rudi gard` — **finnes to steder, endre begge likt** |
| Årstall på tidligere konserter | `program.html` | `KONSERT 1 — ÅRSTALL` osv., eller årstallet direkte |
| Jubileumsstripa «1991–2026» | alle filer | `1991–2026` |

## Bilder

Alle bilder ligger i mappen `images/` ved siden av HTML-filene. Sidene henter bildene
derfra på filnavn — last opp filene med **nøyaktig** disse navnene, så vises de automatisk.
Bytt bilde senere ved å laste opp en ny fil med samme navn.

### Ligger klart

| Filnavn | Hvor | Format |
| --- | --- | --- |
| `orkester-hero.jpg` | Toppbildet på forsiden og Om oss | 2:1 liggende, min. 2400 × 1200 px |
| `atle-sponberg.jpg` | Atle Sponberg, forside + Om oss | 3:4 stående eller kvadratisk, min. 1200 px |
| `oi-logo.png` | Logo i topp og bunn på alle sider | PNG, gjennomsiktig bakgrunn |

### Mangler — last opp til `images/`

#### Konsertbilder på forsiden — 3:2 liggende, 1600 × 1067 px

| Filnavn | Konsert |
| --- | --- |
| `konsert-rudi.jpg` | 23. september, Rudi gard |
| `konsert-byscena.jpg` | 24. september, Byscena Bedehuset, Gjøvik |

#### Programsiden, tidligere konserter — 3:2 liggende, 1600 × 1067 px

| Filnavn | Konsert på siden |
| --- | --- |
| `arkiv-juleoratorium.jpg` | Brahms: Requiem, 2019 |
| `arkiv-leik.jpg` | Beethoven: Eroica, 2019 |
| `arkiv-strykekvintett.jpg` | Gjøvik Galla, 2019 |
| `arkiv-slipp.jpg` | Førjulskonsert, 2019 |
| `arkiv-cd.jpg` | Minnekonsert Kirsten Flagstad, 2018 |
| `arkiv-operafest.jpg` | Operafest Røykenvik, 2018 |
| `arkiv-holberg.jpg` | Holbergsuiten på turné, 2018 |

#### Galleriet på Om oss — 3:2 liggende, 1200 × 800 px

`om-galleri-1.jpg`, `om-galleri-2.jpg`, `om-galleri-3.jpg`

#### Sponsorlogoer på forsiden — PNG med gjennomsiktig bakgrunn, ca. 800 px bred

`partner-1.png` til `partner-8.png` (åtte felt, i rekkefølge fra øverste venstre)

## Filstørrelse

Hold JPG-ene under ca. 400 kB hver. Bilder som ikke er lastet opp vises som et tomt,
lysegrått felt — siden fungerer ellers som normalt.
