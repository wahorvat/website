---
layout: post
title:  "Gene clustering and organoids"
date:   2020-02-07 07:00:00
categories: 
author: Stem Pharm
---
No longer interested in the bench jockey life, I welcomed the move to join Stem Pharm as a bioinformatician. This transition provided the impetus to finding my passion for mathematical analysis of deep neural networks and first principle modeling.

### Organoids for model systems
Hoping to provide a novel, inexpensive, and potentially more accurate, pre-clinical model Stem Pharm developed a functionalized surface chemistry that can support hydrogels with variable mechanical properties. The company hypothesized its hydrogels provided a platform for multicellular organoids to interact with small molecules in a manner akin to live tissue samples. My role was to develop tools to explore their hypothesis by discovering gene sets present in both organoid cells and harvested tissue cells after small molecule perturbation.

### RNA-seq analysis and hierarchical clustering
To the end of validating Stem Pharm's model system, I developed computational methods for sequencing QC, replicate validation, gene expression statistics and subsequent gene clustering. To discover gene clusters, I developed hierarchical clustering models based on the Euclidean distance between gene expression vectors and the KL divergence between ranked genes sets. Applying the clustering analysis to Stem Pharm’s proof-of-concept study comparing neural tissue and neural organoids in the presence of carcinogens—lead and bromodiphenyl ether—I discovered irregular expression of replication and RNA polymerase gene sets within the treatment conditions.

![hierarchical map](https://wahorvat.gitlab.io/wahorvat/images/posts/stem-pharm/dendrites.png){: .center-image }

### Impact for Stem Pharm
The quantitative evidence I provided for Stem Pharm’s technology was foundational to their recently funded NIH Phase II SBIR grant.
