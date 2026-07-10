# StructuredDesignMeerkats

Platform documentation for **Meerkats.ai** — a revenue attribution platform for Indian D2C brands.

## Documents

| File | Description |
|------|-------------|
| [DFD Index](docs/meerkats_dfd_index.html) | Overview + reading order for all docs |
| [DFD Level 0](docs/meerkats_dfd_level0.html) | Context diagram — system boundary, 11 external entities |
| [DFD Level 1](docs/meerkats_dfd_level1.html) | 7 major processes + 10 data stores |
| [DFD Level 2](docs/meerkats_dfd_level2.html) | 28 sub-processes across 7 swim lanes |
| [DFD Level 3](docs/meerkats_dfd_level3.html) | All 26 tables across 9 layer swim lanes |
| [ER Diagram](docs/meerkats_er_diagram.html) | 26 entities, crow's foot notation, all FK relationships |
| [Flowchart + Decision Tree](docs/meerkats_flowchart.html) | End-to-end platform flow + 9-node attribution decision tree |
| [Identity Flow](docs/meerkats_identity_flow.html) | Anonymous → identified → revenue walkthrough |
| [Layer Summary](docs/meerkats_layer_summary_web.html) | 14-page architecture document |

## Reading Order

- **Boardroom** → DFD Level 0
- **Architecture** → DFD Level 1 + Flowchart
- **Engineering** → DFD Level 2 + ER Diagram
- **Data Team** → DFD Level 3 + Attribution Decision Tree

## Platform

- **Stack:** Node.js · PostgreSQL · Next.js 14 · LangGraph
- **Schema:** 26 `workspace_*` tables across 9 layers
- **Attribution:** 3-path confidence scoring (1.0 / 0.7 / 0.0)
- **Proof point:** Purity Prayag — ROAS 0.60× → 0.81×, +26% uncounted revenue surfaced

---
*Meerkats AI · Church Street ESolutions Pvt Ltd · Bengaluru*
