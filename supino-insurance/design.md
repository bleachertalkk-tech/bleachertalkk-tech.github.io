# Supino Insurance: design notes

**Brand premise:** a neighbor who shops 15+ companies for you. Big-carrier clarity, small-town agency.

## Color tokens
| Token | Hex | Use |
|---|---|---|
| `--ink` | #0E1B33 | text, the "Why Supino" band, footer |
| `--harbor` | #1E4FD8 | hero band, primary pill, tabs |
| `--marigold` | #FFC93C | the one bright word ("covered."), CTA on blue, Massachusetts block |
| `--linen` | #F6F4EE | page canvas (never pure white) |
| `--slate` | #56627A | secondary text |

## Fonts
Bricolage Grotesque (display, 500 to 800) + Figtree (body). Google Fonts.

## Section map
1. Light header: brand, 5 links, phone, one pill "Get a quote"
2. Blue hero: one marigold word, ZIP + "Start my quote", photo bleeding off the right edge with a marigold bar under it (slow settle + scroll drift)
3. Quick-links row: pay a bill, file a claim, had an accident, call Malden, call Lynnfield, email
4. "Get a quote today." tab picker (Vehicle / Property / Personal / Business) with outlined tiles
5. Clickable picture row: Auto, Home, Life, Business, each opens the quote with that line pre-picked
6. Massachusetts block: big rounded marigold card with RMV service, notary, real estate referral
7. Already with us: carrier picker (pay / claim links) + accident steps
8. Why Supino: 35+ / 15+ / 2, family story, Michael's quote
9. Real Google reviews (4, word for word), uneven grid
10. Contact: offices with maps, message form, team extensions
11. Footer + sticky call bar on phones

## Borrowed
- GEICO: blue band hero with one bright color word; photo card bleeding right with an accent bar; "Get a quote today." tabbed tile picker; big rounded color block.
- State Farm: clean light header with a single pill CTA; quick-links row for existing customers.
- Pinterest/Dribbble "insurance website" boards: picture cards that act as product doors.
No GEICO or State Farm names, logos, mascots or images on the page.

## Images
Only the photos already in `images/` (StockSnap CC0, swap for real Supino photos when available). Auto and Business cards use flat SVG drawings in the brand colors, not photos.
