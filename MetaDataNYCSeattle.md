# Purpose
The purpose of this project is to determine whether it rains more in New York City or Seattle
using weather data from each city.

# Data
This data comes from the National Centers for Environmental Information's NOAA Climate Data. 
The data comprises precipitation, snowfall, and temperature statistics primarily. The data is
pulled from the Global Historical Climatology Network, which itself receives data from over 
100,000 recording stations, primarily in cities or at airports.

# Links
Data Documentation: https://www.ncei.noaa.gov/pub/data/cdo/documentation/GHCND_documentation.pdf
<br />
NOAA Climate Data: https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND

# Preparation
The raw data frames for both Seattle and NYC have been heavily edited to create a new data frame that includes the average precipitation for each day in both cities across all recording stations. The new data frame is called "new_sea_nyc_data.csv" and the steps taken create it may be found in the "Data Preparation Colab Notebook."
