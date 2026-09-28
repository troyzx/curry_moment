# Curry Moment

A small, mobile-first Curry card machine for the NFC tag on a one-of-one printed card. Tap **Draw a moment** to reveal a Curry highlight; the deck avoids repeats until every regular card has appeared once. A rare 1-in-30 secret friendship card is mixed in too.

## Run it

This is a static site with no build step or dependencies. Open `index.html` in a browser, or publish the repository with GitHub Pages.

## GitHub Pages

The intended URL is:

https://troyzx.github.io/curry_moment/

For a user or organization repository, enable Pages in **Settings → Pages** and choose **Deploy from a branch**, branch `main`, folder `/ (root)`. GitHub may take a few minutes to publish after the setting is saved.

## Notes

- The card selection and seen-card list are stored in the browser's local storage.
- The current artwork is CSS-generated, so the page has no external media dependency and loads quickly on a phone.
- The highlight cards are short captions rather than embedded broadcast footage. Add appropriately licensed media if you want animated clips.
- The friendship card copy can be personalized whenever the trip details are final.
