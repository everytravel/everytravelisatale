# Diari di viaggio – single-page Polynesia edition

This package replaces the earlier multiple-island version.

## Install on GitHub Pages

1. In `everytravel/everytravelisatale`, DELETE the old files `huahine.md`, `raiatea.md`, `bora-bora.md`, `moorea.md`, and `tahiti.md` (they are now all combined into `polinesia.md`).
2. Upload the contents of this ZIP to the **root** of your `main` branch, preserving the folder structure. Replace the old files when asked.
3. Settings → Pages: Deploy from a branch, `main`, `/ (root)`.
4. Check https://everytravel.github.io/everytravelisatale/ and follow “Leggi il diario”.

## Edit the diary

- Edit `polinesia.md` on GitHub, using its Markdown editor. This is the **only** content file for the Polynesia diary.
- `##` headings divide islands; `###` headings divide dates.
- The index at the start links to the explicit `<a id="...">` anchors. If you rename an island or date, keep the anchor unchanged unless you also change its table-of-contents link.
- Photographs are stored in `assets/images`. For a new photo, upload the JPG and add a Markdown image following the existing examples.
- Italic lines beneath photos are the captions, preserving the original text.
- GitHub Pages builds Markdown with Jekyll, so opening `polinesia.md` as a local file will **not** render the website. Preview via the published site.

The `.pages.yml` file is an initial Pages CMS configuration. If using its visual editor, verify formatting after saving because the diary contains Jekyll image URLs and manual anchor tags.
