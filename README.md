# Ligero

A fast, lightweight PDF reader for e-ink Android devices, built for the **Boox Go Color 7 (Gen II)**. This repository only hosts test builds; the source code is not public.

## What it does

- **Plans, maps and drawings:** pinch to zoom, drag to pan and double-tap the center, like any PDF reader. When you let go, only the visible area is redrawn sharp.
- **Scanned books:** splits double-page spreads, trims margins and straightens pages.
- **Reflow mode:** lays out a scanned page again with larger text, without OCR and without text errors.
- **Convert to EPUB** with on-device text recognition.
- **Automatic e-ink refresh on Boox:** fast while moving and flipping through pages, clean when you let go.

Compared with NeoReader, the reader that comes with the Boox, using the same AutoCAD plans on the same device, Ligero opens the PDF about 3× faster, turns pages about 2.7× faster and uses 3–5× less memory.

## Install

1. On the device, open the [latest release](../../releases/latest) and download `Ligero-x.y.apk`.
2. Open it. If Android asks, allow installing apps from that source.

Requirements: Android 10 or later and a 64-bit ARM processor (every recent Boox). It is tested on the Go Color 7 Gen II; how it does on other devices is exactly what we want to find out.

### Get updates automatically

Install [Obtainium](https://github.com/ImranR98/Obtainium), tap **Add app** and paste:

```
https://github.com/F-N-LL/ligero-releases
```

It will tell you about each new version and install it over the old one, keeping your books and reading positions.

## Feedback

[Open an issue](../../issues/new/choose): there is a template for bugs and one for ideas. The most useful details are **your device model and the kind of PDF** (scanned, digital, plan...). If the problem happens with a specific file you can share, even better.

The app's interface is in English and Spanish.
