# Legal documents (Privacy Policy & Terms of Use)

English versions used for App Store review and in-app display.

## Files

| File | Purpose |
|------|---------|
| [privacy-policy.md](privacy-policy.md) | Privacy Policy |
| [terms-of-use.md](terms-of-use.md) | Terms of Use |

The same files are bundled in the app: `Petivo/Legal/`.

## GitHub (public URLs for App Store)

1. Create a repository (e.g. `github.com/YOUR_USERNAME/Petivo`).
2. Push this project; these files will be at `docs/legal/`.
3. Update `AppConstants.URLs.legalRepositoryBase` in `Petivo/Core/AppConstants.swift` with your repo path (default: `Randemix/Petivo`).
4. Public links (Safari-readable):
   - `https://github.com/Randemix/Petivo/blob/main/docs/legal/privacy-policy.md`
   - `https://github.com/Randemix/Petivo/blob/main/docs/legal/terms-of-use.md`

Apple accepts GitHub `blob` links in App Store Connect if they open in Safari.

### Optional: GitHub Pages

For cleaner URLs (`https://YOUR_USERNAME.github.io/Petivo/privacy`), enable Pages from the `docs/legal` folder or use a `gh-pages` branch with HTML exports.

## Before App Store submission

- [ ] Repository is **public** (or host copies at petivo.app)
- [ ] URLs in App Store Connect match `AppConstants`
- [ ] Privacy Policy URL field in Connect
- [ ] Terms link on paywall and Settings works on a real device

## Contact

Update support email in both documents if it changes from `support@petivo.app`.
