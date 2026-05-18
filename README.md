# ShiftSleeper — Static Marketing Site

Static HTML site for Render hosting. Three pages: home, privacy, terms.

## Deploy on Render

1. Push this folder to a Git repo (GitHub, GitLab, Bitbucket).
2. In Render: New → Static Site.
3. Connect the repo. Render auto-detects `render.yaml`.
4. Or set manually:
   - Build command: leave blank
   - Publish directory: `./` (or `website/` if subfolder)

## Update email + URLs before launch

- Replace `hello@shiftsleeper.app` with your support email.
- Update Privacy/Terms `Last updated` dates as needed.
- Drop a real `favicon.png` into this folder.

## Pages

- `index.html` — landing page
- `privacy.html` — privacy policy (required for App Store)
- `terms.html` — terms of service (required for subscriptions)
- `styles.css` — shared styles
