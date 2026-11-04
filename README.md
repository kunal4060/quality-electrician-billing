# Quality Electrician — Billing App

Simple billing web app for **Quality Electrician** (electrical contracts & services).
Enter bill details → live professional Tax Invoice preview → download as PDF.

## Use

Open `index.html` in any browser (mobile or desktop). No build step, no server needed.

1. Fill **Bill To** name & address, Invoice No, Invoice Date.
2. Add items (name, quantity, UOM, price/unit). Use **+ Add Item** for more rows.
3. Enter **Advance Received** (if any).
4. Click **Download Bill (PDF)** — the file is named after the customer, e.g. `Shaskiya_Ashramshala.pdf`.

The bill matches the company's Tax Invoice format: logo header, Bill To / Invoice Details,
item table, total, amount in words (Indian numbering), advance & remaining amounts,
declaration and authorized signatory block.

## Files

- `index.html` — the whole app (form + live preview + vector PDF export via local jsPDF)
- `logo.png` — company logo (transparent background, blends into the navy bill header)
- `jspdf.umd.min.js` — PDF library (bundled locally, works offline)

## Live

Hosted with GitHub Pages.
