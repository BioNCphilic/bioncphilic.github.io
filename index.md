# Documenting my Learning Adventure 
This adventure made possible through the University of Colorado Boulder
and the Environmental Data Science Innovation and Inclusion Lab

### Contact Information
* Email: <a href="mailto:r_neff@southwesterncc.edu">r_neff@southwesterncc.edu</a>
* [LinkedIN](https://www.linkedin.com/in/randi-neff-b7a27823b/)

I have been the Project Coordinator for the Smoky Mountain STEM Collaborative {SMSC} at SCC since 2018. SMSC is part of 
[NASA's SciAct community](https://science.nasa.gov/learn/science-activation-team/). Southwestern is the nation's only 
community college to have a collaborative partnership with NASA which started in 2015. My background is in science education
with experience in the classroom at both the high school and college level. In addition, I have worked as the assistant director
for Western Carolina University's Upward bound Math & Science program. Inspiring young people to answer their own questions and giving
them the tools to do that is my passion.

# My Projects
## Adding a Map - we learned to:
* Define geospatial vector data
* Search for geospatial features
* Construct a map and embed it into a portfolio website

### SMSC is located at Southwestern Community College shown in the map below.
<embed type="text/html" src="img/uttc.html" width="600" height="600">

The land where SCC is located is the ancestral home of the Eastern Band of the Cherokee Indians in the mountains of western North Carolina and 
not far from the Qualla Boundary where the Cherokee People currently reside. Creating an interactive map using Open Street Map was our first assignment.

## Climate Coding Challenge - we learned to:
* Analyze temperature data over time
* Parse date information so that it is represented as a datetime type
* Use operators to convert to different units
* Resample time-series data to different frequencies
  
### Our guided learning focused on Denver Colorado (elevation 5280ft) and then we selected a new location and used data from The Global Historical Climatology Network. Below is a comparison of temperature trends in North Carolina and Denver Colorado.
<img src="img/denver_trendline.png" alt="A graph showing a linear regression of mean annual temperatures in Denver, Co">

### Here is my individual work including the python code showing annual mean temperatures at Coweeta Hydrologic Lab (elevation 2200-3800ft). I chose Coweeta because it is near where I live and work and has been collecting data for a long time. Note that it's hard to compare the two trendlines because one is in degrees Fahrenheit and the other is in degrees Celcisus. However, the slope on both plots show a gradual trend upward. If I weren't trying to finish the rest of the assignments, I might run some additional statistics, but for now I'm thrilled I can share this part of my work especially since hurricane Helene caused the NOAA data center to be offline for a little while.
<embed type="text/html" src="notebooks/nc_climate.html" width="600" height="600">

## Mapping Migration - Species Distribution challenge - we learned to:
* Combine different types of vector data with spatial joins
* Create a chloropleth plot
  
## This Interactive Map of Veery Migration was our guided learning exercise and then we picked another species to try on our own.
<embed type="text/html" src="img/migration.html" width="600" height="600">

The Veery or <i>Catharus fuscescens</i>, is part of the Turdidae family. It is found in the southeastern US during migration and it may be able to anticipate hurricanes in the Atlantic according to a study by Christopher Heckscher. Unfortunately, Atlantic hurricanes tend to coincide with Veery migration and have a negative impact on their breeding season. This is an example of species that is studied in phenology - the impact of a changing climate on the cyclical pattern of an organisms life history.

## Sources:

* Open Street Map "Southwestern Community College - Jackson Campus (601443373), Sept. 2024 [https://www.openstreetmap.org/way/601443373](https://www.openstreetmap.org/way/601443373)
* Heckscher, Christopher M. 2018. “A Nearctic-Neotropical Migratory Songbird’s Nesting Phenology and Clutch Size Are Predictors of Accumulated Cyclone Energy.” Scientific Reports 8 (1): 9899. https://doi.org/10.1038/s41598-018-28302-3.
* GBIF.org (27 October 2024) GBIF Occurrence Download https://doi.org/10.15468/dl.r463v3
* https://nc.audubon.org/news/priority-bird-profile-rose-breasted-grosbeak
