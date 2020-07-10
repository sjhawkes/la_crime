# LA Crime - a study of changes in reported crime by date and region

This repository contains code for exploring the LAPD reported crime database. The files are too large to be hosted on GitHub and must be accessed independently. Before running any code be sure to download the following three files and move them into the datasets folder.

[Reported Crime 2010-2019](https://data.lacity.org/A-Safe-City/Crime-Data-from-2010-to-2019/63jg-8b9z)

[Reported Crime 2020](https://data.lacity.org/A-Safe-City/Crime-Data-from-2020-to-Present/2nrs-mtv8)

[Arrests 2010-2019](https://data.lacity.org/A-Safe-City/Arrest-Data-from-2010-to-2019/yru6-6re4)


### Contents

| Notebook | Description |
| - | - |
| 01_crime_preprocessing | Code for combining the 2010-2019 crime database with the 2020 crime database and generating categorical variables for detailed analysis by date, crime type, and neighborhood. NOTE: this code can take a really long time to run |
| 02_crime_eda | Code for generating plots to explore trends in the types of crimes reported in Los Angeles |
| 03_map_preprocessing | Code for combining crime data with Los Angeles neighborhood GIS polygons |
| 04_maps | Code for generating crime maps |