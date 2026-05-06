# Ascendanti

Source for [ascendanti.github.io](https://ascendanti.github.io) — the research lab of [Atlas Firm](https://atlasfirm.ca).

## Pages

- **index.html** — lab home; currently active project, archive, premises, contact
- **sovereign.html** — project brief: the eight agents, the loop, the calibrator, the stack
- **ethos.html** — the six premises in long form: local-first, bounded, traceable, self-auditing, seamful, infinite
- **reflections.html** — short notes from the bench: the death of the single call, on audits, sovereign mind vs extended mind, etc.
- **address.html** — address delivered at the cutover from the legacy single-call pipeline to Sovereign
- **archive/plato/** — predecessor project, preserved

## Active project

**Sovereign** — multi-agent research-paper authoring system. Local-first, span-traced, self-auditing. Eight specialised agents coordinated through an orchestrator that scores its own output against a 2,401-paper IS/APSR golden set.

## Design

- Static HTML, single shared `style.css`, no build step
- EB Garamond + JetBrains Mono via Google Fonts (one stylesheet link)
- Light + dark via `prefers-color-scheme`
- Editorial typography: hairline rules, drop caps, italic display, section numerals
- Deploys as GitHub Pages on push to `main`
