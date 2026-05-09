# Ummove Deck — Partner Studios

> Pitch deck premium para presentar la propuesta de partnership de Ummove a estudios de fitness. Single-page HTML con Reveal.js + animaciones custom.

Deck standalone, deployable en cualquier hosting estático.

## Stack

- **Reveal.js 5.1.0** (CDN) — engine de slides
- **HTML + CSS puro** — sin build, sin framework
- **Fonts**: DM Sans + Outfit (Google Fonts)
- **Tema**: cyan (#5BC5F2) sobre navy (#0A1628), estética premium con glow effects

## Design system

```css
--cyan: #5BC5F2          /* accent principal */
--navy: #0A1628          /* background */
--navy-mid: #111D30      /* surface */
--white: #F2F5FA         /* texto */
--gray: #7E8A9E          /* texto secundario */
```

Animaciones: `float`, `pulse-glow`, `glow-text`, `slide-up`, `fade-in-up`, `fade-in`.

## Setup

```bash
# No hay build — abre directo
open index.html
```

O sirve estático con cualquier server:

```bash
python3 -m http.server 8000
# o
npx serve .
```

## Deploy

Como es estático, deployable en:
- **Vercel / Netlify**: drag & drop o `vercel --prod`
- **Cloudflare Pages**
- **GitHub Pages**: ya hay `.github.io` configurado en otra org
- **S3 / R2 + CDN**

## Estructura

```
ummove-deck/
├── index.html       # deck completo
└── logo-plain.png   # asset
```

## Uso

Presentación directa con keyboard navigation de Reveal.js:
- `←` / `→` — navegar slides
- `↑` / `↓` — slides verticales (si las hay)
- `f` — fullscreen
- `s` — speaker view
- `Esc` — overview

## Audiencia

Estudios de fitness México que evalúan ser partner studios de Ummove (pase de clases por créditos).
