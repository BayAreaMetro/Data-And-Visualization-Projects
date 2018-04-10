### Description

This is a collection of links to projects to extract, transform, and load data. 

### Category

[General](#general)  
[Transportation](#transportation)   
[Policy](#Policy)  
[Demographic](#demographic)  

#### General

#### Transportation:

##### Transit 


##### Sub-Projects  
- [State of California Code Transit Service Definition Areas](legislative_transit_data.md) 
- [Routes, Stops, and Frequencies by Transit Provider from 2008 to 2017](historical_transit_data.md) 

##### Vehicles

[Traffic](https://github.com/MetropolitanTransportationCommission/vital-signs-traffic-data)     
Source: INRIX, TomTom     
Input: Excel Spreadsheets of Traffic Data, Road Geometries     
Output: Traffic by Geometry      
Dependencies: Python, Pandas  

###### [bridge-transactions](bridge-transactions/)    
Source: BATA  
Input: Transactions    
Output: Various Summaries  
Dependencies: R, Python, Tableau  

#### Policy:  

[Housing Permit Geocoding (2017)](https://github.com/BayAreaMetro/Data-And-Visualization-Projects/blob/master/housing_geocoding/readme.md)  
Source: Various   
Input: Housing Permits   
Output: Geocoded Housing Permits   
Dependencies: Windows 10, SQL Server Spatial, Python, Pandas

[Zoning & General Plans(GP)](https://github.com/MetropolitanTransportationCommission/zoning)   
Source: Jurisdictions   
Input: Zoning/GP, Parcel Geometry   
Output: Zoning by Parcel Geometry   
Dependencies: *nix, PostGIS, GDAL, Make

[Parcels (2010,2015)](https://github.com/BayAreaMetro/Data-And-Visualization-Projects/tree/master/postgis-parcels)   
Source: County Governments   
Input: Edited PGDump from @msmithMTC's parcl schema on GISDB3   
Output: Docker machine running PostGIS with parcels by county    
Dependencies: Docker, Ubuntu, PostGIS

[Affordable Housing Locations (2016)](https://github.com/MetropolitanTransportationCommission/housing/)   
Input: Multiple Spreadsheets  
Output: Records Deduplicated and Located by Address  
Dependencies: Python, Pandas, R  

[Residential Real Estate Prices](https://github.com/MetropolitanTransportationCommission/motm/tree/master/2017_04#redfinplaces)    
Source: Redfin    
Input: Census Places Geometries (TomTom), CSV Export of [Tableau Data file](https://www.redfin.com/blog/data-center)    
Output: Residential Sale Prices by Place Geometry      
Dependencies: Python, Pandas

