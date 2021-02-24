---
title: Reanalysis of PXD022085
---

# Proteomic re-analysis of bronchoalveolar lavage fluid in COVID-19 patients

## Live Resources

| usegalaxy.eu |
|:--------:|:------------:|:------------:|:------------:|:------------:|
| <FlatShield label="Input data" message="view" href="https://usegalaxy.eu/u/pratikjagtap/h/pxd019119inputcovid19pqlk " alt="Raw data" /> |
| <FlatShield label="PXD022085 history" message="view" href="https://usegalaxy.eu/u/pratikjagtap/h/pxd019119searchcovid19pqlk-09032020" alt="Galaxy history" /> |
| <FlatShield label="workflow" message="run" href="https://usegalaxy.eu/u/pratikjagtap/w/imported-imported-pxd019119-workflow-for-pq-and-lk-08202020" /> |


## Description

**[Zeng lab](https://www.iprox.org/page/subproject.html?id=IPX0002429001)** collected bottom-up mass spectrometry (MS) data on bronchoalveolar lavage fluid in COVID-19 positive patient samples with respiratory failure. 
Data-dependent acquisition MS spectra were acquired using Q Exactive HF-X mass spectrometer coupled with an EASY-nLC 1200 system and a nano-electrospray ion source. 


## Workflow

![](./img/wfVal.png)

The Galaxy workflow includes RAW data conversion to MGF and mzML format. The MGF files are searched against the combined database of 
Human Uniprot proteome, contaminant proteins and SARS-Cov-2 proteins database using PepQuery Validation workflow. This resulted in detection of ----- peptides from SARS-CoV-2 proteins. The detected peptides were searched against NCBInr to ascertain that these peptides were specific to SARS-CoV-2 proteins. 
The detected peptides were later subjected to analysis by Lorikeet visualization to ascertain the quality of peptide identification.

## Results

We detected -----COVID-19 peptides from all pooled samples in the respiratory tract datasets. The peptides were subjected to BLAST-P and
Lorikeet analysis to ascertain the validity of peptide spectral matches.
