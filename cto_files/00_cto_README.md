# CTO file transformation read me

Added description of folder here once ready.

This are the files I used to to create the FFIAT study's csv file to use in Survey CTO. The R file labeled "FNDDS to CTO Flow - Workspace.rmd" is the R studio file that pulls everything together and spits out the following outputs.

** all of the following files are CTO search compatible via columns ending with "_key".
1. fndds23_master_JOC.csv : the main file that CTO will use in our search functions. Includes input data from the FNDDS files and ZPG's analysis by FNDDS food code.
2. fndds23_ingredients_JOC.csv : supplementary file from FNDDS. Used to know what ingredients each food code has.
3. fndds23_portions_JOC.csv : supplementary file from FNDDS. Used to know how FNDDS has measured each food code.
