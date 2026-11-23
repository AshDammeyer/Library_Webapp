# 📚 Bibliotheks-Quest

Ein kleines Browser-Spiel: Laufe durch die Bibliothek, löse in drei Leveln je zwei kleine Aufgaben und eine große Abschlussaufgabe und sammle XP.

| Level | Schwierigkeit | Aufgaben (XP) |
|-------|---------------|---------------|
| 1 – Das Foyer | ★☆☆ | 10 · 10 · 30 |
| 2 – Die Lesesäle | ★★☆ | 20 · 20 · 50 |
| 3 – Das Geheimarchiv | ★★★ | 30 · 30 · 80 |

Insgesamt gibt es 280 XP. Die große Aufgabe ist erst freigeschaltet, wenn beide kleinen Aufgaben erledigt sind.

**Steuerung:** Pfeiltasten oder WASD am Computer, Steuerkreuz auf dem Handy.

## Auf GitHub veröffentlichen

1. Neues Repository auf GitHub anlegen, z. B. `bibliotheks-quest`.
2. `index.html` und `README.md` hochladen (Button *Add file → Upload files*).
3. Im Repository: **Settings → Pages → Build and deployment**. Bei *Source* „Deploy from a branch“ wählen, Branch `main`, Ordner `/ (root)`, dann *Save*.
4. Nach ca. 1–2 Minuten ist das Spiel erreichbar unter:
   `https://<DEIN-GITHUB-NAME>.github.io/bibliotheks-quest/`

## QR-Code erstellen

Erzeuge einen QR-Code für die URL aus Schritt 4, zum Beispiel:

- online mit einem beliebigen QR-Code-Generator (URL einfügen, PNG oder SVG herunterladen), oder
- lokal per Terminal: `pip install qrcode[pil]` und dann
  `qr "https://<DEIN-GITHUB-NAME>.github.io/bibliotheks-quest/" > qr.png`

Den QR-Code kannst du anschließend ins Repository legen und mit `![QR-Code](qr.png)` in dieser README anzeigen.

## Anpassen

Alle Level, Karten und Aufgaben stehen oben in `index.html` im Array `LEVELS`. Dort kannst du Fragen, Antworten und XP-Werte ändern.
