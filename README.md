# EASi-seq
EASi-seq (Easily Accessible Single microbe sequencing

# EASi-seq Data analysis

This repository contains the python jupyter notebooks for the data analysis in the manuscript, "Microbiome single cell atlases generated with a commercial instrument".

## Disclaimer:
All jupyter notebooks are provided for reference purpose only. A bioinformatics pipeline for EASi-seq data analysis is currently under development. 
The code here is no longer maintained and is provided as is in order for the reader to get a general idea of the bioinformatics processes. 
  

## Contents
Zymo/: 

	Zymo_reference_based_analysis.ipynb (Zymobiomics EASi-seq reference based data analysis, Figure 2b-f)
	
	Zymo_kraken_based_analysis.ipynb (Zymobiomics EASi-seq TDA analysis)
		
	Zymo_metagenomic_processing.ipynb (Zymobiomics EASi-seq and metagenomic intergration, Figure 2g-j)
	
Simulation/:

	Taxa_profiler_evaluation_for_TDA_barcode_generation.ipynb (Taxonomic profiler evaluation using simulation data, Figure S7 and Discussion S1)

Elenta/:

	Elenta_EASi-seq_analysis.ipynb (Elenta 22 strain EASi-seq data analysis, Figure 3)
	
HM3/: 

	Human_Gut_Microbiome_EASi-seq_data_processing.ipynb	(Human microbiome EASi-seq data processing)
	
	HM3_EASi-seq_and_metagenomic_integration.ipynb (Human microbiome EASi-seq and Metagenomic data integration, Figure 4)
	
	HM3_metagenome_VS_EASi-seq_psudobulk_gtdb.ipynb (Human microbiome EASi-seq and Metagenomic comparasion, Figure S20)
	
Ocean/:

	Ocean_microbiome_EASi-seq_analysis.ipynb (Ocean water microbiome EASi-seq data analysis process, Figure 5a-b)
	
	Halioglobus_analysis_gene_family-Copy1.ipynb (Ocean water microbiome EASi-seq data Halioglobus genus single cell pathway analysis, Figure 5c-d)

Supplimentary_Data/:
This folder contains supplementary tables for the manuscripts. 

	
## Required Tools

Bowtie2 (https://bowtie-bio.sourceforge.net/bowtie2/manual.shtml)

Samtools (http://github.com/samtools/)

SPAdes (https://github.com/ablab/spades)

Quast (https://quast.sourceforge.net/quast.html)

BBTools (https://jgi.doe.gov/data-and-tools/software-tools/bbtools/)

HUMMAN3 (https://github.com/biobakery/humann)

Kraken2 (https://ccb.jhu.edu/software/kraken2/)

Bracken2 (https://ccb.jhu.edu/software/bracken/)

DESeq (https://www.bioconductor.org/packages//2.10/bioc/html/DESeq.html)

Seqtk toolkit (https://github.com/lh3/seqtk) 

## Requried Database
Kraken2/Bracken Database

PlusPF https://benlangmead.github.io/aws-indexes/k2, Version: 1/27/2021

GTDB https://gtdb.ecogenomic.org/tools, Release 95) 

Comprehensive Antibiotic Resistance Database (CARD) (v 3.1.4)
(https://card.mcmaster.ca/download)

## Data availability
All sequencing data is accessible at the NCBI Sequence Read Archive (Accession numbers: SUB12874540).
For Intermediate files and output files, please contact the author: (Xiangpeng.li@ucsf.edu).


 
