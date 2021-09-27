# Demo of a toy pipeline built with nf-core
Given GEO ID, retrieve sample_sheet.csv, download fastq files, perform FastQC, and cutadapt. Finally, generate a MultiQC report.

## Setup Nextflow, nf-core, initiate template:
Check out setup.md.

## Module 1: GET_SAMPLE_SHEET
Given GEO ID, retrive sample_sheet.csv.

## Module 2: GET_FASTQ
Given sample_sheet.csv, download fastq files.

## Module 3: FASTQC
Perform FastQC on fastq files.

## Module 4: CUTADAPT
Perform cutadatp on fastq files.
