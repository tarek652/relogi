# Umzugsservice Landingpage (GitHub Pages) → relogi.de

Diese Repository enthält eine schnelle, SEO-fokussierte GitHub-Pages-Landingpage zum Thema **Umzugsservice** (z. B. „Umzugsservice in Berlin“) mit klarer Weiterleitung/CTA zu **https://relogi.de**.

> Ziel: Long-Tail-Suchanfragen abholen (z. B. „Umzugsservice DEINE_STADT“) und Nutzer zu relogi.de führen.

---

## Live-Demo
- GitHub Pages URL: `https://tarek652.github.io/relogi/`
- Ziel-Website: https://relogi.de/

---

## Inhalt
- `index.html` – Landingpage (SEO: Title/Meta, FAQ, Schema.org, CTA)
- `robots.txt` – Robots + Sitemap-Hinweis
- `sitemap.xml` – Einfache Sitemap für GitHub Pages

---

## Setup (GitHub Pages)
1. Repository erstellen (z. B. `umzug-service`).
2. Dateien hochladen: `index.html`, `robots.txt`, `sitemap.xml`.
3. GitHub → **Settings** → **Pages**
   - **Source**: `main` (oder `master`)
   - **Folder**: `/ (root)`
4. Nach dem Speichern ist die Seite erreichbar unter:
   `https://tarek652.github.io/relogi/`

---

## Anpassen (wichtig)
### 1) Stadt/Region ändern
In `index.html` überall `DEINE_STADT` ersetzen, z. B.:
- `Berlin`
- `Hamburg`
- `München`

Empfohlen: pro Stadt eine eigene Seite (siehe „Mehrere Städte“).

### 2) Canonical (wichtig für SEO)
In `index.html` ist ein Canonical gesetzt:
```html
<link rel="canonical" href="https://relogi.de/" />