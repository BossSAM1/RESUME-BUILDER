# Resume Builder

A free, open-source, phone-first resume builder. No accounts, no server, no tracking.
Everything is saved in your browser on your own device.

## Features

- Edit and Preview tabs designed for one-handed phone use
- Live A4 preview, scaled to fit your screen
- Three templates (Classic, Modern, Compact) and an accent colour
- Save as PDF through the browser's print dialog
- Backup and restore as a JSON file
- Installable as an app and works offline (PWA)

## Run it

It is plain HTML, CSS and JavaScript with no build step.

**Quick test on a computer:** open `index.html` in a browser.
(The offline/install feature needs `http://` or `https://`, not `file://`.)

**Local server:** `python3 -m http.server 8000`, then open `http://localhost:8000`.

## Put it on your phone for free

1. Create a GitHub repository and upload these files.
2. In the repository, go to Settings → Pages → deploy from the `main` branch, root folder.
3. Open the Pages link on your phone.
4. Android Chrome: menu → Install app. iPhone Safari: Share → Add to Home Screen.

Netlify Drop and Cloudflare Pages also work with no configuration.

## Saving the PDF on a phone

Tap **Save as PDF** on the Preview tab. In the print screen:

- **Android (Chrome):** set the destination to "Save as PDF".
- **iPhone (Safari):** pinch-out on the print preview to open it as a PDF, then use Share → Save to Files.

## Known limits

- Data lives in one browser on one device. Use Backup to move it.
- Long resumes flow onto a second page, but page breaks are not tuned.
- Single language, no photo upload.

## Ideas for contributions

- More templates and fonts
- Drag-to-reorder sections
- Extra sections (projects, languages)
- Better page-break handling for PDF export

## License

MIT. See `LICENSE`.
