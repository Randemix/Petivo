# App Store & in-app legal URLs

**Site (GitHub Pages):** https://randemix.github.io/Petivo/ — source in `Site/`, built by `python3 scripts/build_site.py` from `docs/legal/*.md`.

## Paste into App Store Connect

| Field | URL |
|-------|-----|
| Privacy Policy URL | https://randemix.github.io/Petivo/privacy.html |
| Terms of Use (EULA, optional) | https://randemix.github.io/Petivo/terms.html |
| Support URL | https://randemix.github.io/Petivo/support.html |
| Marketing URL (optional) | https://randemix.github.io/Petivo/ |

## In the app

`Petivo/Core/AppConstants.swift` → `AppConstants.URLs.siteBase`, `privacyPolicy`, `termsOfUse`, `supportEmail`.
Settings → Privacy / Terms show the full text inside the app (bundled `Petivo/Legal/*.md`, offline); "Open online" opens the site.
