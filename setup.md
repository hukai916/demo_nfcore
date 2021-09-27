# Setup nf-core environment

## Step1: create new conda env: demo_nfcore
conda create --name demo_nfcore
conda activate demo_nfcore

## Step1: install Nextflow:
conda install -c bioconda nextflow
which nextflow

## Step2: install nf-core:
conda install -c bioconda nf-core

## Step3: initialize pipeline template
nf-core create
-- Workflow Name: geotofastq
-- Description: Given GEO ID, retrieve sample sheet, download fastq, and perform FastQC, cutadapt and finnally generate a multiQC report.
-- Auther: your name

## References:
1.  Install Nextflow:
https://anaconda.org/bioconda/nextflow
https://www.nextflow.io/docs/latest/getstarted.html

2.  Install nf-core:
