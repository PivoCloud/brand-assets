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

| File | Path | Usage |
|---|---|---|
| `colors_and_type.css` | `css/colors_and_type.css` | All brand variables — colors, gradient, surfaces, typography, spacing, radius, shadow. Source of truth. |

## Stable raw URLs

```
https://raw.githubusercontent.com/PivoCloud/brand-assets/main/logos/pivocloud-logo.svg
https://raw.githubusercontent.com/PivoCloud/brand-assets/main/logos/pivocloud-logo.png
https://raw.githubusercontent.com/PivoCloud/brand-assets/main/logos/pivocloud-logo-on-dark.png
https://raw.githubusercontent.com/PivoCloud/brand-assets/main/logos/pivocloud-mark.png
https://raw.githubusercontent.com/PivoCloud/brand-assets/main/logos/pivocloud-mark-on-dark.png
https://raw.githubusercontent.com/PivoCloud/brand-assets/main/css/colors_and_type.css
```

## Quick integration

```html
<link rel="stylesheet" href="https://raw.githubusercontent.com/PivoCloud/brand-assets/main/css/colors_and_type.css">

<img src="https://raw.githubusercontent.com/PivoCloud/brand-assets/main/logos/pivocloud-logo-on-dark.png"
     alt="PivoCloud" height="32">
```

## Full design system

The complete design system (voice & tone, component guidelines, do/don't lists, type scale role classes) is documented in the canonical brain page `concepts/notes/pivocloud-design-system` and in the project repo (private).

## License

Brand assets are proprietary. Logos, wordmark, mark, and visual identity remain the property of PivoCloud / EURL PivoSide. Public hosting in this repo grants **read access for legitimate technical use** (display in integrations, agent automations) — it does not grant rights to modify, re-distribute as part of a different brand, or use in any context that could imply endorsement without authorization.

For any non-trivial use, contact `contact@pivocloud.com`.
