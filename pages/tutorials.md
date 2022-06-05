<img src="../images/tutorials-icon.png" width="80" align="right"/>

This workflow, developed in R markdown files as well as and Jupyter notebook files, includes differential gene expression analysis, statistical analysis of metabolomics data, as well as pathway enrichment analysis for both transcriptomics and metabolomics data followed by integration of this data through network analysis to identify disease-related processes and visualization of multi-omics data. A publicly available (https://ibdmdb.org/) gut-transcriptomic and stool-metabolome dataset of the gut microbial ecosystem in inflammatory bowel diseases was used to test the proposed workflow.<br>

Each analysis section is given with corresponding script and the topic.<br>

To perform the workflow:<br>
* First go to the related section (Transcriptomics Analysis, Metabolomics Analysis or Multi-Omics Visualization)<br> 
* Open .Rmd file in RStudio<br>
* Run the script<br>

**Transcriptomics Analysis**
<table>
<tr>
    <td><b>Tutorial</b></td><td><b>Topic</b></td>
</tr>
<tr>
    <td><a href="https://github.com/BiGCAT-UM/Transcriptomics_Metabolomics_Analysis/tree/master/transcriptomics_analysis/1-data_preprocessing">1-Data preprocessing </a></td><td>Preprocess transcriptomics data to be ready for analysis</td>
</tr>
<tr>
    <td><a href="https://github.com/BiGCAT-UM/Transcriptomics_Metabolomics_Analysis/tree/master/transcriptomics_analysis/2-differential_gene_expression_analysis">2-Differential gene expression analysis</a></td><td>Performing differential gene expression analysis</td>
</tr>
<tr>
    <td><a href="https://github.com/BiGCAT-UM/Transcriptomics_Metabolomics_Analysis/tree/master/transcriptomics_analysis/3-pathway_analysis">3-Pathway Analysis</a></td><td>Perform pathway enrichment analysis to differential expressed genes</td>
<tr>
    <td><a href="https://github.com/BiGCAT-UM/Transcriptomics_Metabolomics_Analysis/tree/master/transcriptomics_analysis/4-create_heatmap">4-Heatmap creation</a></td><td>Heatmap visualization for enriched pathways </td>
</tr>
<tr>
    <td><a href="https://github.com/BiGCAT-UM/Transcriptomics_Metabolomics_Analysis/tree/master/transcriptomics_analysis/5-extract-overlapped_genes">5-Overlapped genes extraction</a></td><td>Extracting overlapped differential expressed genes between Chron`s disease and ulcerative colitis </td>
</tr>
<tr>
    <td><a href="https://github.com/BiGCAT-UM/Transcriptomics_Metabolomics_Analysis/tree/master/transcriptomics_analysis/6-network_analysis">6-Network analysis</a></td><td>Creating PPI-pathway network, applying MCL (Markov Clusetring) algorithm to the created networks</td>
</tr>
</table>

**Metabolomics Analysis**
<table>
<tr>
    <td><b>Tutorial</b></td><td><b>Topic</b></td>
</tr>
<tr>
    <td><a href="https://github.com/BiGCAT-UM/Transcriptomics_Metabolomics_Analysis/tree/master/metabolomics_analysis/7-metabolite_data_preprocessing">7-Data preprocessing </a></td><td>Preprocess metabolomics data to be ready for analysis</td>
</tr>
<tr>
    <td><a href="https://github.com/BiGCAT-UM/Transcriptomics_Metabolomics_Analysis/tree/master/metabolomics_analysis/8-significantly_changed_metabolites_analysis">8-Significantly changed metabolites analysis</a></td><td>Performing statistical analysis</td>
</tr>
<tr>
    <td><a href="https://github.com/BiGCAT-UM/Transcriptomics_Metabolomics_Analysis/tree/master/metabolomics_analysis/9-metabolite_pathway_analysis">9-Metabolite pathway Analysis</a></td><td>Performing pathway enrichment analysis to metabolite data</td>
</tr>
</table>