 Lyons Haulage — Operations Hub

Live operational website for Lyons Haulage Ltd (Barnham & Selsey).
Hosted on Netlify with an admin panel for editing content without touching code.

## Live site structure

```
/                       Home — notices, weather, road incidents
/driving.html           Driving section
/training-guides.html   Training guide library (upload via admin)
/new-staff.html         New staff inductions hub
/links.html             External links (DVLA, Tachomaster, Sage HR, Maps)
/admin/                 ⚙️ Admin panel — edit notices & upload guides
/tools/
  driver-assessment.html    ✅ LIVE
  staff-induction.html      🔜 Placeholder
  agency-induction.html     🔜 Placeholder
```

## Setup — 15 minutes

### 1. GitHub
1. Create free account at github.com
2. New repository → name: `lyons-ops` → Public → Create
3. Upload all files (drag entire folder contents) → Commit

### 2. Netlify
1. Go to netlify.com → Sign up free (use your GitHub account)
2. "Add new site" → "Import an existing project" → GitHub → select `lyons-ops`
3. Build settings: leave blank (static site) → Deploy site
4. Site is live at `https://lyons-ops.netlify.app` (or rename it in Site Settings)

### 3. Enable admin panel (Netlify Identity + Git Gateway)
1. In Netlify dashboard → **Identity** → Enable Identity
2. Set Registration: **Invite only**
3. Go to **Settings → Identity → Services → Git Gateway** → Enable Git Gateway
4. Invite yourself: Identity tab → Invite users → your email
5. Accept the email invite → set your password
6. Go to `https://lyons-ops.netlify.app/admin` → log in → you can now post notices and upload guides

## Adding forms (when ready)
Replace the placeholder files in `/tools/` with the digitised form HTML.
Update the card on `new-staff.html`: remove class `soon` and update the status to Live.
