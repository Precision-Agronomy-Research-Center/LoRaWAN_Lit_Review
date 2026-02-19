# A Systematic Review of LoRa/LoRaWAN Network Design and Performance in Agriculture

*(This project adopts a living, collaborative review model inspired by Rando et al. and the Greene Lab living review framework.)*

---

## Project Status and Review Workflow

This review follows a **technical systematic review workflow**, emphasizing measurable network and system-level performance in real agricultural deployments.

Manuscript sections are developed only after empirical evidence has been identified, screened, and synthesized.

| Review Stage | Description | Status |
|--------------|------------|--------|
| Protocol Definition | Define research questions, metrics, and search strategy | ✔️ Active |
| Literature Search | Execute database searches and identify candidate studies | ✔️ Active |
| Screening | Apply inclusion and exclusion criteria | ⏳ Ongoing |
| Data Extraction | Record technical implementation and performance metrics | ⏳ Planned |
| Quantitative Synthesis | Compare reported performance across deployments | — Planned |
| Writing | Draft manuscript sections based on synthesized results | — Planned |
| Living Updates | Periodically incorporate new literature | — Ongoing |

This project is **under active development** and welcomes contributions.

---

## Review Protocol

### Primary Research Question

> **How are LoRa and LoRaWAN systems architected, implemented, and characterized in agricultural deployments, and what measurable network behaviors determine their scalability and reliability?**

### Secondary Questions

- How do spreading factor selection and ADR behavior affect field performance?
- What packet delivery ratios (PDR) are reported under different agricultural conditions?
- How does vegetation or canopy affect link budget and propagation?
- How does collision behavior scale with node density?
- What are the reported time-on-air and duty-cycle constraints in real deployments?
- How is downlink latency managed for actuation systems?
- How are gateway placement and topology decisions justified?

---

## Literature Search Strategy

The literature search targets peer-reviewed and grey literature describing **implemented LoRa/LoRaWAN systems in agricultural environments** with measurable performance characterization.

### Sources

- IEEE Xplore  
- ACM Digital Library  
- Scopus  
- Web of Science  
- Google Scholar  
- Selected theses and technical reports  

### Search Emphasis

- LoRa / LoRaWAN  
- Agricultural deployment contexts  
- Network architecture and protocol behavior  
- Measured metrics such as:
  - Packet Delivery Ratio (PDR)
  - Collision probability
  - Link budget and propagation
  - Spreading factor and ADR behavior
  - Time-on-air
  - Downlink latency
  - Scalability

All queries and search dates are documented in the repository for reproducibility.

---

## Inclusion and Exclusion Criteria

### Inclusion Criteria

Studies are included if they:

- Describe an implemented LoRa or LoRaWAN system deployed in an agricultural context (field, greenhouse, livestock, pasture, soil, irrigation, etc.)
- Report measurable network or system-level performance metrics (e.g., PDR, collision rate, latency, link budget, spreading factor distribution, time-on-air, scalability, propagation behavior)
- Provide sufficient technical detail on architecture, topology, hardware configuration, or protocol parameters
- Include experimental, prototype, testbed, or field validation

### Exclusion Criteria

Studies are excluded if they:

- Are purely theoretical, simulation-only, or review papers without empirical agricultural deployment
- Focus exclusively on application-layer outcomes (e.g., crop prediction models) without reporting network performance
- Do not involve LoRa or LoRaWAN at the physical or network layer
- Lack sufficient technical implementation detail to support design-level analysis

---

## Data Extraction

For each included study, the following information is recorded.

### Deployment Context
- Agricultural setting (crop, livestock, irrigation, greenhouse, etc.)
- Physical environment (open field, canopy, indoor barn, etc.)

### Network Architecture
- Topology (star, star-of-stars, multihop, mesh)
- Gateway count and placement strategy
- Node density

### Protocol Parameters
- Spreading factor distribution
- ADR usage
- MAC protocol (ALOHA, LBT, TDMA, etc.)
- Device class (A/B/C)

### Performance Metrics
- Packet Delivery Ratio (PDR)
- Collision behavior
- Latency (uplink and downlink)
- Link budget or RSSI/SNR measurements
- Time-on-air
- Duty-cycle constraints
- Scalability limits
- Propagation effects (foliage, canopy, terrain)

### Validation Type
- Field measurement
- Prototype deployment
- Testbed
- Long-term monitoring

Extraction templates are standardized and version-controlled within the repository.

---

## Synthesis Approach

Findings are synthesized by:

- Comparing reported PDR across environments and densities
- Mapping collision behavior to topology and MAC design
- Relating spreading factor choices to reliability and scalability
- Evaluating propagation effects under vegetation and terrain
- Identifying common bottlenecks (duty cycle, ADR misconfiguration, gateway saturation)
- Comparing architectural patterns across use cases

Where possible, performance values will be aggregated and visualized to support cross-study comparison.

---

## Project Description

LoRaWAN has become one of the most widely deployed LPWAN technologies in agriculture. However, existing surveys primarily summarize application domains rather than systematically analyzing **how systems are engineered and how they perform under real agricultural constraints**.

This project provides a structured, living review of:

- Implemented LoRa/LoRaWAN agricultural systems  
- Their network design decisions  
- Their measurable performance characteristics  
- Their scalability limits and architectural tradeoffs  

The goal is to clarify:

- What performance is realistically achievable  
- What design choices matter most  
- Where empirical gaps remain  

---

## Contributions

We welcome contributions from:

- Communications researchers  
- Systems engineers  
- Agricultural technologists  
- Network architects  
- Practitioners with field deployments  

Contributors may help by:

- Adding or screening relevant literature  
- Extracting technical metrics  
- Reporting real deployment measurements  
- Assisting with quantitative synthesis  

Authorship follows community standards and the ICMJE Guidelines.

See `CONTRIBUTING.md` for details.
