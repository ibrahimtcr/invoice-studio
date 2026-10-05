# Invoice Studio

Browser-only invoice generator: import an invoice PDF or photo, edit, and download a new PDF.
Every import is also kept as a **copied design**: the original page, logo and layout stay exactly as they were, and any text on it can be edited in place.
Photos and scanned PDFs are read on-device with [Tesseract.js](https://github.com/naptha/tesseract.js) (Apache-2.0), served from `ocr/`.
Everything is stored in your own browser (localStorage) — nothing is sent to a server.
Use **Export backup** / **Import backup** to move invoices and saved companies between devices.
