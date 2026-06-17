# Regional Insights on Transport in Third-Generation NDCs

An interactive, single-file dashboard exploring how transport is represented across six world regions in third-generation Nationally Determined Contributions (NDCs), submitted to the UNFCCC under the Paris Agreement.

**→ [View the live dashboard](https://slocat-partnership.github.io/ndc-transport-regions/lite/)**

**→ [View the live light version dashboard](https://slocat-partnership.github.io/ndc-transport-regions/lite/)**


---

## About

This dashboard is developed by [SLOCAT Partnership](https://slocat.net) and draws on data from the [NDC Transport Tracker](https://changing-transport.org/tracker/), a joint initiative by GIZ and SLOCAT. It accompanies the report [*Is transport on track for 1.5°C? Insights from the new NDCs*](https://slocat.net/ndcs/).

Data covers NDC submissions as of **26 May 2026**.

---

## What the dashboard shows

Users can select one of six regions (Africa, Asia, Europe, Latin America and the Caribbean, North America, and Oceania) to explore:

- **NDC submission overview**: number of NDCs submitted relative to total Parties in the region
- **Transport mitigation actions**: breakdown by category (mode shift, transport system improvements, energy efficiency, electrification, alternative fuels, aviation & maritime), compared against global totals
- **Mitigation action mix**: regional share of each category vs. the global average
- **Avoid–Shift–Improve (ASI) framework**: distribution of mitigation actions across the three ASI categories, with global reference
- **Transport adaptation & resilience**: adaptation action categories and totals, regional vs. global
- **Country-level targets**: GHG mitigation and adaptation targets for individual countries within the region

---

## Technical notes

- **Single self-contained file** — all data and logic are embedded in `index.html`; no build process, server, or external data files are required
- **No dependencies** — the dashboard functions fully offline if fonts are cached
- **Hosted via GitHub Pages** 

---

## Data source & coverage

| Region | NDCs submitted | Total Parties |
|---|---|---|
| Africa | 32 | 54 |
| Asia | 32 | 48 |
| Europe | 41 | 46 |
| Latin America & the Caribbean | 24 | 33 |
| North America | 2 | 2 |
| Oceania | 13 | 16 |

Global total: **118 third-generation NDCs** (85% of all UNFCCC Parties).

The NDCs are sourced from the [UNFCCC NDC Registry](https://unfccc.int/NDCREG).

---

## Updating the data

All data is stored as a JavaScript object (`REGIONS`) near the top of the `<script>` section in `index.html`. To update figures or add new countries, edit the relevant values directly in that object and re-upload the file.

---

## Licence & attribution

Developed by SLOCAT Partnership. Data sourced from the NDC Transport Tracker (GIZ & SLOCAT). Please credit SLOCAT when reproducing or adapting this work.
