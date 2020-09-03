# Installation

In order to correctly run the notebook and visualize the results, it is necessary to have installed python 3.*, 
the anaconda package and additionally the following packages: mapclassify, descartes, geopandas.

# Motivation

This project is related to the analysis of Airbnb accomodations in Milan, the city were I live. I was interested in
understanding which are the most expensive neighbourhoods, the density of Airbnb accomodations and also to explore
the CRISP-DM process.

# File Description

The jupyter notebook contains the whole process I followed to carry out my analysis and to extract the information needed to arrive to my results. 
The datasets used in the project are csv files contained in the folder "Airbnb Milan Housing", which were downloaded from "http://insideairbnb.com/get-the-data.html"
The folder "Agenzia Entrate Milan Housing" contains other publically available data for housing prices, not used in this project but that could be used to extend it,
taken from official site "www.agenziaentrate.gov.it".

# Details

This project carry out an analysis of Airbnb listings, giving details on the neighbourhoods with highest density and price in the Milan area, together with a first implementation 
of a simple ML model to predict accomodation prices given the available features.
I chose to use geopandas to create choropleth maps to visualize my results, as the dataset was providing a .geojason file containing all the different neighbourhoods.
In order to classify the different zones in the maps, I used the FisherJenks schema as it was appropriate to highlight the natural breaks in the data.

# Acknowledgements

Data provider: 
	"Inside Airbnb" under license "Creative Commons CC0 1.0 Universal (CC0 1.0) "Public Domain Dedication"
	"Agenzia delle Entrate": Banca dati delle quotazioni immobiliari (public bank of real estate quotes)