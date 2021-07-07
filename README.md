# Bulk RNA-seq Workshop

## Instructions


1. Ensure that RStudio is installed. Install the `renv` package by running the following line in the RStudio Console:

```
install.packages("renv")
```

2. Download the workshop material by clicking [here](https://github.com/sagc-bioinformatics/Bulk_RNAseq/archive/refs/heads/master.zip) and unzip the folder. 
  
  - Open the `Bulk_RNAseq.Rproj` file to open the R Project in RStudio. 
  - Navigate to the `analysis` folder, and click the `de.Rmd` file to open up the analysis in RStudio. 
  - Also, navigate to the `docs` folder, and click on the `de.html` file to open up the analysis documentation in a web browser.

3. In the RStudio Console, run the following lines of code to download and install all required packages using `renv`:

```
renv::restore(library = "./rlib/")
.libPaths( c( .libPaths(), "./rlib") )
```

4. You are ready to start running through the workshop material! 
