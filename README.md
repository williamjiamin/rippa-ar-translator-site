# R.I.P.P.A. — AR Translator · Website

Public website, Privacy Policy, and Terms of Use for **R.I.P.P.A.** (Realtime Immersive
Polyglot Processing Architect), the AR translator for Apple Vision Pro.

Served via GitHub Pages. App source lives in a separate private repository.

| Page | URL |
|------|-----|
| Marketing | https://williamjiamin.github.io/rippa-ar-translator-site/ |
| Live AR Demo | https://williamjiamin.github.io/rippa-ar-translator-site/demo.html |
| Privacy Policy | https://williamjiamin.github.io/rippa-ar-translator-site/privacy.html |
| Terms of Use | https://williamjiamin.github.io/rippa-ar-translator-site/terms.html |

These URLs are referenced from the App Store Connect listing.

## Translation target scenes (`targets.html`)

Full-screen **source scenes** — realistic foreign-language signs and menus in 9
languages (Japanese, Chinese, Korean, French, German, Spanish, Italian, Arabic,
Russian) — meant to be displayed on a monitor and pointed at with the real
R.I.P.P.A. app on Vision Pro, so the app performs genuine on-device OCR +
translation for a review/App Preview recording. **The pages contain only source
text — no translations.**

- `←` / `→` switch scene, `F` fullscreen, `H` hide all UI (record mode), `Esc` restore UI.
- Text is large/high-contrast for reliable OCR across a room; Arabic is RTL.

### Image credits (backgrounds)
Atmospheric backdrops are public-domain / CC0 fine-art:
- `assets/scenes/cafe_paris.jpg` — Vincent van Gogh, *Café Terrace at Night* (1888) — CC0 / public domain.
- `assets/scenes/japan_wave.jpg` — Katsushika Hokusai, *The Great Wave* — public domain.

All foreign text and layouts are original. No third-party photos, trademarks, or
copyrighted signage are used.

## Demo

`demo.html` is an interactive, scene-based simulation of R.I.P.P.A.'s real-time
AR translation (scan → detect → translate), built for screen-recording an App
Preview / review video. **Record mode** (button, or auto-loops scenes) hides the
UI chrome for clean capture; press **Esc** to exit.

All four scenes (Tokyo, Paris, Bahnhof, night market) are **original illustrations
rendered in CSS/SVG** — no third-party photos, trademarks, or licensed assets — so
the demo is safe to use in App Store marketing and loads reliably offline. Each
scene is image-swappable if a properly-licensed photo is ever preferred.
