## 2026-10-03 - Bring back the confetti
- Restored the homepage arrival burst and click-to-pop confetti at Simon's request.
- Kept the existing reduced-motion behavior and interactive controls intact.

## 2026-10-03 - Use Simon's clearer storefront photo
- Replaced img-01.jpg and its WebP version with the second supplied photo, showing an unobstructed sign and entrance.
- Updated hero and share previews, preserving the complete frame.

## 2026-10-03 - Put the storefront first
- Replaced the distant street view with a tighter front-facing photo of the sign, entrance, and window balloons.
- Removed the default figure margin so the photo fills its column, and preserved its prepared crop on all screen sizes.
- Updated homepage/contact share previews and the store schema image.

## 2026-10-03 - Make the site easier to use on phones
- Kept the call button inside the mobile header with safe spacing on all main pages.
- Slowed the marquee, restored balloon proportions, and added pause and reduced-motion behavior.
- Clarified Visit & contact navigation and added homepage directions.
- Replaced stale graduation/upcoming-season wording and removed automatic homepage confetti.
- Completed llms.txt, included all three main pages in the sitemap, and linked structured entities.
- Added optimized WebP photo delivery with original JPEG fallback, smaller share images, and intrinsic image dimensions. Corrected the contact-page balloon typo.

## 2026-07-04 — Add Independence Day right-now update
- **Author**: Simon Paige
- **Branch**: main
- **Audit**: PASSED
- **Screenshots**: C:\Users\simon\code\brooksideparty\screenshots\2026-07-04T15-57-24
- **Visual verify**: yes

## 2026-06-24 — Load match-day images eagerly
- **Author**: Simon Paige
- **Branch**: main
- **Audit**: PASSED
- **Screenshots**: C:\Users\simon\code\brooksideparty\screenshots\2026-06-24T19-04-01
- **Visual verify**: yes

## 2026-06-24 — Add Orange Army match-day feature
- **Author**: Simon Paige
- **Branch**: main
- **Audit**: PASSED
- **Screenshots**: C:\Users\simon\code\brooksideparty\screenshots\2026-06-24T18-56-47
- **Visual verify**: yes

## 2026-06-19 — Add another Father's Day photo to seasonal feature
- **Author**: Simon Paige
- **Branch**: main
- **Audit**: PASSED
- **Screenshots**: skipped
- **Visual verify**: yes

## 2026-06-19 — Update seasonal feature for Father's Day and soccer
- **Author**: Simon Paige
- **Branch**: main
- **Audit**: PASSED
- **Screenshots**: skipped
- **Visual verify**: yes

## 2026-05-15 — Fix hours on spookier page to match main floor hours
- **Author**: Simon Paige
- **Branch**: main
- **Audit**: PASSED
- **Screenshots**: C:\Users\simon\code\brooksideparty\screenshots\2026-05-15T22-48-47
- **Visual verify**: yes

## 2026-05-14 — Fix mobile marquee - add will-change: transform for GPU acceleration, fix missing animation name in mobile override (was 12s with no name so animation was dead on mobile)
- **Author**: Simon Paige
- **Branch**: main
- **Audit**: SKIPPED — pre-existing contrast and form label criticals unrelated to marquee fix
- **Screenshots**: C:\Users\simon\code\brooksideparty\screenshots\2026-05-14T13-56-59
- **Visual verify**: yes

## 2026-05-14 — switch contact form from legacy Formspree to our own Cloudflare Worker + Resend
- **Author**: Simon Paige
- **Branch**: main
- **Audit**: PASSED
- **Screenshots**: C:\Users\simon\code\brooksideparty\screenshots\2026-05-14T12-23-18
- **Visual verify**: yes

## 2026-05-14 — speed up mobile marquee from 18s to 12s
- **Author**: Simon Paige
- **Branch**: main
- **Audit**: PASSED
- **Screenshots**: C:\Users\simon\code\brooksideparty\screenshots\2026-05-14T11-28-18
- **Visual verify**: yes

# Changelog - Brookside Party Warehouse

## 2026-05-13 - Website workflow migration
- Added scripts/ directory (audit, screenshot, commit gate, preview, gemma-review)
- Extracted design system to design-system/ (tokens.css, styles.css, logo.jsx, components)
- Created DESIGN.md with full brand documentation
- Added required files: robots.txt, sitemap.xml, 404.html, llms.txt
- Added .gitignore, PHOTO-STYLE-GUIDE.md placeholder
- TODO: favicon.ico still needed (extract from logo, convert to ICO)
- TODO: alt text audit needed (run: node scripts/gemma-review.js --task alt-text)

