# Google Sheet Template for Pasargad Website

Use this file as a guide to build the Google Sheet that powers `Mahi.html`.

## Sheet layout
Create a public Google Sheet with one sheet tab. Use these column headers in row 1:

- `title`
- `image`
- `description`
- `link`

## Example rows

| title | image | description | link |
|---|---|---|---|
| Gate of All Nations | https://images.metmuseum.org/CRDImages/an/web-large/DP-37584-001.jpg | The Gate of All Nations at Persepolis was the ceremonial entrance for foreign envoys. | https://www.metmuseum.org/art/collection/search/324042 |
| Audience Hall (Apadana) | https://images.metmuseum.org/CRDImages/an/web-large/DP226593.jpg | The Apadana was the hall where the Great King received tribute and held public ceremonies. | https://www.metmuseum.org/art/collection/search/323178 |

## How to publish the sheet
1. Open your Google Sheet.
2. Click `File` → `Share` → `Publish to web`.
3. Choose the sheet tab and publish it.
4. Copy the sheet ID from the URL.
   - Example: `https://docs.google.com/spreadsheets/d/1VBVZlviaFWJ0L2JX4A2HyWmc30UwDqUTb3RlgLkORWA/edit`
   - The sheet ID is the long part after `/d/` and before `/edit`.
5. Paste the sheet ID into the `Google Sheet ID` field on `Mahi.html` and click `Load sheet data`.

## Notes
- The page expects the first row to be the header row.
- The `image` field should contain a direct image URL.
- If the sheet cannot load, the page will show default MET Museum cards instead.
