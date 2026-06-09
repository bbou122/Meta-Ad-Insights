# Meta Ad Library Intelligence Dashboard

**Built by Braden Bourgeois** · [Live Dashboard →](https://your-url-here)

An interactive political and corporate advertising intelligence tool built entirely from Meta's public Ad Library data. No paid tools. No APIs. Just raw data, Python, and a single self-contained HTML file.

---

## What It Does

This dashboard transforms 526,000+ advertiser records from the Meta Ad Library into a fully interactive intelligence platform — revealing not just who spent the most, but *how* they spent it, *where* it went, and *why* it matters.

Six sections, all built on real data:

**📈 Overview** — National spend totals, top 20 advertisers, a US choropleth map, and a spend vs. ad volume scatter plot showing strategic positioning at a glance.

**🏆 Spend Leaderboard** — Searchable, filterable, sortable table of the top 200 advertisers with inline spend bars, category tags, and efficiency ratings. Filter by Political, Advocacy, Media, or Corporate.

**⚡ Efficiency Analysis** — The metric most people ignore: cost per ad. A quadrant scatter surfaces who runs thousands of cheap creatives (volume/reach strategy) vs. who runs a few premium targeted placements. Trump: $171/ad. Biden: $980/ad. Same race, completely different playbooks.

**⚔️ Candidate Comparison** — Select any 2–4 figures for a head-to-head breakdown of total spend, ad volume, cost-per-ad, and strategy type. Auto-generated insights explain what the numbers actually mean.

**🗺️ Geographic Intelligence** — Clickable US choropleth map with state-level spend totals and a top-advertiser breakdown for 20 key states. Pennsylvania alone saw $309M in political ads.

**💰 Follow the Money** — The section most dashboards miss. Corporate industry lobbying breakdowns, cause-vs.-corporate battle charts (Oil & Gas vs. conservation, NRA vs. gun safety, PhRMA vs. healthcare advocates), an astroturf exposé table showing pages with innocuous names backed by industry money, and a media ecosystem analysis showing how conservative outlets like PragerU ($38.8M) and Newsmax ($20.6M) use political ad space to buy politically-engaged audiences.

---

## Key Findings

- **Joe Biden** is the all-time top spender at **$135M**, but ran only 137K ads — a premium, targeted approach
- **Donald Trump** ran **708,000 ads** at $171/ad — the most aggressive volume strategy of any major candidate
- **Big Tech** (Meta, Facebook, Instagram combined) spent **~$90M** in the political ad space — advertising their own platforms
- **Oil & Gas** (API/Energy Citizens, ExxonMobil, Shell) spent **~$52M** on narrative ads — not product ads
- Environmental advocacy groups **outspent** the fossil fuel industry on Meta: ~$57M vs. ~$52M
- **PragerU** spent $38.8M — more than the RNC — almost entirely on audience acquisition, not policy
- "**Energy Citizens**" sounds grassroots. The disclaimer says American Petroleum Institute.

---

## Technical Approach

- **Data source:** Meta Ad Library Report (US, Lifelong) — 526,961 advertiser records, 57 state-level CSVs
- **Processing:** Python — aggregated by page ID across disclaimers/committees, extracted state-level top advertisers for 20 key states
- **Visualization:** Plotly.js — choropleth maps, scatter plots, grouped bars, donuts
- **Delivery:** Single self-contained HTML file — no server, no dependencies, opens in any browser

Everything runs client-side. The processed data is embedded directly in the file.

---

## About

Built by **Braden Bourgeois** as a portfolio demonstration of data analysis, visualization, and storytelling with public datasets.

The goal wasn't just to display numbers — it was to surface the narratives hidden inside them. Political ad data is publicly available. Most people scroll past it. This dashboard makes it impossible to ignore.

---

*Data sourced from the [Meta Ad Library](https://www.facebook.com/ads/library). Report date: June 6, 2026.*
