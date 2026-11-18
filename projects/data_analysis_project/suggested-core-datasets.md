# Suggested Core Datasets

This list is a starting point for choosing a core dataset. It includes public data on government, the environment, transportation, health, education, culture, food, and recreation. Some options are easier to work with than others. Before choosing, check the current source, documentation, scope, update schedule, and terms of use. A public dataset is not automatically complete, representative, or suitable for every question. Links and descriptions were reviewed in November 2026.

You may propose another sufficiently rich dataset for approval. Every project must also use at least one relevant supplementary dataset, as described in the [project instructions](README.md#datasets).

## Maryland and local government

| Dataset | Possible questions and notes |
|---|---|
| [Maryland Notices of Intent to Foreclose](https://opendata.maryland.gov/Housing/Maryland-Notices-of-Intent-to-Foreclose-by-Zip-Cod/ftsr-vapt) | Compare monthly patterns across ZIP codes or census tracts and investigate how they relate to housing or economic conditions. These notices are not court foreclosure case records. County-level data are also available from the [Maryland foreclosure tracker](https://opendata.maryland.gov/Housing/Maryland-Foreclosure-Notice-Data-by-County/w3bc-8mnv). |
| [Maryland State Payments Data](https://opendata.maryland.gov/Budget/State-of-Maryland-Payments-Data-FY2008-to-FY2024/7syw-q4cy) | Examine state payments by agency, vendor, purpose, or time period. Transaction-level data can be large. Distinguish payments from budgets, contracts, or total program costs, and check the portal for the latest available years. |
| [Maryland public school enrollment trends, 2014–2024](https://opendata.maryland.gov/Education/Maryland-Public-School-Enrollment-Trends-Kindergar/9ju3-j8k6) | Examine enrollment changes across school systems or grade bands. The data are summarized by jurisdiction and grade band; school-level questions require a school-level source with compatible definitions. |
| [Maryland reported sewer overflows](https://opendata.maryland.gov/Government/Reported-Sewer-Overflows-New-for-2023-/stgj-u72u) | Investigate where and when reported overflows occur and which waterways or communities may be affected. The reporting system changed in 2023, so do not assume older records are directly comparable. |
| [Maryland Department of the Environment air complaints](https://opendata.maryland.gov/Energy-and-Environment/Maryland-Department-of-the-Environment-MDE-Air-and/crti-ybyp) | Look for patterns in complaint types, locations, and agency responses. Complaints are reports of concern, not necessarily confirmed violations or a complete measure of pollution. |
| [Maryland real property assessments](https://opendata.maryland.gov/Business-and-Economy/Maryland-Real-Property-Assessments_Hidden-Property/ed4q-f8tm) | Study assessed values, property characteristics, or geographic patterns in the housing market. The statewide parcel data are very large and require careful reading of field definitions and likely a substantial subset. |
| [Montgomery County food inspections, July 2024 onward](https://data.montgomerycountymd.gov/d/dkrp-gr48) | Explore inspection activity, results, facility types, and geography. Check the dataset's date coverage and inspection definitions; a recorded inspection result is not a complete measure of a restaurant's overall safety. |

## National policy, economy, environment, and health

| Dataset | Possible questions and notes |
|---|---|
| [Federal Election Commission campaign finance data](https://www.fec.gov/data/browse-data/) | Investigate campaign receipts, spending, committees, or independent expenditures for a selected race or election cycle. Bulk transaction files can be very large; select a manageable committee, period, or transaction category and use the file layouts and codes. |
| [USAspending.gov awards data](https://www.usaspending.gov/) | Examine federal contracts, grants, loans, recipients, agencies, or spending in a selected place or program. Define whether you are analyzing award amounts, obligations, or outlays, and consult the data dictionary. |
| [Consumer Financial Protection Bureau Consumer Complaint Database](https://www.consumerfinance.gov/data-research/consumer-complaints/) | Examine complaint counts and company responses for selected financial products, issues, companies, or time periods. Counts reflect submitted complaints and are not representative of all customers' experiences. The CFPB announced in August 2026 that it would stop publishing complaint narratives and visualizations, so check which fields remain available before choosing a question. |
| [Fatality Analysis Reporting System (FARS)](https://www.nhtsa.gov/research-data/fatality-analysis-reporting-system-fars) | Analyze fatal traffic crashes by location, roadway, vehicle, person, or year. FARS is a multi-table system; start with a state or time-period subset and learn how crash, vehicle, and person records relate. It covers fatal crashes, not all crashes. |
| [EPA Toxics Release Inventory (TRI)](https://www.epa.gov/toxics-release-inventory-tri-program/tri-basic-plus-data-files-calendar-years-1987-present) | Examine facility-reported toxic chemical releases, transfers, or waste management over time. Read EPA documentation carefully and be precise about which facilities report and what each measure represents. |
| [EPA Greenhouse Gas Reporting Program](https://www.epa.gov/ghgreporting/data-sets) | Compare reported greenhouse gas emissions by facility, industry, location, or year. The program covers specified large emitters and other regulated entities, not all emission sources. Check current data availability and reporting rules. |
| [FCC National Broadband Map data](https://broadbandmap.fcc.gov/data-download/nationwide-data) | Examine reported broadband availability by provider, technology, speed, or location. Nationwide files can be large. Availability is not the same as subscription or actual service quality; consider a local subset and review the FCC definitions. |
| [CDC PLACES](https://www.cdc.gov/places/tools/data-portal.html) | Compare local estimates for health outcomes and risk factors across counties, places, census tracts, or ZIP Code Tabulation Areas. These are modeled estimates, not direct counts for each small area; avoid treating small differences as precise rankings. |
| [NOAA Storm Events Database](https://www.ncei.noaa.gov/access/storm-events-database/) | Investigate significant storms and other weather events by type, date, location, damage, or reported impacts. The database has defined inclusion criteria and reporting practices; reported impacts and damage estimates are not a complete census of every weather event. |
| [USDA FoodData Central](https://fdc.nal.usda.gov/download-datasets/) | Compare nutrients and ingredients across foods or branded products. The downloads combine several data types with different purposes and sources, so select a specific data type and read its field documentation. |

## Transportation, travel, and public space

| Dataset | Possible questions and notes |
|---|---|
| [Bureau of Transportation Statistics airline on-time performance](https://www.transtats.bts.gov/ontime/) | Compare flight delays, cancellations, routes, carriers, or airports. Use a specific time period or set of airports; the data cover reporting carriers and need context such as weather, schedule, and airport conditions. |
| [Capital Bikeshare trip history](https://capitalbikeshare.com/system-data) | Explore when, where, and how different types of riders use the bike-share system. Monthly files can be large. Trip records describe system use, not all cycling or travel in the region; read the data license and processing notes. |
| [National Park Service visitor use statistics](https://irma.nps.gov/Stats/) | Compare visitation across parks, seasons, or years. The NPS provides monthly estimates for many park units; park counting procedures and visitor-use measures may differ, and some figures are preliminary. |
| [NYC 311 service requests](https://data.cityofnewyork.us/Social-Services/311-Service-Requests/erm2-nwe9) | Explore patterns in service requests, response times, complaint types, or geography. The data are very large and now split across periods; use a focused subset. Requests measure reports made to the city, not necessarily the prevalence of the underlying problem. |

## Culture, recreation, and lighter topics

| Dataset | Possible questions and notes |
|---|---|
| [BoardGameGeek board-game data](https://www.kaggle.com/datasets/andrewmvd/board-games) | Explore relationships among game characteristics, complexity, and user ratings. This static third-party dataset was collected in 2021; it is not current, and its ratings are not a representative survey of players. |
| [MovieLens 25M ratings](https://grouplens.org/datasets/movielens/25m/) | Explore how user ratings vary by genre, release year, or other characteristics, or investigate patterns in tags. Ratings come from MovieLens users and are not representative of all movie viewers. Review the dataset README and terms before use. |
| [Art Institute of Chicago collection API](https://api.artic.edu/docs/) | Analyze collection metadata, such as medium, date, artist, or geography, using a filtered API query. The full data dump is large; work with a purposeful subset. Verify the rights information for any images or records you reproduce. |
| [Smithsonian Open Access collections](https://www.si.edu/openaccess/devtools) | Explore collection metadata across Smithsonian museums and research centers, including topics, dates, locations, or departments. The collection is broad and heterogeneous; narrow the scope and distinguish open-access records from records with other use restrictions. |
| [NCAA women's college basketball rosters](https://github.com/Sports-Roster-Data/womens-college-basketball) | Study roster composition, geography, or changes across seasons. This is a third-party collection; review its documentation, collection methods, and coverage. |
| [NCAA college soccer rosters](https://github.com/Sports-Roster-Data/soccer) | Study roster composition, geography, or differences among programs and divisions. This third-party project collects information from team websites; review its methods and coverage. |

## Choosing a scope

Before proposing a dataset, identify a specific question and check that the data contain the fields, time period, and geography needed to investigate it. A practical project often focuses on one place, subject, population, or time range rather than downloading an entire national database.

The [American Community Survey (ACS)](https://www.census.gov/programs-surveys/acs/data.html) and [Census geographic boundary files](https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html) are often useful as supplementary sources. They can provide denominators, demographic or economic context, and geographic boundaries. Match geographies and years carefully, explain limitations, and do not treat correlation or geographic overlap as proof of causation.
