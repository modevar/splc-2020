---
title: Submission Guidelines
permalink: "/submission/"
author_profile: true
classes: wide
redirect_from:
- "/call-for-papers/"
---

## [Submission link](https://easychair.org/conferences/?conf=splc2020)

 
MODEVAR will receive your submissions via the [official SPLC EasyChair for SPLC](https://easychair.org/conferences/?conf=splc2020).
    - You must click on *New Submission* and select the "3rd W. on Languages for Modelling Variability".



## Submission Guidelines

The submissions must follow the guidelines defined for the SPLC 2020 workshops.

The open call is structured around two kinds of papers :

1. **Short papers (2 to 8 pages)** that will present original research, lessons learned, or a well-argued vision related (but
not limited) to the following topics on variability modelling languages:
    - **Concepts:** domain modelling, language constructs, mapping to other artefacts;
    - **Usages:** writing, reading, generation, reverse engineering, (de-)composition, benchmarking;
2. **Realization papers (4 to 8 pages)** that present an implemented solution or the assessment of an existing implementation, while being structuring by the fulfilled usage scenarios and the supported language levels:
    - **Usage scenarios** include: teaching/learning, storage, domain modeling, mapping to implementation, model generation, exchange, benchmark, analysis (more details in Thorsten Berger and Phillipe Collet. "Usage scenarios for a common feature model scenario" in MODEVAR at VaMoS 2020)
    - **Language levels**
        - 0 Basic constructs (optional, mandatory, group cardinalities), constraints (simple requires/excludes, propositional logic);
        - 1 Attributes (Enum, Integers, Ranges), complex relationships between features and attributes;
        - 2 Temporary constraints violation (visualization/visibility), interfaces from feature models, dependencies between feature models.
    - **A concrete and an abstract syntax** (as given by Thomas Thuem et al. "Towards a Universal Variability Language: Design Tradeoffs" in MODEVAR at VaMoS 2020) can guide the realization and can feed the discussions or the assessment of the proposal. For example, an implementation in JSON or in a fluent API may make it difficult to respect a given concrete syntax whereas some positive properties may emerge (e.g., better interoperability).

---
**Examples** of possible valuable realizations include but are not limited to:

  - Level 0 construct representation (domain modeling, concrete syntax) for learning and teaching;
  - Automated analysis and reasoning (e.g., dead feature, constraints redundancy), especially with languages supporting expressive constructs and levels;
  - Automated analyses with other artifacts (e.g., Web artifacts) made possible by the technological solution;
  - Any extension at Level 1 for supporting any usage scenario;
  - Any extension at Level 2 (which are orthogonal to concepts like information hiding and temporal notions in feature modeling) for supporting any usage scenario;
  - Any automated benchmarking of a previous realization.

---
The paper should describe the covered scenarios, the design choices of the implemented or assessed solution, design choices of this solution, resulting expressiveness tradeoffs, and technological dependencies. In addition, the paper should make available a publicly accessible git repository of the source code, a scenario of live demonstration, and possibly directions to play a demonstration by oneself. A preliminary assessment of the realization w.r.t. the scenarios and language levels could also be provided. For instance, if the proposal targets a teaching/learning scenario, one can expect either a (preliminary) assessment with students, an analysis of the concrete syntax (e.g., w.r.t. conciseness or naturalness) or the usability of the tools supporting the proposed language, or even a planned experimental setup that will be rigorously conducted in further research to demonstrate some expected properties of the proposal. 

All accepted papers will be included in the workshop proceedings and according to the guidelines of workshop chairs in the the SPLC
proceedings. As stated previously, whether we will have formal proceedings or not will depend on the nature of submissions and
prepared material.

