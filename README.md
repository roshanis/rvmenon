# RV Menon: books

The author website for *Horse of the Servant* (Blood and Thrones, Book One), the novel and the graphic novel.

It is a static site with no build step, served at https://rvmenon.com. Shared styles and images are in `assets/`.

| Path | Contents |
| --- | --- |
| `index.html` | Author home page |
| `horse-of-the-servant/index.html` | Book page: both editions with Amazon links, the world of the book, the atlas, the author |
| `sitemap.xml`, `robots.txt` | For search engines; update `lastmod` when a page changes |
| `assets/` | `site.css`, covers, the Malabar map illustration and the social preview image |
| `horse-of-the-servant/atlas/index.html` | A copy of the Travancore 1671 to 1758 reading atlas. Its source and build script live in [roshanis/horse](https://github.com/roshanis/horse); rebuild there and copy the built `index.html` here. |

## Publishing

Deployed on Vercel: framework preset Other, no build command, output directory the root. The domain rvmenon.com points at the Vercel project. `vercel.json` adds trailing slashes so relative links resolve; `.vercelignore` keeps this README off the site.

## Pages

- `/`: author home page
- `/horse-of-the-servant/`: the book page, both editions
- `/horse-of-the-servant/atlas/`: the reading atlas

## Images

- `assets/novel-cover.jpg`: the seated king from the novel (`images/portrait_marthanda.jpg` in roshanis/nagoji), square, shown with class `sq`.
- `assets/graphic-novel-cover.jpg`: the graphic novel's Kindle cover. Both books are credited to RV Menon.
