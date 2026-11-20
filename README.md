# RSD Nexus: Showcase

Public-facing showcase for **RSD Nexus**, a mobile CRM for real-estate sales teams, built for Radhaswami Developers.

This repository holds only presentation material. The app's source code, Firebase configuration and real data live in the private `RSD_nexus` repository and are not copied here.

## Contents

| Path | What |
|---|---|
| `index.html`, `style.css` | Static one-page site (no build step) |
| `assets/screens/` | App screenshots, **redacted**: names, phone numbers, faces and sign-up keys blurred or covered |
| `assets/logo.png` | Brand logo |

## View locally

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

## Publishing

It's plain static files. Enable GitHub Pages (branch → `/ (root)`) or drop the folder on any static host.

## Adding screenshots: redaction checklist

Before adding a new screenshot, cover or blur:

- Personal names (lead names, team members, assignees)
- Phone numbers and emails
- Profile photos and initials avatars
- Team sign-up keys, tokens and project IDs
- Anything from the status bar you don't want public
