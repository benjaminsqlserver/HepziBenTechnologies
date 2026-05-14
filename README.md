# Hepziben Technologies — Corporate Website

The official website for **HEPZIBEN TECHNOLOGIES LTD** — a Lagos-based, engineering-led technology firm specialising in software development, IT consulting, systems integration, training, digital content, and technology trading.

> *Engineering software. Empowering people.*

---

## Pages

| Page | Purpose |
| --- | --- |
| `index.html` | Home — hero, services overview, why us, founder, industries, featured work, CTA |
| `about.html` | Brand story, mission, vision, values, leadership, company snapshot |
| `services.html` | Detailed breakdown of all six service lines + delivery model |
| `portfolio.html` | Selected open-source and production projects |
| `contact.html` | Contact details and project enquiry form |

## Structure

```
.
├── index.html              # Entry point
├── about.html
├── services.html
├── portfolio.html
├── contact.html
├── css/
│   └── styles.css          # Brand stylesheet (per Brand Guidelines v1.0)
├── js/
│   └── main.js             # Nav toggle, scroll reveal, header shadow
├── assets/
│   ├── logo.svg            # Primary logo lockup
│   └── favicon.svg         # Browser icon
└── README.md
```

## Brand

The visual language follows the **Hepziben Technologies Brand Guidelines v1.0 (May 2026)**:

- **Deep Indigo** `#0F2060` — anchor / primary
- **Midnight** `#08123C` — dark variant
- **Electric Cyan** `#00BCD4` — accent / CTA (used sparingly)
- **Deep Teal** `#0097A7` — accent dark
- **Ink** `#181C28`, **Slate** `#495057`, **Stone** `#6C757D`, **Mist** `#F4F6FA`
- Typography: **Inter** (web), Calibri (Office)
- Voice: clear, confident, warm, concrete — no buzzwords

## Running locally

This is a fully static site — no build step. Just open `index.html` in a browser, or serve the folder:

```bash
# Python 3
python -m http.server 8080

# Node
npx serve .
```

Then visit <http://localhost:8080>.

## Hosting

The site is built as a static, hostable bundle. It will run unchanged on:

- GitHub Pages
- Netlify / Vercel / Cloudflare Pages
- Any static-file web server (IIS, Nginx, Apache)

## Contact

**Hepziben Technologies Ltd**
No. 42, Ademola Oduse Street, Ejigbo, Lagos State, Nigeria
📞 +234 705 187 0773
✉️ benjaminsqlserver@gmail.com

RC 9542149 · TIN 2622449765543 · Incorporated 13 May 2026

---

© 2026 Hepziben Technologies Ltd. All rights reserved.
