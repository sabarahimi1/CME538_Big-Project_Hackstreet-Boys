# Premier Doug Ford's Government Passes Bill 212: Should the Bike Lanes be Removed?

Toronto’s bike lanes are under threat. Premier Doug Ford’s government plans to remove bike lanes through the newly enforced bill 212 from three key streets: Bloor Street, University Avenue, and Yonge Street. Ford argues these lanes are a major contributor to gridlock, claiming they’ve brought traffic in our cities to a standstill. He also believes bike lanes are misplaced on major roads. However, these claims don’t align with the reality. Ford’s argument overlooks the vital role bike lanes play in reducing car-bike conflicts and creating safer, greener urban spaces. Hackstreet Boyz examined multiple datasets and explored the different trends in bike collisions throughout the city to gain insight into the results of the Ford Government's decision. 


In this project, data was collected from the City of Toronto Open Data Portal. We chose to analyze the following datasets.

- City Wards (25-Ward Model): Shapefile that contains the ward boundaries that divide the City into specific administrative areas, used to cluster locations for spatial analysis. The data can be downloaded here in a Shapefile format: https://open.toronto.ca/dataset/city-wards/.

- Community Council Boundaries: Defines the areas governed by community councils, used to provide a geographic framework for organizing and interpreting trends. The data can be downloaded here in a GeoJson format: https://open.toronto.ca/dataset/community-council-boundaries/.

- Demographics Data: Provides essential insights into Toronto's population characteristics, enabling analysis of socio-economic factors and their relationship to urban infrastructure and equity issues. The data can be downloaded here in a CSV/.XLX format: https://open.toronto.ca/dataset/ward-profiles-25-ward-model/.

- Zoning By-Law Data: Outlines land use designations across Toronto, enabling analysis of urban development patterns and their relationship to infrastructure, planning, and community needs.The data can be downloaded here in a GeoJson format: https://open.toronto.ca/dataset/zoning-by-law/

- Cycling Network: Shows the existing cycling network across the City, the type of bike lane, the year it was installed and upgraded, and its location. The data can be downloaded here in a GeoJson format: https://open.toronto.ca/dataset/cycling-network/.

- Traffic Collisions Open Data: Contains the location of all car-bicycle collisions from 2014–2024, including temporal data (hour, day of week, month, year) of when the collisions occurred. The data can be downloaded here in a GeoJson format: https://data.torontopolice.on.ca/datasets/TorontoPS::traffic-collisions-open-data-asr-t-tbl-001/about.

Since the files for Traffic Collision, stated above, are too large to be stored directly in the repository, they were saved in a folder located outside the repository named 'data_files'. Hence, all the datasets were called in the following manner:

'../../../data_files/"NAME OF DATASET".geojson'

## Overview of Data:

The following folders consist of the following items:

- Clean Data: This folder contains the cleaned GeoJSON files for all datasets. These files serve as the refined versions of the data and are utilized in other notebooks for analysis and visualization purposes.
- Clustering: Consists of the notebook used to conduct clustering (unsupervised machine learning) on the ward profile demographics data. 
- Datasets: folder contains various datasets related to the City of Toronto. It is recommended that they are read in the following order:
  1. Ward and District Data: Details about the city's administrative divisions, including ward boundaries and district-level information.
  2. City of Toronto Collision Data: Data regarding traffic collisions, including details like location, time, and type of collision.
  3. City of Toronto Demographics Data: Information about the city's population, including age, gender, income, and other demographic factors.   NOTE: Read the clustering notebook here.
  4. Cycling Network Data: Information on Toronto's cycling infrastructure, including bike lanes, trails, and related amenities.
  5. City of Toronto Zoning By-Law Data: Data related to land use, zoning regulations, and city planning.
  - Group5_Big_Project_Presentation.pdf: Presentation showing the EDA process
  - Overall Folium Map.ipynb: Contains the folium map that represents the entire project (excluding demographics and zoning data). 
      
## Links to Medium Articles:

ADD THE LINKS ONCE ARTICLE IS PUBLISHED.
