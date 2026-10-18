# likhsout.github.io

Personal portfolio for **Raisul Islam Likhon** — hand-built, single-file, no build step.

**Live:** https://likhsout.github.io/

## What this is

`index.html` is the entire site. Every style, script, icon, font subset and the
portrait photo are inlined in that one file — no frameworks, no bundler, no
network requests other than the ones you click on. Drop it on any static host
and it works.

- **Sections** — hero, about, stats, services, 03 · automation & data,
  selected work (flagship case study + filterable grid), process, contact.
- **Console easter egg** — open DevTools and type `help` (or run `neofetch`).
- **Contact form** — posts to `formsubmit.co`; the first submission triggers a
  one-time activation email to `raisulislamlikhon12@gmail.com`.

## Editing it

Open `index.html` and search for the block you want:

| What | Where |
| --- | --- |
| Email address | `const EMAIL` near the top of the `<script>` |
| Projects / case studies | `const PROJECTS` |
| Terminal commands | the `C` command map |
| Portrait photo | the `--dp` custom property in the last `<style>` block |
| Fonts | the `<style>` block marked `EMBEDDED` — leave alone |

## Credits

Built on the **NEION-PORTFOLIO** template by Aanneion (MIT) — see the comment at
the top of `index.html`. Icons: Lucide (ISC) and Simple Icons (CC0). Fonts:
Inter, Space Grotesk, JetBrains Mono, Tilt Neon, Hind Siliguri (SIL OFL 1.1).

## Hosting

GitHub Pages serves `main` / root directly. Push to `main` and the site updates.
