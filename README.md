# Data Transmission via Li-Fi (Light Fidelity)

![Topic](https://img.shields.io/badge/Topic-Optical%20Wireless%20Communication-0A7EA4)
![Format](https://img.shields.io/badge/Report-DOCX-2B579A?logo=microsoftword&logoColor=white)
![Citations](https://img.shields.io/badge/References-19%20(IEEE)-informational)
![License](https://img.shields.io/badge/License-MIT-green)

A technical research report on [Li-Fi](https://en.wikipedia.org/wiki/Li-Fi) (Light Fidelity), a wireless communication technology that transmits data by modulating visible light instead of radio waves. The report follows the technology from the physical principle, through the system architecture and the modulation schemes that make high-speed transmission possible, to its advantages, its limitations, and where it is being applied and developed today, including Google X's TAARA project. It was prepared as a course project for *Research and Presentation Method* during my B.Sc. in Computer Engineering at Islamic Azad University, Ardabil, under the supervision of Dr. Masoud Bekravi. All 19 references are cited in strict IEEE order and were checked against their sources.

## Contents

- [Report](#report)
- [Topic map](#topic-map)
- [Sections](#sections)
- [Concepts covered](#concepts-covered)
- [Figures](#figures)
- [References](#references)
- [Repository structure](#repository-structure)
- [Academic context](#academic-context)
- [License](#license)

## Report

The full report is a Word document:

**[Read the full report: `docs/LiFi_paper_EN.docx`](docs/LiFi_paper_EN.docx)**

GitHub does not preview `.docx` files in the browser, so use the download button on the file page and open it in Word, LibreOffice or Google Docs.

## Topic map

| Part | Topic | What it covers |
| --- | --- | --- |
| 1 | Fundamentals | Principles of visible-light communication and end-to-end data transmission |
| 2 | System architecture | Transmitter (LED), optical channel, photodetector |
| 3 | Intensity modulation | OOK and VPPM |
| 4 | Multicarrier modulation | OFDM and its optical variants: ACO-OFDM, DCO-OFDM, ADO-OFDM |
| 5 | Color-based communication | CSK and CIM |
| 6 | Advantages and limitations | Bandwidth, security, energy efficiency, line of sight, ambient-light interference |
| 7 | Applications | Healthcare, aviation, underwater communication, other specialized environments |
| 8 | Recent developments | Emerging optical wireless communication technologies, Google X's TAARA project |

## Sections

### Fundamentals

Explains how Li-Fi uses the visible-light spectrum as a carrier. Light sources such as LEDs are switched or dimmed fast enough that the human eye sees steady illumination while a receiver recovers the data encoded in the intensity or color changes. This section sets out the end-to-end transmission chain that the rest of the report builds on.

### System architecture

Breaks the link into its three physical parts: the **transmitter** (a driver circuit and LED that turns data into light), the **optical channel** (free-space propagation between source and receiver), and the **photodetector** (which converts the received light back into an electrical signal for demodulation).

### Modulation techniques

Visible-light links use intensity modulation with direct detection, so the transmitted signal must be real-valued and non-negative. The report compares the schemes designed around that constraint:

- **OOK (on-off keying)** and **VPPM (variable pulse position modulation)**: simple single-carrier schemes, with VPPM combining pulse-position coding with dimming control.
- **OFDM** and its optical variants **ACO-OFDM**, **DCO-OFDM** and **ADO-OFDM**: multicarrier schemes that adapt the classic OFDM waveform to a unipolar channel, each with a different trade-off between spectral efficiency and power efficiency.

### Color-based communication

Covers schemes that use the color of the light rather than only its brightness: **CSK (color-shift keying)** and **CIM (color intensity modulation)**, which exploit multi-color LEDs to carry additional information.

### Advantages and limitations

Weighs what Li-Fi offers (a large unlicensed bandwidth, security through confinement of light to a room, low electromagnetic interference, energy-efficient use of existing lighting) against what holds it back (the line-of-sight requirement, sensitivity to blockage, interference from ambient light, and limited range).

### Applications

Looks at settings where radio is restricted or unsuitable, including healthcare, aviation and underwater communication, along with other specialized environments.

### Recent developments

Surveys emerging optical wireless communication technologies and discusses Google X's **TAARA** project.

## Concepts covered

- **Optical wireless communication:** visible-light communication, intensity modulation with direct detection, LED transmitters, photodetectors
- **Modulation:** OOK, VPPM, OFDM, ACO-OFDM, DCO-OFDM, ADO-OFDM
- **Color-based schemes:** CSK, CIM
- **System analysis:** bandwidth, security, energy efficiency, line-of-sight and ambient-light constraints
- **Research practice:** literature review, IEEE-style referencing, technical diagrams

## Figures

The technical diagrams used in the report are stored in [`figures/`](figures) so they can be reused on their own.

## References

The report cites 19 sources, in order of first appearance, in IEEE style. They include peer-reviewed publications, conference proceedings and technical sources. The complete numbered list is at the end of the [report](docs/LiFi_paper_EN.docx).

## Repository structure

```
LiFi-Report/
├── docs/
│   └── LiFi_paper_EN.docx   # the full report
├── figures/                 # diagrams used in the report
├── LICENSE
└── README.md
```

## Academic context

Course project for **Research and Presentation Method**  
B.Sc. in Computer Engineering, Islamic Azad University, Ardabil Branch  
supervised by **Dr. Masoud Bekravi**.

## License

Released under the MIT license; see [LICENSE](LICENSE).
