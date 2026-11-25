# CMO.XYZ favicon and app icons

The primary icon: the black-edge monogram on an Iris `#FF51FF` square. Use these files for favicons, app icons and avatars.

| File | Size | Use |
|---|---|---|
| `cmo-xyz-favicon.svg` | Any | Browser tab icon in modern browsers, and the source for every other size |
| `favicon.ico` | 16, 32, 48 px | Browser tab icon for older browsers |
| `cmo-xyz-favicon-16.png` | 16 px | Browser tab |
| `cmo-xyz-favicon-32.png` | 32 px | Browser tab, bookmarks |
| `cmo-xyz-favicon-48.png` | 48 px | Windows shortcuts |
| `apple-touch-icon.png` | 180 px | iPhone and iPad home screen |
| `cmo-xyz-icon-192.png` | 192 px | Android home screen, web app manifest |
| `cmo-xyz-icon-512.png` | 512 px | Web app manifest, app stores, avatars |

## Website setup

```html
<link rel="icon" href="/favicon.ico" sizes="any">
<link rel="icon" href="/cmo-xyz-favicon.svg" type="image/svg+xml">
<link rel="apple-touch-icon" href="/apple-touch-icon.png">
```

Keep the Iris background. Don't recolor, round off or crop the icon yourself, since phones and browsers add their own corner rounding.
