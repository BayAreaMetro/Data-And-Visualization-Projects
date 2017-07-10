## Data Workflows

### Purpose

A list of script repositories used to transform data (mostly spatial).**

[Transportation](#transportation)   
[Land](#land)  
[Demographics](#demographics)  

#### Transportation:

[Transit](https://github.com/MetropolitanTransportationCommission/RegionalTransitDatabase)   
Source: Transit Operators    
Input: [Google Transit Feed Specification](https://developers.google.com/transit/gtfs/) Text Files    
Output: Multiple, Bus Frequency by Geometry    

[Traffic](https://github.com/MetropolitanTransportationCommission/vital-signs-traffic-data)     
Source: INRIX, TomTom     
Input: Excel Spreadsheets of Traffic Data, Road Geometries     
Output: Traffic by Geometry      

[CEQA Streamlining Estimates](https://github.com/MetropolitanTransportationCommission/tpp_ceqa_map_for_pba_17)   
Source: Multiple
Inputs: Transit Priority Areas, Various Land Use Data  
Outputs: Estimates of areas where [CEQA](https://en.wikipedia.org/wiki/Sustainable_Communities_and_Climate_Protection_Act_of_2008) streamlining are likely/possible.  

#### Land:  

[Zoning & General Plans(GP)](https://github.com/MetropolitanTransportationCommission/zoning)   
Source: Jurisdictions   
Input: Zoning/GP, Parcel Geometry   
Output: Zoning by Parcel Geometry   

[Parcels](https://github.com/MetropolitanTransportationCommission/bayarea_urbansim/blob/c3b249c54e8bae14737c6840dc8ff70a858a887f/data_regeneration/Makefile)   
Source: County Governments   
Input: 9 Tables of Parcel Geometries by County   
Output: 1 Table of Parcel Geometries by Region   

[Housing](https://github.com/MetropolitanTransportationCommission/housing/tree/master/ahs)   
Source: American Housing Survey - Census   
Input: Flat Text Files from Census   
Output: A SQLite Database of AHS statistics   

[Residential Real Estate Prices](https://github.com/MetropolitanTransportationCommission/motm/tree/master/2017_04#redfinplaces)    
Source: Redfin    
Input: Census Places Geometries (TomTom), CSV Export of [Tableau Data file](https://www.redfin.com/blog/data-center)    
Output: Residential Sale Prices by Place Geometry      

#### Demographic

[School Quality](https://github.com/MetropolitanTransportationCommission/motm/tree/master/2017_04#stanford-schools-project)   
Source: Stanford   
Input: School Quality,    
Output: School Quality Scores by School District Geometry   

[Climate Change Opinion Survey](https://github.com/MetropolitanTransportationCommission/motm/tree/7848b8404605b0dc64b5f29516dca7da0e9c1e68/2017_07#data-sources)
Source: Yale School of Forestry    
Input: Climate Change Opinions (csv), Census Counties (2015)     
Output: Climate Change opinions by Census Tract     

**where year is not specifically mentioned, the tool is intended (though not necessarily tested on) any year for which data are available.   

#### Need Documentation Improvements:   

[Demographics (Environmental Justice)](https://github.com/MetropolitanTransportationCommission/ej)   
Source: US Census   
Input: JSON retrieved from the US Census   
Output: Census Tracts Geometries & Demographics for 2000, 2010, and Change in Population of communities of Veterans, various Minorities, Disabled, Low Income, Over 65, and more.    

[Environmental Impacts](https://github.com/MetropolitanTransportationCommission/UrbanSim_Spatial_Analysis)   
Source: [Multiple](https://app.smartsheet.com/b/home?lx=kxHiygtZYYFSoNxKdR-2Ww&mt=21)   
Inputs: [Multiple](https://app.smartsheet.com/b/home?lx=kxHiygtZYYFSoNxKdR-2Ww&mt=21)   
Outputs: Tables on Environment Impacts of Transportation Projects and Land Use Forecasts by State, County, and Impact Type   

