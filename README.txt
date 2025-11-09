SkillEd Pro — Dual Build (HTML + Preact 'React-like')

Folders:
 - html_version : simple static HTML/CSS/JS PWA demo
 - react_version : single-file Preact+HTM app (no build required) - mimics React
 - common_icons : icons used

How to preview:
 - Serve either folder with a static server for full PWA behavior (service worker and manifest require HTTPS or localhost).
 - Example: python3 -m http.server 8000
 - Then open http://localhost:8000/html_version or /react_version

Deploy to Vercel:
 - Unzip and drag the entire SkillEd_Pro folder to Vercel dashboard. Pick the folder you want to deploy.

Admin:
 - Admin access via Ctrl+A. Password: 123

Notes:
 - Logo generation was postponed; placeholder icons included.
 - Both versions include splash screen, glowing Start Learning button, and Admin panel.
