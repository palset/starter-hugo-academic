---
title: "CO-GWAS: A co-occurrence graph based GWAS System"
publication_types:
  - "8"
authors:
  - Palash Sethi
  - Pranjal Bhaskare
  - Anurag Sahoo
  - Shailesh Kumar
abstract: ""
image:
  filename: screenshot-2021-11-13-at-3.19.43-pm-min.png
  preview_only: true
  focal_point: SMART
summary: ""
date: 2021-11-13T09:35:35.517Z
---
Research Background :

The tool provides a novel methodology and system for Genome Wide Association Studies (GWAS). In this work, we create large scaled multiprocessing systems which can map genotypes to phenotypes. Phenotypes are defined as observed physical attributes of an organism. Within a specie, phenotypes differ between multiple organisms due to the genotype, which is defined as the gene sequence of the organism. Finding mapping between genotypes and phenotypes is the holy-grail of biology due to the following reasons:

1) Generate novel causal hypothesis regarding biological pathways that affect physical trait of the organism.

2) Results of GWAS can be used to predict an individual’s biological proclivity towards certain diseases through their gene sequence. For example, this can be used to predict future diseases that a new born child might have.

3) Genes which have a considerable effect on phenotype can be used to engineer crops with desired properties.

This tool maps genotype to phenotype, by taking VCF files as input. The tool then transforms the VCF file into a suitable format for generating the probability with which each position in the genome affects the target phenotype

Claims:

The core problem which GWAS addresses is that gene sequence is very large and it is not clear which part of the gene or which alleles in the gene are responsible for which phenotype. The solution for this problem involves reducing the number of ‘candidate alleles’ which have a correlation with the phenotype. In prior-art, p-value is used as a metric to shortlist a set of causal genes that affect phenotype. In our system, we present the following claims:

1) We formulate a new metric for quantifying the goodness of a candidate allele to be correlated with phenotype.

2) We provide a methodology that evaluates the individual allele goodness quantification method by using the top k such candidates produced by the method, build a prediction model only using those features and compare the accuracy of the prediction.

3) Our approach in claim 1 is shown to be doing significantly better than p-value (the prior art) w.r.t. the method proposed in claim 2.

4) We have also come up with a very efficient and scalable pipeline using big-data computing for compressing the traditional data into a binary format, generating the candidate scores, and evaluating the top candidates efficiently.