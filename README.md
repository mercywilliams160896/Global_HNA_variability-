# Global_HNA_variability

<h1> Genetic epidemiology of human neutrophil antigen variants suggest significant global variability </h1>

This repository provides the complete overview of the methodolgy adapted in human neutrophil antigen variant analysis along with the corresponding datafiles used in the study

The study involved a systematic compilation of HNA variants that are approved by Internation Society of Blood Transfusion - Granulocyte Working Party (ISBT-GWP) as well as those extensively curated from various literature sources. Global frequencies of the compiled list of variants were retrieved from major population scale datasets including the 1000 genomes project and gnomAD. Distinct differences or siumilarities of variant frequencies among various global subpopulations were checked and their statistical significance was estimated using Fishers exact test

<h2> Datasets/Tools used in the analysis </h2> <br/>
1. 1000 Genomes Phase 3 vcfs (hg38 build) - https://www.internationalgenome.org/data-portal/data-collection/grch38 <br/>
2. 1000 Genomes Phase 3 subpopulation wise allele frequencies - https://asia.ensembl.org/index.html <br/>
3. gnomAD allele frequencies - https://gnomad.broadinstitute.org/ <br/>
4. Fishers Exact Test (R)

<h2> Steps followed in the analysis of the study data </h2> <br/>

<h3> Compilation of reference file </h3> <br/>
A reference file comprising the list of ISBT approved and curated HNA variants reported till date was compiled in a pre-formatted template to be used as reference <br/>

<h3> Retrieving global population allele frequencies </h3> <br/>
For the compiled list of HNA variants minor allele frequencies from global subpopulations were retrieved <br/>

<h3> Estimation of statistical significance </h3> <br/>
Any statistically distinct differences or similarities were accessed by Fishers exact test (P-value <= 0.05) using the allele counts and allele numbers of the variants

