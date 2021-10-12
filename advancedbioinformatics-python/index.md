Bioinformatics with Python
===============

Python is an easy to learn programming language, and so powerful enough to accomplish most programming goals. Bioinformatists use python for molecular visualization, genome annotation, data manipulation and countless other applications. In this page we will introduce the python tools developed to perform some of the most important data analysis particularly analysis of next-generation sequencing data.

## Sequence Analysis

### libraries

- biopython

    The Biopython Project is an international association of developers of [freely available Python tools](https://www.python.org) for computational molecular biology. The [Biopython web site](http://www.biopython.org) provides an online resource for modules, scripts, and web links for developers of Python-based software for bioinformatics use and research. Basically, the goal of Biopython is to make it as easy as possible to use Python for bioinformatics by creating high-quality, reusable modules and classes. Biopython features include parsers for various Bioinformatics file formats (BLAST, Clustalw, FASTA, Genbank,...), access to online services (NCBI, Expasy,...), interfaces to common and not-so-common programs (Clustalw, DSSP, MSMS...), a standard sequence class, various clustering modules, a KD tree data structure etc. and even documentation.
 
    [biopython tutorial](http://biopython.org/DIST/docs/tutorial/Tutorial.html)
    
### Online sources:

- videos
    Presented for the course COMP 364 at McGill University:
 
    - 
        - [](https://www.youtube.com/watch?v=qQ7rIpB4oOw)
    In order to get the material of this video go to [here](https://nbviewer.jupyter.org/github/cgoliver/Notebooks/blob/master/COMP_364/L25/L25.ipynb)


- For developers 
    - Fork the [BioPython repository on github](https://github.com/biopython/biopython)



## Processing Next Generation Sequencing (NGS) data

### libraries

- Biopython
- numpy
- seaborn

- [pysam](https://pysam.readthedocs.io/en/latest/)
    
    Pysam is a python module for reading, manipulating and writing genomic data sets.
    
    Pysam is a wrapper of the htslib C-API and provides facilities to read and write SAM/BAM/VCF/BCF/BED/GFF/GTF/FASTA/FASTQ files as well as access to the command line functionality of the samtools and bcftools packages. The module supports compression and random access through indexing.
    
- [GATK](https://gatk.broadinstitute.org/hc/en-us/articles/360036194592-Getting-started-with-GATK4)

    GATK (pronounced "Gee-ay-tee-kay", not "Gat-kay"), stands for GenomeAnalysisToolkit. It is a collection of command-line tools for analyzing high-throughput sequencing data with a primary focus on variant discovery. The tools can be used individually or chained together into complete workflows. We provide end-to-end workflows, called GATK Best Practices, tailored for specific use cases.  
    
- [pyvcf](https://pyvcf.readthedocs.io/en/latest/)

- [HTseq](https://htseq.readthedocs.io/en/master/)

    HTSeq is a Python package that provides infrastructure to process data from high-throughput sequencing assays. HTSeq is currently developed by Fabio Zanini at University of New South Wales in Sydney (fabio dot zanini at unsw dot edu dot au) and Simon Anders (anders at embl dot de) at EMBL Heidelberg (Genome Biology Unit). HTseq supports FASTA, FASTQ, SAM, VCF, GFF, and BED file formats. 

    [HTseq documentation](https://htseq.readthedocs.io/en/master/)


    HTseq documentation will teach you how to get started. It explains how to install it, and then walks you through analysis steps with explicit examples. 


### online sources

- books
    - https://hub.packtpub.com/processing-next-generation-sequencing-datasets-using-python/
    - [Beginner's Handbook of Next Generation Sequencing](https://genohub.com/next-generation-sequencing-handbook/)

- videos:
    - [](https://www.youtube.com/watch?v=6Is3W7JkFp8 "Next Generation Sequencing technologies - Elaine Mardis 2014")

- Websites
    - [Bioinformatics at COMAV](https://bioinf.comav.upv.es/courses/sequence_analysis/index.html) 
    - [List of RNA-seq bioinformatics tools](https://en.wikipedia.org/wiki/List_of_RNA-Seq_bioinformatics_tools)

- Publications
    - [Biostars](https://www.biostars.org/p/52152/)
Review papers on the topic of RNA-seq


- For developers:
    - fork [pysam repository on github](https://github.com/pysam-developers/pysam)
    - fork [GATK4 repository on github](https://github.com/broadinstitute/gatk)
    - fork [pycvf repository on github](https://github.com/jamescasbon/PyVCF/)
    - fork [HTseq repository on github](https://github.com/htseq/htseq)
    - [Informatics for RNA-seq: A web resource for analysis on the cloud](https://github.com/griffithlab/rnaseq_tutorial)
 
    

## Population Genetics


- Libraries
- Numpy
- Biopython
- Bio.PopGen

Biopython makes Population Genetics functionality available in the Bio.PopGen module.

[Bio.PopGen documentation](https://biopython.org/wiki/PopGen)

- pygenomics
  
To see details about pygenomics use [pygenomics repository](https://github.com/tiagoantao/pygenomics)

- pypop


PyPop (Python for Population Genomics) is an environment developed by the Thomson lab for doing large-scale population genetic analyses including: (1) conformity to Hardy-Weinberg expectations, (2) tests for balancing or directional selection; (3) estimates of haplotype frequencies (and their distributions) and measures and tests of significance for linkage disequilibrium (LD). 
[PyPop Documentation](http://pypop.org/)


### For developers:
- fork [pygenomics repository](https://github.com/tiagoantao/pygenomics)
- fork [pypop repository](https://github.com/alexlancaster/pypop)


## Phylogenetics

- Biopython
- Bio.Phylo


This module provides classes, functions and I/O support for working with phylogenetic trees.
[Bio.Phylo documentation](https://biopython.org/wiki/Phylo)

- DendroPy

A Python library for phylogenetics and phylogenetic computing: reading, writing, simulation, processing and manipulation of phylogenetic trees (phylogenies) and characters.
[DendroPy documentation](https://pypi.org/project/DendroPy/)


Online Sources:


- Videos
    - Biopython Tutorial: Construct a phylogenetic tree
        - [](https://www.youtube.com/watch?v=8ICbCmZtuSk)

### For developers

- fork [DendroPy repository](https://github.com/jeetsukumaran/DendroPy)



## Working with protein data bank

Libraries:

- BioPython
- Bio.PDB

[Bio.PDB documentation](https://biopython.org/docs/1.75/api/Bio.PDB.html)


Online Resources:


- Videos:
    - BioPython structure analysis
        - [](https://www.youtube.com/watch?v=mL8NPpRxgJA)


## Working with Big Data

Libraries:

- Dask


Dask is a flexible library for parallel computing in Python.

Dask is composed of two parts:

1. Dynamic task scheduling optimized for computation. This is similar to Airflow, Luigi, Celery, or Make, but optimized for interactive computational workloads.

2. Big Data” collections like parallel arrays, dataframes, and lists that extend common interfaces like NumPy, Pandas, or Python iterators to larger-than-memory or distributed environments. These parallel collections run on top of dynamic task schedulers.

[Dask Documentation](https://docs.dask.org/en/latest/)

- PySpark

PySpark is an interface for Apache Spark in Python. It not only allows you to write Spark applications using Python APIs, but also provides the PySpark shell for interactively analyzing your data in a distributed environment. PySpark supports most of Spark’s features such as Spark SQL, DataFrame, Streaming, MLlib (Machine Learning) and Spark Core.

[PySpark Documentation](http://spark.apache.org/docs/latest/api/python/)


- Cython 

Cython is an optimising static compiler for both the Python programming language and the extended Cython programming language (based on Pyrex). It makes writing C extensions for Python as easy as Python itself.

[Cython Documentation](https://cython.org/)

- Numba

Numba translates Python functions to optimized machine code at runtime using the industry-standard LLVM compiler library. Numba-compiled numerical algorithms in Python can approach the speeds of C or FORTRAN.

[Numba Documentation](http://numba.pydata.org/)



### For developers

- [Dask source code](https://github.com/dask/dask)
- [PySpark source code](https://github.com/apache/spark/tree/master/python/pyspark)
- [Cython source code](https://github.com/cython/cython) 
- 


## Additional resources


### Work-flow managers

- [Galaxy](https://galaxyproject.org/)
Galaxy is an open, web-based platform for accessible, reproducible, and transparent computational research.

- [NextFlow](https://nextflow.io/)
Nextflow enables scalable and reproducible scientific workflows using software containers. It allows the adaptation of pipelines written in the most common scripting languages.

### Pipelines

- [ngs-preprocess](https://ngs-preprocess.readthedocs.io/en/latest/?badge=latest)
NGS-preprocess is a pipeline developed with Nextflow and Docker. It was designed to provide an easy-to-use framework for preprocessing sequencing reads from Illumina, Pacbio and Oxford Nanopore platforms. 
- To see a full list of pipelines go to [Awesome-Pipeline](https://github.com/pditommaso/awesome-pipeline)

### Websites    

- [RNA-seqlopedia](https://rnaseq.uoregon.edu/)
The RNA-seqlopedia provides an overview of RNA-seq and of the choices necessary to carry out a successful RNA-seq experiment.




### Publication

- [A survey of best practices for RNA-seq data analysis](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-0881-8)
Abstract

RNA-sequencing (RNA-seq) has a wide variety of applications, but no single analysis pipeline can be used in all cases. We review all of the major steps in RNA-seq data analysis, including experimental design, quality control, read alignment, quantification of gene and transcript levels, visualization, differential gene expression, alternative splicing, functional analysis, gene fusion detection and eQTL mapping. We highlight the challenges associated with each step. We discuss the analysis of small RNAs and the integration of RNA-seq with other functional genomics techniques. Finally, we discuss the outlook for novel technologies that are changing the state of the art in transcriptomics. [Read full article](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-0881-8)


## github repositories for developers 

- [Python data science handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)

This website contains the full text of the Python Data Science Handbook by Jake VanderPlas; the content is available on GitHub in the form of Jupyter notebooks.

- [DataSciencePython](https://github.com/ujjwalkarn/DataSciencePython)

This repo contains a curated list of Python tutorials for Data Science, NLP and Machine Learning.

- [awesome-python](https://awesome-python.com/)

A curated list of awesome Python frameworks, libraries, software and resources.

- [Awesome-Bioinformatics](https://github.com/danielecook/Awesome-Bioinformatics)

A curated list of awesome Bioinformatics software, resources, and libraries. Mostly command line based, and free or open-source. Please feel free to contribute!

- [awosome-bioinformatics](https://github.com/openbiox/awosome-bioinformatics)
 
A curated list of resources for learning bioinformatics. Some of this repo resources were collected by BioInstaller project. You can use BioInstaller to directly download the source code or database files, or fetch the meta information by BioInstaller::get.meta()$item.

- [Awesome-single-cell](https://github.com/seandavi/awesome-single-cell)

List of software packages (and the people developing these methods) for single-cell data analysis, including RNA-seq, ATAC-seq, etc. 

- [awesome-multi-omics](https://github.com/mikelove/awesome-multi-omics)

A community-maintained list of software packages for multi-omics data analysis.

- [Getting started with genomics tools and resources](https://github.com/crazyhottommy/getting-started-with-genomics-tools-and-resources)

- [awesome-datascience](https://github.com/academic/awesome-datascience)

An open source Data Science repository to learn and apply towards solving real world problems.

- [awesome-bigdata](https://github.com/0xnr/awesome-bigdata)

A curated list of aweome big data frameworks, resources and other awesomeness. Inspired by awesome-php, awesome-python, awesome-ruby, hadoopecosystemtable & big-data.
