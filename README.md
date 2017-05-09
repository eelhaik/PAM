# PAM
Pair Matcher (PaM): a computer model to optimise pairings using demographic and genetic data

Pre-requisites:

1) linux operating system such as Ubuntu

2) R programming language (and R studio or RKward) installed


Running the package:

3) place uncompressed PaM_local folder on C drive

4) copy plink files (bed/bim/fam) containing 'your' cohort snp data to

PaM_local/uploaded_data folder

and name these files as:

plink.bed
plink.bim
plink.fam

5) in an Xterm window
cd PaM_local

6) ensure linux script is executable using:

chmod +x elhaik_pp.sh

7) launch script using

./elhaik_pp.sh

8a) results folder contains the pairs/unpaired in:
pairs_case_only.csv & 
unpaired_individuals.csv

8b) results folder also contains the admixture components for all individuals & matcher run/screen dump as:
merge.9.Q & 
matcher.Rout

9) test folder contains the input files & results for a small data test (13 individuals)

10) note that run time on i5 laptop using 3 cores for ~3900 individuals each containing ~115k SNPs
is ~7 hours

