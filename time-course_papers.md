---
title: "Time-course papers"
author: "Ji Huang"
date: '2019-01-16'
---

*Time* is a fascinating new dimension of gene regulation. With the decrease of sequencing cost, we are now able to capture gene expression changes through time. This leads to a new area of the big **Gene Regulation** question. We are able to find early activated genes and later activated genes and see how they change over time.

This post is to organize papers I found that used *time-course* method to study gene expression. No particular order, just order by the time I found the paper.


## Plant

1. [Deciphering and Prediction of Transcriptome Dynamics under Fluctuating Field Conditions](https://www.cell.com/abstract/S0092-8674(12)01352-9). 2010, Cell.

2. [Multiple abiotic stimuli are integrated in the regulation of rice gene expression under field conditions](https://elifesciences.org/articles/08411). 2015, eLife.

3. [Punctual Transcriptional Regulation by the Rice Circadian Clock under Fluctuating Field Conditions](http://www.plantcell.org/content/27/3/633.long). 2015, Plant Cell.

4. [Annual transcriptome dynamics in natural environments reveals plant seasonal adaptation](https://www.nature.com/articles/s41477-018-0338-z). 2019 ,Nature Plant.

5. [Dynamic Maize Responses to Aphid Feeding Are Revealed by a Time Series of Transcriptomic and Metabolomic Assays](http://www.plantphysiol.org/content/169/3/1727). 2015, Plant Physiology.

6. [Spatio-Temporal Transcript Profiling of Rice Roots and Shoots in Response to Phosphate Starvation and Recovery](http://www.plantcell.org/content/25/11/4285). 2013, Plant Cell.

7. [Time-Course RNA-Seq Analysis Reveals Transcriptional Changes in Rice Plants Triggered by Rice stripe virus Infection](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0136736). 2015, PloS One.

8. [A high resolution map of the Arabidopsis thaliana developmental transcriptome based on RNA‐seq profiling](https://onlinelibrary.wiley.com/doi/full/10.1111/tpj.13312). 2016, Plant Journal. This paper does not quite fit in here, it's more a developmental atlas.

9. [RNA-seq analysis of an apical meristem time series reveals a critical point in Arabidopsis thaliana flower initiation](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-015-1688-9). 2015, BMC Genomics.

10. [Rapid Recovery Gene Downregulation during Excess-Light Stress and Recovery in Arabidopsis](http://www.plantcell.org/content/29/8/1836). 2017, Plant Cell.

11. [RNA-Seq Analysis of Rice Roots Reveals the Involvement of Post-Transcriptional Regulation in Response to Cadmium Stress](https://www.frontiersin.org/articles/10.3389/fpls.2015.01136/full). 2015, Front Plant Sci.

12. [Lasy-Seq: a high-throughput library preparation method for RNA-Seq and its application in the analysis of plant responses to fluctuating temperatures](https://www.biorxiv.org/content/early/2018/12/20/463596). 2018, bioRxiv.

13. [Time-Series Transcriptomics Reveals That AGAMOUS-LIKE22 Affects Primary Metabolism and Developmental Processes in Drought-Stressed Arabidopsis](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4790877/). 2016, Plant Cell.


## Method

1. [FIT: statistical modeling tool for transcriptome dynamics under fluctuating field conditions](https://academic.oup.com/bioinformatics/article/33/11/1672/2964729). 2017, Bioinformatics.

2. [Trendy: segmented regression analysis of expression dynamics in high-throughput ordered profiling experiments](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-018-2405-x). 2018, BMC Bioinformatics.

3. [Comparative analysis of differential gene expression tools for RNA sequencing time course data](https://academic.oup.com/bib/advance-article/doi/10.1093/bib/bbx115/4364840). 2017, Briefings in Bioinformatics.

4. [Limma](https://bioconductor.org/packages/release/bioc/html/limma.html). R package. Section **9.6.2 Many time points**. It explains how to add *spline* model to the design to find DEGs. This *spline* idea can be easily applied to [DESeq2](https://bioconductor.org/packages/release/bioc/html/DESeq2.html) and [edgeR](https://bioconductor.org/packages/release/bioc/html/edgeR.html).