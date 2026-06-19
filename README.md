# Lyons Haulage Operations Hub — v3

## File structure
```
index.html                  Home (weather, traffic map, notices)
driving.html                Driving section
training-guides.html        Training library
new-staff.html              Inductions hub
links.html                  External links
tools/
  driver-assessment.html    LIVE - Driver assessment form
  staff-induction.html      Placeholder
  agency-induction.html     Placeholder
admin/                      Decap CMS admin panel
netlify.toml                Netlify config
```

## Deploy to Netlify (replaces old version)
1. Download and unzip this folder
2. Go to your Netlify dashboard → Sites → slhoperations
3. **Deploys** tab → drag the entire unzipped folder onto the deploy dropzone
4. Done — site updates in ~30 seconds

## Enable Admin Panel
1. Netlify dashboard → Identity → Enable
2. Registration: Invite only
3. Settings → Identity → Services → Git Gateway → Enable
4. Invite yourself → accept email → set password
5. Visit slhoperations.netlify.app/admin
