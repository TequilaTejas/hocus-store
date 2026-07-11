# Hocus Store

Static creator storefront for Horcus (gift cards & game top-ups). No build step: edit `index.html` directly. `wireframes.html` is a frozen before-reference copy — don't update it unless asked.

## Workflow

- After making any change, serve the site locally and open it in the browser so it can be reviewed:
  - Start the server if it isn't running: `cd ~/projects/hocus-store && nohup python3 -m http.server 8642 >/dev/null 2>&1 & disown`
  - Then `open http://localhost:8642/`
- All styles live in the `<style>` block at the top of `index.html`. Match the existing design tokens (`--brand`, `--surface`, `--line`, `--ease-out`, etc.) instead of hardcoding colors.
- Images go in `assets/`. The live hero banner is `assets/horcus-hero-v2.png`.
