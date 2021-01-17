---
layout: post
title:  "Peptide chemical tagging"
date:   2014-05-10 13:00:00
categories: 
author: UW-Madison
---

This work was done as my first foray into proper research; the terse details and write-up relate to a conference poster that remains the last material available detailing the work. Thanks for reading and enjoy!

### Alkylation Chemistry for Increased Mass Spectrometric Peptide Detection in Phosphoproteomics
Current methods to analyze peptide mixtures by high performance liquid chromatography (HPLC) and mass spectrometry (MS) have revolutionized bioanalytical analysis, however, detection of hydrophilic, negatively charged peptides still remains a challenge.

In digested cell lysate samples, LC/MS fails to detect many hydrophilic and negatively charged peptides, especially those that are phosphorylated and glycosylated.  It is important to analyze these modified peptides because post translational modifications regulate cellular functions and deregulation of them results in disease, such as cancer.

To increase peptide detection, we exploed reductive amination chemistry to butylate primary amines on tryptic peptides.


### Reductive amination of peptides
Reductive amination was used to chemically label the N-terminus and C-terminal lysines of the studied peptides. The N-terminus of the peptide reacts with butyraldehyde to form a dibutylated amine. The C-terminal lysine reacts with butyraldehyde to form a dibutylated lysine residue. The reductive amination is driven by the presence of excess butyraldehyde and pyridine borane.

![Alkylation reaction](https://wahorvat.gitlab.io/wahorvat/images/posts/chemical-tagging/alkyl-reaction.png){: .center-image }


### Butylation of peptide standards
Single peptides LIWKGLYEGTGR, SSVSTVPNAAPIR, and SPTYLR were butylated by reductive amination. Each peptide was analyzed on an LCQ Deca XP mass spectrometer by direct infusion nanospray electrospray ionization. Results indicated the peptides were successfully butylated and the efficiency of the complete reaction was 85%-95%.

![Peptide standards](https://wahorvat.gitlab.io/wahorvat/images/posts/chemical-tagging/butylation-peptides.png){: .center-image }


### Butylation reaction efficiency
Using Thermo Proteome Discoverer software and the SEQUEST algorithm, the MS data for the Bovine Serum Albumin (BSA) and Cytochrome C Equus caballus (Cyt. C) digests were searched against *in silico* BSA and CytC FASTA sequences, respectively. The degree of match between experimental and theoretical MS spectra were scored with a subsequent XCORR score cut-off used to generate a list of peptide IDs. Reaction efficiency was calculated by ion chromatogram peak intensity of each type of modified form divided by the total of the ion chromatogram intensities.

![Peptide standards](https://wahorvat.gitlab.io/wahorvat/images/posts/chemical-tagging/butyl-peps.png){: .center-image }


### Butylation of peptides in tryptic protein digests
Proteins BSA and Cyt. C were trypically digested, and the resulting peptides were butylated by reductive amination. The butylated samples were run on a capillary column packed with MAGIC aqC18 and integrated with a Thermo Velos- Orbitrap mass spectrometer.
After butylation, the amino acid sequence coverage of BSA doubled. Butylation of the Cyt. C digest resulted in higher spectral counts. The following table illustrates the successful butylation of tryptic peptides by reductive amination.

![Modification table](https://wahorvat.gitlab.io/wahorvat/images/posts/chemical-tagging/mod-table.png){: .center-image }


### Acknowledgments
Thank you to Dr. Gloria Sheynkman and Dr. Brian Frey for their scientific guidance and patience. Funding for this work was provided by NIH grant PO1GM081629.
