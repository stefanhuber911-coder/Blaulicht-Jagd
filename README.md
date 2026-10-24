# Blaulicht-Jagd

Labyrinth-Spiel fürs Handy: THW gegen Feuerwehr in vier Einsätzen, mit Katastrophenfall, Ölspur, Stromausfall, Unfallstelle und Abzeichen.

Spielen: die GitHub-Pages-Adresse dieses Repositorys im Handy-Browser öffnen und über **Teilen → Zum Home-Bildschirm** als App ablegen. Danach läuft das Spiel im Vollbild und auch offline.

## Dateien

| Datei | Zweck |
|---|---|
| `index.html` | Das komplette Spiel |
| `splash.jpg` | Startbild (kann einfach ersetzt werden, gleiches Format 941×1672 bzw. 9:16) |
| `manifest.webmanifest` | Name, Farben, Vollbild, App-Symbole |
| `sw.js` | Offline-Betrieb |
| `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` | App-Symbole |

## Aktualisieren

- Neue `index.html` hochladen: erscheint beim nächsten Start der App (mit Internet).
- `splash.jpg` oder ein Symbol ersetzen: in `sw.js` die Zahl bei `VERSION` um eins erhöhen und mit hochladen.
