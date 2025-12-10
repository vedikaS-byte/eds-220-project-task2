# Biodiversity Intactness Index Change in Phoenix, AZ

## Description 
Maricopa County, the fourth most populous county in the United States, is home to more than half of Arizona's residents and contains the state capital, Phoenix. As of 2022, the county had a population of 4.5 million people and was listed as the fastest-growing county in the U.S., adding nearly 56,000 residents between July 2021 and 2022 (Maricopa County, n.d.). This rapid population growth has contributed to the most significant increase in developed land in the county since at least 2001 (Levitt & Eng, 2021). Consequently, expanding urban sprawl has raised concerns about impacts on biodiversity and ecosystem health in the surrounding areas.

This repository contains the data, code, and figures for a geospatial analysis project using Python based spatial libraries (ex. `geopandas` and `rioxarray`) and open access geospatial datasets. This assignment investigates the impacts of urban sprawl on biodiversity by analyzing Biodiversity Intactness Index (BII) values in the Phoenix county subdivision area for 2017 and 2020. The analysis highlights how urban growth corresponds with changes in biodiversity over time, providing insight into the ecological consequences of expanding urban landscapes. The final output consists of a map illustrating changes in BII across the Phoenix metropolitan area, with an emphasis on areas experiencing biodiversity loss.  


## Contents
This repository is organized as follows and contains: 
- `README.md`: Markdown file detailing repository description, content, structure, data access, and references.

- `.gitignore`: File alerting Git to avoid "unnecessary" files from being committed to the repository. The data folder containing the 2025 TIGER/Line Shapefiles for the County Subdivisions were added to the `.gitignore` to prevent large datasets from being pushed to GitHub. 

- `biodiversty-analysis-SHIRTEKAR.ipynb`: Notebook containing the biodiversity assessment for Phoenix (Maricopa County), examining the impacts of rapid development from 2017 to 2020.

```
Biodiversity Intactness Index Change in Phoenix, AZ
├── README.md
├── biodiversty-analysis-SHIRTEKAR.ipynb
├── .gitignore
```
    
    
## Data Access
*The data utilized in this analysis is not housed in this repository. 

The Biodiversity Intactness Index (BII) is a global dataset that quantifies changes in biodiversity using species abundance information for plants, fungi, and animals [Natural History Museum (n.d.)](https://www.nhm.ac.uk/our-science/services/data/biodiversity-intactness-index.html). For this analysis, BII raster layers from 2017 and 2020 were obtained from the `io-biodiversity` collection in the [Microsoft Planetary Computer STAC catalog](https://planetarycomputer.microsoft.com/dataset/io-biodiversity) and clipped to the Phoenix subdivision. The index captures how terrestrial ecosystems respond to human pressures such as land-use change and increased intensity of development, providing insight into the degree to which local biodiversity remains intact over time.



The U.S. Census Bureau provides public access to geographic boundary data through its [TIGER/Line® Shapefiles](https://www.census.gov/cgi-bin/geo/shapefiles/index.php) database. For this project, the [2025 Arizona County Subdivisions](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2025&layergroup=County+Subdivisions) layer was downloaded to obtain county-level boundary shapefiles representing Arizona’s administrative divisions as of 2025.


## Contributors
This repository is maintained by Vedika Shirtekar as part of the Master of Environmental Data Science program at UC Santa Barbara. This work was completed for the **EDS 220: Working with Environmental Datasets** course at the Bren School of Environmental Science and Management, which provided data access and documentation practices, as well as assignment instructions.


## References
[1] *Biodiversity Intactness Index*. (n.d.). Natural History Museum. Retrieved December 5, 2025, from 
https://www.nhm.ac.uk/our-science/services/data/biodiversity-intactness-index.html


[2] EDS 220. (n.d.). *Working with Environmental Datasets*. Bren School of Environmental Science and Management. Accessed November 29, 2025, from 
https://meds-eds-220.github.io/MEDS-eds-220-course/


[3] Levitt, Z. and Eng J., (2021, August 11). *Where America’s developed areas are growing*. The Washington Post. Accessed December 5, 2025, from 
https://www.washingtonpost.com/nation/interactive/2021/land-development-urban-growth-maps/


[4] *Maricopa county quick facts*. (n.d.). Maricopa County, AZ. Accessed December 5, 2025, from 
https://www.maricopa.gov/3598/County-Quick-Facts


[5] Microsoft Planetary Computer. *Biodiversity Intactness Index (BII) Time Series*. [Dataset] Microsoft Planetary Computer. Accessed December 3, from
https://planetarycomputer.microsoft.com/dataset/io-biodiversity


[6] United States Census Bureau. *2025 TIGER/Line® Shapefiles: County Subdivisions* [Dataset]. U.S. Census Bureau. Accessed December 3, 2025, from 
https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2025&layergroup=County+Subdivisions



