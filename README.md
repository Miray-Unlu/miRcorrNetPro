# miRcorrNetPro

miRcorrNetPro tool utilizes Cross-Validation to reveal hidden biological knowledge in multi-omic data analysis. This tool performs integrative analysis of omics datasets  via machine learning (ML) approach to identify significant biomarkers. Here, the findings and results are presented based on microRNA and gene expression profiles. The miRNA groups and their associated target genes are identified in this study. The tool is also applicable for other omics datatypes. 

The tool tracks group scoring, ranking and other information through the cross-validation iterations.
Heatmap visualizations enable deep novel insights into the collective behavior of clusters of groups in cellular signaling and hence facilitate detection of potential biomarkers for the disease under investigation.

# Data Preparation

The workflow created in KNIME analytics platform takes the data sheets as ‘.table’ extension files. 
The sample IDs are given in rows. Features are represented in columns. The last column represents the class information for control and case samples.

The link for downloading KNIME: https://www.knime.com/downloads. For more information about the Knime platform, please visit https://www.knime.com/software-overview

# Main Workflow

 ![alt text](https://github.com/Miray-Unlu/mirCorrNetPro/blob/main/Images/main_workflow.PNG?raw=true)

 
# Set up Parameters

Default parameters:
* Positive Correlation Threshold (Default: 0.6) 
* Negative Correlation Threshold (Default: -0.6) 
* Number of iteration (Default: 100) 
* Number of iterations for Internal Rank (Default: 10)

# Significant Groups Summary Statistics

![alt text](https://github.com/Miray-Unlu/mirCorrNetPro/blob/main/Images/significant_groups.PNG?raw=true)
 
