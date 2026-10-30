# RV Menon: books

The author website for *Horse of the Servant* (Blood and Thrones, Book One), the novel and the graphic novel.

It is a static site with no build step, served at https://rvmenon.com. Shared styles and images are in `assets/`.

| Path | Contents |
| --- | --- |
| `index.html` | Author home page |
| `horse-of-the-servant/index.html` | Book page: both editions with Amazon links, the world of the book, the atlas, the author |
| `assets/` | `site.css`, covers, the Malabar map illustration and the social preview image |
| `horse-of-the-servant/atlas/index.html` | A copy of the Travancore 1671 to 1758 reading atlas. Its source and build script live in [roshanis/horse](https://github.com/roshanis/horse); rebuild there and copy the built `index.html` here. |

## Publishing

Deployed on Vercel: framework preset Other, no build command, output directory the root. The domain rvmenon.com points at the Vercel project. `vercel.json` adds trailing slashes so relative links resolve; `.vercelignore` keeps this README off the site.

## Pages

- `/`: author home page
- `/horse-of-the-servant/`: the book page, both editions
- `/horse-of-the-servant/atlas/`: the reading atlas

## Before launch

- `assets/novel-cover.jpg` is a stand-in composed from the novel's cover art. Replace it with the cover shown on Amazon (same file name, 800 x 1280 or any 5:8 image).
- The graphic novel byline says RV Menon (matching its cover art). The Amazon listing URL suggests it credits Roshan Venugopal; make the two match.
