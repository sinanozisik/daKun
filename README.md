# daKun

Public **legal pages** for daKun applications, published with GitHub Pages.
This repository is **not** the Android source (that lives in a separate private repo).

## daKun Health

### Privacy Policy

| Use | URL |
| --- | --- |
| Play Console / store listing (no language hash) | https://sinanozisik.github.io/daKun/health/privacy.html |
| In-app English | https://sinanozisik.github.io/daKun/health/privacy.html#en |
| In-app Turkish | https://sinanozisik.github.io/daKun/health/privacy.html#tr |

### Terms of Use

Play Console has no dedicated terms URL field. Use the hashless URL in the store listing long description when you fill listing copy.

| Use | URL |
| --- | --- |
| Store listing (no language hash) | https://sinanozisik.github.io/daKun/health/terms.html |
| In-app English | https://sinanozisik.github.io/daKun/health/terms.html#en |
| In-app Turkish | https://sinanozisik.github.io/daKun/health/terms.html#tr |

Future apps use the same pattern: `/{app-slug}/privacy.html`, `/{app-slug}/terms.html`.

## Publish

1. Repo **Settings → Pages → Source: GitHub Actions** (once).
2. Push to `main` (or run the **Deploy GitHub Pages** workflow).

Do not put secrets, payment data, or a storefront on this site.
