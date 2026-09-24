# PivoCloud — Brand Assets

Public mirror of PivoCloud brand assets for agent / integration access. Source of truth lives in the internal design system; this repo exists so that automated tooling, partners, and integrations can fetch stable URLs.

> **All rights reserved. Use only for authorized PivoCloud integrations (partners, design partners, ANPT-linked initiatives, content co-branded with PivoCloud).** For other uses, contact `contact@pivocloud.com`.

## Files

### Logos

**Current (v2 "Interlock", use these).** The mark was redrawn on 2026-09-09 (same
shape, cleaner geometry, heavier round-ended strokes). These are the files that
match pivocloud.com today.

| File | Path | Usage |
|---|---|---|
| `logo.svg` | `logos/v2/logo.svg` | Mark + wordmark, **light grounds** (wordmark in ink `#0B1633`). Text is outlined, no font needed |
| `logo.png` | `logos/v2/logo.png` | Same, 2112x480 transparent PNG. Use this in PDFs and documents |
| `logo-on-dark.svg` | `logos/v2/logo-on-dark.svg` | Mark + wordmark, **dark grounds** (wordmark in white) |
| `logo-on-dark.png` | `logos/v2/logo-on-dark.png` | Same, 2112x480 transparent PNG |
| `mark.svg` | `logos/v2/mark.svg` | Mark only, any ground. The exact geometry the site nav and favicon use |
| `mark.png` | `logos/v2/mark.png` | Mark only, 1024x1024 transparent PNG |

**Legacy (v1, the old traced mark).** Kept at their URLs because published
material hotlinks them. Do not use them in new work.

| File | Path | Usage |
|---|---|---|
| `pivocloud-logo.svg` | `logos/pivocloud-logo.svg` | Old traced mark + wordmark |
| `pivocloud-logo.png` | `logos/pivocloud-logo.png` | Old wordmark + mark, light theme |
| `pivocloud-logo-on-dark.png` | `logos/pivocloud-logo-on-dark.png` | Old wordmark + mark, dark theme |
| `pivocloud-logo-transparent.png` | `logos/pivocloud-logo-transparent.png` | Old wordmark + mark, transparent |
| `pivocloud-mark.png` | `logos/pivocloud-mark.png` | Old mark only, light theme |
| `pivocloud-mark-on-dark.png` | `logos/pivocloud-mark-on-dark.png` | Old mark only, dark theme |

### Tokens (CSS variables)

**Two systems are live. Use `ink-and-signal.css` for anything new.**

| File | Path | Usage |
|---|---|---|
| `ink-and-signal.css` | `css/ink-and-signal.css` | **Current (v2 "Interlock", confirmed 2026-09-07).** White ground, deep navy ink `#0B1633`, `#0057DF` as the action colour, `#00E4FD` as signal, the mark's cyan-to-blue gradient only in the mark and in seams, 45 degree chamfers instead of rounded corners. Bricolage Grotesque (display and body) + Sometype Mono. The file name is historical: it first held "Ink & Signal" (2026-08-31), which Interlock replaced. Old variable and class names still resolve. |
| `colors_and_type.css` | `css/colors_and_type.css` | **Legacy (v1).** The previous dark system. Kept because already-published material links this URL live, and because it still governs the PivoCloud console until its migration. Do not start new work on it. |

Neither file is the origin: the numeric truth for v2 lives in the PivoCloud
application repo (`frontend/src/app/globals.css`), and these are published
mirrors.

## Stable raw URLs

```
https://raw.githubusercontent.com/PivoCloud/brand-assets/main/logos/v2/logo.svg
https://raw.githubusercontent.com/PivoCloud/brand-assets/main/logos/v2/logo.png
https://raw.githubusercontent.com/PivoCloud/brand-assets/main/logos/v2/logo-on-dark.svg
https://raw.githubusercontent.com/PivoCloud/brand-assets/main/logos/v2/logo-on-dark.png
https://raw.githubusercontent.com/PivoCloud/brand-assets/main/logos/v2/mark.svg
https://raw.githubusercontent.com/PivoCloud/brand-assets/main/logos/v2/mark.png
https://raw.githubusercontent.com/PivoCloud/brand-assets/main/css/ink-and-signal.css
https://raw.githubusercontent.com/PivoCloud/brand-assets/main/css/colors_and_type.css
```

Legacy logo URLs (`logos/pivocloud-*.png|svg`) keep working unchanged.

## Quick integration

```html
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,200..800&family=Sometype+Mono:wght@400..700&display=swap">
<link rel="stylesheet" href="https://raw.githubusercontent.com/PivoCloud/brand-assets/main/css/ink-and-signal.css">

<img src="https://raw.githubusercontent.com/PivoCloud/brand-assets/main/logos/v2/logo.svg"
     alt="PivoCloud" height="32">
```

On a white ground use `logos/v2/logo.svg` (or `logo.png` in a PDF). On navy
use `logos/v2/logo-on-dark.*`. The mark alone works on both.

## Full design system

The complete design system (voice and tone, component guidelines, do/don't lists, type scale role classes, motion rules) is documented in the canonical brain page `concepts/notes/pivocloud-design-system` and in the project repo (private).

Note for partners: v2 is live on the pivocloud.com landing. The signed-in
console still shows v1 until its own migration. New co-branded material should
be built on v2 regardless.

## License

Brand assets are proprietary. Logos, wordmark, mark, and visual identity remain the property of PivoCloud / EURL PivoSide. Public hosting in this repo grants **read access for legitimate technical use** (display in integrations, agent automations) — it does not grant rights to modify, re-distribute as part of a different brand, or use in any context that could imply endorsement without authorization.

For any non-trivial use, contact `contact@pivocloud.com`.
