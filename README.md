# MeinRechner24 - Deutschlands große Rechner-Zentrale

Eine umfassende Sammlung von kostenlosen Online-Rechnern für Finanzen, Gesundheit und Alltag.

## Features

- 15+ präzise Rechner
- Modernes Dark Glow / Glassmorphism Design
- Vollständig responsive
- SEO-optimiert
- Keine Werbung

## Deployment auf Vercel

Dieses Projekt kann direkt auf Vercel deployed werden.

### Option 1: Via Vercel CLI (Empfohlen)

1. Installiere Vercel CLI:
```bash
npm i -g vercel
```

2. Login zu Vercel:
```bash
vercel login
```

3. Deploy:
```bash
vercel
```

4. Für Production:
```bash
vercel --prod
```

### Option 2: Via GitHub (Empfohlen für automatische Deployments)

1. Erstelle ein GitHub Repository
2. Push deinen Code:
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/yourusername/meinrechner24.git
git push -u origin main
```

3. Gehe zu [vercel.com](https://vercel.com)
4. Klicke auf "New Project"
5. Importiere dein GitHub Repository
6. Vercel erkennt automatisch die Konfiguration
7. Klicke auf "Deploy"

### Option 3: Via Vercel Dashboard (Drag & Drop)

1. Gehe zu [vercel.com](https://vercel.com) und logge dich ein
2. Klicke auf "Add New Project"
3. Wähle "Upload" oder "Import Git Repository"
4. Falls Upload: Ziehe den Projektordner in das Upload-Feld
5. Klicke auf "Deploy"

## Nach dem Deployment

1. **Domain aktualisieren**: Nach dem Deployment solltest du die URLs in `index.html` aktualisieren:
   - Ersetze `https://meinrechner24.de` mit deiner tatsächlichen Vercel-URL (z.B. `https://meinrechner24.vercel.app`)
   - Oder konfiguriere eine Custom Domain in Vercel

2. **Assets hinzufügen** (optional):
   - Erstelle einen `assets` Ordner
   - Füge `preview.png` (1200x630px) für Social Media hinzu
   - Füge `logo.png` hinzu

## Projektstruktur

```
DE_Umrechner/
├── index.html          # Hauptdatei (Single Page Application)
├── vercel.json         # Vercel Konfiguration
└── README.md          # Diese Datei
```

## Technologien

- Pure HTML/CSS/JavaScript
- Tailwind CSS (via CDN)
- Chart.js (via CDN)

## Lizenz

Alle Rechner dienen nur zu Informationszwecken.

