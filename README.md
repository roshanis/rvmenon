# RV Menon: books

The author website for *Horse of the Servant* (Blood and Thrones, Book One), the novel and the graphic novel.

It is a static site with no build step. `index.html` is the home page; images are in `assets/`.

| Path | Contents |
| --- | --- |
| `index.html` | Home page: both books with Amazon links, the world of the book, the atlas, the author |
| `assets/` | Covers, the Malabar map illustration and the social preview image |
| `atlas/index.html` | A copy of the Travancore 1671 to 1758 reading atlas. Its source and build script live in [roshanis/horse](https://github.com/roshanis/horse); rebuild there and copy the built `index.html` here. |

## Publishing

Turn on GitHub Pages in the repository settings: Pages, Deploy from a branch, `main`, folder `/ (root)`. The site then appears at https://roshanis.github.io/rvmenon/.

## Before launch

- `assets/novel-cover.jpg` is a stand-in composed from the novel's cover art. Replace it with the cover shown on Amazon (same file name, 800 x 1280 or any 5:8 image).
