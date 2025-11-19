## SYSTEM REQUIREMENTS

### HARDWARE REQUIREMENTS
mem_montecarlo.rmd and tangetal2025_code.ipynb and require only a standard computer with enough RAM to support the in-memory operations.

### SOFTWARE REQUIREMENTS
Mixed effects model and Monte Carlo simulations were run using R (v4.2.0) and the following packages: tidyverse (v2.0.0), transport (v0.14.6), car (v3.1.3), lme4 (v1.1.31), and performance (v0.13.0). All other analyses and figures were generated with Python (v3.11.4) and the following packages: jupyterlab (v4.0.3), pandas (v2.3.3), numpy (v2.3.3), seaborn (v0.13.2), matplotlib (v3.10.6), scipy (v1.16.1), and statsmodels (v0.14.5).

## INSTALLATION GUIDE
Installation of RStudio and JupyterLab takes 3-5 minutes each.

To set up the development environment of tangetal2025_code.ipynb, run the following in command line: 
pip install -r requirements.txt

There are extraneous libraries. 

## DEMO
Since all data are included to reproduce all figures, rather than a subset for demonstrative purposes, this is not a strictly demo. Run all code blocks in sequential order to reproduce figures. 

### EXPECTED OUTPUT
The data provided in 01-data/ contains all data used in the publication and supplementary figures, and the code provided in 02-code/ generates all figures. 

### EXPECTED RUNTIME
Generating all figures in tangetal2025_code.ipynb takes 1-2 minutes. Running the Monte Carlo simulations takes several hours.

## INSTRUCTIONS FOR USE
All data necessary for all figures and models are found in 01-data/. All necessary metadata are added to the data in mem_montecarlo.rmd and tangetal2025_code.ipynb.

Run all code blocks in tangetal2025_code.ipynb in sequential order to generate figures and supplementary figures. Code blocks in tangetal2025_code.ipynb are thoroughly commented to indicate which data are used to generated each figure. Metadata-annotated data are viewable as DataFrames in tangetal2025_code.ipynb. Cartoons were added with BioRender and will not be generated automatically.