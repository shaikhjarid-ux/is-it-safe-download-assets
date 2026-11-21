# Is It Safe to Download? — Visual Identity Pack

## Direction
Minimal, friendly cat mascot with restrained security motifs. The cat is the recognisable identity; the shield/check, magnifier, folder and file icons connect it to download safety without turning the guide into a corporate antivirus brand.

## Palette
- Warm cream: #FFFBFE
- Soft lavender page background: #F5EDF7
- Lavender accent: #D8B8F1
- Plum outline / text: #806493 / #493F52
- Soft pink: #F2D4E2
- Pale blue: #D5E7F2
- Dark-mode background: #211B2B

## Files
- `logo-mark.png` / `.svg`: primary logo mark, transparent outside the badge.
- `favicon.png` / `favicon-64.png` / `.svg`: simplified browser-tab icon.
- `rentry-page-icon-metadata.txt`: ready-to-paste PAGE_ICON line using the compact 64px PNG data URI.
- `wordmark.png` / `.svg`: logo with title and tagline.
- `discord-cover-1200x630.png` / `.svg`: Discord/social share cover. PNG has exact 1200x630 dimensions.
- `rentry-header.png` / `.svg`: optional small header graphic.
- `stickers/`: individual transparent PNG and editable SVG sticker illustrations.
- `sticker-sheet-preview.jpg`: contact sheet preview only.

## Suggested placements
- Use the compact Base64 line in `rentry-page-icon-metadata.txt` for the Rentry `PAGE_ICON` setting. The 64px icon is kept small to stay within the metadata limit.
- Use `favicon.png` as `PAGE_ICON` (host it at a stable direct image URL or use its Base64 data URI in metadata; keep it small).
- Use `discord-cover-1200x630.png` as `PAGE_IMAGE` and/or `SHARE_IMAGE` (host it at a stable direct image URL).
- Use `wordmark.png` above the title only if the page feels too plain; otherwise use the compact `logo-mark.png` near the title.
- Use 3–5 small stickers across the whole guide, not one after every heading. Good locations: introduction, one tier divider, URL inspection, VirusTotal, Android APK section, and final principle.
- Add descriptive alt text to every visual.

## Note
The PNG/SVG visual assets are newly created for this guide. Before using Rentry metadata image URLs, upload/host the images somewhere that provides stable direct image URLs. Do not use temporary or expiring links.
