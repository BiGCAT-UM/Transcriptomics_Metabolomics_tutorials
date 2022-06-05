<img src="../images/tutorials-icon.png" width="80" align="right"/>

This workflow, developed in R markdown files as well as and Jupyter notebook files, includes differential gene expression analysis, statistical analysis of metabolomics data, as well as pathway enrichment analysis for both transcriptomics and metabolomics data followed by integration of this data through network analysis to identify disease-related processes and visualization of multi-omics data. A publicly available (https://ibdmdb.org/) gut-transcriptomic and stool-metabolome dataset of the gut microbial ecosystem in inflammatory bowel diseases was used to test the proposed workflow.

Transcriptomics analysis:
1-Data preprocessing
2-Differential gene expression analysis
3-Gene Pathway Analysis (ORA)
4-Heatmap creation
5-Overlapped genes extraction
6-Network analysis
Metabolomics analysis:
7-Data preprocessing
8-Significantly changed metabolites analysis
9-Metabolite Pathway Analysis (ORA)
Multi-omics visualization
10-Identifier mapping
11-Visualizaiton of multi-omics

***

**Transcriptomics Analysis**
<table>
<tr>
<td><b>Tutorial</b></td><td><b>Topic</b></td>
</tr>
<tr>
<td><a href="https://github.com/BiGCAT-UM/Transcriptomics_Metabolomics_Analysis/tree/master/transcriptomics_analysis/1-data_preprocessing">Data preprocessing </a></td><td>Preprocess transcriptomics data to be ready for analysis</td>
</tr>
<tr>
<td><a href="https://github.com/BiGCAT-UM/Transcriptomics_Metabolomics_Analysis/tree/master/transcriptomics_analysis/2-differential_gene_expression_analysis">Differential gene expression analysis</a></td><td>Performing differential gene expression analysis</td>
</tr>
<tr>
<td><a href="https://github.com/BiGCAT-UM/Transcriptomics_Metabolomics_Analysis/tree/master/transcriptomics_analysis/3-pathway_analysis">Pathway Analysis</a></td><td>perform pathway enrichment analysis to differential expressed genes</td>
<tr>
<td><a href="https://github.com/BiGCAT-UM/Transcriptomics_Metabolomics_Analysis/tree/master/transcriptomics_analysis/4-create_heatmap">Heatmap creation</a></td><td>Heatmap visualization for enriched pathways </td>
</tr>
<tr>
<td><a href="https://github.com/BiGCAT-UM/Transcriptomics_Metabolomics_Analysis/tree/master/transcriptomics_analysis/5-extract-overlapped_genes">Overlapped genes extraction</a></td><td>extracting overlapped differential expressed genes between Chron`s disease and ulcerative colitis </td>
</tr>
<tr>
<td><a href="https://github.com/BiGCAT-UM/Transcriptomics_Metabolomics_Analysis/tree/master/transcriptomics_analysis/6-network_analysis">Network analysis</a></td><td>Creating PPI-pathway network, applying MCL (Markov Clusetring) algorithm to the created networks</td>
</tr>
</table>

***

**API Tutorials CyTargetLinker v.4.0+ (Cytoscape 3.6.+)**
<table>
<tr>
<td><b>Tutorial</b></td><td><b>Topic</b></td>
</tr>
<tr>
<td><a href="https://github.com/CyTargetLinker/cytargetlinker-automation/tree/master/R-automation/UseCase1">Automation Tutorial 1</a></td><td>R tutorial to extend Rett syndrome PPI network with compounds and diseases</td>
</tr>
<tr>
<td><a href="https://github.com/CyTargetLinker/cytargetlinker-automation/tree/master/R-automation/UseCase2">Automation Tutorial 2</a></td><td>R tutorial to extend differentially expressed genes with pathway associations</td>
</tr>
<tr>
<td><a href="https://github.com/CyTargetLinker/cytargetlinker-automation/tree/master/R-automation/UseCase3">Automation Tutorial 3</a></td><td>R tutorial to extend author nodes with their publications and journal information</td>
</tr>
</table>
