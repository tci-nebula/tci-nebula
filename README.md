## Hi, I'm Nick 👋

Developer based in Japan. I build small, focused web tools — mostly TypeScript on
Cloudflare Workers, with D1 and KV for state. I like things that stay cheap to run,
are honest about their trade-offs, and do one job properly.

### Live

| Project | What it is |
| --- | --- |
| **[CadenceFX](https://cadencefx.com)** | Monitors the USD/CAD exchange rate every trading day and sends a free email alert when it moves meaningfully. Bank of Canada data, no noise. |
| **[TotoALL](https://play.totoall.net)** | Free-to-play multi-league football prediction game — headless and API-first, so people and AI agents play the same way. Three in-season leagues ingest, lock, and resolve through a cron pipeline. |

### Open source

| Project | What it is |
| --- | --- |
| **[pulsecheck](https://github.com/tci-nebula/pulsecheck)** | Uptime monitor that runs entirely in one Cloudflare Worker. Cron probes → D1 time-series → JSON API and status page. Rolling 24h/7d uptime is aggregated in SQL, so request cost doesn't grow with history. |
| **[streakboard](https://github.com/tci-nebula/streakboard)** | Local-first habit tracker with streaks and a contribution-style heatmap. React 19 + Vite. Data stays in your browser via IndexedDB — no backend, no accounts, exportable as JSON. |
| **[ratewatch](https://github.com/tci-nebula/ratewatch)** | CLI that tracks foreign-exchange rates and alerts when they cross a threshold. Public ECB data via Frankfurter — no keys, no accounts. |

### Not public

**priorart** — A prior-art gap scoring engine for patent work. BigQuery assembles a coarse
candidate pool from embeddings and citations; the engine then has Claude make the
claim-limitation-level gap distinction that abstract similarity can't resolve. Matter-agnostic
by design — the rubric changes per patent, the engine doesn't. Ships as a CLI plus an MCP
server. Private repo, but happy to talk about it.

### A bit more

- 🇯🇵 Based in Japan — I also run an import/export ecommerce business here
- 🏉 Wheelchair rugby athlete
- 📫 nick.kovac@targetcast.jp
- 😄 he/him

⚡ I wanted to learn German in high school and ended up going on exchange to Japan instead. Never looked back.
