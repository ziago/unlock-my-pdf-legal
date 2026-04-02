# unlock-my-pdf-legal

Legal pages for the **Unlock my PDF** iOS app, hosted on GitHub Pages.

## Live URLs

- **Privacy Policy**: https://ziago.github.io/unlock-my-pdf-legal/privacy/
- **Terms of Service**: https://ziago.github.io/unlock-my-pdf-legal/terms/
- **Support** (App Store *Support URL*): https://ziago.github.io/unlock-my-pdf-legal/support/
- **App / marketing** (App Store *Marketing URL*): https://ziago.github.io/unlock-my-pdf-legal/app/

Enter the **Privacy Policy** URL in **App Store Connect → App Information → Privacy Policy URL**.  
Use **Support** and **App** URLs in the version page metadata (*Support URL*, *Marketing URL*) as needed.

## Structure

```
unlock-my-pdf-legal/
├── index.html          ← redirects to /privacy/
├── app/
│   └── index.html      ← short product / App Store link page (marketing URL)
├── privacy/
│   └── index.html      ← Privacy Policy page
├── support/
│   └── index.html      ← contact & FAQ (support URL)
└── terms/
    └── index.html      ← Terms of Service page
```

## How to update

Edit any `*/index.html` as needed, then commit and push.
GitHub Pages automatically publishes within a few minutes.
