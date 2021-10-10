# Bioinformatics with R


## Bioconductor project

The goal of the Bioconductor project is to advance statistical analysis and understanding of existing and upcoming high-throughput biological experiments. Bioconductor is based on packages written primarily in the R programming language. Bioconductor is committed to open source, collaborative, distributed software development literate and reproducible research. Enabling user and developer communities is an essential part of our mission. Scientific, Technical and Community Advisory Boards provide project oversight.

- [Bioconductor webpage](https://bioconductor.org/)




## Sequence analysis


Go to the workflow package description page developed by Sonali Arora and Martin Morgan with the title "introduction to bioconductor for sequence data" to see a list of the most important packages necessary to deal with sequences in each stage. (https://www.bioconductor.org/packages/release/workflows/vignettes/sequencing/inst/doc/sequencing.html)


[![](images_R/sequence.png)](https://www.bioconductor.org/packages/release/workflows/vignettes/sequencing/inst/doc/sequencing.html)


Reading the Documents provided for all of those packages is essential for effective analysis of the sequencing data.

#### Packages needed for sequencing:

- [ShortRead](https://bioconductor.org/packages/release/bioc/manuals/ShortRead/man/ShortRead.pdf)
- [Biostrings](https://bioconductor.org/packages/release/bioc/manuals/Biostrings/man/Biostrings.pdf)
- [seqinr](https://cran.r-project.org/web/packages/seqinr/seqinr.pdf)
- [biomaRt](https://bioconductor.org/packages/release/bioc/manuals/biomaRt/man/biomaRt.pdf)

#### Packages needed for alignment



- [Biostrings](https://bioconductor.org/packages/release/bioc/manuals/Biostrings/man/Biostrings.pdf)
- [Rsamtools](https://bioconductor.org/packages/release/bioc/manuals/Rsamtools/man/Rsamtools.pdf)
- [GenomicAlignments](https://bioconductor.org/packages/release/bioc/manuals/GenomicAlignments/man/GenomicAlignments.pdf)
- [muscle](https://www.bioconductor.org/packages/release/bioc/manuals/muscle/man/muscle.pdf)


## Microarray analysis

array is a bioconductor workflow package developed to analysis of expression arrays. Reading the manual page for this package gives a comprehensive overview of the workflow. 

- [arrays](https://www.bioconductor.org/packages/release/workflows/vignettes/arrays/inst/doc/arrays.html)

### packages needed for microarray analysis:

In order to learn the process go the html page for the workflow package of RNAseq123.

- [RNAseq123](https://www.bioconductor.org/packages/release/workflows/vignettes/RNAseq123/inst/doc/limmaWorkflow.html)

- [affy](https://www.bioconductor.org/packages/release/bioc/manuals/affy/man/affy.pdf) 
- [arrayQualityMetrics](https://bioconductor.org/packages/release/bioc/manuals/arrayQualityMetrics/man/arrayQualityMetrics.pdf)
- [limma](https://bioconductor.org/packages/release/bioc/manuals/limma/man/limma.pdf)
- [glimma](https://www.bioconductor.org/packages/release/bioc/manuals/Glimma/man/Glimma.pdf)
- [edgeR](https://www.bioconductor.org/packages/release/bioc/manuals/edgeR/man/edgeR.pdf)
- [sva](https://bioconductor.org/packages/release/bioc/manuals/sva/man/sva.pdf)


### books 

- [Bioconductor case studies](https://www.bioconductor.org/help/publications/books/bioconductor-case-studies/)

- [Computational genomics with R](http://compgenomr.github.io/book/)

### Videos

- Bioinformatics workshop1 
    - [](https://www.youtube.com/watch?v=WFA37FPLHqg&t=777s)

- Bioinformatics workshop2
    - [](https://www.youtube.com/watch?v=J9LNYhhNhrk)

### publications

- [Ritchie ME, Phipson B, Wu DI, Hu Y, Law CW, Shi W, Smyth GK. limma powers differential expression analyses for RNA-sequencing and microarray studies. Nucleic acids research. 2015 Apr 20;43(7):e47-.](https://pubmed.ncbi.nlm.nih.gov/25605792/#)
- [Hänzelmann S, Castelo R, Guinney J. GSVA: gene set variation analysis for microarray and RNA-seq data. BMC bioinformatics. 2013 Dec;14(1):1-5.](https://pubmed.ncbi.nlm.nih.gov/23323831/) 
- [Mastriani E, Zhai R, Zhu S. Microarray-based microRNA expression data analysis with bioconductor. InTranscriptome Data Analysis 2018 (pp. 127-138). Humana Press, New York, NY.](https://pubmed.ncbi.nlm.nih.gov/29508294/)


## Analyzing GWAS data

- [SNPassoc](https://cran.r-project.org/web/packages/SNPassoc/SNPassoc.pdf)
- [GenABEL]
- [GWASTools](https://www.bioconductor.org/packages/release/bioc/html/GWASTools.html)
- [GWASdata](http://bioconductor.org/packages/release/data/experiment/html/GWASdata.html)
- [NCBI2R]
- [GWASExactHW](https://cran.rstudio.com/web/packages/GWASExactHW/index.html)
- [CNVassoc](https://cran.r-project.org/web/packages/CNVassoc/index.html)
- [gap](https://cran.r-project.org/web/packages/gap/index.html)
- [postgwas](https://cran.r-project.org/web/packages/postgwas/index.html)
- [taRifx](https://cran.r-project.org/web/packages/taRifx/index.html)



## Analyzing Mass Spectrometry Data

The workflow package "proteomics"  written by Laurent Gatto provides a comprehensive overview of the process of Mass Spectormetry data analysis. 
- [proteomics](https://www.bioconductor.org/packages/release/workflows/html/proteomics.html)

- readMxXmlData
- [mzR](https://bioconductor.org/packages/release/bioc/html/mzR.html)
- [readBrukerFlexData](https://cran.r-project.org/web/packages/readBrukerFlexData/index.html)
- [MALDIquantForeign](https://cran.r-project.org/web/packages/MALDIquantForeign/index.html)
- [MALDIquant](https://cran.r-project.org/web/packages/MALDIquant/index.html)
- [protViz](https://cran.r-project.org/web/packages/protViz/index.html)


## Analyzing NGS data

In order to have an overview of the process visit biocondutor turial for NGS analysis with R and Bioconductor; 
- [bioconductor tutorial](https://bioconductor.org/help/course-materials/2012/CSC2012/Bioconductor-tutorial.pdf)

- [SRAdb](https://bioconductor.org/packages/release/bioc/html/SRAdb.html)
- [Rsamtools](https://bioconductor.org/packages/release/bioc/html/Rsamtools.html); link to source package: git clone git@git.bioconductor.org:packages/SRAdb
 
- [Shortread](https://bioconductor.org/packages/release/bioc/html/ShortRead.html)
- [edgeR](https://www.bioconductor.org/packages/release/bioc/manuals/edgeR/man/edgeR.pdf)
- [limma](https://bioconductor.org/packages/release/bioc/manuals/limma/man/limma.pdf)
- [DESeq](https://www.bioconductor.org/packages//2.10/bioc/html/DESeq.html)
- [pasilla](https://bioconductor.org/packages/release/data/experiment/html/pasilla.html)
- [goseq](https://bioconductor.org/packages/release/bioc/html/goseq.html)
- [methylAnalysis](https://www.bioconductor.org/packages/release/bioc/html/methyAnalysis.html)
- [chipseq](https://www.bioconductor.org/packages/release/bioc/html/chipseq.html)


### publications

- [Sepulveda JL. Using R and Bioconductor in clinical genomics and transcriptomics. The Journal of Molecular Diagnostics. 2020 Jan 1;22(1):3-20.](https://pubmed.ncbi.nlm.nih.gov/31605800/)

## contribute to the bioconductor

Bioconductor is an open development project, meaning that all developers from the scientific community are able to contribute software. In order to see how to contribute, go to the [developers](https://www.bioconductor.org/developers/) page on the bioconductor website.  

##Online resources

- awesomeopensource[https://awesomeopensource.com/projects/bioinformatics/r?categoryPage=29]
The Top 361 R Bioinformatics Open Source Projects on Github

- [R for biologists](https://www.bigbioinformatics.org/r-for-biologists)

- A large-scale analysis of bioinformatics code on GitHub [https://www.biorxiv.org/content/10.1101/321919v2.full]
  [Github repository](https://github.com/pamelarussell/github-bioinformatics)

- [Bioinformatics resources](https://sovacool.dev/posts/2019-05-15-bioinf-resources/)

Resources for Bioinformatics Software Development & Data Analysis.

- [Data analysis and visualization with R](https://datacarpentry.org/R-ecology-lesson/index.html)

Data Carpentry’s aim is to teach researchers basic concepts, skills, and tools for working with data so that they can get more done in less time, and with less pain. The lessons below were designed for those interested in working with ecology data in R.

- [Data skills resources](http://databio.org/skills/)

These are resources to help students interested in developing foundational skills useful for computational biology. The basic section contains short introductions, and advanced resources are more complete references.


## Analysis pipelines for developers 

- [RNA-seq analysis pipeline](https://github.com/mdozmorov/RNA-seq)
RNA-seq analysis pipeline, STAR input, edgeR, functional enrichment, visualization

- [SNP-related notes](https://github.com/mdozmorov/SNP_notes)
SNP- and genome variation-related tools and genomics data analysis resources. Please, contribute and get in touch! See MDmisc notes for other programming and genomics-related notes. 

## Awesome resource repositories for developers

- [Awesome-Bioinformatics](https://github.com/danielecook/Awesome-Bioinformatics)

A curated list of awesome Bioinformatics software, resources, and libraries. Mostly command line based, and free or open-source. Please feel free to contribute!

- [awosome-bioinformatics](https://github.com/openbiox/awosome-bioinformatics)
 
A curated list of resources for learning bioinformatics. Some of this repo resources were collected by BioInstaller project. You can use BioInstaller to directly download the source code or database files, or fetch the meta information by BioInstaller::get.meta()$item.


- [Awesome-single-cell](https://github.com/seandavi/awesome-single-cell)

List of software packages (and the people developing these methods) for single-cell data analysis, including RNA-seq, ATAC-seq, etc. 

- [awesome-multi-omics](https://github.com/mikelove/awesome-multi-omics)

A community-maintained list of software packages for multi-omics data analysis.

- [Getting started with genomics tools and resources](https://github.com/crazyhottommy/getting-started-with-genomics-tools-and-resources)
- [Bioconductor for genomics data science](https://kasperdanielhansen.github.io/genbioconductor/)

- [Bioinformatics_notes](https://github.com/mdozmorov/Bioinformatics_notes)

Bioinformatics learning and data analysis tips and tricks. 


- [Bioinformatics Workbook](https://bioinformaticsworkbook.org/#gsc.tab=0)

The best way to learn bioinformatics is through examples of real world problems. The Bioinformatics Workbook provides the reader with an in depth understanding of experimental design, data acquisition, data wrangling, data analysis and visualization. This is accomplished through worked out example problem in each of these sections along with one or more advanced problem sets and corresponding solutions. This books assumes that the reader has some knowledge of biology and basic understanding of the Unix command line. However, for the beginner, the appendix contains introductory material and tips/tricks for common bioinformatic problems, that is referred to for more information throughout the book.

- [awesome-datascience](https://github.com/academic/awesome-datascience)

An open source Data Science repository to learn and apply towards solving real world problems.

- [awesome-bigdata](https://github.com/0xnr/awesome-bigdata)

A curated list of awesome big data frameworks, resources and other awesomeness. Inspired by awesome-php, awesome-python, awesome-ruby, hadoopecosystemtable & big-data.

- [awesome-R](https://github.com/qinwf/awesome-R)

A curated list of awesome R packages and tools. Inspired by awesome-machine-learning.



