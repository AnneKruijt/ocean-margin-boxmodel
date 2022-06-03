# Ocean margin model for carbon transfer calculations

# Introduction
This PhD project focusses on the role of ocean margins and shallow seas in the global carbon cycle. We aim to better quantify transfer of carbon through the ocean margin domain and study the sensitivity of carbon fluxes to changes in environmental conditions in ocean margins. 

For this we develop a conceptual ocean margin model. This model, which contains simple hydrodynamics and biogeochemical processes, bridges the gap between existing global carbon cycle models and site-specific coastal ocean biogeochemistry models. Using global input fluxes of particulate and dissolved inorganic and organic carbon we will explore global ocean margin calcification,  air-sea CO2-fluxes, and their dependencies on environmental factors.  We will test the effect of changes in bathymetry, temperature and light attenuation on the way carbon is transferred through the coastal interface, and show the models applicability to Cenozoic climate excursions. With our model, necessary first order insights can be gained into the effect of ocean margin calcification dynamics on the global carbon transfer during these past events., flexible in dimensions and number of boxesWe present a new ocean margin model focusing on calcification in the shallow marine realm. 

# Configuration instructions
Code is written in R version 4.1.2 (2021-11-01)
It is running under Windows 10 x64 (build 19042), and has not yet been tested on other operating systems.  

# Installation instructions
The recuired version of R can be downloaded from: https://cran.r-project.org/bin/windows/base/old/
Information on how to use Rmarkdown, which was used to produce the scripts in this project, see: https://rmarkdown.rstudio.com/

# Dependencies
Packages loaded via a namespace (and not attached):
compiler_4.1.2  
fastmap_1.1.0   
cli_3.2.0       
htmltools_0.5.2 
tools_4.1.2     
yaml_2.3.5      
rmarkdown_2.12 
knitr_1.37      
xfun_0.30       
digest_0.6.29   
rlang_1.0.2     
evaluate_0.15 

Packages that need to be installed and loaded:
docstring_1.0.0
rootSolve_1.8.2.3
deSolve_1.30
seacarb_3.3.0
ggplot2_3.3.5
grid_4.1.2

# Additional information
- TODO: refer to doc or csv file containing description of all the variables and paramter settings used in the model simulations.


## Project organization
- PG = project-generated
- HW = human-writable
- RO = read only

```
.
├── .gitignore
├── CITATION.md
├── LICENSE.md
├── README.md
├── requirements.txt
├── bin                <- Compiled and external code, ignored by git (PG)
│   └── external       <- Any external source code, ignored by git (RO)
├── config             <- Configuration files (HW)
├── data               <- All project data, ignored by git
│   ├── processed      <- The final, canonical data sets for modeling. (PG)
│   ├── raw            <- The original, immutable data dump. (RO)
│   └── temp           <- Intermediate data that has been transformed. (PG)
├── docs               <- Documentation notebook for users (HW)
│   ├── manuscript     <- Manuscript source, e.g., LaTeX, Markdown, etc. (HW)
│   └── reports        <- Other project reports and notebooks (e.g. Jupyter, .Rmd) (HW)
├── results
│   ├── figures        <- Figures for the manuscript or reports (PG)
│   └── output         <- Other output for the manuscript or reports (PG)
└── scripts            <- Source code for this project (HW)

```

## Citing

## License

This project is licensed under the terms of the [MIT License](/LICENSE.md)
