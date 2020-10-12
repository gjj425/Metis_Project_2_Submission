# Metis_Project_2_Submission
Submission github for Project 2: Linear Regression of Queens (NYC) real estate data


**Important files:**

Queens_Housing - contains regression information
DE Final Code Run 2 - contains web scraping from Douglas Elliman

DE CLEANING FINAL: contains Douglas Elliman address cleaning, used to link PLUTO information (location data) from NYC Open Data

PLUTO_clean: used to clean PLUTO address information to match DE

Station Work: merges station information pulled from MTA website and wikipedia to larger model



**Description:** Seeking a regression used to predict pricing for real estate properties in Queens

**Target Variable:** Listed Price (Douglas Elliman)

**Features:** URL, Property Type, Address, Neighborhood, Zip Code, Broker’s Description, Bedrooms, Bathrooms, House Sq. Ft., Property Sq. Ft., Year Built, Patio, Pool, Air Conditioning, Garage, Water View, New Construction, Stucco Siding, Brick Siding, Pre-War, Courtyard, Miles Away from Penn Station, Wood Heat, Garde, Pets Allowed, Stone Siding, Private Storage, Terrace, Aluminum Siding, Cedar Siding, Wooded Area, Wood Siding, Vinyl Siding 

**Data Used:** NYC Open Data, Douglas Elliman (Web Scraped), MTA website, MTA Wikipedia (to get neighborhood/borough for each LIRR station)

**Tools Used**: Pandas, Numpy, BeautifulSoup, sklearn, statsmodels, Seaborn

**Possible Impacts**: I was looking for a regression that would allow for proper pricing of single family homes in Queens. This could be used to help analyze properties for a potential real estate investment, or to assist brokerages in pricing their client's houses appropriately.
