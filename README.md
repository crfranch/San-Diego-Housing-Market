Proposal Summary:
Create a database for San Diego real estate (one table at the address level, the other the zip code level). This database can be utilized for subsequent projects.

Data Sources:
Zillow Current Home Listings (http://www.zillow.com/homes)
Listing Price
Zip Code
Street Number
SQFT
Bedrooms
Bathrooms
Sale Type (New construction, foreclosure, sale)
Property Shark for San Diego County (https://www.propertyshark.com/mason/Street-Index/CA/San-Diego-County/)
Year Built
Parcel ID
Legal Description
Units
Property Class
Acreage
Neighborhood
SQFT
Bedrooms
Bathrooms
JSON txt file from Project 1 (Attom Community API, Zip Code Level)
300+ different variables at the zip code level
(Optional, depending on time) Google Places API 
Distance from search term “beach”

Method:
Use open source code to pull zillow current home listings (https://github.com/ChrisMuir/Zillow)
Pass addresses where we have listing price to Beautiful Soup / Splinter Program to pull info from Property Shark.
Merge Zillow & Property Shark data in Python
Extract API output from txt
Transform data sets as needed
Load into Mongo DB

# San-Diego-Housing-Market
