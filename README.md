# Lyons Haulage — Operations Hub

Internal operations tools for Lyons Haulage Ltd (Barnham & Selsey).  
Static website hosted on **GitHub Pages** — no server required, works on any device.

---

## 📁 File structure

```
lyons-ops/
├── index.html                      ← Home dashboard
├── driving-assessment.html         ← Driving Assessment section page
├── inductions.html                 ← Inductions section page
└── tools/
    ├── driver-assessment.html      ✅ LIVE — Driver assessment form
    ├── staff-induction.html        🔜 Placeholder — New employee induction
    └── agency-induction.html       🔜 Placeholder — Agency driver induction
```

---

## 🚀 Getting it live on GitHub Pages (10 minutes)

### 1. Create a GitHub account
[github.com/signup](https://github.com/signup) — free account is fine.

### 2. Create a new repository
- Click **+** → **New repository**
- Name: `lyons-ops`
- Visibility: **Public**
- Click **Create repository**

### 3. Upload files
- Click **Upload files** on your new repo
- Drag in ALL files (index.html, driving-assessment.html, inductions.html, and the whole `tools/` folder)
- Click **Commit changes**

### 4. Enable GitHub Pages
- **Settings** → **Pages** (left sidebar)
- Source: **Deploy from a branch** → branch: `main`, folder: `/ (root)`
- Click **Save**
- Wait ~2 mins → your site is live at `https://YOUR-USERNAME.github.io/lyons-ops/`

---

## ✏️ Adding a new induction form

1. Build the form as a single HTML file (e.g. `staff-induction.html`)
2. Drop it in the `tools/` folder — replacing the placeholder
3. Update the card on `inductions.html`: change `class="tool-card soon"` to `class="tool-card"` and update the status dot/text to "Live"
4. Commit & push — site updates automatically

---

## 📧 Activating email submission (when ready)

The forms are pre-wired for [Formspree](https://formspree.io) (free, no backend needed):
1. Sign up at formspree.io
2. Create a form → copy your form endpoint (looks like `https://formspree.io/f/xxxxxxxx`)
3. In each form file, find `<!-- TODO: FORMSPREE ENDPOINT -->` and replace with your endpoint
4. Completed forms will email straight to your chosen inbox

---

## 💻 Editing locally (recommended)

Install [GitHub Desktop](https://desktop.github.com/), clone the repo, edit files in VS Code (free), then commit & push. Site updates in seconds.
