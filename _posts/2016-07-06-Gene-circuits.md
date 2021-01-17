---
layout: post
title:  "Gene circuits"
date:   2016-07-06 07:00:00
categories: 
author: Prospect Bio
---
With a handful of molecular biology skills alongside a background in chemistry and physics, I traded UW-Madison for San Francisco hoping to join the bio-based economy, eventually landed at Prospect Bio as their first employee.

### Gene circuits for chemical identification and quantification
Prospect Bio was predicated on building a rapid and inexpensive alternative to traditional analytical methods for chemical identification and quantification. To this end, the company engineered bacteria to respond with high specificity to target compounds, productizing the success of previous academic [work](https://www.pnas.org/content/111/28/10143) that led to lignin by-product biosensors.


### Microbial/metagenomic DNA library
To exploit nature's ability to fit elegant solutions to challenging environments, we used
microbial DNA found in diverse environments (oil fields, highly salinated waters, deep ocean layers)
as starting points for genetic diversity. For microbial life to sustain life in these challenging environments they must adapt their cellular machinery to cope with the otherwise deadly conditions.
The adapted genes were inserted into Prospect Bio's expression vector which contained a fluorescent reporter gene downstream of the microbial DNA, and would generate a measurable fluorescent signal if the microbial DNA was expressed. The complete gene construct was transfected into
E.coli, the company's host organism of choice.

![Gene insert](https://wahorvat.gitlab.io/wahorvat/images/posts/gene-circuits/gene-insert.png){: .center-image }

### Implementation
To rapidly assay the metagenomic library, we optimized the E.coli growth and expression timing for 96- and 384-welled plates. Parallelizing biosensor discovery through our plate based approach provided scalability that traditional analytical methods could not offer.

![plates on plates](https://wahorvat.gitlab.io/wahorvat/images/posts/gene-circuits/workflow-sensors.png){: .center-image }

![To plates](https://wahorvat.gitlab.io/wahorvat/images/posts/gene-circuits/to-plates.png){: .center-image }

### Industry partnerships (Descending chronologically 2015-2018)
[Reliance Industries](https://www.ril.com/) - Prospect Bio developed an isoprene sensor for use with Reliance's bioreactors to produce petroleum product precursors.

[Ginkgo Bioworks](https://www.ginkgobioworks.com/) -
Gingko Bioworks asked for three small molecule biosensors, two of which were successfully delivered. This [partner project](https://synbiobeta.com/ginkgo-bioworks-prospect-bio-will-collaborate-develop-deploy-biosensors/) led to seed funding of nearly $3M.

[Constellation Brands](https://www.cbrands.com/) - To combat wine fraud Constellation Brands explored the possibility to rapidly discern wine varietals, and blends of varietals, with biosensors. Measuring heterogenous mixtures proved challenging but eventually possible through panels of biosenors coupled with classification ML analysis.

[Progenity](https://www.progenity.com/) - In an attempt to develop a pre-clinical diagnostic for pre-eclampsia, Progenity partnered with Prospect Bio to identify pre-eclampsia from pre-natal urine samples. Adapting the biosenor panel approach to urine analysis, we developed methods to identify at risk patients with 80% accuracy. Sequence analysis of the panel's constituent biosenors provided indication to which small molecules elicited responses. These small molecules provided an opportunity to develop traditional diagnostics.

Prospect Bio's gene construct contained a Lac-Z reporter inline with the fluorescent reporter. The Lac-Z component was exploited for an enzymatic colorimetric output. This measurement approach is now used at [MiProbes](https://www.miprobes.de/).
