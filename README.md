# OHGW Sprengmeister 🧨

Ein Retro-Pixel-**Abrissspiel** – entstanden im **Vibe-Coding-Workshop** am Ottheinrich-Gymnasium.

Das alte Schulgebäude wird abgerissen und neu gebaut. Du bist der **Sprengmeister**
(Abriss-Profi für kontrollierte Sprengungen) und planst die Sprengung: Ladungen an die
tragenden Wände setzen, Zünder drücken – und zusehen, wie das Gebäude mit echter
Einsturz-Physik in sich zusammenfällt.

## Spielen

Einfach `index.html` im Browser öffnen. **Keine Installation, kein Server** – läuft auf
jedem Gerät (Desktop, Tablet, Handy). Alles steckt in dieser einen Datei.

## Steuerung

| Aktion | Tastatur | Maus / Touch |
|---|---|---|
| Ladung wählen | `1` Dynamit · `2` TNT · `3` C4 | Auf die Buttons tippen |
| Ladung setzen | – | auf das Gebäude klicken/tippen |
| Letzte Ladung zurück | `Z` | – |
| **Zünden** | `Leertaste` | Button „▼ Zünden“ |
| Level neu | `R` | Button „↺“ |
| Ton an/aus | `M` | Button „🔊“ |

## Ziel

Jedes Level hat ein **Einsturz-Ziel** (z. B. 55 %). Tipp vom Profi: die Ladungen **unten**
an den tragenden Wänden ansetzen – dann kappt man die Verbindung zum Boden und alles
darüber stürzt ein (das ist der echte Trick der kontrollierten Sprengung). Vier Level,
immer weniger Ladungen, immer höheres Ziel – bis zur **Meisterprüfung**.

## Technik

Pures HTML/CSS/JavaScript in einer einzigen Datei. Pixel-Grafik auf `<canvas>`,
prozedurale Retro-Sounds über die Web Audio API, kein einziges externes Asset.
