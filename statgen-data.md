# Genomic data resources

- [Data resources](#data-resources)
- [Individual level data](#individual-level-data)
- [Summary association statistics](#summary-association-statistics)
- [Download](#download)


<!-- Below is a list of data resources used in statistical genetics.
//]: --- | UCSC | |
[//]: --- | --------- |:----------------------------------:|
[//]: --- | hg20 | Genome Reference Consortium GRCh38 |
[//]: --- | hg19 | Genome Reference Consortium GRCh37 |
[//]: --- | hg18 | NCBI Build 36 |
- http://blog.kaggle.com/2017/09/11/how-can-i-find-a-dataset-on-kaggle/
-->


## Data Resources

Below is a list of resources of genetic data, in summarised or individual form.

Summary association statistics are mostly public ([Is Reidentifiability a Risk? - Open versus restricted access for summary statistics](https://medium.com/@mjdaly/is-reidentifiability-a-risk-ae62a691a7cc) by Mark Daly), while individual data can mostly only be accessed by selected individuals.



### Individual level data

- [**HapMap Project**](https://www.sanger.ac.uk/resources/downloads/human/hapmap3.html) phase III includes sequencing data from 1'397 individuals, 11 ancestry groups → his database is [not maintained](https://www.ncbi.nlm.nih.gov/variation/news/NCBI_retiring_HapMap/) anymore. <!-- phase one 270 individuals -->
- [**1000 Genomes Project**](http://www.internationalgenome.org/): phase III contains sequencing data from 2'504 individuals, from 26 populations, for 84.4 million variants markers → publicly available data.
- [**UK10K**](http://www.uk10k.org/): sequencing data from 4000 individuals of European/British ancestry → restricted access. 
- [**UK Biobank**](http://www.ukbiobank.ac.uk/): genotype and genotype imputed data for 500K individuals → restricted access.
- [**African Genome Variation Project**](https://www.nature.com/articles/nature13997) Dense genotypes from 1'481 individuals + WGS from 320 individuals across sub-Saharan Africa → restricted access.
- [**OpenSNP**](https://opensnp.org/): Uploaded genotype and phenotype data from direct-to-consumer genetic tests → publicly available data.
- [**gnomAD**](https://gnomad.broadinstitute.org/): Summary statistics (allele frequency) available through exome and genome sequencing of 71,702 individuals (various disease-specific and population genetic studies, large-scale sequencing projects).

Currently, 1000 Genomes Project and UK10K data are often used as **reference panels** for imputation (except if an online imputation service is used, e.g. the [Sanger Imputation Service](https://imputation.sanger.ac.uk/)). 

### Summary association statistics

- [**GWAS Atlas**](http://atlas.ctglab.nl): Comprehensive GWAS catalogue with possibility to compare multiple GWASs (browser).
<!--http://megastroke.org/download.html-->
- [**GWAS Catalog**](https://www.genome.gov/gwastudies/) provides a curated list of all GWAS results, incl [download](https://www.ebi.ac.uk/gwas/downloads/summary-statistics).
- [**gwas.mrcieu.ac.uk**](https://gwas.mrcieu.ac.uk/datasets/): Open GWAS initiative
- [**Pan UK Biobank results**](https://pan.ukbb.broadinstitute.org): Multi-ancestry analysis of 7,221 phenotypes, across 6 continental ancestry groups. 
- [**UK Biobank results**](http://www.nealelab.is/uk-biobank): GWAS summary statistics from genotype imputed UK Biobank data, including 337'000 individuals and 2'419 phenotypes. Based on this, [**UKB phewas**](http://pheweb.sph.umich.edu:5000/) takes a variant id as input and returns the association results for the most relevant phenotypes (browser + download).
- [**Gene Atlas** (UK Biobank GWAS results)](http://geneatlas.roslin.ed.ac.uk/): Associations of 452K UK Biobank White British individuals (browser + download full summary statistics).
- [**Global Biobank Engine**](https://biobankengine.stanford.edu/): Aggregated summary statistics from over 750,000 individuals across three population cohorts: UK Biobank, Million Veterans Program and Biobank Japan (browser).
- [**MR-base**](http://www.mrbase.org/): a web application that displays the result of a systematically performed MR analyses on a number of traits, using > 1000 GWAS summary statistic results. [**MR-base PheWas**](http://phewas.mrbase.org) takes a variant id as input, and returns the traits with relevant MR results as output. 
[**LD-Hub**](http://ldsc.broadinstitute.org/ldhub/): a web application to look up pre-run LD score regression results (browser + download full summary statistics).
- [**eQTL**](https://genenetwork.nl/bloodeqtlbrowser/): Cis- and trans-eQTLs results in whole blood samples, limited to FDR=0.5 (download).
- [**GTEx**](http://www.gtexportal.org/): eQTL summary statistics from over 40 tissues (browser + download full summary statistics).
- [**EBI eQTL catalogue**](https://www.ebi.ac.uk/eqtl/Datasets/) lists a variety of eQTL studies using standardized analyis (download full summary statistics).
- Table 1 in [Pasaniuc & Price (2017)](https://www.nature.com/articles/nrg.2016.142) lists publicly available summary statistics.

- Looks outdated: [**PhenoScanner**](http://www.phenoscanner.medschl.cam.ac.uk/phenoscanner): lookup of curated large-scale GWAS results, takes a variant id as input.

### Download
Places to find full genome summary statistics:
- [**GWAS Catalog**](https://www.genome.gov/gwastudies/) 
- [GWAS Summary Statistics by ctg.cncr.nl](https://ctg.cncr.nl/software/summary_statistics)
- dbGap

Not directly for download, but provide links WHERE to download:
- [**LD-Hub**](http://ldsc.broadinstitute.org/ldhub/)
- [**GWAS Atlas**](http://atlas.ctglab.nl)

