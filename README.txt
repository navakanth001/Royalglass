PHONE INVENTORY – ONLINE APP + LOCAL DATA

This version is designed to be hosted on any HTTPS static website (for example GitHub Pages, Netlify, or Cloudflare Pages).

IMPORTANT DATA MODEL
- The website files are online.
- Inventory/products/stock remain stored locally in the phone browser using IndexedDB.
- Nothing is uploaded to a cloud database by this app.
- Each device/browser has its own separate inventory.
- Use Backup regularly; clearing browser/site data can remove local inventory.

CAMERA SCANNING
- Camera access normally requires HTTPS (or localhost).
- On Chrome Android, open the HTTPS site and allow camera permission.
- The scanner uses the browser's native BarcodeDetector for Code 128.
- If the browser does not support Code 128 scanning, use manual barcode entry or a supported browser.

HOSTING
1. Upload index.html and this README to a static host.
2. Open the HTTPS URL on the phone.
3. Allow camera permission when prompted.
4. Add products and print labels.

PRINTING
- A4 3-column labels
- 50x25 mm
- 60x30 mm
- 100x50 mm
- 1, 2, 3, 4, 5 or 10 copies

BACKUP
Use the Backup button to download a JSON backup. Restore it on the same device/browser when needed.
