# Prayag Gurukul

Single-page tuition-center website for Classes 1–8 in Prayagraj, Uttar Pradesh.

## Project files

- `index.html` — complete website, including inline CSS, vanilla JavaScript, animated classroom SVG and the supplied teacher photograph.
- `.nojekyll` — tells GitHub Pages to serve the files as a static website.
- `README.md` — this guide.

No framework, package installation or build step is required. No separate image files are needed. Google Fonts are optional external resources; system-font fallbacks are included.

## Preview

Open `index.html` in a browser. English is the default, including when JavaScript is disabled. The Hindi and English buttons switch the page language when JavaScript is enabled. The page remembers the language preference when browser storage is available.

## Confirmed business information

- Center: Prayag Gurukul; established in 2016.
- Teacher: Priya Prajapati.
- Qualifications: B.Sc., M.A., B.Ed. (TET, CTET).
- Teaching experience: 10 years, as supplied by the owner.
- Classes 1–8; all subjects; CBSE, ICSE and UP Board.
- Phone: 8738065791 and 8604634641.
- WhatsApp: 8738065791.
- Address: 543/464 Shahganj, near Durga Pooja Park, Prayagraj, Uttar Pradesh 211003.
- Timings: Monday–Saturday, 9:00 AM–9:00 PM.

The map link searches the supplied address. It is not a verified Google Maps place pin.

## Editing

Edit `index.html` directly. Translated page copy is stored in `data-hi` and `data-en` attributes; keep the initial English HTML text and accessible labels in sync. Contact-routing settings, including both phone numbers and the WhatsApp number, are in the `BUSINESS` object near the bottom. When changing contact details, update the visible HTML, routing settings and structured data. Add a canonical URL and `og:url` only after the production URL is confirmed.

The photo is embedded as a JPEG data URL. The classroom illustration is inline SVG. Animation includes a pause/play control and honors reduced-motion preferences.

## Enquiries and privacy

The form validates input and previews the exact WhatsApp message on the page. Parents can edit the form and regenerate the preview before sharing. WhatsApp opens only when they follow the link, and they must still press Send themselves. This website has no backend and does not store enquiry details. Opening a prefilled link shares its text with WhatsApp. Only the language preference is saved locally.

Never add GitHub tokens, passwords or API secrets to these files. Revoke any token that has been shared in a chat.

## GitHub Pages deployment

Requested repository: https://github.com/satyamkumar260398/piping-engineer

Upload `index.html` and `.nojekyll` to the repository root, keeping existing unrelated files. In GitHub, open **Settings → Pages**, select **Deploy from a branch**, choose the branch containing these files and the **/(root)** folder, then save.

If Pages is enabled for this project repository, its expected URL is:
https://satyamkumar260398.github.io/piping-engineer/

This is an expected URL, not confirmation of a live deployment. Publishing requires a GitHub account with write access to the repository and permission to configure Pages.
