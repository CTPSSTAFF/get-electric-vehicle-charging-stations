# get-electric-vehicle-charging-stations
Notebook to use DOE/NREL API to generate shapefiles of electric vehicle charging stations in 
1. Massachusetts statewide
2. the Boston MPO region only

## Pre-requisite
In order to run this notebook, you must have an API key for the Department of Energy National Renewable Energy Laboratory's Developer Network.
An API key may be obtained by filling in and submitting the form at [this URL](https://developer.nrel.gov/signup/).

## Usage
1. The Anaconda environment required to run this notebook is defined in the __ev\_charging\_stations.yml__ file in this repository. Create this environment as follows:
```
conda env create -f ev_charging_stations.yml
```
2. Activate this environment, and launch Jupyter notebooks:
```
conda activate ev_charging_stations
jupyter notebook
```
3. In Jupyter notebooks, open the notebook 'get-electric-vehicle-charging-stations.ipynb'
4. In the second 'code' cell of the notebook, specify the name of the output shapefiles for:
  * EV charging stations in all of Massachusetts
  * EV charging stations in the Boston Region MPO area only
5. In the fourth 'code' cell in the notebook, specify your API key.
6. Run the notebook; select __Cell -> Run All__ from the notebook menu.

Reference document: [Data dictionary for data returned by API calls](https://afdc.energy.gov/data_download/alt_fuel_stations_format)
