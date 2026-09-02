# PivoCloud — Brand Assets

Public mirror of PivoCloud brand assets for agent / integration access. Source of truth lives in the internal design system; this repo exists so that automated tooling, partners, and integrations can fetch stable URLs.

> **All rights reserved. Use only for authorized PivoCloud integrations (partners, design partners, ANPT-linked initiatives, content co-branded with PivoCloud).** For other uses, contact `contact@pivocloud.com`.

## Files

### Logos

| File | Path | Usage |
|---|---|---|
| `pivocloud-logo.svg` | `logos/pivocloud-logo.svg` | Vectoriel, source preferred for scaling |
| `pivocloud-logo.png` | `logos/pivocloud-logo.png` | Wordmark + mark, light theme |
| `pivocloud-logo-on-dark.png` | `logos/pivocloud-logo-on-dark.png` | Wordmark + mark, dark theme |
| `pivocloud-mark.png` | `logos/pivocloud-mark.png` | Mark only, light theme — use ≤ 24px display |
| `pivocloud-mark-on-dark.png` | `logos/pivocloud-mark-on-dark.png` | Mark only, dark theme |

### Tokens (CSS variables)

**Two systems are live. Use `ink-and-signal.css` for anything new.**

| File | Path | Usage |
|---|---|---|
| `ink-and-signal.css` | `css/ink-and-signal.css` | **Current (v2, confirmed 2026-08-31).** Light editorial surfaces, ink-navy type, `#0057DF` as the single action color, `#00E5FA` as a signal accent, dark "vault" panels for evidence. Instrument Serif / Instrument Sans / IBM Plex Mono. Use this for every new integration or co-branded deliverable. |
| `colors_and_type.css` | `css/colors_and_type.css` | **Legacy (v1).** The previous dark system. Kept because already-published material links this URL live, and because it still governs the PivoCloud console until its migration. Do not start new work on it. |

Neither file is the origin: the numeric truth for v2 lives in the PivoCloud
application repo (`frontend/src/app/globals.css`), and these are published
mirrors. The logos are unchanged by v2 and are shared by both systems.

## Stable raw URLs

```
https://raw.githubusercontent.com/PivoCloud/brand-assets/main/logos/pivocloud-logo.svg
https://raw.githubusercontent.com/PivoCloud/brand-assets/main/logos/pivocloud-logo.png
https://raw.githubusercontent.com/PivoCloud/brand-assets/main/logos/pivocloud-logo-on-dark.png
https://raw.githubusercontent.com/PivoCloud/brand-assets/main/logos/pivocloud-mark.png
https://raw.githubusercontent.com/PivoCloud/brand-assets/main/logos/pivocloud-mark-on-dark.png
https://raw.githubusercontent.com/PivoCloud/brand-assets/main/css/ink-and-signal.css
https://raw.githubusercontent.com/PivoCloud/brand-assets/main/css/colors_and_type.css
```

## Quick integration

```html
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Instrument+Serif:ital@0;1&family=Instrument+Sans:wght@400;500;600;700&family=IBM+Plex+Mono:wght@400;500&display=swap">
<link rel="stylesheet" href="https://raw.githubusercontent.com/PivoCloud/brand-assets/main/css/ink-and-signal.css">

<img src="https://raw.githubusercontent.com/PivoCloud/brand-assets/main/logos/pivocloud-logo.svg"
     alt="PivoCloud" height="32">
```

On a light "paper" surface use `pivocloud-logo.svg` or the light-theme PNGs. The
`-on-dark` variants are for the dark "vault" panels.

## Full design system

The complete design system (voice and tone, component guidelines, do/don't lists, type scale role classes, motion rules) is documented in the canonical brain page `concepts/notes/pivocloud-design-system` and in the project repo (private).

Note for partners: v2 was confirmed 2026-08-31 and is rolling out surface by
surface, so `pivocloud.com` may still show v1 on pages not yet migrated. New
co-branded material should be built on v2 regardless.

## License

Brand assets are proprietary. Logos, wordmark, mark, and visual identity remain the property of PivoCloud / EURL PivoSide. Public hosting in this repo grants **read access for legitimate technical use** (display in integrations, agent automations) — it does not grant rights to modify, re-distribute as part of a different brand, or use in any context that could imply endorsement without authorization.

For any non-trivial use, contact `contact@pivocloud.com`.
