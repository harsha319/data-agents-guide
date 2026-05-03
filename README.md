# AI & BI Data Agents 2026

A mobile-friendly, interactive reference guide to the top AI and BI data agents in 2026 — organized by use case.

**Live demo:** Deploy instantly to Vercel (see below)

---

## 📋 Use Cases Covered

| # | Category | Tools |
|---|---|---|
| 1 | 🏗 Pipeline Orchestration & ETL | 4 |
| 2 | 🗂 Data Cataloging | 7 |
| 3 | 🔍 Data Lineage | 6 |
| 4 | 🛡 Data Governance & Compliance | 6 |
| 5 | 💬 NL-to-SQL / Self-Service Analytics | 6 |
| 6 | 📊 BI Copilots & Embedded AI | 8 |
| 7 | 🤖 Autonomous / Agentic Analytics | 6 |

**Total: 43 tools covered**

---

## 🚀 Deploy to Vercel

### Option 1 — One-click (recommended)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/YOUR_USERNAME/data-agents-guide)

> Replace `YOUR_USERNAME` with your GitHub username after pushing.

### Option 2 — Vercel CLI

```bash
# Install Vercel CLI
npm i -g vercel

# Clone and deploy
git clone https://github.com/YOUR_USERNAME/data-agents-guide.git
cd data-agents-guide
vercel
```

Follow the prompts. Your site will be live at `https://data-agents-guide.vercel.app` (or your custom domain).

### Option 3 — Vercel Dashboard

1. Go to [vercel.com/new](https://vercel.com/new)
2. Import this GitHub repository
3. Leave all settings as default — Vercel auto-detects static HTML
4. Click **Deploy**

---

## 🖥 Run Locally

No build step required. It's plain HTML/CSS/JS.

```bash
git clone https://github.com/YOUR_USERNAME/data-agents-guide.git
cd data-agents-guide

# Option A: Python
python3 -m http.server 3000

# Option B: Node
npx serve .

# Option C: VS Code
# Install "Live Server" extension → right-click index.html → Open with Live Server
```

Open `http://localhost:3000` in your browser.

---

## 📁 Project Structure

```
data-agents-guide/
├── index.html      # Full app — single self-contained file
├── vercel.json     # Vercel deployment config
└── README.md       # This file
```

No dependencies. No build step. No npm install. Just HTML.

---

## ✨ Features

- **Filter tabs** — tap to view tools by use case category
- **Mobile-first** — optimized for phone screens, works on desktop too
- **Color-coded cards** — each category has a distinct accent color
- **Stats banner** — key 2026 market figures at a glance
- **Insight panel** — the single most important trend for 2026
- **Animations** — smooth card entrance animations on filter switch
- **Zero dependencies** — Google Fonts only (loaded via CDN)

---

## 🛠 Customization

All content lives in `index.html`. To add or edit a tool:

```html
<div class="tool-card">
  <div class="tool-card-top">
    <div class="tool-name">Your Tool Name</div>
    <div class="tool-badge">Badge Label</div>
  </div>
  <div class="tool-desc">Your description here.</div>
</div>
```

To add an open-source badge, add the `oss` class:
```html
<div class="tool-badge oss">Open Source</div>
```

---

## 📄 License

MIT — free to use, fork, and deploy.
