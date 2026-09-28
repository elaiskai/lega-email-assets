# LEGA C42: Kelnės ar sijonas?

Autumn 2026 outfit newsletter featuring AKORDAS, TAKTAS, SONATA and NATA.

## Files

* `newsletter.html` and `newsletter-hosted.html`: full HTML with public image URLs.
* `newsletter-omnisend.html`: import fragment with styles and email body.
* `newsletter-local.html`: full HTML using relative asset paths.
* `assets/`: original campaign photos.
* `desktop-preview.jpg`: fresh full desktop preview.
* `preview-*.png`: fresh desktop and mobile screenshots, including stripped head CSS variants.
* `qa-automated.json` and `qa-visual.json`: checks tied to the HTML hashes.

## Delivery checks

Browser QA completed at 600, 320, 390 and 430 pixels, with and without head styles and font links. Mobile columns and clickable buttons have been corrected.

Before sending, configure the platform unsubscribe link and send a fresh Omnisend phone test. Browser previews do not verify a real Gmail or Omnisend delivery.

Campaign location: https://github.com/elaiskai/lega-email-assets/tree/main/campaigns/c42-autumn-2026-sets
