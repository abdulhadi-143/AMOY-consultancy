# AMOY Consultancy Website (English, Türkçe, العربية)

A static site with an animated network wallpaper. No build step. Share a language with `?lang=tr` or `?lang=ar`.

## Publish on GitHub Pages
1. Create a new public repository and upload `index.html` (keep it in the root).
2. Upload your images into an `assets` folder (paths below).
3. **Settings → Pages → Deploy from a branch → main → / (root) → Save.**
4. Your site appears at `https://YOUR-USERNAME.github.io/REPO-NAME/` in 1-2 minutes.

## Image paths (missing files are handled gracefully)
| File | Used for |
|---|---|
| `assets/favicon.ico` | Browser tab icon |
| `assets/logo.png` | Header logo (about 36 px tall, transparent background) |
| `assets/mentors/ender-gurgen.jpg`, `tevfik-aytemiz.jpg`, `ayse-sahin.jpg`, `umit-dogrul.jpg` | Mentor photos (square) |

## Before you go public
- In `index.html`, replace `your-email@example.com` (search for `MAIL`).
- Get written consent from each mentor before publishing their names or photos.
- The contact form opens the visitor's email app. Connect a form service such as Formspree later for a real form.
- Have native Turkish and Arabic speakers proofread the translations.
