# A Systematic Review of LoRaWAN for Agriculture Decision Support

(the structure of this repo and project management are based on
[Rando et. al](https://greenelab.github.io/covid19-review/))

Project Status:
| Section | Title | Status Issue | Submission Status | Venue | Links |
| -- | -- | -- | -- | -- | -- |
| Overview | LoRaWAN in Agricultural Decision Support Systems | ✔️ | In preparation | TBD | — |
| Physical Layer | Coverage, Energy, and Reliability Tradeoffs | — | Planned | TBD | — |
| Network Architecture | Gateways, Backhaul, and Scalability | — | Planned | TBD | — |
| Sensing Modalities | Soil, Crop, Weather, and Livestock Sensors | — | Planned | TBD | — |
| Data Pipelines | Edge Processing, Cloud Integration, and Interoperability | — | Planned | TBD | — |
| Decision Support | Agronomic, Environmental, and Operational Decisions | — | Planned | TBD | — |
| Comparative Analysis | LoRaWAN vs Cellular, NB-IoT, and Mesh | — | Planned | TBD | — |
| Methods | Systematic Review Protocol and Taxonomy | ✔️ | In preparation | TBD | — |

This project is under active development and accepting contributions!

---

## Code of Conduct

This project operates under a code of conduct.
Participation in this repository (issues, pull requests, discussions, or other contributions) implies agreement with the [Code of Conduct](CODE_OF_CONDUCT.md).
If you experience or observe violations, please raise the issue with the project maintainers (@avinashbaskaran).

---

## Project Description

The increasing deployment of low-cost sensing systems in agriculture has created a need for reliable, energy-efficient, and scalable wireless communication infrastructure.
**LoRaWAN** has emerged as a leading low-power wide-area networking (LPWAN) technology for agricultural monitoring and decision support, particularly in rural and resource-constrained environments.

This repository hosts a **systematic, open, and continuously updated review** of LoRaWAN technologies as they are applied to **agricultural decision support systems**, including:

- Field-scale and regional sensing deployments  
- Energy and lifetime constraints of distributed sensors  
- Network architectures and gateway strategies  
- Data pipelines linking sensing to actionable decisions  
- Comparisons with alternative wireless technologies  

The goal is to catalog existing deployments, and to extract design patterns, constraints, and failure modes that directly affect the quality, timeliness, and reliability of agricultural decision-making.

---

## Scope and Research Questions

This review focuses on the following guiding questions:

1. What agricultural decision-support tasks are currently enabled by LoRaWAN-based sensing?
2. What technical constraints (range, latency, energy, bandwidth) limit these applications?
3. How do network design choices affect data reliability and decision quality?
4. How does LoRaWAN compare with cellular, NB-IoT, and mesh networks in agricultural contexts?
5. What open challenges remain for scalable, maintainable, and farmer-accessible deployments?

---

## Contributions

We welcome contributions from researchers, engineers, extension specialists, farmers, and practitioners.

You will need a free [GitHub account](https://github.com/join).

Contribution guidelines are provided in [`CONTRIBUTING.md`](CONTRIBUTING.md).

Authorship will follow established community standards for systematic reviews and the
[ICMJE Guidelines](http://www.icmje.org/recommendations/browse/roles-and-responsibilities/defining-the-role-of-authors-and-contributors.html).

Non-academic contributors are encouraged to participate by:
- Opening issues describing real-world deployments
- Sharing datasets or performance observations
- Highlighting operational challenges and failures

---

## Pull Requests

If you are new to GitHub, see [`INSTRUCTIONS.md`](INSTRUCTIONS.md) for step-by-step guidance.

For questions or help, please open a **Request for Help** issue.

This project benefits from cross-disciplinary perspectives across:
- Wireless communications
- Agronomy and soil science
- Systems engineering
- Data science and decision support
- Rural infrastructure and sustainability

---

## Manubot

Manubot enables collaborative scholarly writing using GitHub-based workflows.
It automates citation handling, tracks manuscript versions, and supports transparent peer contribution.

Documentation:
- Manubot overview: https://manubot.org/
- Rootstock template: https://github.com/manubot/rootstock
- Usage guide: [`USAGE.md`](USAGE.md)
- Setup instructions: [`SETUP.md`](SETUP.md)

Please open an issue for Manubot-related questions or technical problems.

---

## Repository Structure

- [`README.md`](README.md): Project overview and entry point
- [`content/`](content): Manuscript source files (Markdown, citations, tables)
- [`output/`](output): Generated manuscript outputs (do not edit manually)
- [`webpage/`](webpage): Static HTML rendering of the manuscript
- [`build/`](build): Build scripts and tooling
- [`ci/`](ci): Continuous integration and deployment files

---

## License

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Unless otherwise noted, the manuscript content is licensed under **CC BY 4.0**, allowing reuse with attribution.

Code, configuration files, and structured data are additionally released under **CC0 1.0** where applicable to encourage reuse and reproducibility.

For licensing questions, please open an issue.

---
