# Linear Regression of Queens (NYC) real estate data


## Important files

1. [Queens_Housing](https://github.com/gjj425/Metis_Project_2_Submission/blob/main/Queens_housing.ipynb) - contains regression information
2. [DE CLEANING FINAL](https://github.com/gjj425/Metis_Project_2_Submission/blob/main/DE_CLEAN_FINAL.ipynb) contains Douglas Elliman address cleaning, used to link PLUTO information (location data) from NYC Open Data
3. [PLUTO_clean](https://github.com/gjj425/Metis_Project_2_Submission/blob/main/pluto_clean.ipynb) - used to clean PLUTO address information to match DE
4. [Station Work](https://github.com/gjj425/Metis_Project_2_Submission/blob/main/Station_work.ipynb) - merges station information pulled from MTA website and wikipedia to larger model
5. [Presentation](https://github.com/gjj425/Metis_Project_2_Submission/blob/main/Project_2_Presentation.pdf)

## Description
Seeking a regression used to predict pricing for real estate properties in Queens

## Target Variable
Listed Price (Douglas Elliman)

## Features
URL, Property Type, Address, Neighborhood, Zip Code, Broker’s Description, Bedrooms, Bathrooms, House Sq. Ft., Property Sq. Ft., Year Built, Patio, Pool, Air Conditioning, Garage, Water View, New Construction, Stucco Siding, Brick Siding, Pre-War, Courtyard, Miles Away from Penn Station, Wood Heat, Garde, Pets Allowed, Stone Siding, Private Storage, Terrace, Aluminum Siding, Cedar Siding, Wooded Area, Wood Siding, Vinyl Siding 

## Data Used
NYC Open Data, Douglas Elliman (Web Scraped), MTA website, MTA Wikipedia (to get neighborhood/borough for each LIRR station)

## Tools Used
Pandas, Numpy, BeautifulSoup, sklearn, statsmodels, Seaborn

## Possible Impacts
I was looking for a regression that would allow for proper pricing of single family homes in Queens. This could be used to help analyze properties for a potential real estate investment, or to assist brokerages in pricing their client's houses appropriately.
