# vulna.dev

Marketing site for [Vulna](https://github.com/codebooker/vulna): a single static
page, no build step, no dependencies. Deployed to <https://vulna.dev> via GitHub
Pages.

## Contents

- [`index.html`](index.html) is the entire site (embedded CSS, inline SVG shield
  mark and topology diagram; the only external requests are two Google Fonts).
- [`favicon.svg`](favicon.svg) / [`vulna-mark.png`](vulna-mark.png) — the Vulna
  shield mark, used as favicon and touch icon.
- [`og.png`](og.png) — 1200x630 social-share card.
- [`PRODUCT.md`](PRODUCT.md) and [`DESIGN.md`](DESIGN.md) document the brand
  positioning and design tokens.

Brand assets are the canonical exports from
[`codebooker/vulna/brand`](https://github.com/codebooker/vulna/tree/main/brand).

## Preview locally

Any static server works:

```sh
python3 -m http.server 4173
# or: npx --yes http-server -p 4173 .
```

Then open <http://localhost:4173>.

## Deploy

Pushing to `main` publishes to GitHub Pages. The [`CNAME`](CNAME) file binds the
custom domain `vulna.dev`; because `.dev` is HSTS-preloaded, HTTPS is enforced
(GitHub provisions the certificate automatically). `.nojekyll` disables Jekyll so
the files are served verbatim.

The page is self-contained, so it also runs as-is on Cloudflare Pages, Netlify,
or any host that can serve a static file.
