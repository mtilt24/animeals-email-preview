# AniMeals — "Two Meals, One Home" Email Campaign Preview

A private, client-facing preview of the 6-email AniMeals donor series for Seniors First, built so the client can review every email and leave feedback in one place before the campaign is loaded into Constant Contact.

**Live preview:** _(GitHub Pages link added after deploy)_

## What's here
- `index.html` — the review site: list of all 6 emails, live desktop/mobile preview, and a per-email feedback panel.
- `emails/` — the source HTML emails exactly as they'll be sent.

## For the client
1. Open the live link.
2. Enter your name (top right).
3. Click each email to preview it. Toggle **Desktop / Mobile**.
4. Mark each **Looks good** or **Needs changes** and add notes.
5. Hit **Send all feedback** — it compiles every note into one email back to Michelle. (Notes are also saved in your browser as you go.)

## Notes
- Feedback is stored client-side (localStorage) and only leaves the browser when the reviewer sends or copies it. There is no backend.
- The page is marked `noindex`; it's a private review, not a public page.
- Image assets are hosted on Constant Contact, so previews match the real send.
