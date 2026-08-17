# danmat.dev

Personal site for **Dan Matthew** — served via GitHub Pages at [www.danmat.dev](https://www.danmat.dev).

Currently a **work-in-progress** arcade landing screen (self-contained `index.html`, no build step). The full portfolio is coming.

## Vision & roadmap

- [`docs/VISION.md`](docs/VISION.md) — positioning, the through-line, and the plan.
- [`docs/fable-design-brief.md`](docs/fable-design-brief.md) — WIP design brief for the identity pass.

The full site will be content-managed by [Nimbus CMS](https://nimbuscms.dev) once it ships.

## Hosting

- GitHub Pages, source = `main` branch, root.
- Custom domain via `CNAME` (`www.danmat.dev`), DNS on Cloudflare.
- `.nojekyll` disables Jekyll (plain static HTML).

## Local preview

Just open `index.html`, or serve the folder:

```sh
python3 -m http.server 4173   # then visit http://localhost:4173
```
