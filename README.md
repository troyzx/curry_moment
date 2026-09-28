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
- The badge is a CSS-built, two-sided metal medallion. Each draw spins it once through 360° and stops; drag horizontally with a mouse or touch to turn it on a fixed axis with momentum. The main card flips between the badge and its matching highlight GIF, so both views fit within a phone screen. GIFs use `object-fit: contain` so square and portrait clips keep their full frame. Reduced-motion preferences are respected.
- Each moment has a distinct GIPHY GIF, a matching badge emblem and keyword, and a source credit link below the highlight title. The badge metal finish changes with rarity: steel for Common, teal silver for Rare, violet for Epic, gold for Legendary, and rose for the 1-in-30 secret card. GIFs stream from their GIPHY pages; the repository does not redistribute the media files.
- GIF source pages are linked in the site for credit and context. Most clips are illustrative Curry or Warriors reactions rather than verified footage of the specific historical play named on the card; the Paris Olympics and Night Night GIFs are the directly themed exceptions.
- The friendship card copy can be personalized whenever the trip details are final.
