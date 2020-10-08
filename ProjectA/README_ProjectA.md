# Nutrient-Transporters of the agent of the Irish Famine.
> The study objective: identification of factors involved in the host-pathogen interaction establishment. 
Approach: a- characterization of nutrient transport families/genes in the pathogen, b- differential gene expression analysis of the identified nutrient transporters families in the pathogen obtained from in vivo and ex vivo cultures


## Table of contents
* [General info](#general-info)
* [Irish Famine](#image)
* [Gene Expression](#R)
* [Status](#status)
* [Inspiration](#inspiration)


## General info
The identified novel pathogenic nutrient transporters have the potential to be used as tools for the design of disease control strategies for this historic plant pathogen. 

## Irish Famine
Famine resulted in death of about 1 million Irish people, and migration of another 1 million from the island to North America and Great Britain.

!["Famine" by Rowan Gillespie](./static/Irish_famine.jpg) 

## Gene Expression
RNA-seq data analysis and visualization

### Packages
systemPipeR, gplots, RColorBrewer, gtools


#### systemPipeR - Analysis on the gene expression profile of the identifed nutrient transports in the pathogen

#### R code examples

##### Code Example - Heatmap
       heatmap.2(yourdata, cexRow=1, cexCol=1, margins=c(6,6),lhei=c(0.2,0.9),lwid=c(3.5,2),density.info="none",trace="none",dendrogram="none",Colv="FALSE",notecex = 0.01,col=colorRampPalette(brewer.pal(9,&quot;YlOrRd&quot;))(300), offsetRow=-0.5) #color brewe is used

##### Code Example - Heatmaps in one page
        grid.arrange(heatmap1, heatmap2, ncol=2) # example of inserting two plots on one page

## Status
Project is published.

## Inspiration
Generate beautiful heatmaps fior everyone! 
