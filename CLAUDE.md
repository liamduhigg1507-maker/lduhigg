# CLAUDE.md

Read this first. It's the running memory for Liam's website business, so a new
session doesn't have to start from zero. Update the "Status" and "Decisions"
sections whenever something changes.

## Who and what

- **Owner:** Liam Duhigg, sole trader, based in Sydney's south (NSW, Australia).
- **Business name:** L Duhigg (rebranded from "LX Website Design").
- **ABN:** 59753894010
- **Contact on the site:** liamduhigg@gmail.com · 0483 865 270
- **What it sells:** websites for local Sydney businesses that don't have one yet:
  cafés, restaurants, takeaway, bakeries, trades, salons, barbers, retail, clinics.
- **Offer:** a one-off fixed-price build (usually half up front, half at launch) plus
  an optional monthly fee for hosting and updates. Free first chat, quote before work starts.

## How Liam works

- Usually on his phone (iOS app), sometimes on a laptop. Messages are short. Ask
  at most one clear question, and otherwise just get on with it.
- Writes in plain Australian English. Site copy uses en-AU spelling.
- Cloud sessions have no memory between chats. This file is the memory.
- Cloud network: the Default environment was switched to **unrestricted** on
  2026-11-07, so Instagram and 21st.dev are reachable. Instagram reels still often
  hit a login wall, so ask for screenshots or the caption when a fetch fails.
- Connectors that worked on 2026-11-07: GitHub, Stripe, Gmail, Google Calendar,
  Google Drive, Shopify. Canva, HubSpot, Notion, Wix, Square, etc. failed with a
  network error before the network change; check again in a new session.
- No laptop folders shared via Remote Control yet.

## The repo

- `index.html`: the L Duhigg one-page site. Single file, no build step.
  Fonts: Bricolage Grotesque (display) + Figtree (body). Colours: harbour teal
  `#0d5c63`, sun yellow `#f2b84b`, paper `#f4f6f5`. Has a dark mode.
- Work goes on a `claude/...` branch, then gets merged to `main`.

## Status (update this)

- [x] One-page business site built and merged to `main`
- [ ] Site live online (GitHub Pages: Settings → Pages → deploy from `main`)
- [ ] Domain bought (e.g. lduhigg.com.au; .com.au needs the ABN)
- [ ] Google Business Profile for L Duhigg ("Website designer")
- [ ] Real prices on the site ("starting from")
- [x] 3 demo sites in `demos/` (Saltbush Kitchen café, Shire Spark Electrical, Kingsway Barber Co.), linked from the "Example sites" section of `index.html`
- [ ] Contact form on the site
- [ ] Stripe payment link for deposits
- [ ] Prospect list of local businesses with no website + walk-in pitch

## Decisions and ideas so far

- Liam likes design inspiration from Instagram (e.g. @buildingwiththane). Tools
  it pointed to: **21st.dev** (component library, free to browse), **SiteReel.ai**
  (website prompts, "Copy prompt" and paste into chat). Manus.im is paid and
  isn't needed because Claude Code already covers tasks, skills, plugins, schedules, and projects.
- Suggested design plugins to install: `frontend-design` (Anthropic), Website
  Design (UXKIN), audit-suite. Check with ListPlugins whether they're installed.
- Suggested starting price range (not yet confirmed by Liam): about $800–1,500
  per build, $30–60/month hosting and updates.
