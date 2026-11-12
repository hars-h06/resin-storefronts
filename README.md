# AuraResin / Resinora — Render deployment

This bundle contains two standalone HTML pages:

- `index.html` — AuraResin Studio (copied from 1.html)
- `resinora.html` — Resinora (copied from 2.html)

## Deploy both on one Render Static Site

1. Create a GitHub repository, for example `resin-storefronts`.
2. Extract this ZIP and upload `index.html`, `resinora.html`, and this README to the repository root.
3. In Render, choose **New + → Static Site** and connect that GitHub repository.
4. Set:
   - Build Command: leave blank
   - Publish Directory: `.`
5. Click **Create Static Site**.

After deployment:
- First site: `https://YOUR-RENDER-SITE.onrender.com/`
- Second site: `https://YOUR-RENDER-SITE.onrender.com/resinora.html`

These are static frontend pages. Real payments, order storage, login, and admin features need a backend/payment integration if the HTML only simulates them.
