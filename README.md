# ETL-Project

## Project Proposal

### Extract

For this project, we will extract data from Realtor API and OpenWeatherMap API. This data is intended to analyze the correlation of weather on property value. 

### Transform

For transformation, we will target the matching location data in each dataset, and the minimum and maximum and average temperature per zip code. For the real estate data, we will focus only on location data, the square feet of the house, and the house price. We will only be looking at homes for sale as this data is intended to be used for someone looking to invest in real estate. 

### Load

For loading, we plan to use a mongo DB database so we can store JSON, as that is the common output format of our APIs. We will use one table that will have information

