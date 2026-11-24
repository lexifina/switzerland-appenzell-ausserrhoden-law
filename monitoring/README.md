<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Beobachtung: was gelesen wird und was daraus folgte

[English](README.en.md)

Wie global-law jedes Land beobachtet: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). Diese Seite zeigt dasselbe nur für Appenzell Ausserrhoden: jedes Lesen einer amtlichen Quelle, wann, und was daraus folgte (Vorschriften hinzugefügt, geändert und entfernt). Maschinenlesbar in [data/checks/](../data/checks/) (JSON Lines, Schema `lexifina-check/1`), in `git log` als Commits mit `Kind: check` und Monat für Monat in [checks/](checks/).

**Letzte Prüfung:** 2026-11-24 14:30 UTC, Appenzell Ausserrhoden: Systematische Sammlung (ar.clex.ch): 63 Adressen gelesen; 27 hinzugefügt, 0 geändert, 0 entfernt; die Prüfung ist fehlgeschlagen; 92 nicht veröffentlicht, davon 0 ohne Grund.

## Quellen

| Quelle | Ordner | Wie oft | Letzte erfolgreiche Prüfung | Letztes Ergebnis | Stand |
| --- | --- | --- | --- | --- | --- |
| [Appenzell Ausserrhoden: Systematische Sammlung (ar.clex.ch)](https://ar.clex.ch/) | `<act>/` | täglich | — | die Prüfung ist fehlgeschlagen | beobachtet |

## Die letzten 30 Tage

| Beginn (UTC) | Quelle | Gelesen | Hinzugefügt | Geändert | Entfernt | Nicht veröffentlicht (ohne Grund) | Ergebnis | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
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
