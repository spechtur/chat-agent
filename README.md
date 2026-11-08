# Maschinenraum · Vom Chat zum Agenten

Ein Experiment für Dozierende der PHGR: Die Teilnehmenden werden zu den Werkzeugen eines KI-Agenten und erleben von innen, was sich beim Schritt vom Chat zum Agenten verändert.

Eine einzige HTML-Datei, ohne Server, ohne Datenbank. Läuft auf GitHub Pages.

## Ansichten

| Adresse | Zweck |
|---|---|
| `index.html` | Beamer-Präsentation (Pfeiltasten, Leertaste, `F` für Vollbild) |
| `#mitmachen` | Handy-Ansicht über den QR-Code: Gruppe, Rolle, nur die eigene Rollenkarte, Reflexion |
| `#moderation` | Hinter den Kulissen: Zuordnung der verdeckten Karten, Ablauf |
| `#druck` | Fallback: alle Rollenkarten und der Prompt zum Ausdrucken |

## Ablauf (ca. 90 Min.)

1. Einordnen auf dem Beamer (Folien 1–16): Ausgangsfrage, vier Prüfsteine mit Auflösung, Vierfeld, Bausteine eines Agenten
2. QR-Code scannen, Rollen verteilen (Folie 17)
3. Durchführung mit Timer (Folie 18)
4. Protokoll und Reflexion auf den Handys
5. Vergleich im Plenum (Folien 19–22)

## Hinweise

- Gruppen zu 3–5 Personen, bis zu 4 Gruppen. Der Operator braucht ein Gerät mit [Lumo](https://lumo.proton.me) oder [Duck.ai](https://duck.ai).
- Fortschritt wird nur lokal im Browser des jeweiligen Geräts gespeichert, damit ein Neuladen nichts verliert.
- Die Zuordnung der verdeckten Karten steht im Code (`HIDDEN`) und in der Moderationsansicht.
- QR-Code: [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) von Kazuhiko Arase (MIT-Lizenz), eingebettet.
