# Population/Schools(Data Analysis Project)
Population/Schools is a personal work that show different faces of data analysis and data processing with real datasets.
The goal of this project is to show examples of input/output data, data cleaning, visualization and data analysis.
## Datasets
Three different datasets were used in this project:
1. [Dataset of Vancouver census 2016 using the City's 22 local planning areas from City of Vancouver open data website](https://data.vancouver.ca/datacatalogue/censusLocalAreaProfiles2016.htm "City of Vancouver open data portal")

2. [Dataset of schools in Vancouver (name, category, coordenates of ubication) from City of Vancouver open data website](https://opendata.vancouver.ca/explore/dataset/schools/information/?location=12,49.24716,-123.11523&dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiQ09VTlQiLCJzY2llbnRpZmljRGlzcGxheSI6dHJ1ZSwiY29sb3IiOiJyYW5nZS1jdXN0b20ifV0sInhBeGlzIjoiZ2VvX2xvY2FsX2FyZWEiLCJtYXhwb2ludHMiOjUwLCJzb3J0IjoiIiwic2VyaWVzQnJlYWtkb3duIjoic2Nob29sX2NhdGVnb3J5IiwiY29uZmlnIjp7ImRhdGFzZXQiOiJzY2hvb2xzIiwib3B0aW9ucyI6e319fV0sInRpbWVzY2FsZSI6IiIsImRpc3BsYXlMZWdlbmQiOnRydWUsImFsaWduTW9udGgiOnRydWV9 "City of Vancouver open data portal")

3. [Map of 22 local planning areas of Vancouver from City of Vancouver open data website](https://data.vancouver.ca/datacatalogue/localAreaBoundary.htm "City of Vancouver open data portal")
## Specific Objetives
1. Data wringling of Census 2016 and school datasets.
2. Creation of two new processed datasets for female and male between 0 and 17 years old from Census 2016.
3. Data wringling of Schools dataset
4. Generation of the map of 22 local planning areas of Vancouver.
5. Visualization of the all data in a map of Vancouver.
## Workflows 
Three different workflows were used in this work in order to generate a final map of the 22 local planning areas of the City os Vancouver with a the localization of the schools, amount of people between 0 and 17 years old.
### Workflow of data wringling of Census 2016 dataset
![alt text](https://github.com/jv80/Population-Schools/blob/master/Diagrams/workflow1.png)
![alt text](https://github.com/jv80/Population-Schools/blob/master/Diagrams/block_diagram.png)
![alt text](https://github.com/jv80/Population-Schools/blob/master/Images/workflowDataGeneration.PNG)
### Workflow of generation of two separated datasets (Female and Male)

### Workflow of data wringling of Schools dataset

### Workflow of generation of the map

The map was generated using GeoPandas.

### Workflow of viazualization all information processed

### Summary

| Input File | Work File | Output File|
|
|[CensusLocalAreaProfiles2016.csv](https://github.com/jv80/Population-Schools/blob/master/Data/CensusLocalAreaProfiles2016.csv)|

