# danmat.dev — Vision & Positioning

> Working notes for the full portfolio. The site is a WIP arcade screen today; this
> captures the direction so the thinking survives the gap. Written 2026-08-17.

## The one-liner

Dan Matthew builds the tools that let people ship. **An app orchestra** — one builder,
many instruments — closing gaps by composing apps, tools, and platforms.

## What the site should say

A personal **business card**, unmistakably *me*, synced to this moment in software:

- I find gaps and build apps to close them.
- My edge isn't hand-writing every line — it's **taste, architecture, orchestration,
  and shipping**. I move *up* the abstraction ladder, I don't skip rungs.
- I'm **transparent about building with AI.** The ritual that used to gate software is
  dissolving; the leverage now is judgment and direction, and I lean into that openly.

## The through-line (why this is earned, not hype)

I've *always* built dev tools and platform enablement:

- **Dealer.com (pre-AI):** ~48 hand-written internal tools — an SPA generator, module
  templates, CI / GitHub-Actions runners & reporters, a website-crawler family,
  schema/config editors, intake bots, internal APIs. JS-heavy, deep, real.
- **Now:** [packkit](https://github.com/PackkitLabs) (a scaffolder), a platform at work
  for spinning up dev tools, and an AI-orchestrated ecosystem of shipped products.
- Same mission — **enable builders** — with an order of magnitude more leverage. packkit
  is the AI-era descendant of that SPA generator.

## The proof (ecosystem to feature — all live, all self-contained)

- **Retroix** — a from-scratch arcade game engine + 7 games + a shared Cloudflare
  leaderboard & hall-of-fame dashboard.
- **droppin / waypoints** — turn a Google Timeline export into a private travel map
  (100% client-side), plus a personal travel log.
- **earshot** — an audiobook-year retrospective that auto-pulls from Audible daily.
- **packkit** — provider-neutral project scaffolding (CLI + MCP + web configurator).
- **@danmat** — npm libraries.
- **Nimbus CMS** — a headless CMS (my own product).
- **PhilatelyOS** — an event-driven platform using AI vision (detection, OCR, embeddings,
  VLMs) to digitalize my **100k+ stamp collection**. A hobby, engineered like a real
  system (contracts-first, ADRs, IaC).
- …with the **Dealer.com** body of work as the pre-AI foundation.

## Not just an engineer — a whole person

The projects double as a portrait of what I actually love: **games** (Retroix), **travel**
(waypoints / droppin), **audiobooks** (earshot), **stamp collecting** (PhilatelyOS). The
throughline isn't the topics — it's that when I'm into something, I build the app for it.
The portfolio should feel like *a person with obsessions who ships*, not a list of
deliverables.

## The flex: the site runs on my own CMS

The portfolio will be **managed by [Nimbus CMS](https://nimbuscms.dev)** — a product I
built. A personal site that's *content-managed by your own CMS* is the strongest possible
demonstration of "app orchestra": not just showing projects, but dogfooding one to present
the rest.

## Build plan

- **Home:** `danmat.dev` (Cloudflare zone). Keep the arcade/synthwave soul of the current
  WIP screen, matured into a real gallery.
- **Content:** Nimbus CMS. **Gate:** Nimbus dev finishing (~mid-Sept 2026).
- **Stack:** packkit react-app scaffold, Cloudflare hosting, cookieless analytics — the
  same discipline as every project.
- **Design:** a distinctive visual identity via a dedicated design pass — see
  [`fable-design-brief.md`](./fable-design-brief.md).
- Project cards → live deployments; lead with the Nimbus + orchestra story.

_Status: not started — gated on Nimbus._
