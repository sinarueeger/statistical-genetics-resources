
# Statistical Genetics Software


## Command line tools

### PLINK
- An all-in-one tool for genotype data (QC, LD, PCA, association testing, ...)
- [download](https://www.cog-genomics.org/plink/2.0/)
- Input file formats: plink, bgen, gen, vcf
  
### GCTA
- Mainly heritability estimation, but also QC and PCA
- [download](https://cnsgenomics.com/software/gcta/#Overview)
- Input file formats: binary plink files
  
### QCTOOL
- Tool to wrangle processed genetic data (bgen, gen, vcf, plink)
- [download](http://www.well.ox.ac.uk/~gav/qctool_v2/): Data handling, converting file formats, combining datasets
- QC
- PCA
- Input file formats: many (vcf, gen, bgen, plink, ...) [check here](http://www.well.ox.ac.uk/~gav/qctool/documentation/genotype_file_formats.html)
  
### BEDTOOLS
- Tool to wrangle "raw" genetic data (bed, bam, vcf, ...)
- [download](https://github.com/arq5x/bedtools2)
- [Cheatsheet](https://gist.github.com/ilevantis/6d6ecf8718a5803acff736c2dffc933e)
  
### QUICKTEST
- Association testing
- [download](https://wp.unil.ch/sgg/quicktest/)

### SNPTEST
- Association testing
- [download](https://mathgen.stats.ox.ac.uk/genetics_software/snptest/snptest.html)

### emeraLD
- LD estimation
- [download](https://github.com/statgen/emeraLD)
  
### LDstore
- LD estimation
- [download](http://www.christianbenner.com/#ldstore)

### FINEMAP
- Fine-mapping
- [download](http://www.christianbenner.com/): 
- [finemap howto](https://sinarueeger.github.io/post/finemapping-howto/)

### SumHer
- [SumHer](http://dougspeed.com/sumher/)
  - heritability estimation
  - uses summary statistics as input
  - [LDAK](http://dougspeed.com/ldak/) is for individual data
  - see also http://dougspeed.com/heritability-model/

### Misc
- https://openmendel.github.io/ (statistical genetic analysis tool in Julia)
- https://hail.is/ (genomic data analysis tool based on Python)
- https://ritchielab.org/software/plato-download (organising, QC and analysis of genetic data)

### Abbreviations
- QC: Data quality control, handling, transformation
- LD: Linkage disequilibrium
- PCA: Principal component analysis

## Webservers

- [GWAS Atlas](https://atlas.ctglab.nl): Collection of summary statistics: browse and compare GWAS results. 

- [MR Base](http://app.mrbase.org/): A platform for Mendelian randomisation using summary data from genome-wide association studies (also has an R package).

- [FUMA GWAS](http://fuma.ctglab.nl/): Functional Mapping and Annotation of Genome-Wide Association Studies. Takes summary statistics as input. 

- Imputation servers: [Sanger Imputation Service](https://imputation.sanger.ac.uk/) and [Michigan Imputation Server](https://imputationserver.sph.umich.edu/index.html).

- [Locuscompare](http://locuscompare.com/): comparison of EQTL and GWAS summary statistics (using rsid and p-values).

## R packages

Packages are either hosted on CRAN or [Bioconductor](https://www.bioconductor.org/). 

### Getting started
- A [tutorial](http://www.stat-gen.org/str/about.html) for implementing a GWAS in R by the [Foulkes Lab](http://www.stat-gen.org/about.html).
- [Task view](https://cran.r-project.org/web/views/Genetics.html) on CRAN.
- R-packages that deal with [genetics](https://rdrr.io/search?q=genetics) or [genomics](https://rdrr.io/search?q=genomics). 


### Bioconductor packages 
- [Bioconductor](https://www.bioconductor.org/packages/release/BiocViews.html#___Software)
- [biomaRt](https://bioconductor.org/packages/release/bioc/html/biomaRt.html) + [user guide](https://bioconductor.org/packages/release/bioc/vignettes/biomaRt/inst/doc/biomaRt.html).

### CRAN packages
- [manhattanly](https://moderndata.plot.ly/manhattanly-r-package-for-interactive-manhattan-plots/) for interactive Manhattan plots. 
- [qqman](https://cran.r-project.org/web/packages/qqman/index.html): for Manhattan plots (see DYI solution in [here](https://www.r-graph-gallery.com/wp-content/uploads/2018/02/Manhattan_plot_in_R.html)).
- [rsnps](https://cran.r-project.org/web/packages/rsnps/): interface to SNP datasets. Check [vignette](https://cran.r-project.org/web/packages/rsnps/vignettes/rsnps_vignette.html).
- [ggman](https://github.com/mkanai/ggman): Well done Manhattan plot in a ggplot2 look.
- [GWAS.utils](https://github.com/sinarueeger/GWAS.utils): helper functions for genotype data and summary statistics.
- [gaston](https://cran.r-project.org/web/packages/gaston/index.html): genetic data handeling + modelling (variety of models)

Related to Manhattan plots: 
- [Crafting Manhattan plots](https://www.r-graph-gallery.com/wp-content/uploads/2018/02/Manhattan_plot_in_R.html) by [Yan Holtz](https://github.com/holtzy/) for the [R graph gallery](https://www.r-graph-gallery.com/). 