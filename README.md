<div align="center">

<img src="./bannerr.png" alt="ULA" width="100%"/>


**One-person studio. Moscow. Eight products in flight, public demos live.**


[![Telegram](https://img.shields.io/badge/@HilzHilzHilz-21262d?style=for-the-badge&logo=telegram&logoColor=f0f6fc&labelColor=161b22)](https://t.me/HilzHilzHilz)
![Location](https://img.shields.io/badge/BASED_IN-MOSCOW-21262d?style=for-the-badge&labelColor=161b22)
![Status](https://img.shields.io/badge/STATUS-SHIPPING-8B0000?style=for-the-badge&labelColor=161b22)

</div>

---

Core repos stay private because they run. Live keys, live infrastructure, live users. Public demo shells are linked below. The products are the proof.

---

## Currently building

### 🔒 Promo Preflight

> *Launch-readiness workspace for regulated promo campaigns.*

An AI-assisted pre-launch QA workspace for iGaming promo operations. One campaign bundle in: offer math, terms, channel copy, GEO, localization, links, and owners. Out comes an 8-stage / 23-rule risk report, blocker table, owner handoff, Go/No-Go board, Slack-ready summary, and version-to-version blocker diff.

**How it's built.** Next.js 16 App Router, React 19, TypeScript strict, Zod contracts at every product boundary, Tailwind custom UI, YAML-backed rule and owner artifacts, deterministic offline check engine, PostgreSQL schema ready for durable persistence, Railway deploy. LLM provider wiring exists, but the live demo runs offline by design: no raw campaign storage, no auth, no payments, no player-facing flow.

**Live:** [promo-preflight-production.up.railway.app](https://promo-preflight-production.up.railway.app/)

Repository stays private until the agent/config history is cleaned.

---

### 🔒 FKNG-MARK

> *My Fucking Marketing Engine, now yours.*

A launch engine for micro-SaaS. One brief in. Forty-eight hours later, out comes deep competitor research, channel strategy, content for VK, Telegram, OK and Dzen, published posts, collected metrics, and an auto-recommendation — kill, iterate, or scale.

**How it's built.** Opus 4.7 runs the research agent through the Claude Agent SDK. Sonnet 4.6 runs strategy, long-form articles, and the decision layer. Haiku 4.5 runs the volume content. Flux handles imagery via Replicate. PostgreSQL and pg-boss carry the state and the queue. TypeScript strict, end-to-end.

V1 shipped in April 2026. V2 is the production core — four weeks of build, tested on a live product in the portfolio.

**Demo:** [launch-engine-demo](https://ulayuga.github.io/launch-engine-demo/)

No open source on the roadmap.

---

## Public demos

| Project | Demo | Repository |
|---|---|---|
| **Гадалка** | [Open demo](https://ulayuga.github.io/Esoteric_MAX_Public/) | [Esoteric_MAX_Public](https://github.com/UlaYuga/Esoteric_MAX_Public) |
| **Веселая Ферма** | [Open demo](https://ulayuga.github.io/farmfun-chat-demo/) | [farmfun-chat-demo](https://github.com/UlaYuga/farmfun-chat-demo) |
| **Незнакомец** | [Open demo](https://ulayuga.github.io/Neznakomets-web/) | [Neznakomets-web](https://github.com/UlaYuga/Neznakomets-web) |
| **ULA Lab** | [Open app](https://ulalab.online/) | Private |
| **FKNG MARK** | [Open demo](https://ulayuga.github.io/launch-engine-demo/) | [launch-engine-demo](https://github.com/UlaYuga/launch-engine-demo) |
| **Promo Preflight** | [Open app](https://promo-preflight-production.up.railway.app/) | Private |

---

## Portfolio

| Product | What it is | Where |
|---|---|---|
| **[ULA Lab](https://ulalab.online)** | A web tool that models how alcohol agents shift green coffee flavor before roasting. Eighteen-SKU catalog with provenance, eight-axis flavor prediction (peat, medicinal, oak, sweetness, coast, fruit, floral, spice), confidence scoring for every forecast, batch-CSV pipeline. Built for Q-graders, fermentation specialists, and coffee R\&D. Currently in CustDev interviews. | [ulalab.online](https://ulalab.online) |
| **[Promo Preflight](https://promo-preflight-production.up.railway.app/)** | A launch-readiness workspace for regulated promo campaigns. Campaign bundle intake, 8-stage / 23-rule offline risk checks, blocker evidence, suggested fixes, owner matrix, Go/No-Go board, Slack-ready handoff, saved local runs, and version diffing. Built as a serious internal-tool study for iGaming promo operations, with no auth, no player-facing flow, and no raw campaign storage. | [Railway app](https://promo-preflight-production.up.railway.app/) |
| **[Гадалка](https://ulayuga.github.io/Esoteric_MAX_Public/)** *(Fortune Teller)* | An esoteric mini-app inside MAX messenger. Four tools — compatibility, daily tarot, name analysis, dream decoder. No pre-written templates; every reading generated fresh by DeepSeek V3.2 via Yandex AI Studio. Paid unlocks through YooKassa СБП. Launching into a market Telegram just vacated — Russia banned it April 1, 2026, and the esoteric niche inside MAX is empty. Window of opportunity comparable to early Telegram. | [MAX demo](https://ulayuga.github.io/Esoteric_MAX_Public/) |
| **[FarmFun](https://ulayuga.github.io/farmfun-chat-demo/)** | A casual farming clicker for MAX. Built for women 35–55, three-to-four short sessions a day. Seasonal crops, plot unlocks, PvP steals, friend deep-links, weekly tournaments, streaks, push retention. Post-harvest AI advisor surfaces tips. Node.js, SQLite, Docker on Yandex Cloud. Monetization through plot upgrades and fertilizer packs. | [Chat demo](https://ulayuga.github.io/farmfun-chat-demo/) |
| **[Незнакомец](https://ulayuga.github.io/Neznakomets-web/)** *(The Stranger)* | A cinematic romance-thriller visual novel for VK Mini App. After a breakup, the heroine starts getting messages from Mark — who knows too much about her. Not horror, not melodrama — something in between. Two hundred scenes, three chapters, three endings. Player's VK name auto-injected into dialogue. Mark voiced via ElevenLabs TTS. Running in a genre dominated by ten-year-old pixel art. | [Web demo](https://ulayuga.github.io/Neznakomets-web/) |
| **ULA Morta** | Debut coffee from the ULA brand. A concept object — intersection of taste, mythology, dark-medieval aesthetic, and packaging narrative. Laphroaig-10 barrel-soak on Honduras Washed beans, seventy-two-hour infusion, A/B/C variants in cupping. Cassette-format packaging in a Norelco case with five-panel J-card and vacuum-sealed 20g bag. Three-part narrative — Side A, Side B, Center. Limited first edition. | Limited release |
| **ULA Honey Horse** *(coming)* | ULA's second coffee release. Honey-infused as the warm counterpart to Morta — if Morta is dark-medieval, whisky, smoke and ash, Honey Horse is sunlit paganism, wild grass, slow amber. Same barrel-infusion method, opposite mood. Currently in development, first lot planned for Summer 2026. | In development |

---

## Stack

![TypeScript](https://img.shields.io/badge/TypeScript-21262d?style=for-the-badge&logo=typescript&logoColor=f0f6fc&labelColor=161b22)
![Next.js](https://img.shields.io/badge/Next.js-21262d?style=for-the-badge&logo=next.js&logoColor=f0f6fc&labelColor=161b22)
![Node.js](https://img.shields.io/badge/Node.js-21262d?style=for-the-badge&logo=node.js&logoColor=f0f6fc&labelColor=161b22)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-21262d?style=for-the-badge&logo=postgresql&logoColor=f0f6fc&labelColor=161b22)
![Zod](https://img.shields.io/badge/Zod-21262d?style=for-the-badge&logo=zod&logoColor=f0f6fc&labelColor=161b22)
![Railway](https://img.shields.io/badge/Railway-21262d?style=for-the-badge&logo=railway&logoColor=f0f6fc&labelColor=161b22)
![Drizzle](https://img.shields.io/badge/Drizzle-21262d?style=for-the-badge&logo=drizzle&logoColor=f0f6fc&labelColor=161b22)
![Docker](https://img.shields.io/badge/Docker-21262d?style=for-the-badge&logo=docker&logoColor=f0f6fc&labelColor=161b22)
![Python](https://img.shields.io/badge/Python-21262d?style=for-the-badge&logo=python&logoColor=f0f6fc&labelColor=161b22)
![Claude](https://img.shields.io/badge/Claude-21262d?style=for-the-badge&logo=anthropic&logoColor=f0f6fc&labelColor=161b22)
![Replicate](https://img.shields.io/badge/Replicate-21262d?style=for-the-badge&logo=replicate&logoColor=f0f6fc&labelColor=161b22)
![Yandex Cloud](https://img.shields.io/badge/Yandex_Cloud-21262d?style=for-the-badge&logo=yandexcloud&logoColor=f0f6fc&labelColor=161b22)

Claude does the thinking. Codex does the typing. I make the calls.

Compliant distribution only. No grey-hat, no multi-accounting. The engine is legal-by-design.

---

## Contact

Telegram is the fastest line. Brand work, product collaborations, conversations about solo building in Russian-speaking markets — all fair game.

[![Telegram](https://img.shields.io/badge/@HilzHilzHilz-8B0000?style=for-the-badge&logo=telegram&logoColor=f0f6fc&labelColor=161b22)](https://t.me/HilzHilzHilz)

---

<div align="center">

*Repos private. Products public. That's the whole deal.*

</div>
