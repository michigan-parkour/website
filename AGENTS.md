# Website Update Notes

## Project

- Static website for Michigan Parkour.
- Main page: `index.html`.
- Styles: `assets/styles.css`.
- Images: `assets/images/`.
- Git branch: `main`.
- Public repository: `https://github.com/michigan-parkour/website`.
- Cloudflare Pages deploys after changes are pushed.

## Local Preview

Run from the repository root:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Open `http://127.0.0.1:8765/`.

## Google Photos Album

Use this shared album when choosing new gallery images:

https://photos.google.com/share/AF1QipMinbzNgXK55iFqa90zufmFOUVu_SDrPCCqwwoBgWwBQKx7_U2muP4ijFW16wCsuQ?pli=1&key=WmdfTWljZWRxM1Jua2N2NUgxT1ZQOWhNdmpFb01B

Workflow for adding album photos:

1. Review the newest uploads in the album and make a numbered list for selection.
2. Download chosen photos into `assets/images/`.
3. Use lowercase descriptive names, for example `album-2026-06-16-wall-climb.jpg`.
4. Resize web images to about 1800 px on the long edge. Keep landscape photos around `1800x1200` and portrait photos around `1200x1800`.
5. Add selected photos near the top of the gallery in `index.html`.
6. Use `class="wide"` on landscape photos that should span more grid width.
7. Write concise, descriptive `alt` text for every image.
8. Preview locally at `#gallery` before committing or pushing.

## Challenger Challenges Section

The site has a `Challenges` section that links to the Challenger app stores and uses store preview images:

- App Store link: `https://apps.apple.com/us/app/challenger-make-local-challenges/id1508719541`
- Google Play link: `https://play.google.com/store/apps/details?id=co.challengerapp.android`
- Current copy: `We use the Challenger app to record videos of challenges around Ann Arbor.`

Keep this section title as `Challenges`, not `Challenger`.

## Git Notes

- Use commit identity `daintyhandiwork <179258705+daintyhandiwork@users.noreply.github.com>`.
- Confirm before pushing unless the user explicitly asks to push.
