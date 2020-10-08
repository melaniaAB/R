# The mtRNA transport pathway.
> The study objective: characterization of the mtRNA transport pathway.   
Approach: a- IP-MS on one of the putative components of the pathway, b- eCLIP-seq study on RNA-bound components of the pathway.


## Table of contents
* [General info](#general-info)
* [Mitochondrial disorders](#image)
* [Packages and approaches](#R)
* [Status](#status)
* [Inspiration](#inspiration)


## General info
The characterized novel mtRNA trasnport pathway can contribute to the disease control measures for mito-disorders.

## Mitochondrial disorders
Defects in mtDNA (e.g., mutation, deletions) can caue several disorders such as neurodegenerative diseases.

![mt-disorders](./static/mitoDisorders.jpg) 

## Packages and approaches
SAINTExpress and STRINGdb(IP-MS data), eCLIP-seq/PureCLIP and RCas (characterisation of RNAs/motifs bound by proteins).


#### Code Example - Coverage profile of query regions for all transcript features - RCAS
	cvgList <- calculateCoverageProfileList(queryRegions = queryRegions,
                                       targetRegionsList = txdbFeatures,
                                       sampleN = 10000)
	pdf("profile transcripts.pdf")
	ggplot2::ggplot(cvgList, aes(x = bins, y = meanCoverage)) +
  		geom_ribbon(fill = 'lightgreen',
              		aes(ymin = meanCoverage - standardError * 1.96,
                  		ymax = meanCoverage + standardError * 1.96)) +
 		geom_line(color = 'black') + theme_bw(base_size = 14) +
 		facet_wrap( ~ feature, ncol = 3)
	dev.off()
 

## Status
Project is ongoing.

## Inspiration
Using bioinfomratics to contribute to Disease Control Strategies.
