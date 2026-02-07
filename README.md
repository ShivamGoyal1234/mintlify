# Mintlify — Landing Page Recreation

A static HTML/CSS recreation of the **Mintlify** marketing site — *The Intelligent Documentation Platform*.

---

## 📸 Live Demo 



## 📸 Preview

![Mintlify landing page – desktop](result.png)

## Sections Recreated

| Section | Description |
|--------|-------------|
| **Header / Navigation** | Fixed nav with Mintlify logo, links (Resources, Documentation, Customers, Blog, Pricing), and CTAs (Contact sales, Start for free). Logo and button styles switch on scroll. |
| **Hero** | Top announcement pill (“Self-updating docs with agent suggestions”), main headline “The Intelligent Knowledge Platform”, subheading, email signup form, and hero illustration. |
| **Company Logos** | Horizontal strip of customer logos (Anthropic, Coinbase, Microsoft, HubSpot, Perplexity, X, PayPal, Lovable). |
| **Features — “Built for the intelligence age”** | Intro copy plus two feature cards: **LLMs.txt & MCP** (Built for both people and AI) and **Agent** (Self-updating knowledge management), plus **Assistant** (Intelligent assistance for your users). |
| **Enterprise** | “Enterprise-reinvention” block with “Bring intelligence to enterprise knowledge”, partnership/compliance bullets, Anthropic customer story card, and logo tabs (Anthropic, Coinbase, Perplexity, Zapier, AT&T). |
| **Customers** | “Unlock knowledge for any industry” with a carousel of customer story cards (e.g. Perplexity, X, Kalshi) and prev/next controls. |
| **Final CTA** | “Make documentation your winning advantage” with “Get started for free” / “Get a demo” and links to Pricing and Quick Start. |
| **Footer** | Mintlify logo, social links (X, LinkedIn, GitHub), Explore / Resources / Documentation / Company / Legal columns, security badge, status link, and copyright. |

---

## Fonts

| Font | Usage | Source |
|------|--------|--------|
| **Inter Variable** | Primary UI and body text (weights 100–900) | `https://www.mintlify.com/_next/static/media/InterVariable-s.p.494bb210.ttf` |
| **Mintlify Sans** | Optional brand/display (weights 400–700) | `https://www.mintlify.com/_next/static/media/797e433ab948586e-s.p.dbea232f.woff2` |
| **Geist Mono** | Code and monospace elements | `/fonts/GeistMono-Regular.ttf` (local) |

`body` uses **Inter Variable** with `system-ui` and `-apple-system` fallbacks.

---

## Colors

### Core palette

| Variable | Value | Use |
|----------|--------|-----|
| `--color-background-main` | `#fff` | Page background |
| `--color-background-invert` | `#08090a` | Dark surfaces, scrolled header buttons |
| `--color-text-main` | `#fff` | Primary text on dark (e.g. hero) |
| `--color-text-invert` | `#08090a` | Primary text on light |
| `--color-text-soft` | `rgba(8, 9, 10, 0.8)` | Secondary text |
| `--color-text-sub` | `rgba(8, 9, 10, 0.6)` | Muted text |
| `--color-muted` | `rgba(8, 9, 10, 0.5)` | Low-emphasis text |
| `--color-brand` | `#0c8c5e` | Mint green — CTAs, badges, accents |
| `--color-brand-light` | `#0c8c5e` | Same as brand |

### Borders & surfaces

| Variable | Value |
|----------|--------|
| `--color-border-sub` | `rgba(8, 9, 10, 0.07)` |
| `--color-border-surface` | `rgba(8, 9, 10, 0.05)` |
| `--color-border-soft` | `rgba(8, 9, 10, 0.15)` |
| `--color-background-soft` | `rgba(8, 9, 10, 0.03)` |

### Grays & utility

| Variable | Value |
|----------|--------|
| `--color-gray-100` | `#f3f4f6` |
| `--color-gray-200` | `#e5e7eb` |
| `--color-gray-600` | `#4a5565` |
| `--color-gray-800` | `#1e2939` |
| `--color-black` | `#000` |
| `--color-white` | `#fff` |

---

## Screenshots (Recommended)

Add screenshots of your final output so reviewers can see the result at a glance.

**Suggested captures:**

1. **Full hero** — Header + hero (announcement pill, headline, form, hero image).
2. **Company logos** — Logo strip below hero.
3. **Features** — “Built for the intelligence age” and the two feature cards.
4. **Enterprise** — Enterprise block and customer story card.
5. **Customers** — Customer carousel (one card visible).
6. **Final CTA + Footer** — Bottom CTA and footer.

**How to add them:**


## Project structure

```
mintlify/
├── index.html      # Single-page markup
├── style.css       # All styles (fonts, variables, layout, components)
├── README.md       # This file
├── assets/         # Logos, images, icons, GIFs
│   ├── logo.svg, bg-image.svg, arrow.svg
│   ├── anthropic.svg, coinbase.svg, microsoft.svg, ...
│   ├── image-1.png, image-2.png, image-3.png
│   ├── product-2.gif, backed-logo.png
│   └── ...
└── screenshots/    # (Optional) Add your screenshots here
```

---

## Running locally

Open `index.html` in a browser (e.g. drag into Chrome or use “Open with Live Server” in VS Code). No build step required. Some assets (hero image, fonts) load from Mintlify’s CDN; for full offline use you’d need to mirror those and update URLs.

---