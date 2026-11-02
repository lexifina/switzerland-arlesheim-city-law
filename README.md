# Arlesheim (city): law history in git

The municipal law of the municipality of Arlesheim (Gemeinde Arlesheim, canton of Basel-Landschaft, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law). The law of the canton of Basel-Landschaft is in [lexifina/switzerland-basel-landschaft-law](https://github.com/lexifina/switzerland-basel-landschaft-law); federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, exactly as the municipality publishes it.

## What this repository holds

32 acts with 66 versions so far: the Gemeindeordnung (the municipality's charter) first, then the municipality's other enactments in force (ordinances, regulations, tariffs and decisions), in the order of the systematic collection, added in parts of about 50. Agreements, concessions, directives and repealed acts are not included.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `1-1-1/` | Gemeindeordnung (SRS 1.1-1) | 2 | oldest version available, then each consolidated version: 26 September 2021 to 15 May 2022 |
| `1-1-2/` | Verwaltungs- und Organisationsreglement (SRS 1.1-2) | 4 | as enacted, then each consolidated version: 1 January 2017 to 1 October 2025 |
| `1-1-3/` | Geschäftsordnung der Rechnungsprüfungskommission (RPK) (SRS 1.1-3) | 1 | as enacted, 1 December 2019 |
| `1-4-1/` | Verordnung betreffend den Aushang von Wahl-, Abstimmungs- und Parteiplakaten auf öffentlichem Grund sowie für den gemeinsamen Versand von Wahlempfehlungen (SRS 1.4-1) | 1 | as enacted, 4 May 2021 |
| `1-4-2/` | Geschäftsordnung der Wahlbüros (SRS 1.4-2) | 2 | as enacted, then each consolidated version: 1 July 2024 to 31 March 2026 |
| `1-6-1/` | Geschäftsordnung des Gemeinderates (SRS 1.6-1) | 2 | as enacted, then each consolidated version: 1 January 2020 to 1 May 2022 |
| `1-6-2/` | Kompetenzordnung (SRS 1.6-2) | 3 | as enacted, then each consolidated version: 1 January 2020 to 1 January 2023 |
| `1-6-3/` | Geschäftsordnung der Kommission für Altersfragen (SRS 1.6-3) | 1 | as enacted, 1 January 2026 |
| `1-6-4/` | Geschäftsordnung der Finanzplankommission (FPK) (SRS 1.6-4) | 1 | as enacted, 1 August 2026 |
| `1-7-1-per/` | Personal- und Entschädigungsreglement (SRS 1.7-1) | 2 | oldest version available, then each consolidated version: 1 January 2015 to 1 January 2026 |
| `1-7-1-1/` | Verordnung zum Personal- und Entschädigungsreglement (Vo PER) (SRS 1.7-1.1) | 9 | oldest version available, then each consolidated version: 1 January 2022 to 18 August 2026 |
| `4-1-1/` | Reglement über die familienergänzende Kinderbetreuung (SRS 4.1-1) | 2 | oldest version available, then each consolidated version: 1 August 2019 to 1 January 2025 |
| `4-1-1-1/` | Verordnung zum Reglement über die familienergänzende Kinderbetreuung (SRS 4.1-1.1) | 3 | oldest version available, then each consolidated version: 18 August 2020 to 1 January 2025 |
| `4-2-1/` | Reglement über die Ausrichtung von Beiträgen an die Kosten des Besuchs von Privatschulen (SRS 4.2-1) | 1 | as enacted, 1 September 2003 |
| `4-2-2/` | Reglement über die Musikschule Arlesheim (SRS 4.2-2) | 2 | as enacted, then each consolidated version: 23 January 2005 to 1 August 2022 |
| `4-2-2-1/` | Geschäftsordnung des Musikschulrates (SRS 4.2-2.1) | 3 | as enacted, then each consolidated version: 17 January 2011 to 22 November 2024 |
| `4-2-2-2/` | Verordnung zum Reglement über die Musikschule Arlesheim (SRS 4.2-2.2) | 3 | as enacted, then each consolidated version: 1 August 2022 to 1 August 2026 |
| `4-7-1/` | Reglement über den Kulturfonds (SRS 4.7-1) | 1 | as enacted, 1 July 2017 |
| `4-7-1-1/` | Richtlinien für die Vergabe von Mitteln gemäss Reglement über den Kulturfonds (SRS 4.7-1.1) | 1 | one version (the oldest available), 19 December 2017 |
| `5-1-2-rro/` | Reglement über die öffentliche Ruhe und Ordnung (SRS 5.1-2) | 1 | as enacted, 1 January 2020 |
| `5-5-1-feuerwehrreglement/` | Reglement über die Feuerwehr (SRS 5.5-1) | 2 | as enacted, then each consolidated version: 1 January 2016 to 1 January 2025 |
| `6-3-1/` | Steuerreglement (SRS 6.3-1) | 2 | as enacted, then each consolidated version: 17 January 2002 to 1 January 2025 |
| `6-4-1/` | Verordnung über die Ausleihe und Vermietung von gemeindeeigenem Mobiliar und Gerätschaften (SRS 6.4-1) | 1 | as enacted, 1 January 2009 |
| `6-4-2/` | Verordnung über die Gebühren der Einwohnerdienste (SRS 6.4-2) | 3 | oldest version available, then each consolidated version: 1 January 2022 to 1 September 2025 |
| `6-6-1/` | Verordnung über die Benutzung und Gebühren für die Allmend, gemeindeeigene Räumlichkeiten, Anlagen und Einrichtungen sowie über die Bewilligung von Gelegenheitswirtschaften und Freinachtbewilligungen (SRS 6.6-1) | 4 | oldest version available, then each consolidated version: 1 January 2021 to 12 August 2025 |
| `7-1-1/` | Zonenreglement Siedlung (SRS 7.1-1) | 1 | as enacted, 4 July 2017 |
| `7-1-2/` | Reglement über die Mehrwertabgaben (SRS 7.1-2) | 1 | as enacted, 1 October 2021 |
| `7-1-2-1/` | Verordnung über die Erhebung von lnfrastrukturbeiträgen und Mehrwertabgaben (SRS 7.1-2.1) | 3 | oldest version available, then each consolidated version: 30 November 2021 to 1 March 2023 |
| `7-1-3/` | Reglement über den Fonds für Infrastrukturbeiträge und Mehrwertabgaben (SRS 7.1-3) | 1 | as enacted, 1 October 2021 |
| `7-1-4/` | Zonenreglement Landschaft (SRS 7.1-4) | 1 | one version (the oldest available), 15 August 1996 |
| `7-1-6-parkplatzersatzabgabereglement/` | Reglement über die Ersatzabgabe für Parkplätze (SRS 7.1-6) | 1 | as enacted, 13 August 2024 |
| `7-1-6-1-parkplatzersatzabgabefonds/` | Verordnung betreffend den Fonds für die Parkplatzersatzabgabe (SRS 7.1-6.1) | 1 | as enacted, 24 September 2024 |

## Source

The SRS (systematic collection) of the municipality, published by the municipality at <https://arlesheim.tlex.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the municipality's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist (`<act key>@arlesheim.tlex.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the municipality publishes as binding. The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
