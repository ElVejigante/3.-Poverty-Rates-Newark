**2019 US Census Poverty Rates in Newark, NJ**
*By Zip Code*
Before running Jupyter notebook (Newark Poverty Rate.ipynb) make sure you have the following:

1. Your Google API key as g_key AND Census API key as census_key in the file named config.py.
2. Check that newark_abandoned_data.csv is in 'data' folder

Once the notebook is run, it should display the following:
1. A csv file with population per zip code and poverty rates (output.csv)
2. A csv file that appends the output.csv to geographical coordinates (newark_poverty_population.csv)
3. A png file that displays the poverty rates per zip code over a map of Newark (newark_poverty_map.png)
4. These 3 files are available in the 'output' folder

This notebook combines the abandoned property data csv with US Census American Community Survey (5-Yr) for 2019.
It then groups the data by zip code and calculates an average value for geographical coordinates, to get at a "central" lat/long coordinate for each zip code. Then this data is displayed over a google map of Newark.
