# Miruro Assets

Scraped from official Miruro domains for MiruroAPI project.

## Sources

- **Official**: https://www.miruro.com (primary hub)
- **Streaming**: https://miruro.tv, https://miruro.to, https://miruro.bz, https://miruro.ru
- **Status**: https://status.miruro.com/status/miruro

## Structure

```
assets/
├── favicons/          # Favicons and app icons
│   ├── icon-dark-1024x1024.svg    # Dark mode SVG favicon
│   ├── icon-light-1024x1024.svg   # Light mode SVG favicon
│   ├── icon-512x512.png           # Main app icon (PNG)
│   ├── favicon.ico                # Classic ICO favicon
│   ├── apple-touch-icon-180x180.png # iOS home screen icon
│   └── maskable-icon-512x512.png  # Android adaptive icon / OG image
├── logos/
│   └── status-logo.png            # Status page logo
├── fonts/             # Inter + FontAwesome subset
│   ├── inter.woff2
│   ├── fa-brands-400.woff2
│   ├── fa-solid-900.woff2
│   └── fa-minimal.css
└── media/             # Testimonial avatars from homepage
    └── *.jpg
```

## Social Links

- Twitter: https://twitter.com/miruro_official
- Discord: https://discord.com/invite/pjsdJp96mY
- Reddit: https://reddit.com/r/miruro

## Notes

- All streaming domains (tv, to, bz, ru) use identical assets
- SVG favicons support dark/light mode via `prefers-color-scheme`
- OG image is `maskable-icon-512x512.png`
