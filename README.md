# Transport Data Sources

## Introduction & Notes

A repo for us to log and share all of our good data sources relating to Transport. This isn't intended to be a complete and exhaustive list of datasets or the variables contained within them, but instead a rough and ready guide to aid people working in transport data in their search for appropriate data. This collection has a UK focus but interesting non-UK datasets may also be included.

This repo is the sister of our [Data Science Learning Resources Repo](https://github.com/departmentfortransport/ds-learning-resources) so feel free to check that out also.

This is intended to be open source! Feel free to [contribute to it](https://akrabat.com/the-beginners-guide-to-contributing-to-a-github-project/) with your own data or data you know of.

### Rules & Conventions for updating:

1. Only include datasets, not statistics, reports, visualisations etc.
2. Only include datasets that might be of interest to people working in transport.
3. Include a source. 
4. Include details of the key variables within each dataset. This helps with searching.
5. Include dates / backseries availability wherever possible.
6. Include the format of the data (e.g. xlsx, csv, API etc.).
7. If the data is in API format also include the API reference, registration, guides, tutorials or links to helpful packages / sample code.
8. Indicate if the dataset(s) is a one-off, discontinued or no longer kept up to date.
9. If the data isn't free or requires a subscription / payment at some point, indicate this in the link.
10. If possibile indicate what region the data is for (e.g. UK, England, London, West Midlands etc.) etc. In future it may be necessary to split the data by national and regional level data.

## General Data Sources

* [NOMIS Labour Force Query Tool](https://www.nomisweb.co.uk/query/select/getdatasetbytheme.asp?opt=3&theme=&subgrp=) ONS ran site focused on official labour market data that lets you build customized queries on a range of datasets including Census (1981-2011), Benefits (from 1999), Population (from 1981), Employment (from 1981), Businesses (from 2010), Earnings (from 1997) and allows you to download these in .csv format.

## Geographic Data Sources

* [Doogal](https://www.doogal.co.uk/) Private but well maintained and updated website with a wealth of geographic data including addresses, postcodes, administrative areas, counties as well as useful map tools including lat/lon finder, distances, elevation and more in .csv format. Much of the data appears to be sourced from ONS and other official government sources.

## GIS Data Sources

## Transport Data Sources

### Road

* [DfT GB Road Traffic Counts (2000 - date)](https://www.dft.gov.uk/traffic-counts/download.php) Traffic count datasets produced by the DfT for the level of traffic on various roads in Great Britain in .csv format.

* [DfT GB Road Safety Data (1979 - date)](https://data.gov.uk/dataset/cb7ae6f0-4be6-4935-9277-47e5ce24a11f/road-safety-data) Road Safety datasets in .csv format about the circumstances of personal injury road accidents in GB the types (including Make and Model) of vehicles involved and the consequential casualties. The statistics relate only to personal injury accidents on public roads that are reported to the police, and subsequently recorded, using the STATS19 accident reporting form.

* [DfT MOT Test Results (2005 - date)](https://data.gov.uk/dataset/e3939ef8-30c7-4ca8-9c7c-ad9475cc9b2f/anonymised-mot-tests-and-results) MOT test outcome dataset produced by the DfT for the UK (I think?). Contains all MOT tests and outcomes, including make and model of vehicle, odometer reading and reasons for failure, since the MOT system was computerised in 2005. Data is in .txt pipe delimiter format.

* [DfT GB Driving Licences (2012 - date)](https://data.gov.uk/dataset/d0be1ed2-9907-4ec4-b552-c048f6aec16a/gb-driving-licence-data) Datasets containing current driving licences issued by the Driver and Vehicle Licensing Agency (DVLA) and published but the DfT. The DVLA is responsible for issuing driving licences in Great Britain (GB). Driving licences issued in Northern Ireland are the responsibility of the Northern Ireland Driver & Vehicle Agency and are outside the scope of this release.

* [Petrol & Diesel Prices (2009 - date)](https://data.gov.uk/dataset/c174a981-b0f2-4b39-adc0-1d0a27a7d8c9/petrol-and-diesel-prices) Weekly updated ataset produced by BEIS, showing petrol & diesel prices.

* [Highways England TRIS (2006 - Date)](http://tris.highwaysengland.co.uk/) Traffic flow and journey time data for the English trunk road network in .csv format.

* [Highways England WebTRIS (2006 - Date)](http://webtris.highwaysengland.co.uk/api/swagger/ui/index)  API for the TRIS traffic flow and journey time data for the English trunk road network. The API is well documented, uder friendly and doesn't require signup, authentication or payment.

### Rail

* [ORR Station Usage Stats (1997 - date)](http://orr.gov.uk/statistics/published-stats/station-usage-estimates) Train station usage dataset in xlsx format compiled by the Office of Rail and Road (ORR) for 1997 - date. Contains data on entries, exits broken down by type as well as geographic data about the station itself as well as the tlc and nlc station identifiers to help with merging to other data. 

* [Doogal Station Usage Stats (1997 - date)](https://www.doogal.co.uk/UkStations.php) Train station usage dataset based upon the ORR Station usage dataset but more succinct and extra area level data (e.g. Rural / Urban classification) and a full timeseries.

* [National Rail Enquiries Data Feeds (API)](http://www.nationalrail.co.uk/46391.aspx) Three separate datafeeds for National Rail data including Darwin (Realtime train running data), Knowledgebase (including data on station facilities, service disruption, and engineering work) and Online Journey Planner (engine used to plan routes, calculate fares and establish ticket availability). Note that Darwin is a SOAP API, but [Huxley](https://github.com/jpsingleton/Huxley), allows easier access to this data. NRE don't provide much documentation however there is information available at the [Open Rail Data Wiki ](https://wiki.openraildata.com/index.php/Main_Page).

* [AppyParking (API)](https://appyparking.com/develop/) APIs for on-street and off-street parking locations and petrol station prices and locations. The parking APIs appear to be free but the petrol station API appears to require a subscription.

### Bus

* [Traveline National Dataset (TNDS)](https://www.travelinedata.org.uk/traveline-open-data/traveline-national-dataset/) Public transport timetables for bus, light rail, tram and ferry services in Great Britain. Data is provided in [TransXChange](https://www.gov.uk/government/collections/transxchange) XML format. Data can be converted to [GTFS](https://en.wikipedia.org/wiki/General_Transit_Feed_Specification) with various tools, including [TransXChange2GTFS](https://github.com/danbillingsley/TransXChange2GTFS).


### Maritime


### Aviation


### Miscellaneous



## Transport Modelling Data Sources

To include: Webtag
