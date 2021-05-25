The scripts takes a batch of fcs files as input, converts them to csv and outputs a big csv file with all files concatenated. The original filename is stored in a new column called `name`. 

Install the Flowcore package from Bioconductor. Then use:
```
fcs-to-csv $fcs_files > cells.csv
```
