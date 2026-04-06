# 🌳 Bettadapura Thangli Family Tree

An interactive family tree web app connecting the Bettadapura and Thangli families across generations. Built with love for family — so everyone can explore, discover, and add to our shared roots.

🌐 **Live app:** [https://sea-turtle-app-cbs39.ondigitalocean.app](https://sea-turtle-app-cbs39.ondigitalocean.app)

---

## Features

- 🌀 **Radial view** — MindNode-style branches spreading from the center
- 📊 **Top-down view** — classic family tree flowing by generation
- 🔍 **Zoom & pan** — explore the full tree freely
- 👤 **Click any person** — see their name, relationship, birthday and family side
- 🎂 **Birthday panel** — upcoming birthdays at a glance
- ➕ **Add family members** — connected live via Supabase
- 🎨 **Color coded** by family side:
  - 🟡 Gold — Bettadapura
  - 🔴 Red — Thangli
  - 🔵 Blue — Banerjee
  - 🟣 Purple — Core / Both

---

## Built With

- HTML5, CSS3, Vanilla JavaScript
- [D3.js v7](https://d3js.org/) — interactive tree visualization
- [Supabase](https://supabase.com/) — database & authentication (free tier)
- [DigitalOcean App Platform](https://www.digitalocean.com/products/app-platform/) — hosting (free static site)

---

## Local Development

No build step needed. Just open `index.html` in your browser or use VS Code Live Server.

```bash
git clone https://github.com/SreenivasBR/bt-family-tree.git
cd bt-family-tree
code .
# Right click index.html → Open with Live Server
```

---

## Deploy

Every push to `main` auto-deploys to DigitalOcean.

```bash
git add .
git commit -m "your message"
git push
# Live in ~2 minutes
```

---

## Roadmap

- [ ] Login with Google / email (Supabase Auth)
- [ ] Edit & delete family members
- [ ] Photo upload per person
- [ ] Search & highlight by name
- [ ] Birthday email reminders
- [ ] Mobile responsive layout
- [ ] Custom domain

---

*Built with HTML, D3.js & Supabase. Our roots run deep. 🌳*
