# awesome-metabolome
List of software packages for metabolomics analysis

## Metabolite/Metaboloism DB
* [HMDB: The human metabolome database](https://hmdb.ca/) - (Probably) the most comprehensive database of human metabolites. HMDB accessions numbers can be used to link to many external databases such as KEGG, MetaCyc, ChEBI, FooDB etc.
* [KEGG: Kyoto Encyclopedia of Genes and Genomes](https://www.genome.jp/kegg/) - Metabolites are registered in KEGG Compounds and linked to enzymes and pathways
* [MetaCyc](https://metacyc.org/) - 
* [FooDB](https://foodb.ca/) - Foods nutrition database, 
* [Reactome]() - 
* [WikiPathways]() - 

## MS spectrum data processing
* [MetaboAnalystR](https://github.com/xia-lab/MetaboAnalystR) - [R] - `MS peak calling`, `MS peak annotation`, `Data preprocessing` (batch correction, normalization), `Differential analysis`, `Enrichment analysis` (Fisher's exact test)
* [xmcs]() - [R] - `MS peak calling`
* [CAMERA]() - [R] - `MS peak annotation`
* [MAIT]() - [R] - ``

## Data preprocessing
* [DBnorm](https://github.com/NBDZ/dbnorm) - [R] - Provides several `Batch correction` methods (ComBat, ber) and enables users to select the best method

## Exploratory data analysis
* [omu](https://cran.r-project.org/web/packages/omu/index.html) - [R] - `Differential analysis`, `Unsupervised clustering` (PCA). Metabolites have to be labeled with KEGG Compound ID.
* [MetaboDiff](https://github.com/andreasmock/MetaboDiff/) - [R] - `Data preprocessing` (imputation, normalization), `Differential analysis`, `Unsupervised clustering` (PCA, tSNE), `Correlation network` (WGCNA for metabolome)

## Network/Pathway analysis
* [FELLA]() - [R] - `Enrichment analysis` based on KEGG database
* [MSEA]() - [R] - `Enrichment analysis`

## Metabolic flux analysis
* [COBRA Toolbox](https://opencobra.github.io/cobratoolbox/stable/index.html) - [MATLAB] - MATLAB toolbox providing diverse flux balance analysis (FBA) methods. Nice protocol paper was published in 2019 ([ref](https://www.nature.com/articles/s41596-018-0098-2)).
* [COBRApy](https://opencobra.github.io/cobrapy/) - [Python] - COBRA in python
* [Sybil](https://cran.r-project.org/web/packages/sybil/index.html) - [R] - Constrained based metabolic modeling in R
* [Compass](https://github.com/YosefLab/Compass) - [Python] - Estimation of metabolic preference in single-cell level by flux balance analysis using using scRNA-seq.


# Review papers
* Marco-Ramell et al. 2018. BMC Bioinformatics [Evaluation and comparison of bioinformatic tools for the enrichment analysis of metabolomics data](https://doi.org/10.1186/s12859-017-2006-0)
    * Compared metabolism identifiers in diveerse DBs and reported some metabolites were represented by same IDs in KEGG & HumanCyc
* 