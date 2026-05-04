# GuitarFlow — Online Gitarrenunterricht Landingpage

Eine elegante, statische Landingpage für Online-Gitarrenunterricht mit Zoom.

## Features

- **Responsives Design** — funktioniert auf Desktop, Tablet und Mobile
- **Kalender-Buchungssystem** — Platzhalter für Calendly Integration
- **Smooth Scrolling** — Navigation durch die Seite
- **FAQ Akkordeon** — interaktive Fragen & Antworten
- **Preistransparent** — klare Preisgestaltung mit 3 Paketen

## Seitenstruktur

1. **Hero** — Haupt-CTA für kostenlose Probestunde
2. **So funktioniert's** — 4-Schritte Erklärung
3. **Kurse** — 3 Level (Anfänger, Aufsteiger, Profis)
4. **Preise** — Probestunde, Einzelstunde, 10er Paket
5. **Testimonials** — 3 Schülerbewertungen
6. **Buchung** — Calendly Kalender Integration
7. **FAQ** — 5 häufige Fragen
8. **Footer** — Links & Social Media

## Calendly Integration

Um den echten Buchungskalender einzubinden:

1. Ersetze den `calendly-placeholder` div mit dem Calendly Inline Widget:

```html
<div class="calendly-inline-widget" data-url="https://calendly.com/DEIN-USERNAME/FREE-TRIAL" style="min-width:320px;height:700px;"></div>
<script type="text/javascript" src="https://assets.calendly.com/assets/external/widget.js" async></script>
```

2. Oder nutze Calendly's WordPress/External Plugin

## Tech Stack

- **Pure HTML5 + CSS3** — kein Framework nötig
- **Vanilla JavaScript** — für Interaktionen
- **Google Fonts** — Outfit & Playfair Display
- **SVG Icons** — inline für Performance

## Deployment

- **GitHub Pages** — gratuita hosting
- **Netlify** — mit Autodeploy
- **Vercel** — alternative Option

## Anpassung

- Farben in CSS Variables (`:root`)
- Preise in der Pricing Section
- Testimonials mit echten Bewertungen
- Lehrer-Foto im Hero einfügen