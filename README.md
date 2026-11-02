# Li-Fi (Light Fidelity): Report and Review Article

![Topic](https://img.shields.io/badge/Topic-Li--Fi%20%2F%20Optical%20Wireless-orange)
![Standard](https://img.shields.io/badge/Standard-IEEE%20802.11bb-informational)
![Type](https://img.shields.io/badge/Type-Review%20Article-3776AB)
![Project](https://img.shields.io/badge/Course%20Project-2025-A51C30)
![Status](https://img.shields.io/badge/Status-Preprint%20(not%20peer%20reviewed)-yellow)
[![Preprint DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23898313.svg)](https://doi.org/10.5281/zenodo.23898313)
![License](https://img.shields.io/badge/License-MIT-green)

This repository contains work on **Li-Fi (Light Fidelity)**, a wireless communication technology that uses modulated light to transmit data. It holds two documents:

| Document | Description |
|---|---|
| **Review article (2026)** | *Li-Fi (Light Fidelity): A Critical Review of Operating Principles, Modulation, Standards, Performance Claims and Open Challenges.* A preprint, not peer reviewed. [DOI: 10.5281/zenodo.23898313](https://doi.org/10.5281/zenodo.23898313) |
| **Original report (2025)** | *Data Transmission via Li-Fi (Light Fidelity).* The first version, written as a course project for *Research and Presentation Methods* at Islamic Azad University, Ardabil Branch, supervised by Dr. Masoud Bekravi. |

## Review article

The review is an expanded and updated version of the 2025 report, a course project supervised by Dr. Masoud Bekravi (Research and Presentation Methods, Islamic Azad University, Ardabil Branch). It covers:

- **Terminology:** separating visible light communication (VLC), Li-Fi and free-space optics (FSO)
- **Architecture and channel:** the intensity-modulation/direct-detection (IM/DD) link and the line-of-sight channel model
- **Modulation and multiple access:** OOK, VPPM, PAM, optical OFDM (DCO-, ACO- and ADO-OFDM), color-domain techniques
- **Standards:** IEEE 802.15.7, ITU-T G.9991 and IEEE 802.11bb (2023)
- **Data rates in context:** laboratory records compared with standard peak rates and vendor-reported figures
- **Applications, limitations and open challenges:** with an indication of maturity
- **Related technology:** free-space optics (Taara)

**Read it:** [Zenodo record](https://doi.org/10.5281/zenodo.23898313) · [`docs/LiFi_Critical_Review_2026_preprint.docx`](docs/LiFi_Critical_Review_2026_preprint.docx)

> Status: preprint (version 1, November 2026). It has not been peer reviewed.

## Original 2025 report

[`docs/LiFi_paper_EN.docx`](docs/LiFi_paper_EN.docx) is the original report, written as a course project for **Research and Presentation Methods** at Islamic Azad University, Ardabil Branch, under the supervision of **Dr. Masoud Bekravi**. It is kept for reference. The 2026 review supersedes it.

## Figures

Figures from the review are in [`figures/`](figures/):

- `review_fig1_architecture.png`: generic Li-Fi link architecture
- `review_fig2_modulation_taxonomy.png`: taxonomy of modulation schemes
- `review_fig3_data_rates.png`: reported data rates in context (log scale)

## Academic context

The original report was prepared as a project for **Research and Presentation Methods** during my B.Sc. in Computer Engineering at Islamic Azad University, Ardabil Branch, under the supervision of **Dr. Masoud Bekravi**.

## How to cite

```
Khadiv, E. (2026). Li-Fi (Light Fidelity): A Critical Review of Operating Principles,
Modulation, Standards, Performance Claims and Open Challenges. Zenodo.
https://doi.org/10.5281/zenodo.23898313
```

A machine-readable citation is in [`CITATION.cff`](CITATION.cff), and GitHub shows a "Cite this repository" button from it.

## Repository structure

```
LiFi-Report/
├── docs/
│   ├── LiFi_paper_EN.docx                      # original 2025 report
│   └── LiFi_Critical_Review_2026_preprint.docx # 2026 review (preprint)
├── figures/
├── CITATION.cff
├── LICENSE
└── README.md
```

## License

Repository contents are under the MIT License (see [`LICENSE`](LICENSE)). The review manuscript on Zenodo is released under CC BY 4.0.
