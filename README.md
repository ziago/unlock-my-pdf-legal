# unlock-my-pdf-legal

Legal pages for the **Unlock my PDF** iOS app, hosted on GitHub Pages.

## Live URLs

- **Privacy Policy**: https://ziago.github.io/unlock-my-pdf-legal/privacy/
- **Terms of Service**: https://ziago.github.io/unlock-my-pdf-legal/terms/

These URLs must be entered in **App Store Connect → App Information → Privacy Policy URL**.

## Structure

```
unlock-my-pdf-legal/
├── index.html          ← redirects to /privacy/
├── privacy/
│   └── index.html      ← Privacy Policy page
└── terms/
    └── index.html      ← Terms of Service page
```

## How to update

Edit `privacy/index.html` or `terms/index.html` directly, then commit and push.
GitHub Pages automatically publishes within a few minutes.
