# Glaze Journal

A web app for documenting ceramic glaze combinations and test results.

## Usage

1. Open `index.html` in Chrome or Edge (recommended)
2. Click **New entry** to add a piece
3. Add image, clay type, firing details, and glaze layers
4. Mark result as Good or Bad
5. Use tabs to filter your collection

## Data Storage

Your data is stored in the browser using IndexedDB. This provides large storage capacity (hundreds of MB) and persists across sessions.

## Export & Import

Export your data to back it up or sync across devices.

**Export:**
1. Click **Export**
2. Select or create a folder
3. App saves `data.json` + `images/` folder

**Import:**
1. Click **Import**
2. Select folder containing `data.json`
3. Entries are added to your collection

**Tip:** Export to a Dropbox/iCloud/Google Drive folder for automatic cloud sync.

## Requirements

- **Chrome or Edge** required for export/import (File System Access API)
- Firefox/Safari work for basic usage but lack export/import
- Must be served over HTTPS or localhost (not `file://`)

## Hosting

To host on GitHub Pages:
1. Push to GitHub
2. Settings → Pages → Source: main branch
3. Access at `https://username.github.io/glaze-journal/`
