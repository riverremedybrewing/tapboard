# RRBC Tap Board

Full-screen tap list + ad slides for the River Remedy Brewing Co. taproom TV.

- **Display page:** https://riverremedybrewing.github.io/tapboard/
- **Data + ads:** Google Apps Script project "RRBC Tap Board" in riverremedybrewing@gmail.com
  - Beers come from Untappd for Business today (GoTab later).
  - Ads are the images in the Google Drive folder **RRBC TV Ads** (1920x1080 JPG/PNG).
    - Order: start names with `01`, `02`, ...
    - Auto-expire: add `until 11-28` to the name.
    - Longer/shorter: add `(20s)` to the name.
    - Stop showing: move to the `Archive` subfolder.
- `config.js` holds the Apps Script `/exec` URL. No keys or passwords live in this repo.

On the Fire TV Stick, set Fully Kiosk Browser's Start URL to the display page.
