# Agent notes for this repo (not published: dot folders are not served by GitHub Pages)

## Modern Web Guidance (front-end code)
Added 24 Nov 2026 at Eytan's request.
- Before writing or changing HTML, CSS or browser JavaScript, use the modern-web-guidance skill (.claude/skills/modern-web-guidance/SKILL.md; the same file is in .agents/skills/ for Codex). Not for back end, data, CI or scripts.
- Run it pinned, with Google's usage reporting off: DISABLE_TELEMETRY=1 npx -y modern-web-guidance@1.0.2 search "<query>", then retrieve "<id>". Never @latest. Never put our business, client, guest or place names in a query.
- Browser support: Baseline Widely available features are fine without fallbacks; anything newer only with the fallback the guide gives. A stricter rule already in this repo wins.
- This repo's own rules, design system and deploy rules come first. The guidance never justifies a redesign, a new dependency or a change nobody asked for. Do not run legacy-scan or modernise code unless Eytan asks.
