# Tax X-Ray

Single-file federal + Ohio + local income tax estimator for W-2 wages plus a Schedule C business. Installable on iPhone via Add to Home Screen.

- All inputs stay on-device (localStorage); export/import as JSON.
- Paystub scan: on-device OCR (Tesseract.js, loaded from jsDelivr on first use); photos are never uploaded. Paste-text mode needs no download.
- Tax figures live in the `TAX_TABLES` object in `index.html`, keyed by year, with sources noted per value.

Estimate only — not tax advice.
