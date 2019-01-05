# Nice Ride Minnesota 2017

Nice Ride is a community biking service where bikes can be picked up from one location and dropped off at another. The idea is to create healthier communities and increase transporation options for people living in the Twin Cities. This project is to answer some questions related to the dataset.

Data Sources:
* http://opendata.minneapolismn.gov/datasets/89f1a70c0cf24d7692e2d02fdf8f4e47_0
* https://www.kaggle.com/brendanhasz/nice-ride-mn-2017/version/2#WeatherDailyMinneapolis2017.csv

Files:
* `trip_history.csv` : A trip history list for each ride taken by a customer
* `station_locations.csv` : A list of all the stations and their locations
* `weather.csv` : A basic weather report for each day
* `msvcGIS_MinneapolisCityLimits.kml` : A list of coordinates that outline the boundary of Minneapolis
* `json_data` : A folder with geojson data for rendering in folium. This file is generated from the `msvcGIS_MinneapolisCityLimits.kml` file.

Libraries used:
* `pandas` : A package for building and utilizing dataframes
* `numpy` : A package for building and utilizing series
* `seaborn` : Used in this project for plotting correlations
* `folium` : To build maps
* `kml2geojson` : Used to convert a kml boundary file into geojson for use in folium
* `shapely` : Used to build points and shapes on a folium map
* `plotnine` : A port of ggplot in python
* `mizani` : To break up dates for plotting
* `geopy` : Used to calculate the distance between two gps coordinates
* `IPython.display` : Used to manipulate the jupyter notebook output
* `sklearn` : Machine learning, clustering, regressions and scaling

Acknowledgements:
* https://stackoverflow.com/questions/27934885/how-to-hide-code-from-cells-in-ipython-notebook-visualized-with-nbviewer
* https://www.kaggle.com/shivamb/4-1-analysis-measuring-equity-minneapolis-pd/notebook
* https://stackoverflow.com/questions/29432629/correlation-matrix-using-pandas#29432741
* https://geoffboeing.com/2014/08/clustering-to-reduce-spatial-data-set-size/
* https://towardsdatascience.com/random-forest-in-python-24d0893d51c0
* https://stackoverflow.com/questions/19412462/getting-distance-between-two-points-based-on-latitude-longitude#19412565