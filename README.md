#RNA-seq quality control Mena

##This repository provides a small workflow for RNA-seq sample metadata quality control


###bio196-week6-git-pcoles01/data/ contains sample_metadata.csv

*sample_metadata.csv provides the sample_id, condition, and replicate of four samples*

###bio196-week6-git-pcoles01/scripts/ contains qc_check.R

*qc_check.R provides a script for ensuring the data is clean and organized before printing a table for inspection*


**To run the qc_check.R script:**

*First, run:*

cd /

*Then, run:*

RScript scripts/qc_check.R


**Expected output:**

*The script should check the sample identifiers and print the number of samples in each condition*


**Data policy:**

*Please do not commit raw sequencing data, private data, credentials, or large generated files to the repository*
