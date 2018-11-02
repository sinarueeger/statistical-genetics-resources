
# Statistical Genetics Software (*in progress*)

## Categories

- 🛠️ Data quality control, handling, transformation (🛠️ representing tooling)
- 🔺 Linkage disequilibrium estimation (🔺 representing the lower triangle of the distance matrix)
- 📷 Principal component computation (📷 as a representation of an approximation of reality)
- ⚖️ Association tests (⚖️ representing measuring and weighing)
- 📏 Heritability estimation (📏 representing measuring heritability)

## Command line tools

- [**PLINK**](https://www.cog-genomics.org/plink/2.0/): An all-in-one tool for genotype data. 
  - 🛠️ QC
  - 🔺 LD
  - 📷 PCA
  - ⚖️ Testing
  - 📏 Heritability
  - Input file formats: plink, bgen, gen, vcf
  
- [**GCTA**](https://cnsgenomics.com/software/gcta/#Overview): heritability
  - (🛠️) QC
  - 📷 PCA
  - 📏 Heritability
  - Input file formats: binary plink files
  
- [**QCTOOL**](http://www.well.ox.ac.uk/~gav/qctool_v2/): Data handling, converting file formats, combining datasets
  - 🛠️ QC
  - 📷 PCA
  - Input file formats: many (vcf, gen, bgen, plink, ...) [check here](http://www.well.ox.ac.uk/~gav/qctool/documentation/genotype_file_formats.html)
  
- [**QUICKTEST**](https://wp.unil.ch/sgg/quicktest/)
  - ⚖️ Testing
  - Input file formats: plink, bgen, gen, vcf

- [**SNPTEST**](https://mathgen.stats.ox.ac.uk/genetics_software/snptest/snptest.html)
  - ⚖️ Testing
  
- Imputation software

- [**emeraLD**](https://github.com/statgen/emeraLD)
  - 🔺 LD
  - Input file formats: VCF
  
- [**LDSTORE**](http://www.christianbenner.com/#ldstore)
  - 🔺 LD
  - Input file formats: bgen, binary plink (no vcf, meaning, reference panels in vcf format have to be transformed first into a bgen file with [QCTOOL](http://www.well.ox.ac.uk/~gav/qctool_v2/))

## R packages

### Getting started
- A [tutorial](http://www.stat-gen.org/tut/tut_intro.html) for implementing a GWAS in R by the [Foulkes Lab](http://www.stat-gen.org/about.html).
- [Task view](https://cran.r-project.org/web/views/Genetics.html) on CRAN.
- R-packages that deal with [genetics](https://rdrr.io/search?q=genetics) or [genomics](https://rdrr.io/search?q=genomics). 

### Blogposts

- [Crafting Manhattan plots](https://www.r-graph-gallery.com/wp-content/uploads/2018/02/Manhattan_plot_in_R.html) by [Yan Holtz](https://github.com/holtzy/) for the [R graph gallery](https://www.r-graph-gallery.com/). 


### rOpenSci packages
- [biomartr](https://github.com/ropensci/biomartr) + [tutorials](https://github.com/ropensci/biomartr#tutorials).
- [rsnps](https://github.com/ropensci/rsnps) + [tutorial](https://github.com/ropensci/rsnps/blob/master/vignettes/rsnps_vignette.Rmd).

### Bioconductor packages 
- [Bioconductor](https://www.bioconductor.org/packages/release/BiocViews.html#___Software)
- [biomaRt](https://bioconductor.org/packages/release/bioc/html/biomaRt.html) + [user guide](https://bioconductor.org/packages/release/bioc/vignettes/biomaRt/inst/doc/biomaRt.html).

### CRAN packages
- [manhattanly](https://moderndata.plot.ly/manhattanly-r-package-for-interactive-manhattan-plots/) for interactive Manhattan plots. 
- [qqman](https://cran.r-project.org/web/packages/qqman/index.html): for Manhattan plots (see DYI solution in [here](https://www.r-graph-gallery.com/wp-content/uploads/2018/02/Manhattan_plot_in_R.html)).
- [rsnps](https://cran.r-project.org/web/packages/rsnps/): interface to SNP datasets. Check [vignette](https://cran.r-project.org/web/packages/rsnps/vignettes/rsnps_vignette.html).

