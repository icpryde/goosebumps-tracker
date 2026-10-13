# Goosebumps Tracker

My collection of the original 62 *Goosebumps* books (1992–1997): which ones I own, which ones I still need, and every cover.

**Live site:** https://icpryde.github.io/goosebumps-tracker/

## How it works

- `index.html` is the whole app: no build step, no dependencies.
- The shelf (which books I own) lives in `shelf.json` on the **`data`** branch, so saving a change doesn't trigger a Pages rebuild.
- Anyone can view the shelf. To change it from a device, open the site, tap the sync status under the progress bar, and paste a fine-grained GitHub token that has **Contents: Read and write** on this repo only. The token stays in that browser's local storage.
- Covers are in `covers/sm` (grid and list) and `covers/lg` (big view), as WebP.

## Credits

Cover images and first-edition details come from the [Goosebumps Wiki](https://goosebumps.fandom.com). *Goosebumps* is a trademark of Scholastic Inc. This is a personal fan project, not an official site. The icon's lettering uses [Creepster](https://fonts.google.com/specimen/Creepster) (SIL Open Font License).
