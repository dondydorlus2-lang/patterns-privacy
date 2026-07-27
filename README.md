# Patterns — Legal & Privacy

Public legal documents for **Patterns** (habit tracker).

| Document | File | Also in app |
|---|---|---|
| Privacy Policy | [privacy.md](./privacy.md) | `/privacy` |
| Terms of Use | [terms.md](./terms.md) | `/terms` |
| Cookie & Local Storage Policy | [cookies.md](./cookies.md) | `/cookies` |

**Effective / last updated:** July 27, 2026  
**Governing law:** State of Missouri, United States  

## Contact

- Support / privacy: **hello@patternshabit.app**
- Alternate: **dondy.dorlus2@gmail.com**
- Privacy alias: **privacy@patternshabit.app** (routes to support until dedicated mailbox is configured)

## Notes

- These documents match the in-app legal pages in the main Patterns app repository (`docs/legal/` and `/terms`, `/privacy`, `/cookies` routes).
- Patterns stores account and habit data on our cloud backend (not "device-only"). Offline cache may keep a temporary copy on your device for sync.
- This repository is for transparency and App Store / Play / web review links. It is **not** a substitute for advice from a licensed Missouri attorney.

## Sync

When legal substance changes, update:

1. This repo (`privacy.md`, `terms.md`, `cookies.md`)
2. The app repo: `docs/legal/*` and `src/pages/{PrivacyPolicy,TermsOfUse,CookiePolicy}.jsx`
3. `src/lib/legalMeta.js` effective dates
