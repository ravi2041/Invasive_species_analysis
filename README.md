# Invasive_species_analysis

The motive of this project is to forecast number of invading species by including citizens science concept and to find how many species has been photographed or not. This helps in montioring indigenious species and if any pest or exotic species are found then it can handled in efficient manner.

The exotic list contained important features like size, region of origin, location of first observation, feeding characteristics and 
taxonomical details of the species (1500). As a start point it was important to find out how many species had been photographed.
A comparison with GBIF showed 371 species which had already been photographed by people. It was seen that GBIF contained certain 
important factors like latitude, longitude of observations, date and time of observation, details of observers and so on. These factors
were also incorporated in the Exotic Data with the aim of creating a Master Dataset.
In addition, other factors like region of the observation in New Zealand, colours, shape, has wings or not etc. were also added after
due deliberations and discussions with SCION. As a result the number of features being examined grew from original 24 in the Exotic 
dataset to 28 in Enriched Exotic and 88 columns in the final Master Sheet.

Data has been collected using web scraping and API provided by GBIF. Few features were added manualy which is important in predicting 
species. 
