# A visitor-enriched census in the U.S. cities using large-scale mobile positioning data
## Introduction
Census data, as a traditional data source of resident socio-demographics, provides valuable information for decision-makers, researchers, and the public. While numerous efforts have been made to develop more comprehensive data products based on published census datasets, most approaches treat census units as static and independent entities, overlooking their interactions. In this paper, we introduce the visitor census dataset, a semantically enriched census that incorporates human visitations extracted from large-scale mobile positioning data. We identified and validated the potential home locations of 3.58 million anonymous mobile phone users across seven U.S. metropolitan statistical areas in July 2021 and utilized home detection results to enrich the socio-demographic profile of the places users visited. The proposed data generation framework is adaptive, allowing future integration of diverse socio-demographic features at varying spatial and temporal scales. Overall, this visitor-based census represents an effort to enrich resident-based census knowledge by incorporating mobilities and spatial interactions in human digital traces, bridging the gap between aggregated and individual analysis, as well as between conventional census and mobile phone data.
## Dataset Structure
Seven MSAs include Los Angeles–Long Beach–Anaheim (LA), Houston–Pasadena–The Woodlands (Houston), Atlanta–Sandy Springs–Roswell (Atlanta), Miami–Fort Lauderdale–West Palm Beach (Miami), Seattle–Tacoma–Bellevue (Seattle), Denver–Aurora–Centennial (Denver), and Minneapolis-Saint. Paul (Twin Cities). There are ten files for each MSA:
* Visitor-based aggregation census table (e.g., Atlanta_visitor_July2021.csv): one file
* Visit-based aggregation census table (e.g., Atlanta_visit_July2021.csv): one file
* One-week (July 19-25, 2021) intermediate home-visit table (e.g., Atlanta_homevisit_July21.csv.gz): seven files
* Geographic boundary file at CBG level (e.g., Atlanta_cbg.geojson): one file
The folders and files are organized as follows.
## Code Usage Guide
