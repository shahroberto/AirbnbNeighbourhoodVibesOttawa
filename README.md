### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

This code requires the Anaconda distribution of Python versions 3.*. and three geospatial data libraries:
```
$ conda install geopandas
$ conda install libpysal
$ conda install pysal
```

## Project Motivation<a name="motivation"></a>

For this project I'm interested in using Airbnb listings data for Ottawa, ON, Canada to better understand the Airbnb vibe throughout Ottawa neighbourhoods.  More specifically:

1. What's the availability of Airbnbs in Ottawa in each neighbourhood?
2. Which neighbourhoods are the most expensive, on average, in Ottawa?
2. Can I find a meaniingful connection between d ifferent neighbourhoods from Airbnb unit features?
3. What are the more desirable neighbourhoods to stay in when travelling to Ottawa?

## File Descriptions <a name="files"></a>

There are 3 notebooks available here to showcase work related to the above questions.  Each of the notebooks is exploratory in searching through the data pertaining to the questions showcased by the notebook title.  Markdown cells were used to assist in walking through the thought process for individual steps.  

1. `DensityAndPriceDemographics.ipynb` shows the analysis used to determine density and pricing distributions over neighbourhoods
2. `ClusteringOnUnitProperties.ipynb` is a clustering analysis to find commoninities in neighbourhoods based on unit features.
3. `ClusteringOnReviews.ipynb` looks for clusters based on user reviews and contiguity weights between neighbourhoods.
4. `listings.csv` is a tabular datafile containing Airbnb listings in the City of Ottawa, ON, Canada.
5. `neighbourhoods.geojson` is a geojson datafile with geospatial data by census tract in Ottawa, ON, Canada.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://robertshaheen.medium.com/best-airbnb-neighbourhoods-in-canadas-capital-34009041ad95).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Airbnb for the data.  You can find the Licensing for the data and other descriptive information at the Licensing link available [here](https://creativecommons.org/publicdomain/zero/1.0/).
