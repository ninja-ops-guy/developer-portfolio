# developer-portfolio

> **Deprecated** — this CRT-terminal portfolio is superseded by **[theemrld-portfolio](https://github.com/ninja-ops-guy/theemrld-portfolio)** ([live site](https://ninja-ops-guy.github.io/theemrld-portfolio/)). This repo is kept for archive only and is no longer updated.

---

CRT terminal-style developer portfolio — phosphor green on black, boot sequence,
typewriter hero with leetspeak glitch, HUD status bar, scanlines/vignette/flicker.

## Stack

Single self-contained `index.html` — no build step, no dependencies.

## Sections

- **Projects** — residual-agent-harness, adversarial-clothing-pipeline, techops-hero, theemrld-portfolio
- **Skills** — offensive/defensive security, CCNA networking (Cisco), engineering, proficiency bars
- **Music** — raikouno tracks (SoundCloud)
- **Contact** — GitHub / SoundCloud / TryHackMe / research portfolio

## Run

Open `index.html` in a browser, or serve statically:

```bash
python3 -m http.server 8000
```

## Accessibility

Respects `prefers-reduced-motion` (disables boot animation, flicker, glitch).
