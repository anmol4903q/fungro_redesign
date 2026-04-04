# Funngro Website Redesign

A complete front-end redesign of the [Funngro](https://www.funngro.com) platform — built as a skill assessment task. Three fully responsive HTML pages redesigned from scratch with a consistent design system, modern UI, and audience-specific messaging.

---

## 📁 Project Structure

```
funngro-redesign/
├── index.html     # Main landing page (funngro.com)
├── teen.html         # Teenlancer page (funngro.com/teen)
├── company.html      # Company page (funngro.com/company)
└── README.md
```

---

## 🖥️ Live Preview

Host on GitHub Pages or open any `.html` file directly in your browser — no build step, no dependencies.

---

## ✨ Pages Redesigned

### 1. Homepage — `funngro-homepage-redesign.html`
The original homepage was a near-empty page with 3 buttons. This redesign turns it into a full conversion-focused landing page:
- Full-screen hero with audience segmentation (Teens / Companies / Shelancers)
- Color-coded audience cards routing visitors to the right sub-page
- 3-track "How it works" section — one column per audience
- Shark Tank India section with real images
- Platform metrics, trusted logos, founders section, and final CTA

### 2. Teen Page — `funngro-teen-redesign.html`
Targeted at teenagers aged 13–18 looking to earn their first income:
- Live earnings ticker with real teenlancer success stories
- Hero with floating proof cards (real earnings data)
- Why work in your teens — benefit cards with icons
- All 12 project categories with hover interactions
- 5-step earning process + earnings breakdown card
- Real company and partner logos from Funngro's CDN
- 4 real testimonials with actual photos and names
- FAQ accordion with real Q&A from the site
- Founders section (Payal Jain CEO + Anik Jain CGO) with LinkedIn links
- App Store + Google Play download CTAs

### 3. Company Page — `funngro-company-redesign.html`
Reframed entirely for business decision-makers — every section answers "what does my company gain?":
- Hero with live ROI comparison card (agency cost vs Funngro cost)
- 6 business-case cards (cost saving, speed, Gen-Z insight, scalability, vetting, CSR)
- All 12 services with real prices and links to sample project folders
- Day-by-day project timeline card
- 3 real company testimonials (Monech, Execute Partners, Let's Evolve)
- Full logo grid — partner companies, investors, press
- FAQ for business owners (legalities, quality guarantee, parallel projects)
- Direct contact card with email CTA

---

## 🎨 Design System

All three pages share an identical design system:

| Token | Value | Usage |
|---|---|---|
| `--green` | `#00D084` | Primary brand color, CTAs, accents |
| `--bg` | `#050F0A` | Page background |
| `--surface` | `#0C1A10` | Section backgrounds |
| `--card` | `#0F1E14` | Card backgrounds |
| `--text` | `#E8F5ED` | Body text |
| `--muted` | `#6B8A72` | Secondary text |
| `--gold` | `#F5C842` | Company accent (homepage) |
| `--purple` | `#9B6DFF` | Shelancer accent (homepage) |

**Typography:**
- Display / Headings: [Syne](https://fonts.google.com/specimen/Syne) — 800 weight
- Body / UI: [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) — 300–600 weight

**Components used across all pages:**
- Fixed nav with scroll-triggered backdrop
- Live earnings ticker (CSS animation)
- Scroll fade-in animations (IntersectionObserver)
- Floating hero cards
- FAQ accordion (vanilla JS)
- Real logo images pulled from Funngro's CDN
- Radial glow backgrounds
- Consistent hover states and micro-interactions

---

## 🛠️ Tech Stack

| Technology | Details |
|---|---|
| HTML5 | Semantic markup |
| CSS3 | Custom properties, Grid, Flexbox, animations |
| Vanilla JavaScript | Scroll observer, nav behavior, FAQ accordion |
| Google Fonts | Syne + Plus Jakarta Sans via CDN |
| No frameworks | Zero dependencies, no build tools required |

---

## 🚀 How to Run

site will be live at `https://anmol4903q.github.io/fungro_redesign/`

---

## 📌 Key Design Decisions

- **Dark theme** — matches Funngro's brand energy; energetic but professional
- **Company page is B2B-first** — original page talked about teens; this talks about ROI
- **Homepage routes traffic** — serves as a hub that gets visitors to the right sub-page fast
- **Real data only** — all logos, images, testimonials, and prices pulled from the actual Funngro site
- **No placeholder content** — every card, stat, and quote is from Funngro's real platform

---

## 👤 Author

**Anmol**                        
GitHub: [github.com/anmol4903q](https://github.com/anmol4903q)

---

## 📄 License

This project is a design exercise / skill assessment submission for Funngro. All brand assets, logos, and content belong to [Funngro (Wishbanc Technologies Pvt. Ltd.)](https://www.funngro.com). This redesign is not an official Funngro product.
