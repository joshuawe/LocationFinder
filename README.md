# LocationFinder

## Description
Finds latitude and longitude locations from text and plots them on a map. 

How it works:
1. Create a *.csv file containing the data. The first column contains the variable names. It should contain a a column with the "Location" or "Place" information.
2. The longitude and latitude information for each "Location" will be requested from [maps.co](www.maps.co) and the most likely location will be returned. This is the first result from the search. Therefore, it is better to include more information in the Location, such as country, in order to minimize the error and mixing up.
3. This list of Locations will be visualized by a geo plot using *Plotly*.


## Requirements

> requests
> pandas
> plotly
