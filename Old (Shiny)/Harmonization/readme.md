#### This web application contains two functions:
1. Quality Control Check: internal functionality to check and get some stats from the master harmonized file generated by Adam
2. Harmonization Check: allows consortium members to check whether their list of metabolites has already been integrated and harmonized into the master harmonized file.

#### Here's a little more description on how to use each utility:


#### 1) Quality Control Check 
This app takes in two data files:

- uids.csv (harmonized file that Adam compiles)
- Refmet.csv (BIOCHEMICAL names with refmet ids)

All files must be in comma-delimited format (.csv).  To get a csv file, simply save your Excel sheet as a csv.

#####Mapping to Refmet:
Take the BIOCHEMICAL ids from uids.csv, and plug them into this web application:

http://www.metabolomicsworkbench.org/data/name_to_refmet_form.php

Then copy paste the output into Excel and save as csv.  

#####Important note: this app requires a column named BIOCHEMICAL

#### 2) Harmonization Check
This app takes in one data file:

- list of metabolite names with one name per line (.txt format preferred)

#### 3) Questions/Concerns
Please email the COMETS Harmonization group should you run into any issues.