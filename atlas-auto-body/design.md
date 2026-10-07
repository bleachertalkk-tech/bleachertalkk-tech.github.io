# Atlas Auto Body: design notes

**Brand premise:** your car goes back the way it left the factory. Calm, certain, nothing to sell you twice.

## Color tokens
| Token | Hex | Use |
|---|---|---|
| `--night` | #0D0E11 | photo sections, promise band, footer |
| `--ink` | #16181D | text on light |
| `--canvas` | #F2F1ED | page (never pure white) |
| `--steel` | #5B5E66 | secondary text |
| `--signal` | #FF5A0A | the one accent; only as a fill or on dark (fails AA as text on light) |

## Fonts
Archivo (display: italic 900, wide, ALL CAPS) + Geist (body). Google Fonts.

## Section map
1. Quiet header over the photo; turns light on scroll
2. Edge-to-edge hero (shop floor on desktop, the building at night on phones), "BACK TO FACTORY.", one line, two small pills, tiny caption with live open status
3. Promise band: EVERY DENT | EVERY CLAIM | SINCE 1983
4. Schedule your repair: facts (4.6, 217, 1983, Sat) + "What happened?" options that open the estimate
5. Full-bleed service tiles: Collision repair, then Frame + Dents and scratches side by side, then a plain list (Paint, Auto glass, Rental cars, Insurance claims)
6. How it works: 4 numbered steps
7. All 14 Google reviews, word for word, in a row the visitor scrolls
8. Full-bleed photo band with tiny caption
9. Our work: three shop photos
10. Visit: building, address, hours, directions + call
11. Footer; sticky call bar slides up on phones after the hero

## Borrowed
- Tesla homepage + tesla.com/service: huge edge-to-edge photo heroes, centered short headline, two small pill buttons, lots of space, "schedule service" style option list. (tesla.com returned 403 to automated fetches, so this is from the brief and known layout, not a fresh capture.)
- Nike: full-bleed photo with a tiny caption in the corner.
- Michelin: heavy slanted ALL-CAPS headlines; promise band.
No Tesla, Nike or Michelin names, logos or images on the page.

## Motion
One signature moment: hero photo arrives with a slow scale, then drifts with the scroll. Everything else is still. All of it is off under prefers-reduced-motion.
