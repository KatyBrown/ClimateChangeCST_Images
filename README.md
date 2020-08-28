# ClimateChangeCST_Images

This repository contains the images generated as part of a project to determine if the overlap between the distribution of two species is likely to increase in the future under different climate change projections, in order to later use this data to investigate potential for viral transmission.

### Current_Species_Distribution_Maps
Maps showing the observed occurrences of different species from the GBIF database, filtered to remove instances with no geographical information, a country code not corresponding to their latitude and longitude or not on land.

### Predicted_Species_Distribution_Maps
Maps showing the predicted distribution of different species under a random forest species distribution model (applied with the R dismo package) under future climate predictions under different climate models and shared socioeconomic pathways, downloaded from WORLDCLIM.

### SSP_Pollutant_Plots
The predicted emissions of different pollutants under various climate models, sourced from https://tntcat.iiasa.ac.at

### Species_Distribution_Overlap_Barcharts
Bar charts showing the predicted % overlap and total overlap in the distribution of various pairs of species under the random forest model under different climate change projections.

### WORLDCLIM_variable_barcharts
Bar charts showing the predicted mean for the 19 Bioclim bioclimatic variables under different climate change projections.

### WORLDCLIM_variable_maps
Maps showing the predictions for the 19 Bioclim bioclimatic variables under different climate change projections.

**Model_comparison.png**

Bar chart comparing model accuracy on test data for three species distribution models

**Species_counts_filtering.png**

Bar chart showing the number of species occurences in GBIF for each species and the number filtered out because they had no geographical information, a country code not corresponding to their latitude and longitude or were not on land.
