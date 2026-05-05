# Portfolio — Jahaan Chaudhary

> Personal portfolio site. Minimal, fast, deployed on Vercel.
> **Live:** [jahaanchaudhary.vercel.app](https://jahaanchaudhary.vercel.app)

A single-page portfolio built with vanilla HTML, CSS, and JavaScript — no framework, no build step. True-black minimalist palette inspired by editorial design, with a sticky sidebar layout.

---

## Why this exists

Recruiters and hiring managers spend ~60 seconds on a portfolio. This site is built around that constraint:

- **Sticky sidebar** keeps name, role, and navigation visible the entire scroll
- **Projects lead with the problem**, not the tech stack — so a senior engineer can articulate what I've built within 30 seconds
- **Numbers up front** for the things that matter: 1+ year at Infosys, 500+ DSA problems, 25% latency improvement, LeetCode Knight (top 5%)

---

## Design

| | |
|---|---|
| Background | `#0a0a0a` (true black) |
| Card surface | `#141414` |
| Primary text | `#ededed` |
| Muted text | `#a1a1a1` |
| Highlight (hover only) | `#fbbf77` (warm amber) |

**No color is used statically.** The amber highlight only appears on hover and on the cursor spotlight — the page is quiet, but every interaction is rewarded with warmth. Hierarchy comes from typography (Plus Jakarta Sans + Fraunces serif for stat numbers + JetBrains Mono for labels), spacing, and hairlines — not color.

---

## Sections

1. **About** — bio + portrait
2. **Experience** — Infosys (current), Brity Media internship, E-Cell DTU leadership
3. **Featured Projects** — ComplaintIQ, RakhtSathi, CinemaScribe, Sorting Visualizer
4. **Achievements** — LeetCode Knight, Codeforces Specialist, CodeChef 3★, CGPA, latency improvement
5. **Tech Stack** — grouped by category
6. **Contact**

---

## Tech

- **HTML5** + **CSS3** (vanilla, no preprocessor)
- **Vanilla JavaScript** — IntersectionObserver for scroll-active nav, requestAnimationFrame for cursor spotlight
- **Google Fonts** — Plus Jakarta Sans, Fraunces, JetBrains Mono
- **No build step.** Single `index.html` file with embedded CSS and JS. ~60KB unminified.

### Why no framework?

A framework here would be a tax, not a tool. The site has no state management needs, no routing, no API calls. Vanilla JS ships less code, loads faster, and the entire site is one file you can read top-to-bottom in 10 minutes.

---

## Project structure

```
portfolio/
├── index.html              # Everything — markup, styles, scripts
├── README.md               # You are here
└── assets/
    ├── profile.jpg
    ├── complaintiq-dashboard.png
    ├── complaintiq-detail.png
    ├── rakhtsathi.png
    ├── cinemascribe.png
    ├── sorting-visualizer.png
    └── Jahaan_Chaudhary_Resume.pdf
```

---

## Run locally

No dependencies. Two options:

**Just open the file:**
```bash
open index.html      # macOS
start index.html     # Windows
xdg-open index.html  # Linux
```

**Or serve it (recommended — needed for some browsers to load relative paths cleanly):**
```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

---

## Deploy

This site is built to deploy to Vercel in one command:

```bash
npx vercel
```

Or drag the folder onto [vercel.com/new](https://vercel.com/new). Works the same on Netlify, Cloudflare Pages, or GitHub Pages.

---

## Connect

- **Email** — [jahaan.chaudhary01@gmail.com](mailto:jahaan.chaudhary01@gmail.com)
- **LinkedIn** — [in/jahaan-chaudhary-015ba1205](https://www.linkedin.com/in/jahaan-chaudhary-015ba1205/)
- **GitHub** — [@JahaanChaudhary](https://github.com/JahaanChaudhary)
- **LeetCode** — [Knight, top 5%](https://leetcode.com/u/MpTkt43r41/)
- **Codeforces** — [Specialist, 1400+](https://codeforces.com/profile/JC_codescf)

---

Made by Jahaan Chaudhary
