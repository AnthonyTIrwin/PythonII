# Python II Project - Metro Service Utilization and Weather Conditions

#### Is there a relationship to calls to Louisville Metro Services and weather conditions? This is a simple jupyter notebook that explores weather conditions, specifically temperature, has any bearing on any calls made to the city of Louisville, Kentucky for city services related to issues like building code violations, abandoned cars, unkept yards. If such a corrleation can be detected, this may pave way for city planners to predict in advance the likelihood of certain types of service calls and possibly implement preventative measures which would lower service demand and more efficently utilize city resources.
#### Louisville Metro services data has been aquired from a city ran website and the most complete dataset has been chosen, which is from 2011. The dataset contains a history of service calls to Louisville, and each entry contains data regarding location and type of service, time and date, and whether or not the service request was complete. any correlation to the maximum temperature recorded that day. Factors that were considered where the frequency of calls made in a given district, looking in that district for the type of call, and determining whether it would have


The files come from:
- City of Louisville Open Data - https://data.louisvilleky.gov/ 
- NASA - https://power.larc.nasa.gov/downloads/POWER_Regional_Daily_20110101_20111231_b287c874.csv
- OpenStreetMap - https://openstreetmap.org

# **To Run:**

### Clone github repositry : 
- https://github.com/AnthonyTIrwin/PythonII.git
### Ensure that you have the juypter notebook installed, if not please get it here: 
- https://www.anaconda.com/products/individual
### Ensure that the following files are in the same directory:

- Weather_and_Demand_for_Municipal_Services.ipynb
- citizen311data_2011_0.csv
- lou_map.png
- 2011_TempData.csv

Launch jupyter notebook and then open the file **"Weather_and_Demand_for_Municipal_Services.ipynb"**.  The project file should then be ready to view. 

# **Conclusion**

Attention was placed on Metro District 5, which was the district with the most service calls.  In Metro District 5 the most common request was in regards to a property ownder not maintaining the lawn.   There was a weak to nonexistent correlation (P = .038) between the maximum daily temperature and the frequency of calls made to Louiville Metro Services, so the answer is inconclusive.  Although there isn't a strong correlation, other factors should be considered for future analysis, like comparison between districts, and over the course of several years. 
