---
type: assets
tags:
  - save8
  - assets
  - logos
  - icons
  - cards
  - products
  - onboarding
---

# Save8 assets

Logos, icons, card art, product photos and reference screens for Save8 designs and prototypes. Collected from the live site, https://www.save8.ai, starting 12 Oct 2026. Last checked against the folder contents on 31 Oct 2026.

Project rules, tokens and Figma links are in `F:\work\PD- Claude\save8\context\` (start with `general\save8-context.md`).

## Folders

| Folder | What | Format | Source |
|---|---|---|---|
| `logos/stores/` | 22 store logos (list below) | 128×128 PNG | logo.dev, as loaded by save8.ai |
| `logos/banks/` | 8 issuer logos: Axis, Bank of Baroda, HDFC, ICICI Amazon Pay, IndusInd, SBI Card, Standard Chartered, Yes Bank | PNG, about 96×96 | assets.save8.ai (HDFC from the local prototype) |
| `logos/gift-cards/` | 8 gift card tiles: Amazon Fresh, Pay, Prime, Prime 12 months, Shopping; bb now; BigBasket; JioMart | PNG, original size | assets.myhubble.money |
| `logos/save8/` | Save8 wordmark and app icon | PNG (app icon 192×192) | save8.ai |
| `cards/` | 27 credit card images, named `<bank>-<card>` (for example `hdfc-millennia`) | PNG and WebP, one pair per card | `assets.save8.ai/images/cc/<bank>/<slug>.webp` |
| `icons/` | 13 UI icons (list below) | SVG, `currentColor` | Copied from save8.ai markup (Heroicons-style) |
| `icons/3d/` | 17 gift card category icons, `icon3d-<key>.png` | PNG 192×192, trimmed, transparent | save8.ai `/gift-cards/categories/`, normalised 27 Oct 2026 |
| `products/` | Apple iPhone 15 128GB (Black, Blue, Pink) and Sony WH-1000XM5 Black | JPG | Amazon.in product images; Pink from Apple, cropped and whitened |
| `onboarding/` | Onboarding illustration drafts and exports, light and dark (`01-compare`, `02-giftcards`, `03-cards` and so on), plus `screens/` | PNG | Made for the onboarding slides |
| `live-screens/` | Screenshots of the live home page: desktop and mobile, light and dark | PNG | save8.ai |

## Using the files

- **Figma doesn't render WebP.** For fills, use the PNG next to each card image. Keep the WebP for code.
- **Bank logos in the UI:** see `logos/banks/` for the 8 banks that have a logo. AU, HSBC, Kotak, RBL and slice don't have one yet.
- **3D icons** are for gift card categories only. See `save8\context\general\save8-3d-icon-style.md`.
- **Icon families:** UI icons here are the flat Heroicons-style set. See `save8\context\general\save8-icon-system.md` for the illustrated and line families.

## Cards (`cards/`)

AU: altura, ixigo, zenith · Axis: ace, airtel, atlas, flipkart, supermoney · HDFC: infinia, millennia, phonepe-ultimo, pixel-go, pixel-play, regalia-gold, swiggy, tata-neu-infinity · HSBC: live-plus, premier · ICICI: amazon-pay, emeralde-private-metal · IndusInd: tiger · Kotak: 811 · RBL: shoprite · SBI: cashback, phonepe-select-black, simplyclick · slice.

Cards are horizontal except **slice**, which is vertical. Layout rules for both are in `save8\context\tasks\save8-my-cards-select-context.md`.

## Store logos (`logos/stores/`)

| File | Store | Domain |
|---|---|---|
| amazon.png | Amazon | amazon.in |
| bigbasket.png | BigBasket | bigbasket.com |
| bigcmobiles.png | Bigcmobiles | bigcmobiles.com |
| croma.png | Croma | croma.com |
| flipkart.png | Flipkart | flipkart.com |
| girias.png | Girias | giriasindia.com |
| greateastern.png | Great Eastern Retail | greateasternretail.com |
| imagine.png | Imagine | imagineonline.store |
| inspireonline.png | Inspireonline | inspireonline.in |
| instamart.png | Swiggy Instamart | instamart.in |
| iplanet.png | iPlanet | iplanet.one |
| ivenus.png | iVenus | ivenus.in |
| jiomart.png | JioMart | jiomart.com |
| myg.png | Myg | myg.in |
| poorvika.png | Poorvika | poorvika.com |
| reliancedigital.png | Reliance Digital | reliancedigital.in |
| sathya.png | Sathya | sathya.store |
| sathyamobiles.png | Sathya Mobiles | sathyamobiles.com |
| shopsy.png | Shopsy | shopsy.in |
| vasanth.png | Vasanth & Co | vasanthandco.in |
| vijaysales.png | Vijay Sales | vijaysales.com |
| zepto.png | Zepto | zepto.com |

## UI icons (`icons/`)

`close`, `menu`, `more-horizontal`, `chevron-down`, `chevron-down-thin`, `chevron-right`, `chevron-right-thin`, `chevron-up`, `location-pin`, `external-link`, `send-arrow-up`, `card-offer-arrow`, `share`.

They use `currentColor`, so they take the text colour of wherever they're placed. `menu` is the Heroicons "bars-3" icon; save8.ai draws its menu icon with CSS.

## Notes

- Brand logos and card art belong to their companies. Use them for internal design work only.
- The store logos come from logo.dev through save8.ai's key, which only works on save8.ai. That's why they're saved here rather than linked.
- To add a store logo, open it on save8.ai and export it from the Figma file, which already has every logo above applied.
- Two folders, `save8-local\save8-assets` and `save8-search-flow-iphone\save8-assets`, are junctions to this folder, not copies. Don't delete them with a tool that follows links.
- Add new files to the matching folder and update the table above.
