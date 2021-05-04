README FILE
Final Project Interim 1, Tyler Bull


Checklist of items for Interim 1

a. Github Repository Name: Human-Impacts-on-Fire-Instances

b. Links to the fire data datasources: 
1.	https://earthdata.nasa.gov/earth-observation-data/near-real-time/firms/viirs-i-band-active-fire-data
2.	https://databank.worldbank.org/reports.aspx?source=2&series=SP.POP.TOTL&country=AFG
3.	https://www.countries-ofthe-world.com/largest-countries.html

c. 

Project Statement:
By selecting discrete years 2000, 2005, 2010, 2015, and 2019 – this analysis will aim to determine the presence of a relationship between population density (population/landmass) of various countries and the quantities of fires in these countries. To accomplish this, I will select the 5 developed countries with the highest population density gradient across the range 2000-2019 and 5 with the lowest population density gradient over the period as a control group. This analysis will target the frequency and quantity of fires in the countries over this period (Fourier and Means analysis) and develop correlational and regression models and analysis for the relationship between population density and fire instances (Correlation, regression).

Code Capabilities:
The code will be capable of reading the fire data from the datasource 1 above and selecting countries and their data based upon the population rate of change conditions analyzed from datasource 2 above. The code will then be capable of interpreting the fire data of the select countries to determine the quantity, locations and durations of fires in the country of interest across the years of data. 

Hypothesis:
That population density changes will affect the quantity and durations of the fires detected in the data.

Expected results:
Visualizations of the data regressions, both traditional regression plots as well as mapped plots with fires indicated in time to visually display the changes over years. 

d. The data is loaded and formatted in sections 1.2,1.3, and 3.1 of the FinalProject.ipynb with comments. 

2. All of the fire data is imported to pandas dataframes for analysis in the sections described in (d). 

3. The datasets are analyzed for size and shape, along with plots of their sizes in section  3.2 of the code. 

4. I intend to use the Basemap module to develop geographic plot of the data, but my python started having a lot of issues when importing basemap. I originally intended to use metpy for this, but I do not think Metpy is the right module for this task. I am open to advice on the best modules to use to generate mapped data. 

5.  Hypothesis:
That population density changes will affect the quantity and durations of the fires detected in the data.
