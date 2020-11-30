# ANAPURRNAseq : Automated Nexflow Alignement Pipeline for Uncleared Reads from RNAseq

> #Bioinformatics #pipeline 

## Tasks

- [ ] [README](Bioinformatics/ReadCountPipeline/README.md)
  - [ ] Usage 
  - [ ] Step description
  - [ ] introduction
- [ ] publish the pipeline on Github
- [ ] Adapt the pipeline for C.glabrata

## Done

- [x] Create a pipeline using [NextFlow](Notes/Nextflow.md) The pipeline can be found into [/Bioinformatics/ReadCountPipeline](/Bioinformatics/ReadCountPipeline)
  - [x] download all files
  - [x] generate fastQC reports
  - [x] generate MultiQC report
  - [x] sort reads using Clumpify
  - [x] Remove adapters 
  - [x] Quality filtring
  - [x] Artifact filtering
  - [x] Contamination removal
  - [x] filtering for low complexity
  - [x] Remove rRNA
  - [x] QC Analysis
- [x] Test the pipeline on the a dataset  in [Data/Sample_dataset](Data/Sample_dataset)
  - [x] adapt the code to reduce space usage at the rRNA step
  - [x] test on [Data/Sample_dataset](Data/Sample_dataset)