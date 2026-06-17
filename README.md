# TFP Bau – Mietpark Hagenow · Website

Statische Website (eine Seite + Impressum + Datenschutz) für **TFP Bau Mietpark Hagenow**,
veröffentlicht über **GitHub Pages** unter **https://www.tfpbau-mietpark-hagenow.de**.

## Inhalt
| Datei | Zweck |
|-------|-------|
| `index.html` | Startseite (Hero, Mietpark, Vorteile, Über uns, FAQ, Kontakt) |
| `impressum.html` | Pflicht-Impressum (D) — Platzhalter mit ⚠️ markiert |
| `datenschutz.html` | Datenschutzerklärung (DSGVO) — Platzhalter mit ⚠️ markiert |
| `assets/firmenschild.jpg` | Foto des Firmenschilds (Branding-Vorlage / Standortbild) |
| `assets/mietpark/` | Produktbilder der 39 Vermietartikel (`NN-slug.jpg/.png/.webp`) |
| `CNAME` | Custom-Domain für GitHub Pages |

## Mietpark (Stand: Juni 2026)
- **39 Vermietartikel** mit echten Tagespreisen (Brutto/Tag inkl. MwSt., teils „VB" / „ab" / Monatsmiete).
- Sortiert in **9 Kategorien** mit Filter-Leiste (Vanilla-JS): Bagger · Radlader & Teleskoplader ·
  Arbeitsbühnen · Sägen & Schneiden · Schleifen, Fräsen & Verdichten · Garten & Forst ·
  Transport & Heben · Strom & Baustelle · Anhänger & Transporter.
- Datenquelle: Ordner `Ergebnis Recherche Anzeigen Vermietung/` (Kleinanzeigen-Inventar + Bildrecherche).
- Klick auf „Verfügbarkeit anfragen" trägt das gewählte Gerät ins Anfrageformular ein
  (Hidden-Feld „Gewünschtes Gerät").

## Branding
- Hintergrund hellgrau, Primärfarbe edles Blau (`#1b3c8c`), Gelb (`#ffd11a`) als Akzent.
- Abgeleitet vom Firmenschild des Unternehmens.

## Bearbeiten
Reines HTML/CSS, kein Build nötig. Datei lokal im Browser öffnen oder bei GitHub direkt bearbeiten.
Nach jedem Push auf `main` aktualisiert GitHub Pages die Live-Seite automatisch (1–2 Min.).

## Bildrechte (wichtig)
Die Produktbilder in `assets/mietpark/` sind **recherchierte Hersteller-/Händler- bzw. Stock-Fotos**
und dienen aktuell als beispielhafte Darstellung des jeweiligen Gerätetyps. Sie sind **nicht
automatisch lizenziert**. Vor dem dauerhaften Live-Betrieb sollten sie durch **eigene Fotos** oder
**lizenzierte Bilder** ersetzt werden (Abmahnrisiko in DE). Eigene Fotos sind ohnehin am
wirkungsvollsten — sie zeigen den tatsächlichen Mietpark.

Empfohlen, mit eigenem Foto zu ersetzen (Typ/Maßstab nur näherungsweise getroffen):
- `07-luftentfeuchter`, `18-teleskoplader-kramer-1245` (3D-Render),
  `24-transporter-sprinter-317` (jetzt korrekte weiße Pritsche, aber Händler-Foto mit dezentem Aufbauhersteller-Wasserzeichen),
  `31/34-planenanhaenger…` (ähnliche Plane-Motive), `33-schwerlastanhaenger-35t` (niedrig aufgelöst).

## Noch zu erledigen
- ✅ Echte Tagespreise eingepflegt (Juni 2026).
- ✅ 38 Vermietartikel + Bilder + Kategorie-Filter ergänzt.
- ✅ Bildwechsel (Juni 2026): 7 unpassende Geräte-/Anhänger-Bilder durch modellgenaue Hersteller-/Händlerbilder ersetzt (Magni DAB18RT, Bomag-Rüttelplatte, Lägler-Bodenschleifer, Forst ST6P, WC-Doppelcontainer, Sprinter-Pritsche, Planenanhänger) + neue Card „Takeuchi TB 225" (Preis/Daten noch zu bestätigen).
- Bilder vor Live-Gang prüfen/ersetzen (siehe „Bildrechte").
- Echte Kundenbewertungen (Bewertungs-Sektion wurde bewusst entfernt).
- Impressum & Datenschutz finalisieren (siehe ⚠️-Hinweise).
- Anfrageformular: nutzt FormSubmit (formsubmit.co) → liefert an vermietung@tfpbau-mietpark-hagenow.de; erste Bestätigung nötig.
- Optional: echtes Maschinen-/Teamfoto ergänzen.

Erstellt von **Zukunft mit KI**.
