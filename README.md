# Data Transmission via Li-Fi (Light Fidelity) Technology

A research report on Li-Fi (Light Fidelity), a wireless communication technology that transmits data through the modulation of visible light — covering its architecture, modulation techniques, advantages, limitations, applications, and recent developments (including Google X's TAARA project).

> This was a supplementary research report prepared for the "Wireless Networks" course — not a coding project, and not part of the author's AI/ML work (see [HBALS-TSP](https://github.com/ErfanKhadiv/HBALS-TSP) for that). Included here as a writing/research sample covering a different area of communications engineering.

## Contents

- [`docs/LiFi_paper_EN.docx`](docs/LiFi_paper_EN.docx) — full research report (academic English)
- [`figures/`](figures) — diagrams referenced in the report

## Summary

Li-Fi, introduced by Prof. Harald Haas (University of Edinburgh) in 2011, transmits data by rapidly modulating the light output of an LED — fast enough to be imperceptible to the human eye — and recovering the signal with a photodetector. The report covers:

- **Architecture & operation** — how optical signals are encoded, transmitted, and decoded end-to-end
- **Modulation techniques** — single-carrier (OOK, VPPM) and multi-carrier (OFDM and its optical variants: ACO-OFDM, DCO-OFDM, ADO-OFDM), plus color-based schemes (CSK, CIM)
- **Advantages** — security (light doesn't pass through walls), higher potential bandwidth, lower energy use, safe for aircraft and underwater use
- **Limitations** — dependence on line-of-sight and ambient lighting, weather sensitivity, infrastructure retrofit cost
- **Applications** — healthcare, aviation, underwater exploration, military use
- **Recent developments** — Google X's TAARA project (10 Gbps over 1 km using silicon photonic chips)

19 references — including peer-reviewed journal articles with DOIs, conference proceedings, and industry sources — all individually verified and numbered in strict order of first appearance in the text (IEEE convention).

## License

MIT — see [LICENSE](LICENSE). Figure 2 (Li-Fi operation diagram) is credited to pureLiFi (reference [6] in the report); Figure 1 is a diagram recreated in English from the author's original.
