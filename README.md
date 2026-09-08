<img width="512" height="512" alt="SearchLight Logo 1" src="https://github.com/user-attachments/assets/eba639e0-37c1-4759-aaa6-01420cac7168" />

# SearchLight

SearchLight is an Android app for before-and-after photo comparison. Photograph a room, drawer, shelf, or bag once, photograph it again later, and the app lines the two pictures up and marks what looks different. You decide whether a mark matters.

Photos, session names, and masks stay on the device. SearchLight does not create an account and does not upload your pictures.

## Use cases

- **Home inventory** — Snapshot a nightstand, closet, or workbench so you can see if something was moved or is missing.
- **Travel and lodging** — Photograph a hotel desk, rental, or packed bag when you leave and when you return.
- **Shared spaces** — Recheck a roommate kitchen, office drawer, or storage unit without relying on memory.
- **Projects and layouts** — Compare a workspace or display before and after a change so small shifts are easier to spot.

Typical flow: create a session, take a **baseline** photo, take a **check** photo of the same scene, then compare.

## What it does

- **Sessions** — Keep separate baseline/check sets for different places (desk drawer, nightstand, bag).
- **Capture** — Use the camera or pick a photo with the system picker. Optional ghost overlay, composition grid, flash, autofocus, and pinch zoom help you match the original angle. **Match zoom** returns a later check to the zoom saved with the baseline.
- **Alignment** — Auto-aligns photos taken from slightly different positions. If that fails, tap matching points on both images. A figure of merit (FoM) shows how well they lined up.
- **Comparison views** — Flip-flop, wipe slider, difference, heatmap, gray diff, subtract, edge (Canny), overlay, and side-by-side.
- **Masks** — Paint **ignore** regions to hide motion you do not care about (a clock, a window). Paint **include** regions to limit marking to a drawer, bag, or other area of interest.
- **Review tools** — Pinch to zoom, paired luminance histograms, check history, and Save Difference for a session.

The software only points at differences. It does not rank threats or decide importance.

## Privacy

See the [privacy policy](https://undrcrrnt.github.io/SearchLight/privacy.html).

## User manual

See the [user manual](https://undrcrrnt.github.io/SearchLight/manual.html).
