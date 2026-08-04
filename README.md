# Our-Date-Drop — Wedding site (Noela & Rahul)

This is a simple, static wedding website (no RSVP form) with placeholders for your images.

Files included
- `index.html` — main page (personalized with ceremony & reception details)
- `styles.css` — styling
- `images/` — add your photos here (not included)
- `README.md` — this file

How to add photos
1. Add image files to the `images/` folder in the repository.
2. Suggested filenames used by the template:
   - `images/hero.jpg` — optional hero/header photo
   - `images/photo1.jpg`, `images/photo2.jpg`, `images/photo3.jpg` — gallery photos
3. If you use different filenames, edit the `<img src="">` values in `index.html`.

Preview locally
- Open `index.html` directly in a browser (file://) for a quick preview.
- Or run a local static server:
  - Python 3: `python -m http.server 8000` then open http://localhost:8000

Publish with GitHub Pages (automatic)
- I added a GitHub Actions workflow that will deploy the site to the `gh-pages` branch automatically on pushes to `main`.
- The site will be published at: `https://rahulreji3124-art.github.io/Our-Date-Drop/` once the workflow completes.

Replace contact info or wording by editing `index.html`.
