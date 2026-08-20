# Glass Price Calculator

A simple offline web application built with plain HTML, CSS and JavaScript.

## Included
- 162 unique priced entries from the supplied price list.
- Category/type selector.
- Thickness selector.
- Product selector with original item number.
- Height × width pricing for Sqft items.
- Inches or feet measurement.
- Quantity pricing for Pcs and Job items.
- Add multiple glass/items to one estimate.
- Remove individual rows or clear the estimate.
- Professional customer details modal before printing.
- A4-friendly professional printed estimate.
- Company name, phone, address and GSTIN settings saved in the browser.
- No server, database or internet connection required.

## How to use
1. Extract the ZIP.
2. Open `index.html` in Chrome, Firefox or Edge.
3. Use **Company** to enter your company's details.
4. Select the glass/category/thickness/product.
5. Enter height and width for Sqft items.
6. Click **Add to Estimate** for each item.
7. Click **Print Estimate**, enter customer details, then print/save as PDF.

## Pricing
For Sqft:
- Inches: `(height × width) / 144 × rate`
- Feet: `height × width × rate`

For Pcs/Job:
- `quantity × rate`

The source data contains some duplicate descriptions with different rates. They are intentionally kept as separate original-number entries.
