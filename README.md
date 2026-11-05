# Deutsch-Spiele

Interaktive Lernspiele für den Deutschunterricht. Jedes Spiel ist ein eigenes Sub-Projekt in einem eigenen Ordner.

| Ordner | Spiel | Thema |
| --- | --- | --- |
| [`zeitformen/`](zeitformen/) | Zeitreise-Express | Zeitformen |
| [`vier-faelle/`](vier-faelle/) | Kommissariat 4 Fälle | Nominativ, Akkusativ, Dativ, Genitiv |

Die `index.html` im Hauptordner ist die Startseite, die auf alle Spiele verlinkt.

Alles sind reine HTML-Seiten ohne Build-Schritt.

## Deployen auf Vercel

**Alle Spiele zusammen:** Repository importieren, Framework «Other», Root Directory unverändert lassen, «Deploy». Die Spiele liegen dann unter `/zeitformen/`, `/vier-faelle/` usw.

**Ein Spiel einzeln:** Dasselbe Repository als weiteres Vercel-Projekt importieren und bei «Root Directory» den Ordner des Spiels wählen, z. B. `zeitformen`. Das Spiel liegt dann direkt unter der eigenen Adresse.

## Neues Spiel hinzufügen

1. Neuen Ordner anlegen, z. B. `mein-spiel/`, mit einer eigenen `index.html`.
2. In der `index.html` im Hauptordner eine Karte mit dem Link `/mein-spiel/` ergänzen.
3. Das Spiel in der Tabelle oben eintragen.
