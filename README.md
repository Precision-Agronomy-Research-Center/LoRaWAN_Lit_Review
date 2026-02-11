# A Systematic Review of LoRaWAN for Agricultural Decision Support

*(This project adopts a living, collaborative review model based on Rando et al. and the Greene Lab COVID-19 Review.)*

---

## Project Status and Review Workflow

This review follows a **standard systematic review workflow**, adapted for continuous, collaborative updating.  
Manuscript sections are developed only after evidence has been identified, screened, and summarized.

| Review Stage | Description | Status |
|---|---|---|
| Protocol Definition | Define research questions, search strategy, and inclusion criteria | ✔️ Active |
| Literature Search | Execute database searches and identify candidate studies | ✔️ Active |
| Screening | Apply inclusion and exclusion criteria | ⏳ Ongoing |
| Data Extraction | Record key technical and application details from included studies | ⏳ Planned |
| Synthesis | Summarize findings across studies | — Planned |
| Writing | Draft manuscript sections based on synthesized results | — Planned |
| Living Updates | Periodically incorporate new literature | — Ongoing |

This project is **under active development** and **accepting contributions at all stages**.

---

## Review Protocol

### Research Question

This review addresses the following primary question:

> **How is LoRaWAN used in agricultural decision support systems, and what factors determine whether those systems effectively support decisions?**

Secondary questions include:
- What types of agricultural decisions are reported?
- What technical constraints are commonly encountered?
- How do reported deployments perform in practice?
- How does LoRaWAN compare to alternative wireless technologies in agricultural settings?

---

### Literature Search Strategy

The literature search targets peer-reviewed and grey literature describing **LoRaWAN deployments in agriculture**.

Sources include:
- IEEE Xplore
- ACM Digital Library
- Scopus
- Web of Science
- Google Scholar
- Selected reports and theses reflecting topics not well addressed in peer-reviewed literature

Search terms include combinations of:
- *LoRaWAN*, *LoRa*
- *agriculture*, *farming*, *precision agriculture*
- *decision support*, *monitoring*, *sensing*, *IoT*

The exact search strings and dates are documented in the repository for transparency and reproducibility.

---

### Inclusion and Exclusion Criteria

Studies are included if they:
- Describe a LoRaWAN-based system applied to an agricultural context
- Report on sensing, data collection, or system performance
- Link sensing data to an agricultural monitoring or decision-support use case

Studies are excluded if they:
- Are purely theoretical with no agricultural application
- Do not involve LoRa or LoRaWAN
- Lack sufficient technical or application detail

---

### Data Extraction

For each included study, the following information is recorded:
- Agricultural context and use case
- Sensors and data collected
- Network configuration and scale
- Reported performance (e.g., range, reliability, energy use)
- Reported limitations, failures, or challenges
- Comparison to other communication technologies (if provided)

Extraction fields are standardized and documented in the repository.

---

### Synthesis Approach

Findings are summarized by:
- Aggregating reported use cases and decision types
- Identifying common technical constraints and failure modes
- Comparing reported performance across deployments
- Highlighting recurring design choices and tradeoffs

Manuscript sections are created **after** synthesis, based on what patterns emerge in the literature.

---

## Project Description

The increasing deployment of low-cost sensing systems in agriculture has created a need for wireless communication infrastructure that is reliable, energy-efficient, and scalable in rural and resource-constrained environments.

**LoRaWAN** has emerged as a widely used low-power wide-area networking (LPWAN) technology in this space. However, published deployments vary widely in design, performance, and usefulness for real agricultural decision-making.

This repository hosts a **systematic, open, and continuously updated review** of LoRaWAN-based agricultural decision support systems, with the goal of clarifying:
- What LoRaWAN is actually being used for in agriculture
- Where it works well and where it does not
- What practical constraints matter most for deployment and maintenance

---

## Contributions

We welcome contributions from researchers, engineers, extension specialists, farmers, and practitioners.

Contributors may help by:
- Adding or screening relevant literature
- Extracting data from published studies
- Reporting real-world deployment experiences
- Assisting with synthesis and writing

Authorship follows established community standards for systematic reviews and the  
[ICMJE Guidelines](http://www.icmje.org/recommendations/browse/roles-and-responsibilities/defining-the-role-of-authors-and-contributors.html).

Contribution details are provided in [`CONTRIBUTING.md`](CONTRIBUTING.md).

---

## Governance, Tooling, and Transparency

*(Remaining sections: Code of Conduct, Pull Requests, Manubot, Repository Structure, License — unchanged.)*
