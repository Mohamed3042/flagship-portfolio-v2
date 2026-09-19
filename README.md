# flagship-portfolio-v2

The **DARB / Deep Field Round 5** landing, published as a second GitHub Pages project site:

<https://mohamed3042.github.io/flagship-portfolio-v2/>

The first site is untouched and still at
<https://mohamed3042.github.io/flagship-portfolio/>.

## What is in this repository

The **built site only** — this is a deploy target, not a source repository.
The source is `Mohamed3042/flagship-portfolio`, branch `feature/deep-field`,
and the build that produced this tree is:

```bash
node scripts/build-ghpages.mjs --base flagship-portfolio-v2 --outDir dist-v2
```

## What is deliberately NOT here

`worlds/` — the cinematic scroll-film pages and their 1.68 GB of clips and
posters. They are already published on the first site, they are the same
worlds, and nothing on this site links to them by a relative path: the five
world portals on the landing point at
`https://mohamed3042.github.io/flagship-portfolio/worlds/…` absolutely. A
second copy would be 1.7 GB of duplicated media for no new page.

Everything else the site serves — both language routes, all 80 pages, the
archive, the work pages, the fonts, the images, the CV — is here, and this
tree is 33.6 MiB.

Round 5 source implementation: `1220e24`, branch `feature/deep-field`. All 1,968 browser checks pass. The four game films are edge-star holograms; raw game footage is not published. Four owner character illustrations remain pending.
