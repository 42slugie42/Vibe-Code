# OHGW Sprengmeister 🧨

Ein Retro-Pixel-**Abrissspiel** – entstanden im **Vibe-Coding-Workshop** am Ottheinrich-Gymnasium.

Das alte Schulgebäude wird abgerissen und neu gebaut. Du bist der **Sprengmeister**
(Abriss-Profi für kontrollierte Sprengungen): setze die Ladungen an die tragenden Wände,
drück den Zünder – und sieh zu, wie das Gebäude mit echter Einsturz-Physik in sich zusammenfällt.

## Spielen

Einfach `index.html` im Browser öffnen. **Keine Installation, kein Server** – läuft auf jedem
Gerät (Desktop, Tablet, Handy). Der komplette Fortschritt wird lokal im Browser gespeichert.

## Was steckt drin

- **6 Level** mit eigener Stimmung: Tag ☀️, Dämmerung 🌇, **Nacht** 🌙 (Sterne, Mond, leuchtende Fenster)
  und **Sturm** ⛈️ (Regen & Wind, der die Trümmer zur Seite treibt).
- **Verstärkte Schule:** ab Level 2 wird das Gebäude mit **Holzträgern** abgestützt, ab Level 3
  kommen **Stahlträger** dazu, im Finale sogar **Stahlbeton**. Je härter das Material, desto
  stärkeren Sprengstoff brauchst du.
- **💥 Sprengcoins & Shop:** Du startest nur mit **Dynamit**. Für gelungene Sprengungen gibt es
  Coins, mit denen du im Shop nach und nach **TNT**, **C4**, **Thermit** (schmilzt Stahl!) und die
  **Nitro-Megaladung** freischaltest.
- **Levelübersicht** mit Fortschritt, Bestwerten und Sperren.
- **Atombomben-Zünder:** Abdeckung aufklappen, roten Knopf drücken, **3 – 2 – 1 – BOOM** mit
  Countdown, Blitz und Kettenzündung.
- Einsturz-Physik (Auflast + Kragweite), fliegende Trümmer, wachsende Schutthaufen und
  prozedurale Retro-Sounds – **alles in einer einzigen Datei, ohne externe Assets**.

## Steuerung

| Aktion | Tastatur | Maus / Touch |
|---|---|---|
| Ladung wählen | `1`–`5` | Auf die Buttons tippen |
| Ladung setzen | – | auf das Gebäude klicken/tippen |
| Letzte Ladung zurück | `Z` | ↶-Button |
| **Zünder scharf → zünden** | `Leertaste` | Abdeckung öffnen, dann roter Knopf |
| Level neu | `R` | ↺-Button |
| Ton an/aus | `M` | 🔊-Button |
| Zurück zum Menü | – | ☰ Menü |

## Ziel & Taktik

Jedes Level hat ein **Einsturz-Ziel** (z. B. 40 %). Der Profi-Trick der kontrollierten Sprengung:
die Ladungen in einer **Reihe ganz unten** an den tragenden Wänden setzen. Kappst du die untere
Etage, verliert alles darüber den Halt und stürzt ein. Stahlträger überleben Dynamit – dafür
brauchst du **C4** oder **Thermit** aus dem Shop.

## Technik

Pures HTML/CSS/JavaScript in einer einzigen Datei. Pixel-Grafik auf `<canvas>`, Einsturz-Simulation
(senkrechte Auflast + begrenzte Kragweite), Web-Audio-Retro-Sounds, `localStorage` für den
Fortschritt. Kein Build, keine Abhängigkeiten.
