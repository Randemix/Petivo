# App Store & in-app legal URLs

**Repository:** https://github.com/Randemix/Petivo

## Paste into App Store Connect

| Field | URL |
|-------|-----|
| Privacy Policy | https://github.com/Randemix/Petivo/blob/main/docs/legal/privacy-policy.md |
| Terms of Use (if required) | https://github.com/Randemix/Petivo/blob/main/docs/legal/terms-of-use.md |

## In the app (source of truth in code)

`Petivo/Core/AppConstants.swift` → `AppConstants.URLs.privacyPolicy` and `termsOfUse`

## How users see documents

| Place | Behaviour |
|-------|-----------|
| Settings → Privacy / Terms | Full text **inside the app** (bundled `Petivo/Legal/*.md`), works offline |
| Button «Open in Safari» | Rendered markdown on GitHub (`/blob/main/...`) |
| Paywall footer links | Same GitHub URLs (Apple-acceptable) |

Legal text is **English**; UI note says the English version is binding.
