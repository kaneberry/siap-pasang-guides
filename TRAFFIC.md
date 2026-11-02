# SiapPasang — traffic plan (no spend)

**Status:** Karven OK (via Kane-berry, 2026-11-03) for SEO polish this week. Community/social posts still held.  
**Hard holds until separate OK:** paid ads, custom domain, affiliate KYC/join, spend, social/community posts that go live.  
**Owner:** Earnie (~99% of weekly cadence). Kane-berry relays decisions.  
**Site:** https://kaneberry.github.io/siap-pasang-guides/  
**Repo:** https://github.com/kaneberry/siap-pasang-guides  

Goal: get BM/ID readers who search for “cara pasang … Docker / VPS” onto the existing guides, without Karven as operator.

---

## 1. SEO — BM / ID long-tail (primary, compounding)

**Why:** guides already match how people search (“cara pasang n8n”, “install Immich Docker”, “Uptime Kuma VPS”).

**Earnie weekly (automated + light edit):**
- Keep one clear H1 + meta description per guide (already in source front matter).
- Add / refresh `sitemap.xml` + link it from `robots.txt` (Allow already set).
- Internal links: each guide ↔ language twin (hreflang / “versi BM|ID”) + hub index.
- One new long-tail angle per week *only after* Karven OK on new guides — until then, polish existing pages (FAQ block, “ralat biasa”, clearer titles).
- Track impressions with free tools only: Google Search Console (needs property verify — **needs Karven OK** to add DNS/HTML or GitHub Pages verify file). Bing Webmaster optional same.

**Target query families (examples):**
- `cara pasang n8n docker` / `install n8n vps ubuntu`
- `pasang open webui ollama` / `install open webui docker`
- `cara install dify self host` / `dify docker compose`
- `install immich docker` / `alternatif google photos self host`
- `uptime kuma docker` / `monitor website sendiri`

**Do not:** buy backlinks, spin doorway pages, or keyword-stuff.

---

## 2. GitHub discovery (free, Earnie-run)

**Why:** developers already browse louislam/uptime-kuma, n8n, Immich issues/Discussions for install help.

**Earnie weekly:**
- Keep repo README sharp: what SiapPasang is, BM+ID links, no work-in-progress noise.
- Topics/tags on the repo (`docker`, `n8n`, `self-hosted`, `bahasa-melayu`, `bahasa-indonesia`, …).
- Watch upstream “install help” threads; when OK to engage: **one helpful answer + link to the matching guide** (never spam multiple repos/threads same day).
- Optional: Discussions or wiki stub on *our* repo pointing to Pages (after OK).

**Hold:** mass commenting, unsolicited PR spam, or “promo” issues.

---

## 3. Community posts — no spam (queued; need post OK)

**Channels (when Karven lifts “no posts”):**
- Reddit: r/selfhosted, r/homelab, r/n8n, locale subs (MY/ID tech) — answer first, link second.
- Facebook groups / Telegram: MY & ID self-host / VPS / AI hobby — same rule.
- Dev.to / Hashnode: one evergreen “cara pasang X di VPS Ubuntu” article that **embeds or links** SiapPasang (faceless OK).

**Cadence after OK:** max 2 helpful posts/week total across platforms; log URL + date in this file’s changelog.

**Never:** identical copy-paste blasts, affiliate-first posts, or fake “I just built…” claims.

---

## 4. Optional no-face social (queued; need post OK)

**Idea:** short screen-capture or carousel: terminal → browser → working UI; BM or ID captions; link in bio to Pages hub.

**Platforms:** TikTok / IG Reels / YouTube Shorts / X — faceless, stock or terminal-only.

**Cadence after OK:** 1–2 shorts/week, batch-recorded by Earnie; Karven only reviews if he wants.

**Hold until OK:** any account creation that needs phone KYC spend, boosts, or ads.

---

## 5. Weekly cadence Earnie can run alone (~99%)

| Day | Task | Needs Karven? |
|-----|------|----------------|
| Mon | SEO pass: one guide title/FAQ polish; sitemap check | No (content already public) |
| Tue | GitHub: README/topics hygiene; scan 3 upstream threads | Reply/post only after post OK |
| Wed | Prepare 1 community answer (save locally in `queue/`; don’t publish if held) | Publish needs OK |
| Thu | Optional short script for no-face clip (don’t upload if held) | Upload needs OK |
| Fri | Metrics note to Kane: Pages traffic (if GSC live), top guide, blockers | No |
| Anytime | New guide only on backlog OK; no domain/affiliates/ads | Separate OK |

**Metrics without spend:** GitHub Traffic insights, Cloudflare-free none on Pages — prefer GSC once verified; until then: qualitative + `curl`/manual spot checks.

---

## First week actions (SEO polish OK’d 2026-11-03)

1. **Commit `TRAFFIC.md` to repo** (ops doc; linked from README only, not public nav). — *staged 2026-11-03*  
2. **Add `sitemap.xml`** listing all BM/ID guide URLs + hub; update `robots.txt` with Sitemap line. — *staged 2026-11-03*  
3. **Ask Karven OK** (still pending — no verify file created) to verify Google Search Console on `kaneberry.github.io/siap-pasang-guides/` (HTML file upload via repo — no domain buy).  
4. **Repo polish:** topics, README “Panduan” list matching live guides, pin Pages URL. — *README staged 2026-11-03; topics/About URL are GitHub repo settings (Kane)*  
5. **Queue only (no publish):** one sample Reddit/TG answer + one Shorts script for n8n — hold publish until “posts OK”. — *queued locally 2026-11-03, not in repo*

---

## Explicit non-goals (until separate OK)

- Paid ads, boosts, influencer fees  
- Custom domain  
- Affiliate program join / KYC / tracked links live  
- Spammy mass outreach  

---

## Changelog

- 2026-11-03 — Written by Earnie for Kane → Karven.
- 2026-11-03 — **Karven OK: SEO polish this week; posts still held.** Staged: TRAFFIC.md, sitemap.xml, robots.txt Sitemap line, README guide list, BM↔ID twin + hub links, hreflang/canonical/meta description, FAQ blocks on all 5 guides (BM+ID). Community post + Shorts script queued locally only. No Search Console verify file (awaiting Kane/Karven OK).
