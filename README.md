# 3D Assets Credits

Automated credit collection for Creative Commons 3D models used in our video productions.

- **Live page**: https://welcomepack01.github.io/3d-credits/
- Credits are added automatically via Chrome extension when downloading from Sketchfab.

## How it works

1. Chrome extension detects Sketchfab model page
2. One-click "Add Credit" button parses title/author/license/URL
3. Pushed to this repository's `credits.json`
4. GitHub Pages renders `index.html` with searchable table

## Data structure

```json
[
  {
    "title": "Road Barrier",
    "author": "Sousinho",
    "license": "CC Attribution 4.0",
    "licenseCode": "CC BY",
    "url": "https://sketchfab.com/3d-models/xxxxx",
    "addedAt": "2026-04-22T10:30:00.000Z"
  }
]
```
