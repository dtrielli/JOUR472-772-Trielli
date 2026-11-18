# Suggested Core Datasets

This menu focuses on Maryland, Washington, D.C., and the broader DMV, along with federal datasets that can be narrowed to the region. It includes four options in each category. Check each source's documentation, current coverage, and terms before choosing. Every project must also use at least one relevant supplementary dataset; see the [project instructions](data_analysis_project_intro.md#datasets).

## Maryland and local communities

| Dataset | Potential reporting directions | Source and considerations |
|---|---|---|
| [Maryland foreclosure notices by census tract](https://opendata.maryland.gov/Housing/Maryland-Notices-of-Intent-to-Foreclose-by-Census-/nme2-wik5) | Compare notice patterns across communities and time. | Notices are not court foreclosure case records. Review the definitions and limits. |
| [Maryland State Payments Data](https://opendata.maryland.gov/Budget/State-of-Maryland-Payments-Data-FY2008-to-FY2024/7syw-q4cy) | Examine payments by agency, vendor, purpose, or time. | Distinguish payments from budgets and contracts; check the portal for current years. |
| [Maryland public school enrollment trends](https://opendata.maryland.gov/Education/Maryland-Public-School-Enrollment-Trends-Kindergar/9ju3-j8k6) | Compare enrollment by jurisdiction and grade band from 2014 to 2024. | The data are summarized by jurisdiction and grade band, not individual school. |
| [Montgomery County food inspections, July 2024 onward](https://data.montgomerycountymd.gov/d/dkrp-gr48) | Explore inspection types, results, facility types, or location. | Read the inspection definitions; results are not a complete measure of a restaurant's overall safety. |

## Environment and public health

| Dataset | Potential reporting directions | Source and considerations |
|---|---|---|
| [Maryland reported sewer overflows](https://opendata.maryland.gov/Government/Reported-Sewer-Overflows-New-for-2023-/stgj-u72u) | Examine reported events by location, time, and overflow type. | The reporting system changed in 2023, so do not assume older records are directly comparable. |
| [Maryland Department of the Environment air complaints](https://opendata.maryland.gov/Energy-and-Environment/Maryland-Department-of-the-Environment-MDE-Air-and/crti-ybyp) | Look for patterns in complaint type, location, and response. | Complaints are not confirmed violations or a complete measure of pollution. |
| [EPA Toxics Release Inventory (TRI)](https://www.epa.gov/toxics-release-inventory-tri-program/tri-basic-data-files-calendar-years-1987-present) | Study facility-reported chemical releases at Maryland and nearby facilities. | Review reporting thresholds and field definitions; the data do not cover all facilities or chemicals. |
| [CDC PLACES](https://www.cdc.gov/places/tools/data-portal.html) | Compare health estimates across Maryland, D.C., and nearby communities. | Estimates are modeled, including at small-area levels; they are not direct counts. |

## Transportation and infrastructure

| Dataset | Potential reporting directions | Source and considerations |
|---|---|---|
| [Capital Bikeshare trip history](https://capitalbikeshare.com/system-data) | Investigate when, where, and by whom bikes are used across the DMV. | Trip records describe this system, not all regional travel; review the data license and processing notes. |
| [NHTSA Fatality Analysis Reporting System (FARS)](https://www.nhtsa.gov/research-data/fatality-analysis-reporting-system-fars) | Analyze fatal crashes in Maryland and D.C. by location, roadway, vehicle, or person. | FARS covers fatal crashes, not all collisions, and uses linked tables. |
| [FCC National Broadband Map data](https://broadbandmap.fcc.gov/data-download/nationwide-data) | Compare reported internet availability by provider, technology, speed, or location in the DMV. | Availability is not the same as subscription or service quality; national files can be large. |
| [Bureau of Transportation Statistics airline on-time data](https://www.transtats.bts.gov/ontime/) | Examine delays and cancellations at BWI, DCA, and IAD. | Narrow the data to selected airports, airlines, or time periods; the source covers reporting carriers. |

## Federal government and public life

| Dataset | Potential reporting directions | Source and considerations |
|---|---|---|
| [Federal Election Commission campaign finance data](https://www.fec.gov/data/browse-data/) | Examine contributions or spending in Maryland and D.C. federal races. | Transaction-level files can be large; select a race, committee, or period and review the data codes. |
| [USAspending.gov awards data](https://www.usaspending.gov/) | Investigate federal contracts and grants connected to Maryland and D.C. | Distinguish awards, obligations, and outlays; consult the data dictionary. |
| [CFPB Consumer Complaint Database](https://www.consumerfinance.gov/data-research/consumer-complaints/) | Compare complaint counts and company responses by product, issue, or location. | Complaints are not representative of all customers' experiences. Check current fields and publication changes before choosing a question. |
| [National Park Service visitor use statistics](https://irma.nps.gov/Stats/) | Compare visits to DMV-area park units over time. | Check each park's counting methods and whether recent estimates are final. |

## Culture and recreation

| Dataset | Potential reporting directions | Source and considerations |
|---|---|---|
| [NCAA women's college basketball rosters](https://github.com/Sports-Roster-Data/womens-college-basketball) | Compare roster composition, geography, or seasons, including DMV-area programs. | This is a third-party collection; review its methods, coverage, and documentation. |
| [BoardGameGeek board-game data](https://www.kaggle.com/datasets/andrewmvd/board-games) | Explore relationships among game characteristics, complexity, and ratings. | This static third-party dataset was collected in 2021; ratings are not a representative survey of players. |
| [MovieLens 25M ratings](https://grouplens.org/datasets/movielens/25m/) | Explore ratings and tags by genre, release year, or other movie characteristics. | Ratings come from MovieLens users, not a representative sample of movie viewers; review the dataset terms. |
| [Smithsonian Open Access collections](https://www.si.edu/openaccess/devtools) | Explore collection records by topic, date, location, or Smithsonian unit. | The collection is broad and heterogeneous; check the rights status of individual items and media. |

## Food and nutrition

| Dataset | Potential reporting directions | Source and considerations |
|---|---|---|
| [USDA Foundation Foods](https://fdc.nal.usda.gov/food-search/?type=Foundation) | Compare nutrients in foods using USDA analytical data. | Read the data documentation; coverage and available nutrients vary by food. |
| [USDA Branded Foods](https://fdc.nal.usda.gov/food-search/?type=Branded) | Compare nutrition information across packaged products and brands. | Data are based on manufacturer label information; products and fields change over time. |
| [Food and Nutrient Database for Dietary Studies (FNDDS)](https://fdc.nal.usda.gov/food-search/?type=Survey) | Examine foods and nutrients associated with foods reported in dietary surveys. | FNDDS is tied to specific survey cycles; use the matching documentation and dates. |
| [FDA food recalls and safety alerts](https://www.fda.gov/safety/recalls-market-withdrawals-safety-alerts) | Track recalled food products, reasons, and timing. | The FDA's current page covers three years before records move to its archive; recalls are not a complete measure of food safety problems. |

## Supplementary data

The [American Community Survey (ACS)](https://www.census.gov/programs-surveys/acs/data.html) can add population denominators or demographic and economic context. [Census geographic boundary files](https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html) can help match data by place. Align geography and time periods carefully, and do not treat correlation or geographic overlap as proof of causation.
