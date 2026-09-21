# developer-portfolio

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
