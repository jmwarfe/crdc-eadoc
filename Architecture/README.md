# CRDC Architecture Overview

The CRDC is designed to provide secure access to high-value cancer dataset including TCGA, TARGET, and other data along with computational power for analysis. 

![CRDC Architecture Diagram](/assets/CRDC_Architecture.png)


The CRDC is broken into several components:

**Common Infrastructure services** - A framework of modular and reusable core components that provides common approaches to functions that are required across the CRDC. 

**Data Commons Components** - Web application portals and APIs that allow researchers to share, analyze, and visualize harmonized genomic data, including many high-value datasets.

**Cloud Resources** - Provides access to cancer data sets to perform large scale analysis using the elastic compute of commercial cloud platforms. The three resources include:
- Seven Bridges CGC (SB-CGC) [(http://www.cancergenomicscloud.org/)](http://www.cancergenomicscloud.org/)
- Institute for Systems Biology CGC (ISB-CGC) Genomics Cloud [(http://isb-cgc.org/)](http://isb-cgc.org/)
- Broad Institute FireCloud  [(http://firecloud.terra.bio/#)](http://firecloud.terra.bio/#)