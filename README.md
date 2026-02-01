# A Systematic Review of LoRaWAN for Agricultural Decision Support

*(This project adopts a living, collaborative review model based on Rando et al. and the Greene Lab COVID-19 Review.)*

---

## Project Status and Review Workflow

Rather than predefining topical sections, this review is organized around a **coordinated, question-driven review process**. Manuscript sections are instantiated only after sufficient evidence has been collected, screened, and synthesized.

| Review Stage | Description | Status | Issue Tracker |
|---|---|---|---|
| Protocol Definition | Review questions, inclusion criteria, taxonomy design | ✔️ | Active |
| Literature Acquisition | Search strategy, corpus expansion, citation tracking | ✔️ | Active |
| Screening & Annotation | Relevance screening, metadata extraction, tagging | ⏳ | Ongoing |
| Evidence Synthesis | Cross-study comparison, pattern identification | ⏳ | Planned |
| Section Formation | Emergent section drafting based on synthesis | — | Planned |
| Comparative & Gap Analysis | Cross-technology and cross-context comparison | — | Planned |
| Living Updates | Continuous incorporation of new literature | — | Continuous |

This project is **under active development** and **accepting contributions at all stages of the review lifecycle**.

---

## Review Framework

This review follows a **systems-level evidence synthesis framework** designed to connect communication infrastructure characteristics to downstream agricultural decision quality.

### Unit of Analysis
Each included study is treated as a **system instantiation**, characterized by:
- Deployment context (crop, livestock, environment, scale)
- Network configuration and constraints
- Data flow from sensing to decision
- Reported performance, failures, and tradeoffs

### Analytical Dimensions (Non-Prescriptive)
Rather than fixed sections, studies are annotated along **orthogonal dimensions**, which later give rise to manuscript structure:

- **Physical constraints** (energy, range, duty cycle, reliability)
- **Network design choices** (topology, gateways, backhaul)
- **Sensing–decision coupling** (what decisions depend on what data)
- **Operational context** (farm scale, labor, connectivity access)
- **Failure modes** (packet loss, maintenance burden, misalignment with decisions)
- **Comparative baselines** (cellular, NB-IoT, mesh, proprietary LPWANs)

Manuscript sections are formed only once stable clusters emerge across these dimensions.

---

## Project Description

The increasing deployment of low-cost sensing systems in agriculture has created a demand for wireless communication infrastructure that is reliable, energy-efficient, and scalable in rural and resource-constrained environments.

**LoRaWAN** has emerged as a widely adopted low-power wide-area networking (LPWAN) technology in this space. However, reported deployments vary widely in performance, architecture, and suitability for decision support.

This repository hosts a **systematic, open, and continuously updated review** of how LoRaWAN is used within **agricultural decision support systems**, with emphasis on:

- How sensing data is transformed into agronomic, environmental, or operational decisions  
- Which technical and organizational constraints limit decision quality  
- What design patterns recur across successful and failed deployments  

The objective is not merely to catalog technologies, but to **extract actionable system-level insights** that inform future agricultural sensing and decision infrastructures.

---

## Scope and Research Questions

This review is guided by the following high-level questions, which drive screening, annotation, and synthesis:

1. What agricultural decisions are actually supported by LoRaWAN-based sensing in practice?
2. How do physical-layer and network-level constraints propagate to decision latency, reliability, and usefulness?
3. Which design choices consistently succeed or fail across deployment contexts?
4. Under what conditions does LoRaWAN outperform or underperform alternative wireless technologies?
5. What unresolved challenges limit scalable, maintainable, and farmer-accessible deployments?

These questions shape the review process; **they do not presuppose the final manuscript structure**.

---

## Contributions

We welcome contributions from researchers, engineers, extension specialists, farmers, and practitioners.

Contributors may engage at any stage of the review process, including:
- Identifying and adding relevant literature
- Annotating deployments and extracting system metadata
- Reporting real-world operational experiences and failures
- Participating in synthesis and section formation

Authorship follows established community standards for systematic reviews and the  
[ICMJE Guidelines](http://www.icmje.org/recommendations/browse/roles-and-responsibilities/defining-the-role-of-authors-and-contributors.html).

Contribution details are provided in [`CONTRIBUTING.md`](CONTRIBUTING.md).

---

## Governance, Tooling, and Transparency

*(Remaining sections: Code of Conduct, Pull Requests, Manubot, Repository Structure, License — unchanged.)*
