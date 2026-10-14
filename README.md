# Jose Art Gallery

A static art gallery website showcasing the oil and watercolor paintings of
**Jose Gonzales Guzman**, a Bolivian painter known for his landscape and rural
scenes.

## Live site

The gallery is published via GitHub Pages:

**https://wildergonzo.github.io/jose-gallery/**

- Gallery: https://wildergonzo.github.io/jose-gallery/
- About the artist: https://wildergonzo.github.io/jose-gallery/about.html

## Structure

- `index.html` — main gallery grid of paintings (thumbnails linking to full-size images).
- `about.html` — artist biography, exhibitions, education, and artistic philosophy.
- `images/fulls/` — full-resolution paintings.
- `images/thumbs/` — gallery thumbnails.
- `images/profile.jpg` — artist profile photo.
- `assets/` — CSS, JavaScript, fonts, and Sass sources.

## Running locally

This is a static site with no build step. Open `index.html` directly in a browser,
or serve the folder with any static file server, for example:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Source

Repository: https://github.com/wildergonzo/jose-gallery

Gallery template based on work by @ajlkn.
