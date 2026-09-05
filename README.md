# Vorlage: Handwerker-Website

Basis-Template für Kundenprojekte (Handwerksbetriebe & Kleingewerbe).

## Struktur
- `index.html` – Seitenaufbau (Hero, Leistungen, Über uns, Referenzen, Kontakt)
- `styles.css` – Design (Farben oben in `:root` zentral anpassbar)

## Neue Kundenwebsite erstellen
1. Diesen Ordner kopieren, z. B. nach `03_Website/Kunden/<Kundenname>/`
2. Alle `{{PLATZHALTER}}` in `index.html` durch echte Kundeninhalte ersetzen
3. Akzentfarbe in `styles.css` unter `:root { --color-accent: ... }` anpassen
4. Bilder statt der `image-placeholder`-Boxen einsetzen
5. Auf GitHub pushen und mit Netlify/GitHub Pages verbinden (siehe Business-Plan-Dokument)

## Kontaktformular
Ist bereits für Netlify Forms vorbereitet (`data-netlify="true"`) – funktioniert automatisch,
sobald die Seite über Netlify gehostet wird. Kein eigenes Backend nötig.
