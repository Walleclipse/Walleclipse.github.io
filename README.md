# Abulikemu Abuduweili: personal website

Source of <https://walleclipse.github.io>. It is a [Jekyll](https://jekyllrb.com/) site that GitHub Pages builds.

The site started as a fork of [Jekyll Now](https://github.com/barryclark/jekyll-now). The design follows [Jon Barron's website](https://jonbarron.info/) and [Ruixuan Liu's website](https://waynekyrie.github.io/). You may use the template for your own site. Please respect the copyright of the content in `images/`, `_posts/`, `_layouts/` and `_includes/`.

## Pages

| File | Page | Built from |
|---|---|---|
| `index.html` | Home: bio and news | written by hand |
| `publications.html` | Publications and side research | posts with the category `research` (main list) and `optics` or `med` (side research) |
| `projects.html` | Coursework and personal projects | posts with the category `project` |
| `service.html` | Teaching and reviewing | written by hand |
| `misc.html` | About me | written by hand |
| `blog.html` | Blog (a "Coming soon" page for now) | written by hand |

Each paper or project is one file in `_posts/`, named `YYYY-MM-DD-Name.md`. Posts appear newest first.

## Add a paper

1. Put a picture or GIF in `images/`.
2. Create `_posts/YYYY-MM-DD-Name.md` with this front matter, then write two or three sentences below it:

   ```yaml
   ---
   layout: post
   title:  "Paper title"
   date:   2026-11-16 02:00:00 +00:00      # the real date; it sets the order
   image: /images/Name.gif
   categories: research
   author: "Abulikemu Abuduweili"
   authors: "<strong>Abulikemu Abuduweili</strong>, Coauthor One, Coauthor Two"
   venue: "arXiv preprint"                  # the card shows "venue, year"
   arxiv: https://arxiv.org/abs/XXXX.XXXXX  # the "Paper" button
   code: https://github.com/...             # optional buttons: code, video, website
   website: https://...
   video: https://...
   ---
   ```

   Other optional keys: `award` (a line under the venue), `highlight: true` (a highlighted card), and `pin: true`.

3. Run the site locally (see below) and check the card.

### Order and pinning

Papers are sorted by `date`, newest first. A post with `pin: true` always comes first, whatever its date. Today HALO is pinned. If you pin more than one post, the pinned posts are shown in date order, newest first.

### Pictures

- The card shows the image in a 280×175 px box (16:10) and crops it to fill the box. Use a 16:10 image, or letterbox it, so nothing important is cut off.
- GIFs work. Keep them near 5 MB or less. The page loads images as you scroll, but a large GIF is still slow on a phone.
- Transparent PNGs show a black background if you convert them to GIF. Put them on white first.

## Run locally

Install Jekyll (the `github-pages` gem matches what GitHub builds), then from this folder run:

```sh
jekyll serve        # serves the site at http://localhost:4000
jekyll build        # writes the finished site to _site/ (ignored by git)
```

## Other files

| Path | What it does |
|---|---|
| `_includes/pub-card.html` | One publication card. `publications.html` uses it for pinned and unpinned papers. |
| `_layouts/` | Page templates: `default.html` and `post.html`. |
| `style.scss`, `_sass/` | All styling, including the light and dark themes. |
| `_config.yml` | Site settings. The permalink pattern is `/:categories/:title/`. |
| `_make_favicon.sh` | Builds `favicon.ico` from `images/photo_crop.JPG`. Needs ImageMagick. |

## License

The template code is under the MIT license (see `LICENSE`, copyright Barry Clark). The text, papers and images are mine; please ask before you reuse them.
