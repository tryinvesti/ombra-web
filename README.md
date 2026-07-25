# ombra-web

Landing page for [Ombra, Inc.](https://ombrainc.com) — the company behind
[Investi](https://tryinvesti.com).

Hand-written HTML and CSS, served by GitHub Pages from the root of `main`.

Paths are root-absolute, so preview over HTTP rather than `file://`:

```bash
python3 -m http.server 4000
```

`CNAME` and `.nojekyll` are load-bearing: the first holds the custom domain, the
second tells Pages to publish the files as-is.

Space Grotesk is bundled under the OFL (`fonts/OFL.txt`). Everything else is
© Ombra, Inc.
