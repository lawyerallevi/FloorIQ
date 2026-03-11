# CLAUDE.md — FloorIQ

> **Ultimo aggiornamento**: 2026-03-11

---

## Progetto

**Nome**: FloorIQ
**Tipo**: Landing page / Waitlist
**Stack**: HTML/CSS/JS (single-page, no framework)
**Path**: `C:\AI_Projects\lawyer_allevi\FloorIQ`
**Repo**: Git (main branch)
**Cliente**: Islam Boulahdjel (Londra, UK)

---

## Cosa fa

FloorIQ è una piattaforma AI che trasforma i manuali di brand standards in scenari di training interattivi per staff retail premium. Il prodotto:

1. **Upload** del documento brand (PDF/Word/testo)
2. **AI genera** 20-50 scenari di interazione cliente brand-specific
3. **Staff completa** scenari in 5 min su qualsiasi device, con scoring AI
4. **Dashboard** real-time per performance per staff e per topic

**Target**: Brand retail premium (luxury confectionery, premium beverage, jewellery, cosmetics & fragrance)

---

## Stato attuale

- Landing page con waitlist form (no backend collegato)
- Private beta, Londra
- Form submit: attualmente solo UI (nasconde form, mostra success message)
- **TODO**: collegare form a backend (Formspree, Netlify Forms, o custom)

---

## File principali

| File | Descrizione |
|------|-------------|
| `index.html` | Landing page completa (HTML + CSS inline + JS) |
| `generate-og-image.html` | Tool per generare og-image.png (1200x630) |
| `og-image.png` | Immagine OG per WhatsApp/social share (da generare) |

---

## Design

- **Font**: Playfair Display (serif), DM Sans (body), DM Mono (accents)
- **Colori**: `--ink: #0D0D0F`, `--paper: #F5F2EC`, `--gold: #C8972B`, `--gold-lt: #E8C060`
- **Stile**: Dark luxury, noise texture overlay, gold accents
- **Responsive**: breakpoint a 900px

---

## Contatti

- **Founder**: Islam Boulahdjel
- **Email**: lamine.boulahdjel@gmail.com
- **LinkedIn**: linkedin.com/in/islam-mohamed-el-amine-boulahdjel
- **Location**: London, UK
- **Dominio previsto**: flooriq.app

---

## Meta OG (WhatsApp Share)

- `og:title`: "FloorIQ — Brand Training, Reimagined"
- `og:description`: "Turn your brand standards manual into AI-powered training scenarios. Deployed to your team in 24 hours. Built for premium retail."
- `og:image`: `https://flooriq.app/og-image.png` (1200x630px)
- **IMPORTANTE**: Aggiornare URL se il dominio cambia

---

## Note

- Progetto esterno (non RBK/Catholically)
- Path sotto `lawyer_allevi/` (cartella cliente)
- No framework, no build step — tutto inline in index.html
- Per deploy: può andare su Vercel o qualsiasi hosting statico
