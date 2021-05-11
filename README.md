# Human-Impacts-on-Fire-Instances
Final Project, Tyler Bull to investigate how population density affect fire instances.
Final Project,Tyler Bull
tybull74@gmail.com


b. Links to the data datasources: 
1.	https://earthdata.nasa.gov/earth-observation-data/near-real-time/firms/viirs-i-band-active-fire-data
2.	https://databank.worldbank.org/reports.aspx?source=2&series=SP.POP.TOTL&country=AFG
3.	https://www.countries-ofthe-world.com/largest-countries.html

Abstract – 
This project has sought to analyze the relationships between instances of active fire events and how population density and changes in population of various countries around the world affect the quantity of active fire incidences as recorded in the NASA VIIRS I-Band 375 m Active Fire Data [1]. It was hypothesized at the onset of the project that human population would increase fire instances due to human activities. Using Python Numpy and Cartopy modules to analyze and visualize the data revealed correlations and regressions within this data when compared with the human population over the time range under consideration (2003-2019). From this analysis it was found that increasing population density tends to have a negative relationship with active fire instances across the world. The shape of this relationship was not found to be clear enough from the data to determine the non-linear regression, however a linear and quadratic relationship were attempted on the worldwide dataset. 

Hypothesis:
That population density changes will affect the quantity of the fires detected in the data. It is expected that human activity will be found to be positively the quantites of fires. 

Notable use of Modules:
Cartopy
Numpy
Matplotlib

Code Capabilities:
The code iscapable of reading the fire data from the datasource 1 above and selecting countries and their data based upon the population rate of change conditions analyzed from datasource 2 above. The code will then be capable of interpreting the fire data of the select countries to determine the quantity, and tions of fires in the country of interest across the years of data. Further capabilities of the code include looping through a list of countries to evaluate any number of analyses of the datasets, and demonstrating this capability by performing regressional analyses on all of the datasets. 

All other details of the function and operation of the code can be found in the notes within the code. 



