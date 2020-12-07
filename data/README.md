## COGS 108 Individual Project Datasets 

Below are a number of datasets about San Diego Parks & Recreation
- You are NOT expected to use all of these, but are expected to use data from at least one in your final project
- You ARE allowed (but are not required nor expected) to use outside datasets, if you want

#### SD Parks & Recreation Location Data

- Park Locations Data
	- Source: https://data.sandiego.gov/datasets/park-locations/
	- Files Included:
		- Dataset (geojson): `parks_datasd.geojson`
		- Dictionary: `parks_dictionary_datasd.csv`

- Rec Center Locations Data
	- Source: https://data.sandiego.gov/datasets/recreation-center-locations/
	- Files Included
		- Dataset (geojson): `rec_centers_datasd.geojson`
		- Dictionary: unavailable

- Joint Use Parks Data
	- Source: https://data.sandiego.gov/datasets/joint-use/
	- Files Included: 
		- Dataset (geojson): `joint_use_datasd.geojson`
		- Dictionary: `joint_use_dictionary_datasd.csv`

#### San Diego Parks Yelp Data			
- Yelp Data for San Diego Parks
	- Source: https://www.yelp.com/ (Prof Ellis curated these data for you)
	- Files Included:
		- Dataset (CSV, Park Information): `yelp_SD_parks.csv`
		- Dataset (CSV, Reviews): `yelp_SD_reviews.csv`
		- Documentation (APIs used to collect data shared above):
			- Reviews: https://www.yelp.com/developers/documentation/v3/business_reviews
			- Park Information: https://www.yelp.com/developers/documentation/v3/business_search
			- Note: I've included some but not all fields, but for fields included, the variable (column) name corresponds to what you see in the documentation links included. In reviews dataset, `text` is the text from the review on Yelp.

#### CA Access to Parks Data
- California Park, Beach, Open Space, or Coastline Access:
	- Source:  https://data.ca.gov/dataset/park-beach-open-space-or-coastline-access
	- Files Included:
		- Dataset (XLSX): `hci_accesstoparks_469_ca_re_co_cd_pl_ct-7-3-2017-ada.xlsx`
		- Data Dictionary (XLSX): `hciaccesstoparks-data-dictionary.xlsx` 
	
#### San Diego Budget Data
- Source: https://data.sandiego.gov/datasets/operating-actuals/
- Files Included: 
	- Dataset (CSV): `actuals_operating_datasd.csv`
	- Dictionary: `operating_actuals_dictionary_datasd.csv`	
		
#### San Diego Crime Data
- Source: https://data.sandiego.gov/datasets/police-calls-for-service/
- Files Included: 
	- Dataset (CSV, 2019): `pd_calls_for_service_2019_datasd.csv`
	- Dataset (CSV, 2020): `pd_calls_for_service_2020_datasd.csv`
	- Dictionary: `pd_calls_for_service_dictionary_datasd.csv`
			- See data dictionary for links to additional datasets you may need to understand the data in the datasets provided
			
#### California Environmental Health Screening Data
- Source: https://data.ca.gov/dataset/calenviroscreen-2-0
- Files Included:
	- Dataset (CSV): `calenviroscreen-final-report.csv`
	- Dictionary (XLSX): `cal-enviro-screen-data-dictionary.xlsx`

		
Possible other helpful resources/sources of data:
- [SANDAG Data Surfer](https://datasurfer.sandag.org/) - population of SD information
- [California Open Data Portal](https://data.ca.gov/) 
- [`geopandas`](https://geopandas.org/io.html) - for working with geojson data
