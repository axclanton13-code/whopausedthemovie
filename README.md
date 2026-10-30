# WhoPausedTheMovie — Exhibition v8

Open `index.html` to preview the interactive site. For consistent local video playback, run `python -m http.server 8000` inside this folder and open `http://localhost:8000`.

## Included
- 35 unique photographs, including **both different color grades** in Tone Change. Exact duplicates excluded.
- 18 unique source videos represented by 5-second muted web-optimized preview clips (the large original files are NOT packaged).
- The uploaded YSL intro thumbnail serves as the dominant featured-film preview. Clicking it opens the YouTube film `https://youtu.be/sDNuJl7Kxxc` in a floating iframe.
- WORK, MOTION, ABOUT ME tabs; image lightbox; animated scroll reveals, ticker, staggered editorial grid, floating YouTube player, mobile layout and reduced-motion support.

## Updating
- `js/content.js` controls image groups, captions, video cell titles, and YouTube ID.
- `css/styles.css` controls visual appearance and motion.
- `js/site.js` controls routing, gallery, video playback and lightboxes.
- `assets/photos/` contains resized versions of the user's real photographs.
- `assets/videos/` contains **short 5-second silent previews**, not the full original videos.

## Notes
- Source filenames for all video previews are displayed below their respective cells. These are working titles.
- This is an independent HTML/CSS/JS prototype, **not a native Readymag project**. Embeds and custom animations need adaptation to Readymag.
- YouTube embedding requires an internet connection and the video's embedding permissions.
- Confirm rights before publishing any client-owned inspection or commercial material.

V9: TONE CHANGE is now an accessible touch/keyboard slider comparing the two original graded photographs. Homepage renamed MOVIE IN MOTION; approved FLOURISH and TONE CHANGE captions applied; vertical gaps reduced.


## Naming your media
Edit `js/content.js`. Each video has a `title` (public-facing name), a `caption` (public-facing subtitle), and a `sourceFilename` (private original filename used for matching media). The public website no longer displays source filenames. The current MOTION STUDY titles are placeholders to be replaced with your preferred artistic names.

## Preview quality
All 18 preview videos are regenerated from their original uploaded files at up to 1280 pixels wide, 24 fps, H.264 CRF 20, five seconds long, muted and optimized for browser playback. Source clips with lower native resolution are not artificially upscaled.

## Version 12 — Full-length in-gallery video player

Click or keyboard-activate any motion gallery tile to play the complete uploaded video in a central gallery player. Use MINIMIZE to turn it into a persistent floating mini-player without resetting playback; EXPAND restores the central layout. CLOSE stops playback. Native video controls provide volume, scrubbing and fullscreen. All full films are locally included in `assets/full/` as web-friendly MP4 encodes, retaining the complete durations and available audio. Five-second thumbnails remain in `assets/videos/`. The featured YouTube film still opens through its existing YouTube player.


## Version 13 — CMYK Slate visual identity
Dominant cinema black (`#090909`) and slate white (`#F5F5F0`), with electric cyan (`#34D7E8`), film pink (`#FF65AD`), and slate yellow (`#F8D74A`). CSS-only clapperboard stripes and CMY registration bars were added. Original photography, all 18 five-second thumbnails, all 18 full-length videos, the three-tone image comparison, and the central/minimized video player remain intact. Edit palette variables in `css/styles.css` under the V13 section.

## Version 14 — Question mark identity

Added an oversized 25-degree pink question mark behind the homepage title and a gently tilted, continuously scrolling cyan/pink/yellow/white question-mark banner. Hover pauses the banner. Reduced-motion preferences disable animation. All V13 gallery assets and interactive features are unchanged.


V15: Responsive hero image now uses a stable 3:4 desktop crop and full-width 16:9 mobile image; typography and question-mark banner adjusted for 320px–large displays. Test with a deployed HTTP site on multiple devices before external submission.


## Version 19 reconstruction (October 29, 2026)
Reconstructed all 18 motion project labels from the user-supplied Claude Agent transcript. The original featured video remains featured, with 17 archive entries renamed. LXID tile 16 now has a six-second silent preview from 00:19 to 00:25 and a poster frame at 00:19. Original full-length LXID film remains untouched. The prior photography, Showpony and Baby Osamaa changes are retained. Tezzus/Diamond* ordering reflects the latest Claude transcript and can be swapped if needed.
