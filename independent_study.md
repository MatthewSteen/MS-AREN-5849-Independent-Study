# Abstract

https://www.elsevier.com/journals/renewable-and-sustainable-energy-reviews/1364-0321/guide-for-authors

# 1. Introduction

Electrification trend vs. other fuels

How the grid works - supply, demand

How do GEBs fit in to recent trends, needs

# Methods and materials

## Literature review

IN PROGRESS

## Data

Identify data sources to test and use for future analysis.

[Commercial and Residential Hourly Load Profiles for all TMY3 Locations in the United States](https://openei.org/datasets/dataset/commercial-and-residential-hourly-load-profiles-for-all-tmy3-locations-in-the-united-states)

Use [OpenStudio Standards](https://github.com/NREL/openstudio-standards) to generate [DOE Commercial Reference Buildings](https://www.energy.gov/eere/buildings/commercial-reference-buildings).

  * (16) Building Types
  * (3) Templates: pre-1980, 1980-2004, new construction (90.1-yyyy)
  * (15) Climate Zones
  * (720) Total combinations

* [U.S. Department of Energy Commercial Reference Building Models of the National Building Stock](https://www.nrel.gov/docs/fy11osti/46861.pdf)

  * Weighting factors (new construction only) indicate that Small Office is the most common building type across all climate zones. 

Building Types (use most common)

* SecondarySchool
* PrimarySchool
* SmallOffice*
* MediumOffice
* LargeOffice
* SmallHotel
* LargeHotel
* Warehouse
* RetailStandalone
* RetailStripmall
* QuickServiceRestaurant
* FullServiceRestaurant
* MidriseApartment
* HighriseApartment
* Hospital
* Outpatient

Templates (use most common)

* DOE Ref Pre-1980
* DOE Ref 1980-2004
* 90.1-2004
* 90.1-2007
* 189.1-2009 (in development)
* 90.1-2010
* 90.1-2013
* NECB 2011 (canada)

Climate Zones

| Climate Zone | Representative City | Representative Building Type |
| --- | --- | --- |
| 1A | Miami, Florida | 
| 2A | Houston, Texas | 
| 2B | Phoenix, Arizona | 
| 3A | Atlanta, Georgia | 
| 3B-Coast | Los Angeles, California | 
| 3B | Las Vegas, Nevada | 
| 3C | San Francisco, California | 
| 4A | Baltimore, Maryland | 
| 4B | Albuquerque, New Mexico | 
| 4C | Seattle, Washington | 
| 5A | Chicago, Illinois | 
| 5B | Boulder, Colorado | 
| 6A | Minneapolis, Minnesota | 
| 6B | Helena, Montana | 
| 7 | Duluth, Minnesota | 
| 8 | Fairbanks, Alaska | 

Outputs from EnergyPlus

* Output:Meter object(s)
  * Electricity:Facility (total) or break down electric end uses?
```
Output:Meter,
  Electricity:Facility,                   !- Key Name
  Timestep;                               !- Reporting Frequency
```
* timestep = 60 min or 15 min, 8760 or 35040 data points
* Visualization
  * Python dashboard or plotting library

Energy Efficiency Measures

* Write [OpenStudio Measures](https://nrel.github.io/OpenStudio-user-documentation/getting_started/about_measures/) (Ruby script)

Energy Cost

* EnergyPlus DOE Reference Building Models *do* include energy cost
  * OpenStudio DOE Reference Building Models *do not* include energy cost
  * Could inject EnergyPlus energy cost objects into OpenStudio models as solution
* [U.S. Utility Rate Database](https://openei.org/apps/USURDB/)
  * [API Documentation](https://openei.org/services/doc/rest/util_rates/?version=3)
  * Write script to request
* [OpenEI GitHub Repositories](https://github.com/search?q=openei&type=Repositories)
  * Use existing code

Energy Efficiency Measure Cost

* RS Means
  * API
  * Check if CU has license

Renewable Energy Cost

* PV installed $/kW
  * https://openpv.nrel.gov/
    * https://emp.lbl.gov/tracking-the-sun/
* Calculate PV kW for ZNE (electricity) using location-based kWh/kW?

# Results

Categorize measures and technologies that are suitable for GEBs.

# Discussion

TODO

# Conclusions

TODO