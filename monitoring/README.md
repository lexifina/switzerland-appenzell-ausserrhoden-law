<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Beobachtung: was gelesen wird und was daraus folgte

[English](README.en.md)

Wie global-law jedes Land beobachtet: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). Diese Seite zeigt dasselbe nur für Appenzell Ausserrhoden: jedes Lesen einer amtlichen Quelle, wann, und was daraus folgte (Vorschriften hinzugefügt, geändert und entfernt). Maschinenlesbar in [data/checks/](../data/checks/) (JSON Lines, Schema `lexifina-check/1`), in `git log` als Commits mit `Kind: check` und Monat für Monat in [checks/](checks/).

**Letzte Prüfung:** 2026-11-28 05:40 UTC, Appenzell Ausserrhoden: Systematische Sammlung (ar.clex.ch): 89 Adressen gelesen; 0 hinzugefügt, 1 geändert, 0 entfernt; Änderungen gefunden; 66 nicht veröffentlicht, davon 0 ohne Grund.

## Quellen

| Quelle | Ordner | Wie oft | Letzte erfolgreiche Prüfung | Letztes Ergebnis | Stand |
| --- | --- | --- | --- | --- | --- |
| [Appenzell Ausserrhoden: Systematische Sammlung (ar.clex.ch)](https://ar.clex.ch/) | `<act>/` | täglich | 2026-11-28 05:40 UTC | Änderungen gefunden | beobachtet |

## Die letzten 30 Tage

| Beginn (UTC) | Quelle | Gelesen | Hinzugefügt | Geändert | Entfernt | Nicht veröffentlicht (ohne Grund) | Ergebnis | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 05:38](checks/2026-11.md#ch-lexwork-appenzell-ausserrhoden-20261128t053847z) | lexwork-appenzell-ausserrhoden | 89 | 0 | 1 | 0 | 66 (0) | Änderungen gefunden | — |
| [2026-11-27 05:39](checks/2026-11.md#ch-lexwork-appenzell-ausserrhoden-20261127t053949z) | lexwork-appenzell-ausserrhoden | 86 | 0 | 0 | 0 | 65 (0) | keine Änderung | — |
| [2026-11-26 05:38](checks/2026-11.md#ch-lexwork-appenzell-ausserrhoden-20261126t053801z) | lexwork-appenzell-ausserrhoden | 94 | 0 | 0 | 0 | 65 (0) | keine Änderung | — |
| [2026-11-25 05:41](checks/2026-11.md#ch-lexwork-appenzell-ausserrhoden-20261125t054131z) | lexwork-appenzell-ausserrhoden | 151 | 27 | 0 | 0 | 65 (0) | Änderungen gefunden | [44](https://github.com/lexifina/switzerland-appenzell-ausserrhoden-law/compare/631e8a4d7645...e608e6a0597d) |
| [2026-11-24 14:29](checks/2026-11.md#ch-lexwork-appenzell-ausserrhoden-20261124t142915z) | lexwork-appenzell-ausserrhoden | 63 | 27 | 0 | 0 | 92 (0) | die Prüfung ist fehlgeschlagen | — |
| [2026-11-24 12:51](checks/2026-11.md#ch-lexwork-appenzell-ausserrhoden-20261124t125147z) | lexwork-appenzell-ausserrhoden | 70 | 27 | 1 | 0 | 93 (0) | die Prüfung ist fehlgeschlagen | — |
| [2026-11-24 11:50](checks/2026-11.md#ch-lexwork-appenzell-ausserrhoden-20261124t115003z) | lexwork-appenzell-ausserrhoden | 189 | 92 | 1 | 0 | 95 (0) | die Prüfung ist fehlgeschlagen | — |

## Selbst prüfen

```
python tools/checktrail.py                      # die letzte Prüfung jeder Quelle
python tools/checktrail.py --day 2026-11-23     # jede Prüfung eines Tages
python tools/checktrail.py --act <id>           # wann eine Vorschrift gesehen und veröffentlicht wurde
git log --grep='^Kind: check' --format='%ci %s'  # die Prüfungen in der Historie
```

Rechtskraft hat nur die amtliche Verkündung; die Texte hier sind Kopien zum Lesen und Suchen.
