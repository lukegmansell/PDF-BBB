# Dossier Builder

Dossier Builder is now a portable offline folder app built for Chromium-based browsers in locked-down environments.

## Folder contents

- `index.html`
- `assets/`
- `libs/`
- `runtime/`

All files are local and loaded with relative paths. No server, install step, or internet connection is required at runtime.

## Setup

1. Keep the full folder together.
2. Open `index.html` by double-clicking it in Edge or Chrome.
3. Use the four tabs to build the queue, review pages, set the cover page, and export the final PDF.

## User flow

1. `Build Bundle`
   Add PDFs and set their order.
2. `Review Bundle`
   Preview source pages and check whether selected pages already contain text.
3. `Cover Page`
   Edit the generated first page.
4. `Pagination`
   Choose numbering and OCR mode, then build and download the merged PDF.

## Notes

- OCR uses the bundled English language model in `runtime/tessdata/eng.traineddata.gz`.
- The app merges PDFs locally, adds the generated cover page, stamps page numbers, and can overlay hidden OCR text onto the output PDF.
- No data leaves the machine while the app is in use.
