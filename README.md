# Deines, Archontoulis, Huber, & Lobell, PNAS
## Derived data, and analysis code

8 August 2024  
Code by: Jillian Deines  
Contact: jillian.deines@gmail.com  

This codebase accompanies the paper:

Deines, JM, SV Archontoulis, I Huber, & DB Lobell. 2024. Observational evidence for groundwater influence on crop yields in the United States. Proceedings of the National Academy of Sciences. [DOI to come]

## Contents

### Data
All data needed to reproduce the figures in the manuscript can be found in the `data` folder. 

The larger "master" data files of our sampled data needed to run the analyses, plus model intermediates, can be found in a Zenodo repository at [https://zenodo.org/doi/10.5281/zenodo.13274562](https://zenodo.org/doi/10.5281/zenodo.13274562). Other input data are available at their respective sources as described in the manuscript.

**Data included here**

* `data/analysisOutput_forFigures`: clean, simple csv's holding the data needed to reproduce manuscript figures
* `data/misc`: Various data used in analysis scripts, including NASS maize prices
* `data/well_data_FigS5`: Data used to demonstrate water table simulation accuracy in figure S5
* `data/gis`: GIS files for producing the manuscript figures via the figure scripts


### Code
* Code to perform all paper analyses and generate figures in the paper 

Script filenames are numbered in sequential order of use. Processing is done using [R Markdown](https://rmarkdown.rstudio.com/) within an R project structure. Operational scripts have extension .Rmd; notebook style docs (code + outputs) in .md (for easy viewing on Github) and .html (for desktop viewing) are also provided.

To run "analysis" scripts, please download the zipped data folder at [https://zenodo.org/doi/10.5281/zenodo.13274562](https://zenodo.org/doi/10.5281/zenodo.13274562) and save to your local computer. Use the filepath to "RepoData" for the `masterDataDir` variable at the top of each analysis script in the "Directories" code chunk.

Scripts producing figures can run as is, referencing the `data` subfolder of the repository.

### Figure
Informal figure output from scripts 
