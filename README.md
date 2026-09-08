# Der Kümmerer im Oberland – Webseite

Statische Webseite für **Der Kümmerer im Oberland** – Reparaturen & Hilfe im Alltag.

**Live-Version:** https://DEIN-BENUTZERNAME.github.io/der-kuemmerer/

## Was ist drin?

- 9 fertige HTML-Seiten (Start, Über uns, Leistungen, Für wen, Bike-Service, Einsatzgebiet, Mehr Infos, Kontakt, Impressum)
- Ordner `images/` mit allen Bildern
- `sitemap.xml` und `robots.txt` für Suchmaschinen
- `SEO-Anleitung.md` mit den nächsten SEO-Schritten

## Deployment über GitHub Pages – Schritt für Schritt

1. Neues **öffentliches** Repository auf GitHub anlegen, z. B. `der-kuemmerer`
2. Alle Dateien aus diesem Ordner hochladen (Drag & Drop im Browser reicht)
3. Im Repository: **Settings → Pages**
4. Bei "Build and deployment" → Source: **Deploy from a branch**
5. Branch: **main**, Ordner: **/ (root)** → **Save**
6. Nach 1–2 Minuten ist die Seite unter der oben genannten URL erreichbar

## Eigene Domain verbinden (optional, empfohlen)

1. Bei eurem Domain-Anbieter (z. B. Strato, IONOS): DNS-Eintrag setzen
   - Typ: `CNAME` → Ziel: `DEIN-BENUTZERNAME.github.io`
2. In GitHub: **Settings → Pages → Custom domain** → `www.der-kuemmerer.de` eintragen
3. HTTPS aktivieren (Haken bei "Enforce HTTPS")

## Änderungen machen

- **Text ändern:** HTML-Datei im Browser bei GitHub direkt bearbeiten (Stift-Symbol)
- **Bild austauschen:** neue Datei in `images/` hochladen mit gleichem Namen
- **Neues Bild einbauen:** hochladen und im HTML `<img src="images/dateiname.jpg" alt="…">`

## Technische Details

- **Statisches HTML** – kein Build, kein npm, kein Framework
- **Keine externen Abhängigkeiten** außer Google Fonts (via CDN)
- **Mobile-optimiert**, Ladezeit ~50 KB pro Seite
- **SEO-optimiert** mit Schema.org LocalBusiness, Open-Graph-Tags, FAQ-Schema

## Aktuelle Info-Banner deaktivieren

Der Slide-In-Toast oben rechts (zur Icking-Standzeit-Ankündigung) sitzt in
jeder HTML-Datei zwischen `<!-- INFO SLIDE-IN TOAST -->` und dem darauf
folgenden `</script>`. Zum Entfernen: diesen Block in allen 9 Dateien löschen.

## Kontakt

Der Kümmerer im Oberland
82515 Wolfratshausen
Tel: 0155 11441969
info@dein-kuemmerer.de
