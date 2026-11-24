# Mother Cluckers Homestead: sample website

A one-page sample site for **Mother Cluckers Homestead**, a small farm in Columbia Station, Ohio.

## Contact (from the Google Maps listing)

- **Phone / text:** (440) 781-1806
- **Address:** 26198 Crocker Rd, Columbia Station, OH 44028 (Lorain County)
- **Google category:** Farm
- **Hours, website, reviews, photos:** none on the listing
- **Ohio LLC:** "MOTHER CLUCKERS HOMESTEAD LLC, Columbia Station, OH" appears on Bizapedia (filing details were behind a CAPTCHA)

## Sections

1. Sticky header with a tap-to-call button
2. Hero: egg-shaped photo frame, Call and Text buttons, address
3. Info strip: where, phone, "no set hours, reach out first", "what's ready changes with the season"
4. From the coop: "ask about" cards for eggs, birds, and whatever else is ready. These are prompts to call, not product claims.
5. How it works: reach out, hear what's ready, swing by Crocker Road
6. The flock: photo grid (stock, labeled as such)
7. Find us: address, phone, hours "by arrangement", directions, embedded map
8. Call band, then a footer with the data source and photo credit
9. Floating call button on mobile

Sendra tracking: `data-section` is set on the header, every section, and the footer. `data-track` (Call / Text / Directions) is set on every tel:, sms:, and Maps link. The smb.airoxlab.com script is placed before `</body>`.

## Design

- Fonts: Corben (display) and Red Hat Text (body)
- Palette: eggshell cream, yolk yellow, comb red, barn brown, grass green
- Supports light and dark mode

## Data sources

- Google Maps listing, matched by phone: "Mother Cluckers Homestead", Farm, 26198 Crocker Rd, Columbia Station, OH 44028, +1 440-781-1806
- Web search (Google Maps, Bing, WebSearch): no website, Facebook, Instagram, Etsy, or farmers-market listing was found for this business

## Excluded (same pun name, not this business)

- Mother Cluckers Homestead Market, Waynesboro GA (phone 409-504-3851; store, sourdough, apple butter)
- Mother Cluckers Homestead, Farmington MO (Facebook)
- Mother Clucker's Homestead, Valleyview Dr / Enterprise (poultry farm)
- Mother Cluckers restaurants and chicken shops (Columbus OH and elsewhere), @bigmotherclucker, and similar accounts

## Photos

The business has no photos online, so all images are free-license stock from Unsplash. The footer and gallery say they are representative.

| File | Unsplash photo ID |
|---|---|
| img/hens-doorway.jpg | 1553531009-c4605f302b47 |
| img/egg-basket.jpg | 1701252776710-d81bfd7a5806 |
| img/egg-carton.jpg | 1506976785307-8732e854ad03 |
| img/coop-ramp.jpg | 1778621200241-27218b5c7d78 |
| img/speckled-hen.jpg | 1792976737414-61ee31817c41 |
| img/hens-grass.jpg | 1588597989061-b60ad0eefdbf |

Swap in the homestead's own photos when they're available.

## Honesty notes

The site contains no invented products, prices, hours, history, or testimonials. Nothing online confirms what they sell, so the copy invites people to call or text and ask.

## Deploy

Static files. Push to `airoxlab/Mother-Cluckers-Homestead` on `main`, then turn on GitHub Pages (main / root).
