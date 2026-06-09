# Semester project "Stochastic Hydrology"- Analyzing discharge and precipitation in the Rhone catchment
## Abstract
Floods and droughts pose major threats to humans and ecosystems with significant potential for damage. 
Reliable forecasting is therefore essential to support risk mitigation, particularly under the inherent 
variability and uncertainty of hydrological processes. Based on a case study in Sion of the Rhone 
streamflow, various stochastic hydrology methods are applied such as univariate frequency analysis and 
time series analysis. Furthermore, we performed a multivariate frequency analysis using joint density 
approach with copulas to model discharge and precipitation jointly.  

## Main workflow steps
This workflow follows a clear step-wise approach: 
First, univariate frequency analysis was conducted. Second, time series analysis was perfomed. Third, a bivariate analysis using copulas was done.

## Data Sources
This analysis is based on the CAMELS-CH dataset (Höge et al., 2023), wich is available under following link: https://essd.copernicus.org/articles/15/5755/2023/
We selected the Sion gauging station (gauge_id 2011) on the Rhône, covering the period 1990–2020 (31 years).


## Setup Instructions
This project was developed with Python 3.12 using Visual Studio Code and requires a specific environment. 
For recreating the environment, please see the environment.yml file.

## Execution Order
Recreate environment using the provided environment.yml. Then, execute the Jupyter Notebook 'final.ipynb' from top to bottom.

Step 1:
cd ~/Desktop
git clone https://github.com/javierfeller/stochastic_hydrology.git
cd stochastic_hydrology

Step 2: Create and Activate the Environment
conda env create -f environment.yml
conda activate stochastic_hydrology

## Step 3: Initialize the Directory Structure
Open your Jupyter environment.