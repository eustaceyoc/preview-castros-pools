# Castro's Pool & General Contractors: sample site

A one-page sample site I put together for Castro's Pool & General Contractors (Grand Prairie, TX). It's a concept, not their official website, and it says so at the top of the page and in the footer.

Live preview: https://preview-castros-pools.vercel.app

The request form doesn't send anything to a server. It just opens your own email app with a message addressed to joecastrospool@gmail.com, and the phone buttons dial (800) 807-1363 or (469) 735-2988. There's no tracking or analytics, and the fonts are self-hosted.

## What's on the page

Only details from Castro's Pool & General Contractors's own website and public listings: business name, owner Joe Castro, Grand Prairie address, both phone numbers, email, hours, and the services and new-build steps listed on castrospools.com. Anything I couldn't confirm is left out or marked to be confirmed. There are no reviews, ratings, prices, years in business or team photos.

## Photos

Stock photos from Pexels, used under the Pexels License (https://www.pexels.com/license/). They're there for mood. None of them shows Castro's Pool & General Contractors, its people or its work.

- `backyard-build.jpg`: "Backyard Patio Construction in Texas Home" by Ryan  Stephens on Pexels (https://www.pexels.com/photo/backyard-patio-construction-in-texas-home-33404224/)
- `drained-pool.jpg`: "Abandoned Empty Pool" by Strange Happenings on Pexels (https://www.pexels.com/photo/abandoned-empty-pool-11757136/)
- `finished-pool.jpg`: "Large Poolside Shed in Summer" by Max Vakhtbovych on Pexels (https://www.pexels.com/photo/large-poolside-shed-in-summer-8143667/)

Fonts: Oswald, Rubik (Google Fonts, SIL Open Font License). Full details are in `assets/provenance.json`.

## Indexing

The page has `noindex, nofollow` in a meta tag and in the `X-Robots-Tag` header (`vercel.json`), and `robots.txt` disallows everything, so it shouldn't turn up in search.

Eustace Crentsil
