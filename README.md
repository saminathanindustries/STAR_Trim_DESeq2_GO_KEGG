# STAR_Trim_DESeq2_GO_KEGG
This folder contains all the scripts needed for analysis. All used packages and software are reported in the manuscript.

Step 1: Preprocessing RNAseq data

This step processes raw data to gene counts, including quality control, alignment, duplicates removal and generate gene counts. The codes are desgined for the linux environment.

Step 2: Initial gene expression analysis

This step performs gene expression analysis by "DESeq2" (R package), based on the gene counts data. The initial analysis includes Principle Component Analysis, and correlation. The codes are desgined for the R environment.

Step 3: Differentially gene expression analysis

This step is processed by "DESeq2" (R package), based on the gene counts data. The Differentially expressed gene analysis utilizes the function of "DESeq2": "res". The codes are desgined for the R environment. The threshold of low gene counts is 3. The differentially expressed gene threshold is |LFC>|1 and padj<0.05. The codes are desgined for the R environment.

Step 4: Function analysis

The function analysis includes gene ontology enrichement analysis, KEGG pathway enrichment analysis. These analysis is done by "clusterProfiler" (R package). The codes are desgined for the R environment.
