# WPC Webseite – Prototyp

Klickbarer Entwurf für die GL-Diskussion. **Nicht die offizielle Webseite.**
Alle Seiten haben `noindex` und `robots.txt` sperrt Suchmaschinen.

## Seiten
- `index.html` – Startseite
- `waermepumpe.html` – Erdsonde / Luft / Grundwasser im Vergleich
- `kosten.html` – Kosten & Förderung (gelbe Felder = Platzhalter für WPC-Richtwerte)
- `offerte.html` – eigene Richtofferte in 4 Schritten
- `service.html` – Service, Pikett, Service-Anfrage mit Foto-Upload
- `referenzen.html` + `referenz-grosshoechstetten.html` – Referenzen als Fallstudie
- `kontakt.html` – Standorte

## Auf GitHub Pages veröffentlichen
1. Auf github.com: **New repository** → Name z. B. `wpc-prototyp` → *Public* → Create.
2. **Add file → Upload files** → alle Dateien aus diesem Ordner hineinziehen (inkl. `.nojekyll`) → *Commit changes*.
3. **Settings → Pages** → Source: *Deploy from a branch* → Branch `main`, Ordner `/ (root)` → Save.
4. Nach 1–2 Minuten ist die Seite erreichbar unter `https://<benutzername>.github.io/wpc-prototyp/`.

## Hinweise
- Bilder werden direkt von wpcenter.ch geladen (keine Kopien im Repository).
- Formulare senden nichts ab – sie zeigen nur, wie der Ablauf wäre.
- Strukturierte Daten (schema.org: HVACBusiness, FAQPage) sind auf Start, Wärmepumpe und Kontakt eingebaut.
