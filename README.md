# Dominik Lohmar - Web App

Elegante Linktree-aehnliche Web App fuer Zauberkuenstler Dominik Lohmar.

## Features
- Oeffentliche Links (Social Media, Website)
- Passwortgeschuetzte Bereiche (VIP, Promo, Presse)
- Geheimes Admin-Menue (5x auf Logo klicken)
- PWA - auf dem iPhone Homescreen installierbar
- Einstellungen werden lokal gespeichert (localStorage)

## Deployment auf Vercel

### Option A - GitHub + Vercel (empfohlen)

1. Erstelle ein neues GitHub Repository (z.B. dominik-lohmar-app)
2. Lade alle Dateien hoch (Ordnerstruktur beibehalten):
   dominik-lohmar-app/
   - public/index.html
   - public/manifest.json
   - public/icon.png
   - public/icon-192.png
   - public/icon-512.png
   - public/apple-touch-icon.png
   - vercel.json
   - .gitignore
   - README.md

3. Gehe zu vercel.com > Add New Project
4. Verbinde GitHub und waehle das Repository
5. Klicke auf Deploy - fertig!

### Option B - Drag & Drop auf Vercel

1. Gehe zu vercel.com/new
2. Ziehe den gesamten Ordner in das Upload-Feld
3. Klicke auf Deploy

## PWA auf dem iPhone installieren

1. Oeffne die Vercel-URL in Safari
2. Tippe auf das Teilen-Symbol (unten Mitte)
3. Waehle "Zum Home-Bildschirm"
4. Die App erscheint mit dem goldenen Logo auf dem Homescreen

## Admin-Bereich

5x auf das Logo oder den Namen tippen - Admin-Panel oeffnet sich
Dort koennen Links, Untertitel, URLs und Passwoerter bearbeitet werden.

## Standard-Passwoerter

| Bereich         | Passwort |
|-----------------|----------|
| VIP-Backstage   | vip2026  |
| Aktions-Angebot | magic50  |
| Pressematerial  | press24  |

Passwoerter koennen jederzeit im Admin-Bereich geaendert werden.
