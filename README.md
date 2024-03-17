# Git + GitHub As A Platform For Reproducible Research 

## Overview
This is a repository which shows the cell type clustering and characterization of mouse paraventricular nucleus of the thalamus (PVT). The data is collected from previous publications (listed below in citations). In this project, I used these data to cluster PVT cells into different cell types and mapped out the marker of each cell clusters. I also wrote code to show the expression of gene of interests in different cell clusters to better visualize expression specificity. 

## Methods
The analysis is done in python using existing single cell analysis packages such as scanpy. Various steps are taken (shown in the jupyter notebook file under the templates folder) to remove low quality sequences and cells, remove unwanted genes, and reduce the dimensionality of the population for better visualization.

## Results
The analysis showed that there are 16 different cell clusters based on the previously published sequencing data. After annotating the clusters with previously generate labels, the integrity of most clusters held well. We were able to successfully extract most differentially expressed genes in each clusters, and these genes have highly specific expression in the UMAP. With these information, we looked into publish datasets such as the allen brain atlas and found that different cell types are distributed differentially along the anterior/posterior axis of the PVT, and these different subregions have different projections patterns (data in the experiment folder). Overall, the data hinted that the PVT have diverse cell types and different projection patterns along the AP axis, which might mean that different regions of PVT have different functions.

## Citations
1. Shima Y, Skibbe H, Sasagawa Y, Fujimori N, Iwayama Y, Isomura-Matoba A, Yano M, Ichikawa T, Nikaido I, Hattori N, Kato T. Distinctiveness and continuity in transcriptome and connectivity in the anterior-posterior axis of the paraventricular nucleus of the thalamus. Cell Rep. 2023 Oct 31;42(10):113309. doi: 10.1016/j.celrep.2023.113309. Epub 2023 Oct 19. PMID: 37862168.
