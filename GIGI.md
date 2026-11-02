# Brief for gigi (ChatGPT) — SiapPasang guide drafts

**Repo / site:** https://github.com/kaneberry/siap-pasang-guides · https://kaneberry.github.io/siap-pasang-guides/  
**Public brand:** SiapPasang (never use internal code names like Pasang-berry on public pages)  
**Workflow (Karven 2026-11-03):** gigi drafts; Earnie/Kane review the PR and publish to GitHub Pages. Do not ask Earnie to write new full guides in Grok Bot.

## What to deliver

For each new tool, open a PR that adds **both**:

- `ms/<slug>/index.html` — Bahasa Melayu  
- `id/<slug>/index.html` — Bahasa Indonesia  

Plus update:

- `ms/index.html` and `id/index.html` (link the new guide)  
- `sitemap.xml` (new URLs)  
- `README.md` guide table  

Match the layout of an existing live guide (e.g. `ms/uptime-kuma/` or `ms/immich/`): nav, language twin + hub links, soft “official docs read on &lt;date&gt; / verify on your VPS” note, numbered sections, VPS size box with **official** Vultr / DigitalOcean / Hostinger links + disclosure link, security/HTTPS or SSH-tunnel tip, FAQ, footer legal links.

All internal `href`s must start with `/siap-pasang-guides/`.

## Public tone (required)

**Do not** put on public pages: `DRAFT`, Phase A/B, 🚧, 🧪, “belum diuji penuh”, Pasang-berry, internal Kane/Earn ops notes.

Soft honesty is OK: steps follow official docs (cite URL + date read); reader should verify on their own VPS.

## Sources

Use only official docs / GitHub release notes for install steps. Prefer Docker Compose when the project recommends it. Do not invent Certbot/nginx configs — link the project’s own reverse-proxy docs.

## Affiliates / Phase B (held)

Keep provider links as official (non-affiliate) URLs. Do not join affiliate programs, buy domains, run ads, or publish community/social posts unless Karven OK is relayed.

## Review checklist (Earnie)

- [ ] BM + ID both present, clean tone  
- [ ] Prefix `/siap-pasang-guides/` on internal links  
- [ ] sitemap + indexes + README updated  
- [ ] No spend / affiliate / domain / posts  
- [ ] Pages 200 after merge/publish  

## Live guides (do not duplicate)

n8n · Open WebUI · Dify · Immich · Uptime Kuma  

Next tools: only after Karven names them via Kane.

## Ops

Traffic plan: see `TRAFFIC.md` (SEO polish OK this week; community posts still held).
