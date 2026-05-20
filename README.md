# KinCircle Legal (public GitHub Pages)

Public static site for **App Store Connect** and **Google Play** legal URLs only.

The KinCircle app source lives in a **private** repository. This repo intentionally contains nothing except these HTML pages.

## Live URLs (after Pages is enabled)

Replace `vijubylaiah` if your GitHub username differs:

| Use | URL |
|-----|-----|
| Support / Marketing | `https://vijubylaiah.github.io/KinCircle-legal/` |
| Privacy Policy | `https://vijubylaiah.github.io/KinCircle-legal/privacy.html` |
| Terms of Service | `https://vijubylaiah.github.io/KinCircle-legal/terms.html` |

Test in Safari (private window): all links must load over HTTPS with no login.

## Enable GitHub Pages

1. Create this repo on GitHub as **Public** named `KinCircle-legal`.
2. Push this folder to `main`.
3. **Settings → Pages → Build and deployment**
4. **Source:** Deploy from a branch
5. **Branch:** `main` → folder **`/ (root)`**
6. Save and wait 1–5 minutes.

## App environment (optional)

In the private app repo `.env` / EAS production:

```env
EXPO_PUBLIC_LEGAL_PRIVACY_URL=https://vijubylaiah.github.io/KinCircle-legal/privacy.html
EXPO_PUBLIC_LEGAL_TERMS_URL=https://vijubylaiah.github.io/KinCircle-legal/terms.html
EXPO_PUBLIC_SUPPORT_EMAIL=viju.bylaiah@gmail.com
```

## Updating legal text

Edit `privacy.html`, `terms.html`, or `index.html` here, commit, and push. Pages redeploys automatically.

Do not copy app code into this repository.
