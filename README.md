# CV Workshop

A single-page CV editor that runs entirely in the browser. Edit content and design on the left, see a live paper preview on the right, and export to PDF or DOCX.

**Live:** https://abdullohkariev.github.io/CV-generator/

## Features
- Content and Design tabs with live preview and page-length readout
- PDF export (jsPDF, embedded fonts) and DOCX export (JSZip)
- QR code for a public video/portfolio link
- Autosaves to your browser (localStorage). Nothing is uploaded anywhere.

## Run locally
The PDF export loads fonts via `fetch`, so serve the folder instead of opening the file directly:

```
python -m http.server 8000
```

Then open http://localhost:8000.

## Deploy
Static site, no build step. Enable GitHub Pages (Settings, Pages, deploy from `main`, root).
