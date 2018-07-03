# Genomic data resources

<!-- Below is a list of data resources used in statistical genetics.
//]: --- | UCSC | |
[//]: --- | --------- |:----------------------------------:|
[//]: --- | hg20 | Genome Reference Consortium GRCh38 |
[//]: --- | hg19 | Genome Reference Consortium GRCh37 |
[//]: --- | hg18 | NCBI Build 36 |
- http://blog.kaggle.com/2017/09/11/how-can-i-find-a-dataset-on-kaggle/
-->

## Types of data
The statistical methods mentioned in the Section [before](#beyond-gwas) use either *individual data* or an aggregated form called *summary statistics*. A-C in Figure below illustrate the difference between individual and aggregated data in terms of information loss. Most importantly, because of privacy restrictions, the LD structure between markers cannot be retrieved anymore, once the data is aggregated and published, and thus has to be estimated from external data. 

### Individual data vs. summary statistics

![summarystats 001](https://user-images.githubusercontent.com/4454726/41023833-d133b840-696d-11e8-9824-6abba73f24d6.png)

**A.** Genotype data for *K* individuals and *M* markers. 

**B.** LD structure between SNVs estimated through squared correlation. 

**C<sup>1</sup>.** How to aggregate individual data: estimating per allele effect sizes, along with the standard error. Using these two summary statistics, along with sample size (*N*), *MAF* or *EAF*, we can derive other summary statistics, such as Z-statistics (*Z*) or the explained phenotypic variance (*r<sup>2</sup>*).

**C<sup>2</sup>.** Aggregated data form, also called *summary statistics*, listing sample size, effect allele frequency, effect size and its standard error. 

## Data

Below is a list of resources of genetic data, in summarised or individual form.

Summary stats are public, while individual data can mostly only be accessed by selected individuals.

### Individual data{-}


```{marginfigure, echo = TRUE}
Figure \@ref(fig:summarystats) (A)
```

- [**HapMap Project**](https://www.sanger.ac.uk/resources/downloads/human/hapmap3.html) phase III includes sequencing data from 1'397 individuals, 11 ancestry groups [@hapmap-2003] $\to$ this database is [not maintained](https://www.ncbi.nlm.nih.gov/variation/news/NCBI_retiring_HapMap/) anymore. <!-- phase one 270 individuals -->
- [**1000 Genomes Project**](http://www.internationalgenome.org/) [@1kg-2010]: phase III contains sequencing data from 2'504 individuals, from 26 populations, for 84.4 million variants markers $\to$ public data.
- [**UK10K**](http://www.uk10k.org/) [@moayyeri-etal-2013;@boyd-etal-2013]: sequencing data from 4000 individuals of European/British ancestry $\to$ restricted access. 
- [**UK Biobank**](http://www.ukbiobank.ac.uk/) [@ukbb; @ukbb-imp]: genotype and genotype imputed data for 500K individuals $\to$ restricted access.

Currently, 1000 Genomes Project and UK10K data are often used as **reference panels** for imputation (Figure \@ref(fig:summarystats) (B))

### GWAS summary statistic results{-}


```{marginfigure, echo = TRUE}
Figure \@ref(fig:summarystats) (C)
```

- **GIANT**, a consortium focusing on anthropometric traits has [released](https://portals.broadinstitute.org/collaboration/giant/index.php/GIANT_consortium_data_files) all summary statistics of 15 large-scale meta GWASs. 
<!--http://megastroke.org/download.html-->
- The [**Catalog of published GWAS studies**](https://www.genome.gov/gwastudies/) [@gwas-catalog-2014] provides a curated list of all GWAS results. <!-- -->
- [**UK Biobank results**](https://sites.google.com/broadinstitute.org/ukbbgwasresults/home?authuser=0) [@ukbb-neale]: GWAS summary statistics from genotype imputed UK Biobank data, including 337'000 individuals and 2'419 phenotypes. Based on this, [**UKB phewas**](http://pheweb.sph.umich.edu:5000/) takes a variant id as input and returns the association results for the most relevant phenotypes. 
- [**LD-Hub**](http://ldsc.broadinstitute.org/ldhub/) [@zheng-etal-2016]: a centralised database of summary-level GWAS results. 
- [**eQTL**](https://genenetwork.nl/bloodeqtlbrowser/) [@westra-etal-2013]: Cis- and trans-eQTLs results in whole blood samples, limited to FDR=0.5.
- [**GTEx**](http://www.gtexportal.org/) [@gtex]: eQTL summary statistics from over 20 different tissues.
- [**PhenoScanner**](http://www.phenoscanner.medschl.cam.ac.uk/phenoscanner): lookup of curated large-scale GWAS results, takes a variant id as input.
- [**ExAC**](http://exac.broadinstitute.org/) [@exac]: Summary statistics (allele frequency) available through exome sequencing of 60'706 individuals (various disease-specific and population genetic studies, large-scale sequencing projects).
- Table 1 in @pasaniuc-price-2017 lists resources.

### Follow-up summary statistics{-}


Performing methods such as the ones described in [Beyond GWASs](#beyond-gwas), also output summary statistics that can be accessed.

- [**MR-base**](http://www.mrbase.org/) [@hemani-etal-2016]: a web application that displays the result of a systematically performed MR analyses on a number of traits, using over 1000 GWAS summary statistic results. [**MR-base PheWas**](http://phewas.mrbase.org) takes a variant id as input, and returns the traits with relevant MR results as output. 
- [**LD-Hub**](http://ldsc.broadinstitute.org/ldhub/) [@zheng-etal-2016]: a web application to look up pre-run LD score regression results.

## Contribute resources

add a comment below


## Open data versus privacy

- open data
- cite steph: https://user2018.r-project.org/blog/2018/05/30/interview-with-steph-de-silva/
- We have to find that a good place between maximum value and minimal exposure.

## Fake data

- https://github.com/ropensci/charlatan
- generate fake data
- `ch_generate('job', 'phone_number', n = 30)`


