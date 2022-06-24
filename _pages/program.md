---
title: Program
permalink: "/program/"
author_profile: true
sitemap: false
classes: wide
redirect_from:
- "/agenda/"
---

---

## Tuesday, October 20


|  Time             | Session                         |
| ----------------- |-------------------------------- |
|  8:30am - 10:00am | [__MODEVAR Session 1__](#modevar-session-1-830am---1000am) |
|                   | __Keynote: “Standardizing languages – promises and perils”__ _Oysten Haugen_ (45 min) |
|                   | __“Towards a Universal Variability Language”__ _Dominik Engelhardt, Chico Sundermann, Thomas Thüm, Ina Schaefer_  (~35 min) | 
| 10:30am - 12:00pm | [__MODEVAR Session 2__](#modevar-session-2-1030am---1200pm)           |
|                   | __“Towards Transforming Variability Models: Usage Scenarios, Required Capabilities and Challenges”__ _Kevin Feichtinger and Rick Rabiser_ (45 min) |
|                   | __“A Python framework for the automated analysis of feature models.”__ _José A. Galindo and David Benavides_  (45 min) |
|  12:30pm - 2:00pm |  [__MODEVAR Session 3__](#modevar-session-3-1230pm---2pm)          |
|                   | __Keynote: “The Dhall Configuration Language”__  _Gabriel Gonzalez_ (45 min) |
|                   | __Final discussions (summary, action points, etc.)__  | 







## MODEVAR Session 1, 8:30am - 10:00am

__Keynote: “Standardizing languages – promises and perils”__
_Oystein Haugen_   (45 minutes, including Q/A)

Oystein will *not* only talk about his experience with the Common Variability Language (CVL) standardization. Oystein has been involved with a number of standardization efforts on languages in both ITU and OMG, and will talk about standardizing languages in a broad sense, including promises and perils.

__“Towards a Universal Variability Language”__ 
_Dominik Engelhardt, Thomas Thüm, Ina Schaefer_  (~35 minutes, including Q/A)

While feature diagrams have become the de facto standard to graphically describe variability models in Software Product Line Engineering (SPLE), none of the many textual notations have gained widespread adoption.
However, a common textual language would be beneficial for better collaboration and exchange between tools. The main goal of this line of work is to propose a language for this purpose, along with fundamental tool support. The language should meet the needs and preferences of the community, so it can attain acceptance and adoption, without becoming yet another variability language. Its guiding principles are simplicity, familiarity, and flexibility.
These enable the language to be easy to learn and to integrate into different tools, while still being expressive enough to represent existing and future models. We incorporate general design principles for Domain-Specic Languages (DSLs), discuss usage scenarios collected by the community, analyze existing languages, and gather feedback directly through questionnaires submitted to the community.
In the initial questionnaire, the community was in disagreement on whether to use nesting or references to represent the hierarchy. Thus, we presented two proposals to be compared side by side. Of those, the community clearly prefers the one using nesting, as determined by a second questionnaire.
We call that proposal the Universal Variability Language (UVL). The community awards good ratings to this language, deems it suitable for teaching and learning, and estimates that it can represent most of the existing models.
Evaluations reconsidering the requirements show that it enables the relevant scenarios and can support the editing of large-scale real-world feature models, such as the Linux kernel.
We provide a small default library that can be used in Java, containing a parser and a printer for the language. We integrated it into the variability tool FeatureIDE, demonstrating its utility in quickly adding support for the proposed language. Overall, we can conclude that UVL is well-suited for a base language level of a universal textual variability language.
Along with the acquired insights into the requirements for such a language, it can pose as the basis for the SPLE community to commit to a common language. As exchange and collaboration would be simplified, higher-quality research could be conducted and better tools developed, serving the whole community.


## MODEVAR Session 2, 10:30am - 12:00pm

__“Towards Transforming Variability Models: Usage Scenarios, Required Capabilities and Challenges”__
_Kevin Feichtinger and Rick Rabiser_ (45 minutes, including Q/A)

A plethora of variability modeling approaches has been developed in the last 30 years, e.g., feature modeling, decision modeling, Orthogonal Variability Modeling (OVM), and UML-based variability modeling. While feature modeling approaches are probably the most common and well-known group of variability modeling approaches, even within that group multiple variants have been developed, i.e., there is not just one type of feature model. Many variability modeling approaches have been demonstrated as useful for a certain purpose, e.g., domain analysis or configuration of products derived from a software product line. Nevertheless, industry frequently develops their own custom solutions to manage variability. The (still growing) number of modeling approaches simply makes it difficult to find, understand, and eventually pick an approach for a specific (set of) systems or context. In this paper, we discuss usage scenarios, required capabilities and challenges for an approach for (semi-)automatically transforming variability models. Such an approach would support researchers and practitioners in experimenting with and comparing different variability models and switching from one modeling approach to another. We present the key components of our envisioned approach and conclude with a research agenda.

__“A Python framework for the automated analysis of feature models.”__
_José A. Galindo and David Benavides_  (45 minutes, including Q/A)

Feature modeling is the ``de facto'' standard to describe the common and variant parts of software product lines. Different tools, approaches, and operations for the automated analysis of feature models (AAFM) have been proposed in the last 20 years. The increasing popularity of languages such as Python made the usage of AAFM techniques require lots of integration efforts with exiting Java-based tools. In this paper, we present a design for a Python-based framework to analyze feature models. This framework implements the most common operations while enabling support for multiple solvers and backends.

## MODEVAR Session 3, 12:30pm - 2pm

__Keynote: “The Dhall Configuration Language”__ 
_Gabriel Gonzalez_ (45 minutes, including Q/A)

Dhall is a configuration language that began life as an academic exercise in building a non-Turing-complete programming language and then evolved into an industrial language with IDE support, a package ecosystem, a language standard, and even some amateur marketing.  This talk will highlight some features of Dhall that might inspire feature modeling languages such as declarative syntax, strong normalization, and dependent types.  Additionally, the talk will cover lessons learned about building tooling and mindshare to promote adoption of a fledgling language.

__Final discussions (summary, action points, etc.)__
